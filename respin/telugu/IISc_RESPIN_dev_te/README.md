## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Telugu (TE)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_te
- Total Audio Duration (HH:MM:SS): 2:18:07
- Average Sample Duration: 5.763 secs
- Total Unique Text IDs: 500
- Unique Word Count: 2444
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 360 | 52 | 65 | 117 | 20 | 20 | 0.26 | 0.34 | 0.60 |
| D2 | 360 | 70 | 58 | 128 | 20 | 20 | 0.30 | 0.26 | 0.56 |
| D3 | 360 | 79 | 49 | 128 | 20 | 20 | 0.37 | 0.21 | 0.58 |
| D4 | 358 | 64 | 63 | 127 | 20 | 20 | 0.27 | 0.29 | 0.56 |
| Total | 1438 | 265 | 235 | 500 | 80 | 80 | 1.21 | 1.09 | 2.30 |



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

### Metadata File Sample (meta_dev_te.json) ###

```json
{
    "IISc_RESPIN_te_D1_90130_524101_F_BANK_902401_90000644": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 9.65,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "te",
        "pincode": "524101",
        "slab": "clean",
        "speaker_id": "90130",
        "speaker_id_reassigned": "90130_1",
        "text": "టర్మ్ సేవింగ్స్ చెయ్యడం కోసం ఖాతాని ఓపెన్ చేయాలంటే తప్పనిసరిగా ఆధార్ కార్డు కావాలి",
        "text_id": "902401",
        "text_type": "statement",
        "utterance_id": "90000644",
        "wav_path": "D1/90130/IISc_RESPIN_te_D1_90130_524101_F_BANK_902401_90000644.wav"
    },
    "IISc_RESPIN_te_D1_90130_524101_F_AGRI_900593_90000678": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 9.49,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "te",
        "pincode": "524101",
        "slab": "clean",
        "speaker_id": "90130",
        "speaker_id_reassigned": "90130_1",
        "text": "వాతావరణంలో ఉష్ణోగ్రతల్లో మార్పులొస్తే వైన్ ద్రాక్షా పంటకి ఇబ్బందవుతుంది",
        "text_id": "900593",
        "text_type": "statement",
        "utterance_id": "90000678",
        "wav_path": "D1/90130/IISc_RESPIN_te_D1_90130_524101_F_AGRI_900593_90000678.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_te_D1_90130.txt) ###
```
IISc_RESPIN_te_D1_90130_524101_F_BANK_902401_90000644	టర్మ్ సేవింగ్స్ చెయ్యడం కోసం ఖాతాని ఓపెన్ చేయాలంటే తప్పనిసరిగా ఆధార్ కార్డు కావాలి
IISc_RESPIN_te_D1_90130_524101_F_AGRI_900593_90000678	వాతావరణంలో ఉష్ణోగ్రతల్లో మార్పులొస్తే వైన్ ద్రాక్షా పంటకి ఇబ్బందవుతుంది
IISc_RESPIN_te_D1_90130_524101_F_BANK_900507_90000779	అకౌంటింగ్ ప్రమాణాలు ఆర్థిక లావాదేవీల కొలతకు మార్గాలను సెట్ చేస్తది
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