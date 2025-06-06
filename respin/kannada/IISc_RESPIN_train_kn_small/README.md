## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Kannada (KN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_kn_small
- Total Audio Duration (HH:MM:SS): 164:50:03
- Average Sample Duration: 6.916 secs
- Total Unique Text IDs: 17160
- Unique Word Count: 39904
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D5 | 17158 | 1716 | 1716 | 3432 | 402 | 335 | 19.29 | 16.96 | 36.25 |
| D2 | 17161 | 1716 | 1717 | 3433 | 338 | 294 | 17.00 | 16.88 | 33.88 |
| D4 | 17160 | 1716 | 1716 | 3432 | 353 | 282 | 16.83 | 15.29 | 32.12 |
| D3 | 17160 | 1716 | 1716 | 3432 | 356 | 297 | 16.32 | 15.90 | 32.21 |
| D1 | 17161 | 1676 | 1757 | 3433 | 410 | 359 | 15.39 | 14.99 | 30.38 |
| Total | 85800 | 8540 | 8622 | 17160 | 1859 | 1563 | 84.81 | 80.02 | 164.83 |



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

### Metadata File Sample (meta_train_kn_small.json) ###

```json
{
    "IISc_RESPIN_kn_D5_50012_560064_M_AGRI_503184_50000037": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 12.15,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "560064",
        "slab": "clean",
        "speaker_id": "50012",
        "speaker_id_reassigned": "50012_1",
        "text": "ಮಾನ್ಸೂನ್ ಮಾರುತ ವರ್ಷದಲ್ಲಿ ಆರ್ ತಿಂಗಳ ಕಾಲ ಈಶಾನ್ಯದಿಂದ ಉಳಿದ ಆರ್ ತಿಂಗಳಕಾಲ ನೈರುತ್ಯದಿಂದ ಬೀಸುತ್ತೆ",
        "text_id": "503184",
        "text_type": "statement",
        "utterance_id": "50000037",
        "wav_path": "D5/50012/IISc_RESPIN_kn_D5_50012_560064_M_AGRI_503184_50000037.wav"
    },
    "IISc_RESPIN_kn_D5_50012_560064_M_AGRI_502225_50000039": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 12.63,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "560064",
        "slab": "clean",
        "speaker_id": "50012",
        "speaker_id_reassigned": "50012_1",
        "text": "ಗಡಿ ರೋಗ ಮೇಕೆಗಳ ವೈರಾಣು ರೋಗವಾಗಿದ್ದು ಜನ್ಮಜಾತ ರೋಗ ಉಂಟುಮಾಡ್ತದೆ ಆದರೆ ತೀವ್ರವಾದ ಸೋಂಕನ್ನು ಉಂಟುಮಾಡ್ಬೋದು",
        "text_id": "502225",
        "text_type": "statement",
        "utterance_id": "50000039",
        "wav_path": "D5/50012/IISc_RESPIN_kn_D5_50012_560064_M_AGRI_502225_50000039.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_kn_D5_50012.txt) ###
```
IISc_RESPIN_kn_D5_50012_560064_M_AGRI_503184_50000037	ಮಾನ್ಸೂನ್ ಮಾರುತ ವರ್ಷದಲ್ಲಿ ಆರ್ ತಿಂಗಳ ಕಾಲ ಈಶಾನ್ಯದಿಂದ ಉಳಿದ ಆರ್ ತಿಂಗಳಕಾಲ ನೈರುತ್ಯದಿಂದ ಬೀಸುತ್ತೆ
IISc_RESPIN_kn_D5_50012_560064_M_AGRI_502225_50000039	ಗಡಿ ರೋಗ ಮೇಕೆಗಳ ವೈರಾಣು ರೋಗವಾಗಿದ್ದು ಜನ್ಮಜಾತ ರೋಗ ಉಂಟುಮಾಡ್ತದೆ ಆದರೆ ತೀವ್ರವಾದ ಸೋಂಕನ್ನು ಉಂಟುಮಾಡ್ಬೋದು
IISc_RESPIN_kn_D5_50012_560064_M_BANK_501300_50000042	ದಾನ ನೀಡುವುದು ಮಾನವೀಯತೆಯ ಧರ್ಮ
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