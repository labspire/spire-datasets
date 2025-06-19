## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Hindi (HI)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_hi
- Total Audio Duration (HH:MM:SS): 2:12:30
- Average Sample Duration: 5.166 secs
- Total Unique Text IDs: 722
- Unique Word Count: 2522
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D5 | 286 | 49 | 38 | 87 | 20 | 20 | 0.24 | 0.17 | 0.41 |
| D3 | 300 | 56 | 42 | 98 | 20 | 20 | 0.19 | 0.16 | 0.35 |
| D1 | 272 | 51 | 48 | 99 | 20 | 20 | 0.15 | 0.16 | 0.30 |
| D2 | 331 | 114 | 108 | 222 | 20 | 20 | 0.28 | 0.28 | 0.56 |
| D4 | 350 | 118 | 98 | 216 | 20 | 20 | 0.31 | 0.27 | 0.58 |
| Total | 1539 | 388 | 334 | 722 | 100 | 100 | 1.17 | 1.03 | 2.21 |



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

### Metadata File Sample (meta_dev_hi.json) ###

```json
{
    "IISc_RESPIN_hi_D5_40291_249180_M_AGRI_417597_40029387": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D5",
        "domain": "Agriculture",
        "duration": 3.02,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "hi",
        "pincode": "249180",
        "slab": "clean",
        "speaker_id": "40291",
        "speaker_id_reassigned": "40291_1",
        "text": "मंडुवा से क्या बनाया जाता है ?",
        "text_id": "417597",
        "text_type": "question",
        "utterance_id": "40029387",
        "wav_path": "D5/40291/IISc_RESPIN_hi_D5_40291_249180_M_AGRI_417597_40029387.wav"
    },
    "IISc_RESPIN_hi_D3_40171_210430_M_AGRI_408904_40039722": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 4.58,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "hi",
        "pincode": "210430",
        "slab": "clean",
        "speaker_id": "40171",
        "speaker_id_reassigned": "40171_1",
        "text": "क्या पेपरमिंट की जगह फसल चक्रण में तिलहन की पैदावार अच्छी होती है ?",
        "text_id": "408904",
        "text_type": "question",
        "utterance_id": "40039722",
        "wav_path": "D3/40171/IISc_RESPIN_hi_D3_40171_210430_M_AGRI_408904_40039722.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_hi_D5_40291.txt) ###
```
IISc_RESPIN_hi_D5_40291_249180_M_AGRI_417597_40029387	मंडुवा से क्या बनाया जाता है ?
IISc_RESPIN_hi_D5_40291_249180_M_AGRI_417430_40055037	पथरीली जमीन पर कौन सी फसल उगाई जाए ?
IISc_RESPIN_hi_D5_40291_249180_M_AGRI_417566_40055187	आलू उत्पादन एक हेक्टेयर में कितनी उर्वरक डालनी पड़ती है ?
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