## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Magahi (MG)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mg_noisy
- Total Audio Duration (HH:MM:SS): 60:10:53
- Average Sample Duration: 5.984 secs
- Total Unique Text IDs: 14943
- Unique Word Count: 17945
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 8850 | 1727 | 1894 | 3621 | 574 | 659 | 6.26 | 6.72 | 12.98 |
| D1 | 8446 | 1932 | 1915 | 3847 | 477 | 359 | 6.72 | 7.60 | 14.32 |
| D4 | 12552 | 2169 | 2221 | 4390 | 510 | 430 | 10.83 | 11.58 | 22.42 |
| D2 | 6358 | 1521 | 1564 | 3085 | 464 | 405 | 5.03 | 5.43 | 10.47 |
| Total | 36206 | 7349 | 7594 | 14943 | 2025 | 1850 | 28.84 | 31.34 | 60.18 |



#### Notes:
- DID: Dialect ID
- #utt: Number of utterances
- #sent: Number of sentences
- #spk: Number of speakers
- #re-spk: Number of reassigned speakers

### Directory Structure ###
```
train_bh_small/
├── D1
│   ├── <speaker_id>
│   │   ├── IISc_RESPIN_<lid>_<dialect>_<speaker_id>_<pincode>_<genderTag>_<domainTag>_<text_id>_<uttid>.wav
│   │   ├── [...]
│   │   └── IISc_RESPIN_<lid>_<dialect>_<speaker_id>.txt
│   ├── [...]
├── D2
│   ├── [...]
├── [...]
└── meta_train_bh_small.json
└── README.md
```

### Metadata File Sample (meta_train_mg_noisy.json) ###

```json
{
    "IISc_RESPIN_mg_D3_60256_844121_M_AGRI_615762_60000039": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 9.05,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "844121",
        "slab": "noisy",
        "speaker_id": "60256",
        "speaker_id_reassigned": "60222_1",
        "text": "रोहन खेती के उत्पादन के बढ़ावे के लेल ग्रीनहाउस तकनिक के सलाह देलथिन",
        "text_id": "615762",
        "text_type": "statement",
        "utterance_id": "60000039",
        "wav_path": "D3/60256/IISc_RESPIN_mg_D3_60256_844121_M_AGRI_615762_60000039.wav"
    },
    "IISc_RESPIN_mg_D3_60218_844121_F_BANK_612689_60000054": {
        "age_group": "31-35",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 3.77,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "mg",
        "pincode": "844121",
        "slab": "noisy",
        "speaker_id": "60218",
        "speaker_id_reassigned": "NA",
        "text": "आर्थिक खतरा के कम करेके लेल हमरा सभके कोनो उपाय लगाएल जाइ छै",
        "text_id": "612689",
        "text_type": "statement",
        "utterance_id": "60000054",
        "wav_path": "D3/60218/IISc_RESPIN_mg_D3_60218_844121_F_BANK_612689_60000054.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mg_D3_60256.txt) ###
```
IISc_RESPIN_mg_D3_60256_844121_M_AGRI_615762_60000039	रोहन खेती के उत्पादन के बढ़ावे के लेल ग्रीनहाउस तकनिक के सलाह देलथिन
IISc_RESPIN_mg_D3_60256_844121_M_BANK_612893_60000211	पे.टी.एम द्वारा कएगो वित्तीय सेवा देल जाय लगलई ह
IISc_RESPIN_mg_D3_60256_844121_M_AGRI_612163_60000400	कीट प्रबंधन के उद्देश्य स्तर से नीच्चाके पिलुआके आबादी के हतोत्साहित करनाइ हइ
```

For more details, please refer to database page at [RESPIN Corpus](http://spiredatasets.iisc.ac.in/respinCorpus).

### Copyright and license ###

ASR data created under RESPIN project  by Indian Institute of Science, Bengaluru is available
at http://spiredatasets.iisc.ac.in/respinCorpus and the copyright in the ASR data belongs to
Indian Institute of Science, Bengaluru and the said ASR data is released or distributed under
CC-BY-4.0 license (https://creativecommons.org/licenses/by/4.0/legalcode.en).  The user of
said ASR data is referred to the disclaimer of warranties section in the CC-BY-4.0 license
agreement.


### Acknowledgments ###

We extend our gratitude to all speakers from various districts whose contributions were fundamental to this initiative's success.
We are particularly grateful to Navana Tech for their efforts in collecting and curating the ASR corpus.
We thank the Bill and Melinda Gates Foundation for their generous support in this project.

### Contact Information ###

SPIRE Lab, EE Dept., IISc, Bengaluru
Email: contact.respin@iisc.ac.in