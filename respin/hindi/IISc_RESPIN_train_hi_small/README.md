## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Hindi (HI)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_hi_small
- Total Audio Duration (HH:MM:SS): 128:28:27
- Average Sample Duration: 5.391 secs
- Total Unique Text IDs: 17160
- Unique Word Count: 14673
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 17160 | 1716 | 1716 | 3432 | 467 | 330 | 12.39 | 12.48 | 24.88 |
| D2 | 17160 | 1716 | 1716 | 3432 | 470 | 463 | 11.95 | 12.43 | 24.38 |
| D5 | 17160 | 1716 | 1716 | 3432 | 336 | 268 | 14.37 | 14.47 | 28.84 |
| D3 | 17160 | 1716 | 1716 | 3432 | 431 | 473 | 12.11 | 12.19 | 24.30 |
| D4 | 17160 | 1709 | 1723 | 3432 | 468 | 430 | 12.92 | 13.16 | 26.08 |
| Total | 85800 | 8573 | 8587 | 17160 | 2172 | 1960 | 63.75 | 64.73 | 128.47 |



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

### Metadata File Sample (meta_train_hi_small.json) ###

```json
{
    "IISc_RESPIN_hi_D1_40002_251001_M_AGRI_402372_40000001": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 5.47,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "hi",
        "pincode": "251001",
        "slab": "clean",
        "speaker_id": "40002",
        "speaker_id_reassigned": "NA",
        "text": "पोखरण के प्रशिक्षण के दौरान प्याज का भाव बहुत ऊपर उठ गया था",
        "text_id": "402372",
        "text_type": "statement",
        "utterance_id": "40000001",
        "wav_path": "D1/40002/IISc_RESPIN_hi_D1_40002_251001_M_AGRI_402372_40000001.wav"
    },
    "IISc_RESPIN_hi_D1_40002_251001_M_AGRI_401495_40000002": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 5.65,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "hi",
        "pincode": "251001",
        "slab": "clean",
        "speaker_id": "40002",
        "speaker_id_reassigned": "NA",
        "text": "मार्शल कार्बोनेट समूह का एक विश्व प्रसिद्ध कीटनाशक है",
        "text_id": "401495",
        "text_type": "statement",
        "utterance_id": "40000002",
        "wav_path": "D1/40002/IISc_RESPIN_hi_D1_40002_251001_M_AGRI_401495_40000002.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_hi_D1_40002.txt) ###
```
IISc_RESPIN_hi_D1_40002_251001_M_AGRI_402372_40000001	पोखरण के प्रशिक्षण के दौरान प्याज का भाव बहुत ऊपर उठ गया था
IISc_RESPIN_hi_D1_40002_251001_M_AGRI_401495_40000002	मार्शल कार्बोनेट समूह का एक विश्व प्रसिद्ध कीटनाशक है
IISc_RESPIN_hi_D1_40002_251001_M_AGRI_400729_40000003	कश्मीर के केसर को जी.आई टैग मिला है
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