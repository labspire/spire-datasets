## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Telugu (TE)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_te
- Total Audio Duration (HH:MM:SS): 3:22:29
- Average Sample Duration: 5.458 secs
- Total Unique Text IDs: 652
- Unique Word Count: 2964
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 526 | 73 | 95 | 168 | 40 | 40 | 0.31 | 0.49 | 0.80 |
| D2 | 558 | 81 | 84 | 165 | 40 | 40 | 0.45 | 0.45 | 0.90 |
| D4 | 533 | 89 | 63 | 152 | 40 | 40 | 0.45 | 0.33 | 0.78 |
| D3 | 609 | 93 | 74 | 167 | 40 | 40 | 0.46 | 0.44 | 0.90 |
| Total | 2226 | 336 | 316 | 652 | 160 | 160 | 1.67 | 1.70 | 3.37 |



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

### Metadata File Sample (meta_test_te.json) ###

```json
{
    "IISc_RESPIN_te_D1_90050_522412_M_AGRI_900641_90000060": {
        "age_group": "31-35",
        "age_group_reassigned": "31-35",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 6.98,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "te",
        "pincode": "522412",
        "slab": "clean",
        "speaker_id": "90050",
        "speaker_id_reassigned": "90050_1",
        "text": "ఒక వారం నుంచి భోజనం తర్వాత బొప్పాస్కాయ తింటన్నాను , తిన్న తిండి చక్కగా అరుగుతంది",
        "text_id": "900641",
        "text_type": "statement",
        "utterance_id": "90000060",
        "wav_path": "D1/90050/IISc_RESPIN_te_D1_90050_522412_M_AGRI_900641_90000060.wav"
    },
    "IISc_RESPIN_te_D1_90088_522001_M_BANK_902319_90000773": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 8.09,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "te",
        "pincode": "522001",
        "slab": "clean",
        "speaker_id": "90088",
        "speaker_id_reassigned": "90088_1",
        "text": "ఎంపీల్యాడ్స్ నిధులను ఏ ప్రాజెక్ట్ కోసం అమలు చెయ్యాలో కూడా కొన్ని నియమాలున్నాయి",
        "text_id": "902319",
        "text_type": "statement",
        "utterance_id": "90000773",
        "wav_path": "D1/90088/IISc_RESPIN_te_D1_90088_522001_M_BANK_902319_90000773.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_te_D1_90050.txt) ###
```
IISc_RESPIN_te_D1_90050_522412_M_AGRI_900641_90000060	ఒక వారం నుంచి భోజనం తర్వాత బొప్పాస్కాయ తింటన్నాను , తిన్న తిండి చక్కగా అరుగుతంది
IISc_RESPIN_te_D1_90050_522412_M_BANK_900386_90021704	మన సేవింగ్స్ అకౌంట్ ని శాలరీ అకౌంట్ గా మార్చుకోవడం వలన చాలా రకాల లాభాలున్నాయి
IISc_RESPIN_te_D1_90050_522412_M_BANK_902226_90021726	పెద్ద పెద్ద హైవేల పైన వెళ్తున్నప్పుడు కొన్ని టోలు గేటులుంటాయని మా మేష్టారు చెప్పారు
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