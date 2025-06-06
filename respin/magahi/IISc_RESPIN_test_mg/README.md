## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Magahi (MG)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_mg
- Total Audio Duration (HH:MM:SS): 3:10:22
- Average Sample Duration: 5.209 secs
- Total Unique Text IDs: 640
- Unique Word Count: 2267
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 570 | 102 | 74 | 176 | 40 | 40 | 0.42 | 0.35 | 0.77 |
| D4 | 508 | 83 | 74 | 157 | 40 | 40 | 0.45 | 0.36 | 0.81 |
| D2 | 574 | 68 | 93 | 161 | 40 | 40 | 0.38 | 0.55 | 0.92 |
| D3 | 541 | 72 | 74 | 146 | 40 | 40 | 0.31 | 0.36 | 0.67 |
| Total | 2193 | 325 | 315 | 640 | 160 | 160 | 1.56 | 1.62 | 3.17 |



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

### Metadata File Sample (meta_test_mg.json) ###

```json
{
    "IISc_RESPIN_mg_D1_60025_823311_M_BANK_603672_60004132": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 8.41,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "823311",
        "slab": "clean",
        "speaker_id": "60025",
        "speaker_id_reassigned": "60025_1",
        "text": "वित्तीय वर्ष के अंत में बैंक के द्वारा बैंक कर्मि के बोनस प्रदान कैल जा हइ",
        "text_id": "603672",
        "text_type": "statement",
        "utterance_id": "60004132",
        "wav_path": "D1/60025/IISc_RESPIN_mg_D1_60025_823311_M_BANK_603672_60004132.wav"
    },
    "IISc_RESPIN_mg_D1_60025_823311_M_BANK_603495_60004353": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 3.45,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "823311",
        "slab": "clean",
        "speaker_id": "60025",
        "speaker_id_reassigned": "60025_1",
        "text": "सामान्य ब्याज के अवधि निश्चित होवऽ हई",
        "text_id": "603495",
        "text_type": "statement",
        "utterance_id": "60004353",
        "wav_path": "D1/60025/IISc_RESPIN_mg_D1_60025_823311_M_BANK_603495_60004353.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mg_D1_60025.txt) ###
```
IISc_RESPIN_mg_D1_60025_823311_M_BANK_603672_60004132	वित्तीय वर्ष के अंत में बैंक के द्वारा बैंक कर्मि के बोनस प्रदान कैल जा हइ
IISc_RESPIN_mg_D1_60025_823311_M_BANK_603495_60004353	सामान्य ब्याज के अवधि निश्चित होवऽ हई
IISc_RESPIN_mg_D1_60025_823311_M_BANK_603051_60004376	पृथ्वी पर बहुत तरह के वृक्ष पावल जा हइ
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