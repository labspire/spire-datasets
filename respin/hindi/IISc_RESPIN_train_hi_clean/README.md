## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Hindi (HI)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_hi_clean
- Total Audio Duration (HH:MM:SS): 712:36:40
- Average Sample Duration: 4.465 secs
- Total Unique Text IDs: 19345
- Unique Word Count: 15712
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 144135 | 1997 | 2054 | 4051 | 510 | 402 | 78.17 | 82.20 | 160.38 |
| D5 | 120714 | 2034 | 2049 | 4083 | 370 | 295 | 89.88 | 92.92 | 182.80 |
| D2 | 103336 | 1863 | 1818 | 3681 | 491 | 528 | 62.16 | 56.80 | 118.96 |
| D3 | 123406 | 2070 | 1986 | 4056 | 466 | 550 | 75.83 | 71.06 | 146.89 |
| D4 | 82953 | 1829 | 1783 | 3612 | 468 | 445 | 49.43 | 54.16 | 103.59 |
| Total | 574544 | 9793 | 9690 | 19345 | 2305 | 2216 | 355.48 | 357.14 | 712.61 |



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

### Metadata File Sample (meta_train_hi_clean.json) ###

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