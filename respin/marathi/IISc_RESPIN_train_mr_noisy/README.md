## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Marathi (MR)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mr_noisy
- Total Audio Duration (HH:MM:SS): 174:09:39
- Average Sample Duration: 5.704 secs
- Total Unique Text IDs: 20306
- Unique Word Count: 32976
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 33261 | 2337 | 3284 | 5621 | 729 | 492 | 21.36 | 29.94 | 51.29 |
| D3 | 15729 | 1992 | 1928 | 3920 | 598 | 454 | 10.87 | 9.96 | 20.83 |
| D4 | 34712 | 2661 | 2550 | 5211 | 745 | 647 | 30.40 | 27.68 | 58.08 |
| D2 | 26208 | 2893 | 2661 | 5554 | 562 | 518 | 22.99 | 20.96 | 43.95 |
| Total | 109910 | 9883 | 10423 | 20306 | 2634 | 2108 | 85.62 | 88.54 | 174.16 |



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

### Metadata File Sample (meta_train_mr_noisy.json) ###

```json
{
    "IISc_RESPIN_mr_D1_70125_670143_F_AGRI_707427_70000001": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 0.97,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "mr",
        "pincode": "670143",
        "slab": "noisy",
        "speaker_id": "70125",
        "speaker_id_reassigned": "NA",
        "text": "कापणी झाल्यावर पिकाचो उपयोगी भाग कापून ट्रकमध्ये भरलो जाता",
        "text_id": "707427",
        "text_type": "statement",
        "utterance_id": "70000001",
        "wav_path": "D1/70125/IISc_RESPIN_mr_D1_70125_670143_F_AGRI_707427_70000001.wav"
    },
    "IISc_RESPIN_mr_D3_70002_416510_F_BANK_701105_70000002": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 7.46,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "mr",
        "pincode": "416510",
        "slab": "noisy",
        "speaker_id": "70002",
        "speaker_id_reassigned": "NA",
        "text": "घर घेण्यासाठी कोणती योजना आहे ?",
        "text_id": "701105",
        "text_type": "question",
        "utterance_id": "70000002",
        "wav_path": "D3/70002/IISc_RESPIN_mr_D3_70002_416510_F_BANK_701105_70000002.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mr_D1_70125.txt) ###
```
IISc_RESPIN_mr_D1_70125_670143_F_AGRI_707427_70000001	कापणी झाल्यावर पिकाचो उपयोगी भाग कापून ट्रकमध्ये भरलो जाता


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