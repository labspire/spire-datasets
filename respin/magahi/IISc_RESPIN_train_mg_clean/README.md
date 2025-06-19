## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Magahi (MG)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mg_clean
- Total Audio Duration (HH:MM:SS): 1066:18:12
- Average Sample Duration: 4.987 secs
- Total Unique Text IDs: 21500
- Unique Word Count: 20893
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 217594 | 2479 | 2754 | 5233 | 588 | 697 | 129.10 | 139.77 | 268.87 |
| D1 | 191621 | 3000 | 2839 | 5839 | 488 | 388 | 138.68 | 133.20 | 271.87 |
| D4 | 171396 | 2571 | 2583 | 5154 | 525 | 460 | 125.44 | 126.11 | 251.55 |
| D2 | 189068 | 2534 | 2741 | 5275 | 477 | 455 | 131.60 | 142.40 | 274.01 |
| Total | 769679 | 10584 | 10917 | 21500 | 2078 | 1997 | 524.83 | 541.48 | 1066.30 |



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

### Metadata File Sample (meta_train_mg_clean.json) ###

```json
{
    "IISc_RESPIN_mg_D3_60256_844121_M_AGRI_614887_60000001": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 16.58,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "844121",
        "slab": "clean",
        "speaker_id": "60256",
        "speaker_id_reassigned": "60222_1",
        "text": "अलसी के तेल के उपयोग वर्णित रंग साबुन पेंट और सब में कइल जाहई",
        "text_id": "614887",
        "text_type": "statement",
        "utterance_id": "60000001",
        "wav_path": "D3/60256/IISc_RESPIN_mg_D3_60256_844121_M_AGRI_614887_60000001.wav"
    },
    "IISc_RESPIN_mg_D3_60256_844121_M_BANK_615711_60000003": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 10.6,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "844121",
        "slab": "clean",
        "speaker_id": "60256",
        "speaker_id_reassigned": "60222_1",
        "text": "राम यू.पी.आई से पइसा भेजे के लेल ओ.टी.पी डाललई",
        "text_id": "615711",
        "text_type": "statement",
        "utterance_id": "60000003",
        "wav_path": "D3/60256/IISc_RESPIN_mg_D3_60256_844121_M_BANK_615711_60000003.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mg_D3_60256.txt) ###
```
IISc_RESPIN_mg_D3_60256_844121_M_AGRI_614887_60000001	अलसी के तेल के उपयोग वर्णित रंग साबुन पेंट और सब में कइल जाहई
IISc_RESPIN_mg_D3_60256_844121_M_BANK_615711_60000003	राम यू.पी.आई से पइसा भेजे के लेल ओ.टी.पी डाललई
IISc_RESPIN_mg_D3_60256_844121_M_AGRI_612325_60000004	खेती लेल किनल गेल मशीन जाच परख के किने चाहि
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