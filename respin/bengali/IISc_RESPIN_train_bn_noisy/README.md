## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bengali (BN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_bn_noisy
- Total Audio Duration (HH:MM:SS): 5:46:13
- Average Sample Duration: 3.154 secs
- Total Unique Text IDs: 5393
- Unique Word Count: 9029
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 1493 | 758 | 495 | 1253 | 174 | 25 | 0.58 | 0.39 | 0.98 |
| D2 | 756 | 365 | 329 | 694 | 136 | 33 | 0.37 | 0.29 | 0.66 |
| D5 | 982 | 467 | 322 | 789 | 165 | 42 | 0.67 | 0.50 | 1.17 |
| D1 | 1178 | 547 | 485 | 1032 | 156 | 54 | 0.64 | 0.51 | 1.15 |
| D4 | 2178 | 860 | 765 | 1625 | 174 | 72 | 0.96 | 0.85 | 1.82 |
| Total | 6587 | 2997 | 2396 | 5393 | 805 | 222 | 3.22 | 2.55 | 5.77 |



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

### Metadata File Sample (meta_train_bn_noisy.json) ###

```json
{
    "IISc_RESPIN_bn_D3_21825_221001_F_AGRI_210965_20000004": {
        "age_group": "41-45",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 4.81,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "bn",
        "pincode": "221001",
        "slab": "noisy",
        "speaker_id": "21825",
        "speaker_id_reassigned": "NA",
        "text": "কম্পোস্টিং করা মানে যখন জৈব পদার্থকে পচিয়ে তাকে সার হিসেবে ব্যবহার করা হয়",
        "text_id": "210965",
        "text_type": "statement",
        "utterance_id": "20000004",
        "wav_path": "D3/21825/IISc_RESPIN_bn_D3_21825_221001_F_AGRI_210965_20000004.wav"
    },
    "IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209923_20000005": {
        "age_group": "41-45",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 5.91,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "bn",
        "pincode": "221001",
        "slab": "noisy",
        "speaker_id": "21825",
        "speaker_id_reassigned": "NA",
        "text": "একধরনের সরকারি উদ্যোগ প্রধানমন্ত্রী ফসল বীমা যোজনা আর্থিক সহায়তা দেয়",
        "text_id": "209923",
        "text_type": "statement",
        "utterance_id": "20000005",
        "wav_path": "D3/21825/IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209923_20000005.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bn_D3_21825.txt) ###
```
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_210965_20000004	কম্পোস্টিং করা মানে যখন জৈব পদার্থকে পচিয়ে তাকে সার হিসেবে ব্যবহার করা হয়
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209923_20000005	একধরনের সরকারি উদ্যোগ প্রধানমন্ত্রী ফসল বীমা যোজনা আর্থিক সহায়তা দেয়
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209148_20000006	গরু মহিষের যেমন গবাদি কন্ট্রোল্ড ভাবে অনুকরন করা হয়
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