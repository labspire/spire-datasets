## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Kannada (KN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_kn_hidden
- Total Audio Duration (HH:MM:SS): 3:32:30
- Average Sample Duration: 5.898 secs
- Total Unique Text IDs: 685
- Unique Word Count: 3542
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D5 | 474 | 84 | 64 | 148 | 40 | 40 | 0.50 | 0.32 | 0.83 |
| D4 | 414 | 93 | 84 | 177 | 40 | 40 | 0.35 | 0.33 | 0.68 |
| D2 | 427 | 66 | 52 | 118 | 40 | 40 | 0.43 | 0.31 | 0.74 |
| D1 | 444 | 58 | 64 | 122 | 40 | 40 | 0.32 | 0.38 | 0.69 |
| D3 | 403 | 55 | 65 | 120 | 40 | 40 | 0.30 | 0.31 | 0.61 |
| Total | 2162 | 356 | 329 | 685 | 200 | 200 | 1.90 | 1.65 | 3.54 |



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

### Metadata File Sample (meta_test_kn_hidden.json) ###

```json
{
    "IISc_RESPIN_kn_D5_50008_570001_M_BANK_501535_50000283": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Banking",
        "duration": 7.45,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "570001",
        "slab": "clean",
        "speaker_id": "50008",
        "speaker_id_reassigned": "50008_1",
        "text": "ಅಪಘಾತ ವಿಮೆ ಅಪಘಾತಕ್ಕೀಡಾದ ವ್ಯಕ್ತಿಗೆ ಕಂಪನಿ ಪರಿಹಾರ ಹಣ ಕಟ್ಟಿಕೊಡುತ್ತದೆ",
        "text_id": "501535",
        "text_type": "statement",
        "utterance_id": "50000283",
        "wav_path": "D5/50008/IISc_RESPIN_kn_D5_50008_570001_M_BANK_501535_50000283.wav"
    },
    "IISc_RESPIN_kn_D5_50008_570001_M_BANK_501376_50000420": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Banking",
        "duration": 7.46,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "570001",
        "slab": "clean",
        "speaker_id": "50008",
        "speaker_id_reassigned": "50008_1",
        "text": "ಕ್ಯಾಲೆಂಡರ್ ಬೇಸಿಸ್ ರಿಸ್ಕ್ , ಲೊಕೇಶನ್ ಫೇಸಸ್ ರಿಸ್ಕ್ ಪ್ರಾಡಕ್ಟ್ ಕ್ವಾಲಿಟಿ ಬೇಸಿಸ್ ರಿಸ್ಕ್ ಗಳಿವೆ",
        "text_id": "501376",
        "text_type": "statement",
        "utterance_id": "50000420",
        "wav_path": "D5/50008/IISc_RESPIN_kn_D5_50008_570001_M_BANK_501376_50000420.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_kn_D5_50008.txt) ###
```
IISc_RESPIN_kn_D5_50008_570001_M_BANK_501535_50000283	ಅಪಘಾತ ವಿಮೆ ಅಪಘಾತಕ್ಕೀಡಾದ ವ್ಯಕ್ತಿಗೆ ಕಂಪನಿ ಪರಿಹಾರ ಹಣ ಕಟ್ಟಿಕೊಡುತ್ತದೆ
IISc_RESPIN_kn_D5_50008_570001_M_BANK_501376_50000420	ಕ್ಯಾಲೆಂಡರ್ ಬೇಸಿಸ್ ರಿಸ್ಕ್ , ಲೊಕೇಶನ್ ಫೇಸಸ್ ರಿಸ್ಕ್ ಪ್ರಾಡಕ್ಟ್ ಕ್ವಾಲಿಟಿ ಬೇಸಿಸ್ ರಿಸ್ಕ್ ಗಳಿವೆ
IISc_RESPIN_kn_D5_50008_570001_M_BANK_500823_50000436	ಫೈನಾನ್ಸ್ ಬಗ್ಗೆ ಅಧ್ಯಯನ ಮಾಡುವವರನ್ನು ವಾಣಿಜ್ಯ ತಜ್ಞ ಎಂದು ಕರಿತಾರೆ
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