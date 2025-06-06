## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bengali (BN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_bn_clean
- Total Audio Duration (HH:MM:SS): 894:36:02
- Average Sample Duration: 4.987 secs
- Total Unique Text IDs: 20187
- Unique Word Count: 18024
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 145223 | 2452 | 1544 | 3996 | 358 | 303 | 128.26 | 83.36 | 211.62 |
| D2 | 150262 | 2007 | 1772 | 3779 | 347 | 360 | 105.61 | 100.08 | 205.69 |
| D5 | 111930 | 3351 | 1452 | 4803 | 377 | 362 | 106.84 | 61.51 | 168.36 |
| D4 | 118368 | 1910 | 1760 | 3670 | 364 | 305 | 85.73 | 73.08 | 158.81 |
| D1 | 120008 | 2127 | 1812 | 3939 | 345 | 329 | 83.02 | 67.10 | 150.12 |
| Total | 645791 | 11847 | 8340 | 20187 | 1791 | 1655 | 509.47 | 385.13 | 894.60 |



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

### Metadata File Sample (meta_train_bn_clean.json) ###

```json
{
    "IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209278_20000001": {
        "age_group": "41-45",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.14,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "bn",
        "pincode": "221001",
        "slab": "clean",
        "speaker_id": "21825",
        "speaker_id_reassigned": "NA",
        "text": "সারা ভারত দেশ জুড়ে আমরা বিভিন্ন ভাবে চা বানিয়ে খাই",
        "text_id": "209278",
        "text_type": "statement",
        "utterance_id": "20000001",
        "wav_path": "D3/21825/IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209278_20000001.wav"
    },
    "IISc_RESPIN_bn_D3_21825_221001_F_AGRI_208606_20000002": {
        "age_group": "41-45",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 11.25,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "bn",
        "pincode": "221001",
        "slab": "clean",
        "speaker_id": "21825",
        "speaker_id_reassigned": "NA",
        "text": "পশু প্রাণীদের চিকিৎসার কাজের সঙ্গে যারা যুক্ত তাদের ভেটেরিনারি ডাক্তার বলা হয়",
        "text_id": "208606",
        "text_type": "statement",
        "utterance_id": "20000002",
        "wav_path": "D3/21825/IISc_RESPIN_bn_D3_21825_221001_F_AGRI_208606_20000002.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bn_D3_21825.txt) ###
```
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209278_20000001	সারা ভারত দেশ জুড়ে আমরা বিভিন্ন ভাবে চা বানিয়ে খাই
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_208606_20000002	পশু প্রাণীদের চিকিৎসার কাজের সঙ্গে যারা যুক্ত তাদের ভেটেরিনারি ডাক্তার বলা হয়
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209233_20000003	সেমোলিনা মানে সুজি যেটা গুঁড়ো খাওয়া হয়
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