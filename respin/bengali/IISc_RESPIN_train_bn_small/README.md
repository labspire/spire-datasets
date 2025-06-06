## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bengali (BN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_bn_small
- Total Audio Duration (HH:MM:SS): 142:57:28
- Average Sample Duration: 5.998 secs
- Total Unique Text IDs: 17160
- Unique Word Count: 16201
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 17160 | 1920 | 1512 | 3432 | 228 | 208 | 16.68 | 12.72 | 29.40 |
| D2 | 17160 | 1716 | 1716 | 3432 | 186 | 204 | 13.32 | 12.89 | 26.20 |
| D5 | 17160 | 2030 | 1402 | 3432 | 295 | 265 | 21.17 | 12.21 | 33.39 |
| D4 | 17160 | 1716 | 1716 | 3432 | 291 | 240 | 15.10 | 13.75 | 28.85 |
| D1 | 17160 | 1716 | 1716 | 3432 | 280 | 271 | 13.48 | 11.63 | 25.11 |
| Total | 85800 | 9098 | 8062 | 17160 | 1280 | 1184 | 79.76 | 63.20 | 142.96 |



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

### Metadata File Sample (meta_train_bn_small.json) ###

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
    "IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209233_20000003": {
        "age_group": "41-45",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 5.58,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "bn",
        "pincode": "221001",
        "slab": "clean",
        "speaker_id": "21825",
        "speaker_id_reassigned": "NA",
        "text": "সেমোলিনা মানে সুজি যেটা গুঁড়ো খাওয়া হয়",
        "text_id": "209233",
        "text_type": "statement",
        "utterance_id": "20000003",
        "wav_path": "D3/21825/IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209233_20000003.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bn_D3_21825.txt) ###
```
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209278_20000001	সারা ভারত দেশ জুড়ে আমরা বিভিন্ন ভাবে চা বানিয়ে খাই
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209233_20000003	সেমোলিনা মানে সুজি যেটা গুঁড়ো খাওয়া হয়
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_209619_20000007	স্ট্রবেরি মানে হচ্ছে  এক ধরনের টক ফল যাতে ভিটামিন থাকে
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