## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Hindi (HI)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_hi_noisy
- Total Audio Duration (HH:MM:SS): 304:33:05
- Average Sample Duration: 5.886 secs
- Total Unique Text IDs: 19286
- Unique Word Count: 15724
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 43947 | 1993 | 2053 | 4046 | 509 | 401 | 31.85 | 35.83 | 67.68 |
| D5 | 26284 | 2004 | 2023 | 4027 | 371 | 295 | 23.96 | 23.20 | 47.16 |
| D2 | 37940 | 1862 | 1818 | 3680 | 495 | 528 | 28.62 | 30.80 | 59.42 |
| D3 | 39474 | 2069 | 1990 | 4059 | 465 | 550 | 30.76 | 30.41 | 61.17 |
| D4 | 38630 | 1831 | 1781 | 3612 | 474 | 451 | 34.86 | 34.25 | 69.11 |
| Total | 186275 | 9759 | 9665 | 19286 | 2314 | 2221 | 150.06 | 154.49 | 304.55 |



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

### Metadata File Sample (meta_train_hi_noisy.json) ###

```json
{
    "IISc_RESPIN_hi_D1_40002_251001_M_BANK_402107_40000018": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 5.46,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "hi",
        "pincode": "251001",
        "slab": "noisy",
        "speaker_id": "40002",
        "speaker_id_reassigned": "NA",
        "text": "रिकरिंग डिपॉजिट के लिए में आज मख्य पोस्ट ऑफिस गयी थी",
        "text_id": "402107",
        "text_type": "statement",
        "utterance_id": "40000018",
        "wav_path": "D1/40002/IISc_RESPIN_hi_D1_40002_251001_M_BANK_402107_40000018.wav"
    },
    "IISc_RESPIN_hi_D1_40002_251001_M_BANK_401092_40000019": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 6.69,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "hi",
        "pincode": "251001",
        "slab": "noisy",
        "speaker_id": "40002",
        "speaker_id_reassigned": "NA",
        "text": "वित्तीय लेखांकन मानक बोर्ड का उद्देश्य जनहित सिद्धांतों को स्थापित करना है",
        "text_id": "401092",
        "text_type": "statement",
        "utterance_id": "40000019",
        "wav_path": "D1/40002/IISc_RESPIN_hi_D1_40002_251001_M_BANK_401092_40000019.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_hi_D1_40002.txt) ###
```
IISc_RESPIN_hi_D1_40002_251001_M_BANK_402107_40000018	रिकरिंग डिपॉजिट के लिए में आज मख्य पोस्ट ऑफिस गयी थी
IISc_RESPIN_hi_D1_40002_251001_M_BANK_401092_40000019	वित्तीय लेखांकन मानक बोर्ड का उद्देश्य जनहित सिद्धांतों को स्थापित करना है
IISc_RESPIN_hi_D1_40002_251001_M_AGRI_401940_40000351	शुष्क क्षेत्र में बसंत ऋतु में कटहल की जिरीयां लगती है
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