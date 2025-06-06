## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bhojpuri (BH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_bh_seminoisy
- Total Audio Duration (HH:MM:SS): 91:49:39
- Average Sample Duration: 5.682 secs
- Total Unique Text IDs: 16493
- Unique Word Count: 12185
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D2 | 6211 | 1816 | 1791 | 3607 | 390 | 230 | 4.78 | 5.33 | 10.11 |
| D1 | 17194 | 3333 | 2803 | 6136 | 500 | 422 | 14.94 | 13.21 | 28.15 |
| D3 | 34774 | 3908 | 2842 | 6750 | 615 | 403 | 28.54 | 25.02 | 53.57 |
| Total | 58179 | 9057 | 7436 | 16493 | 1505 | 1053 | 48.27 | 43.56 | 91.83 |



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

### Metadata File Sample (meta_train_bh_seminoisy.json) ###

```json
{
    "IISc_RESPIN_bh_D2_10988_221001_F_AGRI_111961_10000739": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D2",
        "domain": "Agriculture",
        "duration": 6.17,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "bh",
        "pincode": "221001",
        "slab": "seminoisy",
        "speaker_id": "10988",
        "speaker_id_reassigned": "10988_1",
        "text": "सबसे पहिले कागज चीन में तइयार कइल जात रहे",
        "text_id": "111961",
        "text_type": "statement",
        "utterance_id": "10000739",
        "wav_path": "D2/10988/IISc_RESPIN_bh_D2_10988_221001_F_AGRI_111961_10000739.wav"
    },
    "IISc_RESPIN_bh_D2_10988_221001_F_BANK_111978_10000741": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D2",
        "domain": "Banking",
        "duration": 8.02,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "bh",
        "pincode": "221001",
        "slab": "seminoisy",
        "speaker_id": "10988",
        "speaker_id_reassigned": "10988_1",
        "text": "बैंक के जब जरूरत हो तब आपन पइसा मांग सकला",
        "text_id": "111978",
        "text_type": "statement",
        "utterance_id": "10000741",
        "wav_path": "D2/10988/IISc_RESPIN_bh_D2_10988_221001_F_BANK_111978_10000741.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bh_D2_10988.txt) ###
```
IISc_RESPIN_bh_D2_10988_221001_F_AGRI_111961_10000739	सबसे पहिले कागज चीन में तइयार कइल जात रहे
IISc_RESPIN_bh_D2_10988_221001_F_BANK_111978_10000741	बैंक के जब जरूरत हो तब आपन पइसा मांग सकला
IISc_RESPIN_bh_D2_10988_221001_F_AGRI_110336_10000744	भारत क अर्थव्यवस्था में कागज व्यवसाय क बड़ा योगदान हौ
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