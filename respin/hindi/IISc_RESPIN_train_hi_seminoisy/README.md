## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Hindi (HI)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_hi_seminoisy
- Total Audio Duration (HH:MM:SS): 273:15:55
- Average Sample Duration: 5.414 secs
- Total Unique Text IDs: 19180
- Unique Word Count: 15687
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 27709 | 1984 | 2041 | 4025 | 509 | 401 | 18.36 | 21.37 | 39.73 |
| D5 | 16868 | 1948 | 1977 | 3925 | 368 | 294 | 14.27 | 15.30 | 29.56 |
| D2 | 43277 | 1864 | 1819 | 3683 | 491 | 529 | 30.93 | 32.01 | 62.95 |
| D3 | 41140 | 2073 | 1993 | 4066 | 465 | 550 | 30.25 | 29.53 | 59.78 |
| D4 | 52716 | 1833 | 1783 | 3616 | 471 | 450 | 40.49 | 40.75 | 81.24 |
| Total | 181710 | 9702 | 9613 | 19180 | 2304 | 2220 | 134.31 | 138.96 | 273.27 |



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

### Metadata File Sample (meta_train_hi_seminoisy.json) ###

```json
{
    "IISc_RESPIN_hi_D1_40002_251001_M_BANK_402293_40000006": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 8.47,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "hi",
        "pincode": "251001",
        "slab": "seminoisy",
        "speaker_id": "40002",
        "speaker_id_reassigned": "NA",
        "text": "उपभोक्ता व्यापारी द्वारा प्रदर्शित क्यू.आर कोड को स्मार्टफोन से स्कैन करता है ताकि भुगतान कर सकें",
        "text_id": "402293",
        "text_type": "statement",
        "utterance_id": "40000006",
        "wav_path": "D1/40002/IISc_RESPIN_hi_D1_40002_251001_M_BANK_402293_40000006.wav"
    },
    "IISc_RESPIN_hi_D1_40002_251001_M_BANK_402848_40000009": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 7.21,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "hi",
        "pincode": "251001",
        "slab": "seminoisy",
        "speaker_id": "40002",
        "speaker_id_reassigned": "NA",
        "text": "स्थायी खाता संख्या एक अक्षरांकीय संख्या होती है , जो कार्ड के रूप में जारी की जाती है",
        "text_id": "402848",
        "text_type": "statement",
        "utterance_id": "40000009",
        "wav_path": "D1/40002/IISc_RESPIN_hi_D1_40002_251001_M_BANK_402848_40000009.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_hi_D1_40002.txt) ###
```
IISc_RESPIN_hi_D1_40002_251001_M_BANK_402293_40000006	उपभोक्ता व्यापारी द्वारा प्रदर्शित क्यू.आर कोड को स्मार्टफोन से स्कैन करता है ताकि भुगतान कर सकें
IISc_RESPIN_hi_D1_40002_251001_M_BANK_402848_40000009	स्थायी खाता संख्या एक अक्षरांकीय संख्या होती है , जो कार्ड के रूप में जारी की जाती है
IISc_RESPIN_hi_D1_40002_251001_M_AGRI_400327_40000024	क्या पेड़ों को काटकर कागज व लुगदी बनाए जाते हैं ?
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