## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Marathi (MR)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_mr
- Total Audio Duration (HH:MM:SS): 3:02:29
- Average Sample Duration: 5.046 secs
- Total Unique Text IDs: 711
- Unique Word Count: 3028
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 555 | 84 | 65 | 149 | 40 | 40 | 0.42 | 0.34 | 0.76 |
| D1 | 559 | 105 | 107 | 212 | 40 | 40 | 0.44 | 0.41 | 0.85 |
| D4 | 516 | 82 | 116 | 198 | 40 | 40 | 0.29 | 0.43 | 0.73 |
| D2 | 540 | 72 | 80 | 152 | 40 | 40 | 0.36 | 0.34 | 0.70 |
| Total | 2170 | 343 | 368 | 711 | 160 | 160 | 1.51 | 1.53 | 3.04 |



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

### Metadata File Sample (meta_test_mr.json) ###

```json
{
    "IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700256_70000268": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.76,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mr",
        "pincode": "411011",
        "slab": "clean",
        "speaker_id": "70093",
        "speaker_id_reassigned": "70093_1",
        "text": "बकरी किंवा मेंढीपासून खत मिळते का ?",
        "text_id": "700256",
        "text_type": "question",
        "utterance_id": "70000268",
        "wav_path": "D3/70093/IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700256_70000268.wav"
    },
    "IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700289_70000298": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.02,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mr",
        "pincode": "411011",
        "slab": "clean",
        "speaker_id": "70093",
        "speaker_id_reassigned": "70093_1",
        "text": "ठिबक सिंचनाची जोडणी कशी असावी ?",
        "text_id": "700289",
        "text_type": "question",
        "utterance_id": "70000298",
        "wav_path": "D3/70093/IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700289_70000298.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mr_D3_70093.txt) ###
```
IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700256_70000268	बकरी किंवा मेंढीपासून खत मिळते का ?
IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700289_70000298	ठिबक सिंचनाची जोडणी कशी असावी ?
IISc_RESPIN_mr_D3_70093_411011_F_BANK_700808_70000923	के.वाय.सी फॉर्म भरणे गरजेचे असते का ?
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