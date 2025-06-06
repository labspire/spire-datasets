## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Kannada (KN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_kn_seminoisy
- Total Audio Duration (HH:MM:SS): 202:25:26
- Average Sample Duration: 6.985 secs
- Total Unique Text IDs: 22004
- Unique Word Count: 47612
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D5 | 24686 | 3113 | 1968 | 5081 | 401 | 350 | 32.93 | 19.61 | 52.54 |
| D2 | 15505 | 2351 | 2273 | 4624 | 339 | 307 | 15.10 | 14.64 | 29.74 |
| D4 | 14499 | 2191 | 2060 | 4251 | 398 | 337 | 14.56 | 12.15 | 26.71 |
| D3 | 23842 | 2170 | 2337 | 4507 | 362 | 316 | 21.84 | 23.69 | 45.53 |
| D1 | 25792 | 1703 | 1879 | 3582 | 419 | 392 | 23.78 | 24.12 | 47.91 |
| Total | 104324 | 11528 | 10517 | 22004 | 1919 | 1698 | 108.21 | 94.21 | 202.42 |



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

### Metadata File Sample (meta_train_kn_seminoisy.json) ###

```json
{
    "IISc_RESPIN_kn_D5_50012_560064_M_BANK_501265_50000061": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Banking",
        "duration": 6.69,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "560064",
        "slab": "seminoisy",
        "speaker_id": "50012",
        "speaker_id_reassigned": "50012_1",
        "text": "ಸ್ಮಾಲ್ ಬಿಸಿನೆಸ್ ಅಂಟ್ರಪ್ರಿನರ್ಶಿಪ್ ಭಾರತದಲ್ಲಿ ಹೆಚ್ಚು ಕಂಡುಬರುತ್ತದೆ",
        "text_id": "501265",
        "text_type": "statement",
        "utterance_id": "50000061",
        "wav_path": "D5/50012/IISc_RESPIN_kn_D5_50012_560064_M_BANK_501265_50000061.wav"
    },
    "IISc_RESPIN_kn_D5_50001_NA_F_BANK_503350_50000121": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D5",
        "domain": "Banking",
        "duration": 10.98,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "kn",
        "pincode": "200119",
        "slab": "seminoisy",
        "speaker_id": "50001",
        "speaker_id_reassigned": "50001_1",
        "text": "ಮುನ್ಸಿಪಲ್ ಬಾಂಡ್ಗಳು ಕೂಪನ್ ದರಗಳು ಸಾಮಾನ್ಯವಾಗಿ ಹೋಲಿಸಬಹುದಾದ ಕಾರ್ಪೊರೇಟರ್ ಬಾಂಡ್ಗಳಿಗಿಂತ ಕಡಿಮೆ ಇರುತ್ತೆ",
        "text_id": "503350",
        "text_type": "statement",
        "utterance_id": "50000121",
        "wav_path": "D5/50001/IISc_RESPIN_kn_D5_50001_NA_F_BANK_503350_50000121.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_kn_D5_50012.txt) ###
```
IISc_RESPIN_kn_D5_50012_560064_M_BANK_501265_50000061	ಸ್ಮಾಲ್ ಬಿಸಿನೆಸ್ ಅಂಟ್ರಪ್ರಿನರ್ಶಿಪ್ ಭಾರತದಲ್ಲಿ ಹೆಚ್ಚು ಕಂಡುಬರುತ್ತದೆ
IISc_RESPIN_kn_D5_50012_560064_M_BANK_503502_50000722	ಡಿಸೆಂಬರ್ ಸಾವಿರದಒಂಬೈನೂರ ತೊಂಬತ್ತಒಂಬತ್ತು ರಲ್ಲಿ ಸ್ವತಂತ್ರ ಸಚಿವಾಲಯವಾಗಿ ಹೂಡಿಕೆ ಸಚಿವಾಲಯ ಸ್ಥಾಪಿಸಿದ್ದ್ರು
IISc_RESPIN_kn_D5_50012_560064_M_BANK_501521_50000733	ಇಂಟರ್ನೆಟ್ ಬ್ಯಾಂಕಿಂಗ್ ನಲ್ಲಿ ಅಕೌಂಟ್ನ ಬೇನಿಫಿಷರಿಗಳನ್ನು ನೋಡಬೋದು
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