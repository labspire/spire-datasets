## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Kannada (KN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_kn
- Total Audio Duration (HH:MM:SS): 2:21:57
- Average Sample Duration: 5.956 secs
- Total Unique Text IDs: 518
- Unique Word Count: 2799
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D5 | 293 | 76 | 46 | 122 | 20 | 20 | 0.36 | 0.17 | 0.53 |
| D2 | 286 | 54 | 43 | 97 | 20 | 20 | 0.28 | 0.24 | 0.52 |
| D4 | 286 | 47 | 55 | 102 | 20 | 20 | 0.21 | 0.24 | 0.45 |
| D3 | 265 | 51 | 46 | 97 | 20 | 20 | 0.24 | 0.16 | 0.40 |
| D1 | 300 | 59 | 41 | 100 | 20 | 20 | 0.27 | 0.20 | 0.47 |
| Total | 1430 | 287 | 231 | 518 | 100 | 100 | 1.35 | 1.02 | 2.37 |



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

### Metadata File Sample (meta_dev_kn.json) ###

```json
{
    "IISc_RESPIN_kn_D5_50126_570001_M_AGRI_500363_50000207": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 6.13,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "570001",
        "slab": "clean",
        "speaker_id": "50126",
        "speaker_id_reassigned": "50126_1",
        "text": "ಕಳೆ ಕೊಚ್ಚುವ ಯಂತ್ರವನ್ನು ಸಬ್ಸಿಡಿ ದರದಲ್ಲಿ ಕೃಷಿ ಇಲಾಖೆಯಿಂದ ರೈತ್ರು ತಗೋಬೋದು",
        "text_id": "500363",
        "text_type": "statement",
        "utterance_id": "50000207",
        "wav_path": "D5/50126/IISc_RESPIN_kn_D5_50126_570001_M_AGRI_500363_50000207.wav"
    },
    "IISc_RESPIN_kn_D5_50126_570001_M_AGRI_502593_50000221": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 8.93,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "570001",
        "slab": "clean",
        "speaker_id": "50126",
        "speaker_id_reassigned": "50126_1",
        "text": "ಕಳೆ ನಿರ್ಮೂಲನೆ ಬದಲಾಗಿ ಕಳೆ ನಿಗ್ರಹ ಹಾಗೂ ಕಳೆಗಳ ಮೇಲೆ ಫೈಟೊಟಾಕ್ಸಿಕ್ ಪರಿಣಾಮವನ್ನು ಹೆಚ್ಛಿಸ್ತದೆ",
        "text_id": "502593",
        "text_type": "statement",
        "utterance_id": "50000221",
        "wav_path": "D5/50126/IISc_RESPIN_kn_D5_50126_570001_M_AGRI_502593_50000221.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_kn_D5_50126.txt) ###
```
IISc_RESPIN_kn_D5_50126_570001_M_AGRI_500363_50000207	ಕಳೆ ಕೊಚ್ಚುವ ಯಂತ್ರವನ್ನು ಸಬ್ಸಿಡಿ ದರದಲ್ಲಿ ಕೃಷಿ ಇಲಾಖೆಯಿಂದ ರೈತ್ರು ತಗೋಬೋದು
IISc_RESPIN_kn_D5_50126_570001_M_AGRI_502593_50000221	ಕಳೆ ನಿರ್ಮೂಲನೆ ಬದಲಾಗಿ ಕಳೆ ನಿಗ್ರಹ ಹಾಗೂ ಕಳೆಗಳ ಮೇಲೆ ಫೈಟೊಟಾಕ್ಸಿಕ್ ಪರಿಣಾಮವನ್ನು ಹೆಚ್ಛಿಸ್ತದೆ
IISc_RESPIN_kn_D5_50126_570001_M_AGRI_500281_50000225	ದ್ರಾಕ್ಷಿ ಗಿಡವನ್ನು ಬಳ್ಳಿಯಂತೆ ಹಬ್ಬುವುದರಿಂದ ಅದನ್ನು ಚಪ್ಪರಕಟ್ಟಿ ಬೆಳೆಸಬೇಕು
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