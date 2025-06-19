## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Hindi (HI)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_hi
- Total Audio Duration (HH:MM:SS): 3:18:05
- Average Sample Duration: 5.195 secs
- Total Unique Text IDs: 853
- Unique Word Count: 2774
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 401 | 85 | 60 | 145 | 40 | 40 | 0.29 | 0.19 | 0.48 |
| D5 | 441 | 58 | 56 | 114 | 40 | 40 | 0.34 | 0.35 | 0.68 |
| D2 | 520 | 129 | 130 | 259 | 41 | 41 | 0.43 | 0.39 | 0.82 |
| D3 | 396 | 55 | 55 | 110 | 40 | 40 | 0.23 | 0.24 | 0.48 |
| D4 | 530 | 126 | 99 | 225 | 40 | 40 | 0.44 | 0.40 | 0.84 |
| Total | 2288 | 453 | 400 | 853 | 201 | 201 | 1.74 | 1.57 | 3.30 |



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

### Metadata File Sample (meta_test_hi.json) ###

```json
{
    "IISc_RESPIN_hi_D1_40042_251001_F_BANK_400361_40000764": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 7.0,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "hi",
        "pincode": "251001",
        "slab": "clean",
        "speaker_id": "40042",
        "speaker_id_reassigned": "40042_1",
        "text": "कर माफी उन लोगों के लिए है जो सालों से अपनी संपत्ति को छिपाते हैं",
        "text_id": "400361",
        "text_type": "statement",
        "utterance_id": "40000764",
        "wav_path": "D1/40042/IISc_RESPIN_hi_D1_40042_251001_F_BANK_400361_40000764.wav"
    },
    "IISc_RESPIN_hi_D1_40042_251001_F_BANK_401691_40000785": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 3.2,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "hi",
        "pincode": "251001",
        "slab": "clean",
        "speaker_id": "40042",
        "speaker_id_reassigned": "40042_1",
        "text": "ऑडिटर ने खाता बखूबी मिलाया",
        "text_id": "401691",
        "text_type": "statement",
        "utterance_id": "40000785",
        "wav_path": "D1/40042/IISc_RESPIN_hi_D1_40042_251001_F_BANK_401691_40000785.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_hi_D1_40042.txt) ###
```
IISc_RESPIN_hi_D1_40042_251001_F_BANK_400361_40000764	कर माफी उन लोगों के लिए है जो सालों से अपनी संपत्ति को छिपाते हैं
IISc_RESPIN_hi_D1_40042_251001_F_BANK_401691_40000785	ऑडिटर ने खाता बखूबी मिलाया
IISc_RESPIN_hi_D1_40042_251001_F_AGRI_400641_40006396	कुछ कीटनाशक स्प्रेयर रॉकिंग स्प्रेयर होते हैं
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