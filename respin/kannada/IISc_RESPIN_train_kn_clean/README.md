## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Kannada (KN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_kn_clean
- Total Audio Duration (HH:MM:SS): 888:43:04
- Average Sample Duration: 5.771 secs
- Total Unique Text IDs: 23294
- Unique Word Count: 48953
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D5 | 89774 | 3184 | 2020 | 5204 | 405 | 348 | 102.71 | 65.24 | 167.95 |
| D2 | 102730 | 2635 | 2569 | 5204 | 343 | 307 | 92.74 | 84.00 | 176.74 |
| D4 | 126483 | 2374 | 2256 | 4630 | 399 | 343 | 99.41 | 91.22 | 190.63 |
| D3 | 118866 | 2243 | 2420 | 4663 | 364 | 316 | 86.63 | 89.85 | 176.48 |
| D1 | 116545 | 1718 | 1921 | 3639 | 420 | 393 | 84.77 | 92.15 | 176.92 |
| Total | 554398 | 12154 | 11186 | 23294 | 1931 | 1703 | 466.27 | 422.45 | 888.72 |



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

### Metadata File Sample (meta_train_kn_clean.json) ###

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
    "IISc_RESPIN_kn_D5_50012_560064_M_AGRI_500400_50000038": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 12.92,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "560064",
        "slab": "clean",
        "speaker_id": "50012",
        "speaker_id_reassigned": "50012_1",
        "text": "ಸಾವಯವ ಆಹಾರ ಪದಾರ್ಥಗಳು ಆಹಾರ ಉತ್ಪನ್ನಗಳಿಗೆ ನಗರ ಭಾಗದ ಜನ ಆರೋಗ್ಯದ ದೃಷ್ಟಿಯಿಂದ ಹೆಚ್ಚಿನ ಆದ್ಯತೆ ನೀಡಿದ್ದಾರೆ",
        "text_id": "500400",
        "text_type": "statement",
        "utterance_id": "50000038",
        "wav_path": "D5/50012/IISc_RESPIN_kn_D5_50012_560064_M_AGRI_500400_50000038.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_kn_D5_50012.txt) ###
```
IISc_RESPIN_kn_D5_50012_560064_M_AGRI_503184_50000037	ಮಾನ್ಸೂನ್ ಮಾರುತ ವರ್ಷದಲ್ಲಿ ಆರ್ ತಿಂಗಳ ಕಾಲ ಈಶಾನ್ಯದಿಂದ ಉಳಿದ ಆರ್ ತಿಂಗಳಕಾಲ ನೈರುತ್ಯದಿಂದ ಬೀಸುತ್ತೆ
IISc_RESPIN_kn_D5_50012_560064_M_AGRI_500400_50000038	ಸಾವಯವ ಆಹಾರ ಪದಾರ್ಥಗಳು ಆಹಾರ ಉತ್ಪನ್ನಗಳಿಗೆ ನಗರ ಭಾಗದ ಜನ ಆರೋಗ್ಯದ ದೃಷ್ಟಿಯಿಂದ ಹೆಚ್ಚಿನ ಆದ್ಯತೆ ನೀಡಿದ್ದಾರೆ
IISc_RESPIN_kn_D5_50012_560064_M_AGRI_502225_50000039	ಗಡಿ ರೋಗ ಮೇಕೆಗಳ ವೈರಾಣು ರೋಗವಾಗಿದ್ದು ಜನ್ಮಜಾತ ರೋಗ ಉಂಟುಮಾಡ್ತದೆ ಆದರೆ ತೀವ್ರವಾದ ಸೋಂಕನ್ನು ಉಂಟುಮಾಡ್ಬೋದು
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