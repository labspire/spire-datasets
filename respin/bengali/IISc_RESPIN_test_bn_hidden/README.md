## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bengali (BN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_bn_hidden
- Total Audio Duration (HH:MM:SS): 3:12:38
- Average Sample Duration: 5.322 secs
- Total Unique Text IDs: 630
- Unique Word Count: 2240
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 425 | 74 | 35 | 109 | 40 | 40 | 0.44 | 0.21 | 0.65 |
| D2 | 425 | 58 | 54 | 112 | 40 | 40 | 0.29 | 0.32 | 0.61 |
| D5 | 431 | 78 | 43 | 121 | 40 | 40 | 0.46 | 0.23 | 0.69 |
| D4 | 435 | 88 | 61 | 149 | 40 | 40 | 0.41 | 0.24 | 0.64 |
| D1 | 456 | 78 | 61 | 139 | 40 | 40 | 0.35 | 0.26 | 0.61 |
| Total | 2172 | 376 | 254 | 630 | 200 | 200 | 1.96 | 1.25 | 3.21 |



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

### Metadata File Sample (meta_test_bn_hidden.json) ###

```json
{
    "IISc_RESPIN_bn_D3_21204_700039_F_AGRI_208594_20000506": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 9.8,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "bn",
        "pincode": "700039",
        "slab": "clean",
        "speaker_id": "21204",
        "speaker_id_reassigned": "21204_2",
        "text": "ইতিহাস থেকে জানা যায় যে খ্রিস্টপূর্ব সাতাশো সাঁইত্রিশ সাল থেকে মানুষ চা পান করে আসছে",
        "text_id": "208594",
        "text_type": "statement",
        "utterance_id": "20000506",
        "wav_path": "D3/21204/IISc_RESPIN_bn_D3_21204_700039_F_AGRI_208594_20000506.wav"
    },
    "IISc_RESPIN_bn_D3_21153_700144_F_AGRI_209059_20001046": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 8.05,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "bn",
        "pincode": "700144",
        "slab": "clean",
        "speaker_id": "21153",
        "speaker_id_reassigned": "21153_2",
        "text": "স্বাস্থ্যবিধিজনিত কারণে ভেড়ার মাথা , নিতম্ব ও পায়ের থেকে লোম সংগ্রহ করাকে ক্রাচিং বলা হয়",
        "text_id": "209059",
        "text_type": "statement",
        "utterance_id": "20001046",
        "wav_path": "D3/21153/IISc_RESPIN_bn_D3_21153_700144_F_AGRI_209059_20001046.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bn_D3_21204.txt) ###
```
IISc_RESPIN_bn_D3_21204_700039_F_AGRI_208594_20000506	ইতিহাস থেকে জানা যায় যে খ্রিস্টপূর্ব সাতাশো সাঁইত্রিশ সাল থেকে মানুষ চা পান করে আসছে
IISc_RESPIN_bn_D3_21204_700039_F_AGRI_209170_20003341	যে সমস্ত বিভাগ গুলিতে সিল্ক চাষ করা হয়
IISc_RESPIN_bn_D3_21204_700039_F_AGRI_208529_20005951	আরব দেশে প্রাপ্ত জুঁই ফুল মনোরম সুগন্ধযুক্ত হয়
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