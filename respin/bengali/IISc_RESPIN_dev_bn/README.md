## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bengali (BN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_bn
- Total Audio Duration (HH:MM:SS): 2:16:22
- Average Sample Duration: 5.455 secs
- Total Unique Text IDs: 494
- Unique Word Count: 2039
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 300 | 59 | 26 | 85 | 20 | 20 | 0.36 | 0.16 | 0.52 |
| D5 | 300 | 66 | 37 | 103 | 20 | 20 | 0.29 | 0.16 | 0.45 |
| D2 | 300 | 49 | 50 | 99 | 20 | 20 | 0.21 | 0.24 | 0.45 |
| D1 | 300 | 61 | 42 | 103 | 20 | 20 | 0.24 | 0.18 | 0.42 |
| D4 | 300 | 56 | 48 | 104 | 20 | 20 | 0.23 | 0.20 | 0.43 |
| Total | 1500 | 291 | 203 | 494 | 100 | 100 | 1.33 | 0.94 | 2.27 |



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

### Metadata File Sample (meta_dev_bn.json) ###

```json
{
    "IISc_RESPIN_bn_D3_21023_700096_F_AGRI_209142_20001411": {
        "age_group": "41-45",
        "age_group_reassigned": "41-45",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.24,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "bn",
        "pincode": "700096",
        "slab": "clean",
        "speaker_id": "21023",
        "speaker_id_reassigned": "21023_2",
        "text": "চিকেন হারভেস্টার মেশিনে পোল্ট্রি ফার্মের মুরগি জবাই করে",
        "text_id": "209142",
        "text_type": "statement",
        "utterance_id": "20001411",
        "wav_path": "D3/21023/IISc_RESPIN_bn_D3_21023_700096_F_AGRI_209142_20001411.wav"
    },
    "IISc_RESPIN_bn_D3_21046_700153_F_AGRI_208885_20002724": {
        "age_group": "46-50",
        "age_group_reassigned": "46-50",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 10.34,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "bn",
        "pincode": "700153",
        "slab": "clean",
        "speaker_id": "21046",
        "speaker_id_reassigned": "21046_2",
        "text": "জোয়ান বা ক্যারম সীড ভিটামিন এবং অ্যান্টিঅক্সিডেন্টে পরিপূর্ণ",
        "text_id": "208885",
        "text_type": "statement",
        "utterance_id": "20002724",
        "wav_path": "D3/21046/IISc_RESPIN_bn_D3_21046_700153_F_AGRI_208885_20002724.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bn_D3_21023.txt) ###
```
IISc_RESPIN_bn_D3_21023_700096_F_AGRI_209142_20001411	চিকেন হারভেস্টার মেশিনে পোল্ট্রি ফার্মের মুরগি জবাই করে
IISc_RESPIN_bn_D3_21023_700096_F_AGRI_208764_20011396	উড ওয়ার্ম হচ্ছে এক ধরণের পোকা যেটা কাঠের ভেতরে বাসা বেঁধে কাঠকে ক্ষইয়ে দেয়
IISc_RESPIN_bn_D3_21023_700096_F_AGRI_208576_20011401	রিচ গোর্ড বা ঝিঙে হল এক রকমের পুষ্টিকর সবজি যেটিকে আমরা খাদ্য হিসেবে গ্রহণ করি
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