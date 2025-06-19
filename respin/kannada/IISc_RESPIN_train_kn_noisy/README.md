## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Kannada (KN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_kn_noisy
- Total Audio Duration (HH:MM:SS): 191:11:05
- Average Sample Duration: 7.037 secs
- Total Unique Text IDs: 21918
- Unique Word Count: 47610
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D5 | 17233 | 2998 | 1835 | 4833 | 410 | 347 | 24.10 | 12.41 | 36.51 |
| D2 | 17067 | 2427 | 2326 | 4753 | 344 | 303 | 17.06 | 15.57 | 32.62 |
| D4 | 20322 | 2293 | 2154 | 4447 | 401 | 337 | 21.22 | 17.80 | 39.02 |
| D3 | 19614 | 2091 | 2297 | 4388 | 364 | 316 | 17.75 | 20.48 | 38.23 |
| D1 | 23570 | 1684 | 1856 | 3540 | 420 | 388 | 22.27 | 22.53 | 44.80 |
| Total | 97806 | 11493 | 10468 | 21918 | 1939 | 1687 | 102.40 | 88.78 | 191.18 |



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

### Metadata File Sample (meta_train_kn_noisy.json) ###

```json
{
    "IISc_RESPIN_kn_D5_50012_560064_M_AGRI_502572_50000049": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 11.8,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "560064",
        "slab": "noisy",
        "speaker_id": "50012",
        "speaker_id_reassigned": "50012_1",
        "text": "ಸಮುದ್ರ ಮೀನಲ್ಲಿ ಹ್ಯಾಗ್ಫಿಶ್ಲ್ಯಾಂಪ್ರೇಮತ್ತುಕಾರ್ಟಿಲ್ಯಾಜಿನಸ್ ಹಾಗೂ ಎಲುಬಿನಮೀನು ಅಳಿವಿನಲ್ಲಿದಾವೆ",
        "text_id": "502572",
        "text_type": "statement",
        "utterance_id": "50000049",
        "wav_path": "D5/50012/IISc_RESPIN_kn_D5_50012_560064_M_AGRI_502572_50000049.wav"
    },
    "IISc_RESPIN_kn_D5_50012_560064_M_AGRI_503090_50000079": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 2.77,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "kn",
        "pincode": "560064",
        "slab": "noisy",
        "speaker_id": "50012",
        "speaker_id_reassigned": "50012_1",
        "text": "ಹತ್ತಿ ಭಾರತದ ವಾಣಿಜ್ಯ ಬೆಳೆಯಾಗಯ್ತೆ ಅನಾದಿಕಾಲ್ದಿಂದಲೂ ಹತ್ತಿ ಭಾರತ ಜನಜೀವನ್ದಲ್ಲಿ ಒಂದಾಗೈತೆ",
        "text_id": "503090",
        "text_type": "statement",
        "utterance_id": "50000079",
        "wav_path": "D5/50012/IISc_RESPIN_kn_D5_50012_560064_M_AGRI_503090_50000079.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_kn_D5_50012.txt) ###
```
IISc_RESPIN_kn_D5_50012_560064_M_AGRI_502572_50000049	ಸಮುದ್ರ ಮೀನಲ್ಲಿ ಹ್ಯಾಗ್ಫಿಶ್ಲ್ಯಾಂಪ್ರೇಮತ್ತುಕಾರ್ಟಿಲ್ಯಾಜಿನಸ್ ಹಾಗೂ ಎಲುಬಿನಮೀನು ಅಳಿವಿನಲ್ಲಿದಾವೆ
IISc_RESPIN_kn_D5_50012_560064_M_AGRI_503090_50000079	ಹತ್ತಿ ಭಾರತದ ವಾಣಿಜ್ಯ ಬೆಳೆಯಾಗಯ್ತೆ ಅನಾದಿಕಾಲ್ದಿಂದಲೂ ಹತ್ತಿ ಭಾರತ ಜನಜೀವನ್ದಲ್ಲಿ ಒಂದಾಗೈತೆ
IISc_RESPIN_kn_D5_50012_560064_M_BANK_500873_50000739	ಬ್ಯಾಂಕಿನ ವ್ಯವಹಾರಗಳು ಆರ್.ಬಿ.ಐನ ರೆಗುಲೇಷನ್ಗೆ ಒಳಪಟ್ಟಿರುತ್ತದೆ
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