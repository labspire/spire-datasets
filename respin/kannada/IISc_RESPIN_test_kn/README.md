## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Kannada (KN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_kn
- Total Audio Duration (HH:MM:SS): 3:36:28
- Average Sample Duration: 6.011 secs
- Total Unique Text IDs: 663
- Unique Word Count: 3399
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D5 | 395 | 79 | 51 | 130 | 40 | 40 | 0.45 | 0.27 | 0.72 |
| D4 | 444 | 85 | 80 | 165 | 40 | 40 | 0.41 | 0.33 | 0.75 |
| D2 | 453 | 68 | 65 | 133 | 40 | 40 | 0.44 | 0.37 | 0.82 |
| D1 | 436 | 63 | 52 | 115 | 40 | 40 | 0.40 | 0.30 | 0.71 |
| D3 | 433 | 54 | 66 | 120 | 40 | 40 | 0.30 | 0.33 | 0.62 |
| Total | 2161 | 349 | 314 | 663 | 200 | 200 | 2.00 | 1.60 | 3.61 |



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

### Metadata File Sample (meta_test_kn.json) ###

```json
{
    "IISc_RESPIN_kn_D5_50008_570001_M_AGRI_502012_50000018": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 8.96,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "570001",
        "slab": "clean",
        "speaker_id": "50008",
        "speaker_id_reassigned": "50008_1",
        "text": "ಬಾದಾಮಿ ಮರಗಳು ಎರಡು ರೀತಿಯ ಕಾಯನ್ನು ಕೊಡ್ತವೆ ಒಂದುಸಿಹಿಯಾಗಿದ್ದರೆ ಇನ್ನೊಂದುಕಹಿಕಾಯಿಯನ್ನು ಕೊಡ್ತವೆ",
        "text_id": "502012",
        "text_type": "statement",
        "utterance_id": "50000018",
        "wav_path": "D5/50008/IISc_RESPIN_kn_D5_50008_570001_M_AGRI_502012_50000018.wav"
    },
    "IISc_RESPIN_kn_D5_50008_570001_M_AGRI_501743_50000247": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 7.29,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "570001",
        "slab": "clean",
        "speaker_id": "50008",
        "speaker_id_reassigned": "50008_1",
        "text": "ಗುಲಾಬಿ , ಮಲ್ಲಿಗೆ , ಸಂಪಿಗೆ , ಕನಕಾಂಬರ , ಮನೆಯಲ್ಲಿ ಆಕಬಹುದಾದಂತ ಹೂವಿನ ಗಿಡಗಳು",
        "text_id": "501743",
        "text_type": "statement",
        "utterance_id": "50000247",
        "wav_path": "D5/50008/IISc_RESPIN_kn_D5_50008_570001_M_AGRI_501743_50000247.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_kn_D5_50008.txt) ###
```
IISc_RESPIN_kn_D5_50008_570001_M_AGRI_502012_50000018	ಬಾದಾಮಿ ಮರಗಳು ಎರಡು ರೀತಿಯ ಕಾಯನ್ನು ಕೊಡ್ತವೆ ಒಂದುಸಿಹಿಯಾಗಿದ್ದರೆ ಇನ್ನೊಂದುಕಹಿಕಾಯಿಯನ್ನು ಕೊಡ್ತವೆ
IISc_RESPIN_kn_D5_50008_570001_M_AGRI_501743_50000247	ಗುಲಾಬಿ , ಮಲ್ಲಿಗೆ , ಸಂಪಿಗೆ , ಕನಕಾಂಬರ , ಮನೆಯಲ್ಲಿ ಆಕಬಹುದಾದಂತ ಹೂವಿನ ಗಿಡಗಳು
IISc_RESPIN_kn_D5_50008_570001_M_BANK_501551_50000264	ರೈತರ್ರು ತಾವು ಬೆಳೆದ ಬೆಳೆಗೆ ಇನ್ಸೂರೆನ್ಸ್ ಮಾಡಸ್ಸಿದ್ದರೇ ಉತ್ತಮ
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