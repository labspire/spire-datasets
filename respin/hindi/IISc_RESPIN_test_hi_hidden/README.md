## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Hindi (HI)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_hi_hidden
- Total Audio Duration (HH:MM:SS): 3:18:53
- Average Sample Duration: 5.220 secs
- Total Unique Text IDs: 833
- Unique Word Count: 2796
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 424 | 72 | 69 | 141 | 40 | 40 | 0.24 | 0.30 | 0.54 |
| D5 | 439 | 67 | 45 | 112 | 40 | 40 | 0.41 | 0.28 | 0.69 |
| D2 | 493 | 107 | 117 | 224 | 41 | 41 | 0.37 | 0.40 | 0.78 |
| D3 | 440 | 72 | 61 | 133 | 40 | 40 | 0.31 | 0.22 | 0.53 |
| D4 | 490 | 114 | 109 | 223 | 40 | 40 | 0.38 | 0.39 | 0.78 |
| Total | 2286 | 432 | 401 | 833 | 201 | 201 | 1.72 | 1.59 | 3.31 |



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

### Metadata File Sample (meta_test_hi_hidden.json) ###

```json
{
    "IISc_RESPIN_hi_D1_40042_251001_F_BANK_400802_40002999": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 7.2,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "hi",
        "pincode": "251001",
        "slab": "clean",
        "speaker_id": "40042",
        "speaker_id_reassigned": "40042_1",
        "text": "मांग ऋण में आमतौर पर दुबारा भुगतान के लिए निश्चित तिथियां नहीं होती हैं",
        "text_id": "400802",
        "text_type": "statement",
        "utterance_id": "40002999",
        "wav_path": "D1/40042/IISc_RESPIN_hi_D1_40042_251001_F_BANK_400802_40002999.wav"
    },
    "IISc_RESPIN_hi_D1_40042_251001_F_BANK_401029_40003009": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 3.93,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "hi",
        "pincode": "251001",
        "slab": "clean",
        "speaker_id": "40042",
        "speaker_id_reassigned": "40042_1",
        "text": "मुझे तकनीक से जुड़े स्टॉक पसंद हैं",
        "text_id": "401029",
        "text_type": "statement",
        "utterance_id": "40003009",
        "wav_path": "D1/40042/IISc_RESPIN_hi_D1_40042_251001_F_BANK_401029_40003009.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_hi_D1_40042.txt) ###
```
IISc_RESPIN_hi_D1_40042_251001_F_BANK_400802_40002999	मांग ऋण में आमतौर पर दुबारा भुगतान के लिए निश्चित तिथियां नहीं होती हैं
IISc_RESPIN_hi_D1_40042_251001_F_BANK_401029_40003009	मुझे तकनीक से जुड़े स्टॉक पसंद हैं
IISc_RESPIN_hi_D1_40042_251001_F_AGRI_400412_40006415	करी पत्ता अक्सर कढ़ी और अन्य सब्ज्यिओं में डाला जाता है
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