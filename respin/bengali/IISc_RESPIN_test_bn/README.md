## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bengali (BN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_bn
- Total Audio Duration (HH:MM:SS): 3:15:42
- Average Sample Duration: 5.401 secs
- Total Unique Text IDs: 648
- Unique Word Count: 2361
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 455 | 68 | 42 | 110 | 40 | 40 | 0.46 | 0.26 | 0.71 |
| D2 | 455 | 56 | 60 | 116 | 40 | 40 | 0.27 | 0.35 | 0.62 |
| D5 | 449 | 77 | 47 | 124 | 40 | 40 | 0.48 | 0.24 | 0.72 |
| D4 | 402 | 89 | 77 | 166 | 40 | 40 | 0.34 | 0.31 | 0.65 |
| D1 | 413 | 73 | 59 | 132 | 40 | 40 | 0.32 | 0.24 | 0.56 |
| Total | 2174 | 363 | 285 | 648 | 200 | 200 | 1.87 | 1.39 | 3.26 |



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

### Metadata File Sample (meta_test_bn.json) ###

```json
{
    "IISc_RESPIN_bn_D3_21204_700039_F_AGRI_211235_20000484": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.33,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "bn",
        "pincode": "700039",
        "slab": "clean",
        "speaker_id": "21204",
        "speaker_id_reassigned": "21204_2",
        "text": "বিভিন্ন দামের সরঞ্জাম , টুলস্ এবং মেশিন পাওয়া যায়",
        "text_id": "211235",
        "text_type": "statement",
        "utterance_id": "20000484",
        "wav_path": "D3/21204/IISc_RESPIN_bn_D3_21204_700039_F_AGRI_211235_20000484.wav"
    },
    "IISc_RESPIN_bn_D3_21096_700154_F_AGRI_209303_20000764": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.53,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "bn",
        "pincode": "700154",
        "slab": "clean",
        "speaker_id": "21096",
        "speaker_id_reassigned": "21096_1",
        "text": "সংগৃহীত ফসল হারভেস্ট করার পর তাকে সংরক্ষণ করা হয়",
        "text_id": "209303",
        "text_type": "statement",
        "utterance_id": "20000764",
        "wav_path": "D3/21096/IISc_RESPIN_bn_D3_21096_700154_F_AGRI_209303_20000764.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bn_D3_21204.txt) ###
```
IISc_RESPIN_bn_D3_21204_700039_F_AGRI_211235_20000484	বিভিন্ন দামের সরঞ্জাম , টুলস্ এবং মেশিন পাওয়া যায়
IISc_RESPIN_bn_D3_21204_700039_F_BANK_208680_20001080	কেন্দ্রীয় সরকার দ্বারা পরিচালিত ব্যাঙ্কগুলোকে সেন্ট্রাল ব্যাঙ্ক বলা হয়
IISc_RESPIN_bn_D3_21204_700039_F_BANK_209723_20001101	কোনো টাকা জমা করলে সেটাকে ক্রেডিট করা বলে
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