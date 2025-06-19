## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Maithili (MT)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mt_small
- Total Audio Duration (HH:MM:SS): 159:19:18
- Average Sample Duration: 6.020 secs
- Total Unique Text IDs: 19056
- Unique Word Count: 16321
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 23820 | 2382 | 2382 | 4764 | 527 | 427 | 17.82 | 17.54 | 35.36 |
| D1 | 23820 | 2404 | 2360 | 4764 | 413 | 382 | 21.91 | 22.20 | 44.12 |
| D2 | 23820 | 2378 | 2386 | 4764 | 488 | 452 | 19.81 | 20.49 | 40.30 |
| D4 | 23820 | 2382 | 2382 | 4764 | 485 | 487 | 19.44 | 20.10 | 39.54 |
| Total | 95280 | 9546 | 9510 | 19056 | 1913 | 1745 | 78.99 | 80.33 | 159.32 |



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

### Metadata File Sample (meta_train_mt_small.json) ###

```json
{
    "IISc_RESPIN_mt_D3_80002_847304_F_BANK_818050_80000047": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 8.0,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mt",
        "pincode": "847304",
        "slab": "clean",
        "speaker_id": "80002",
        "speaker_id_reassigned": "80002_1",
        "text": "भारतीय कर कानून एवं नियममे अनेक प्रकारक छूटक प्रावधान सेहो कयल गेल छै",
        "text_id": "818050",
        "text_type": "statement",
        "utterance_id": "80000047",
        "wav_path": "D3/80002/IISc_RESPIN_mt_D3_80002_847304_F_BANK_818050_80000047.wav"
    },
    "IISc_RESPIN_mt_D3_80003_846004_M_BANK_815631_80000058": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 10.73,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mt",
        "pincode": "846004",
        "slab": "clean",
        "speaker_id": "80003",
        "speaker_id_reassigned": "80003_1",
        "text": "विदेशी मुद्रा बाजार मे प्रति दिन बहुत मुद्रा के हस्तांतरण कयल जाइत अछि",
        "text_id": "815631",
        "text_type": "statement",
        "utterance_id": "80000058",
        "wav_path": "D3/80003/IISc_RESPIN_mt_D3_80003_846004_M_BANK_815631_80000058.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mt_D3_80002.txt) ###
```
IISc_RESPIN_mt_D3_80002_847304_F_BANK_818050_80000047	भारतीय कर कानून एवं नियममे अनेक प्रकारक छूटक प्रावधान सेहो कयल गेल छै
IISc_RESPIN_mt_D3_80002_847304_F_AGRI_813721_80037884	भारत के विभिन्न क्षेत्र में मौसम आ भूगोल के अनुकूल कृषि कार्य कयल जाइत अछि
IISc_RESPIN_mt_D3_80002_847304_F_BANK_816143_80037915	सापेक्ष वापसी सॅ संस्थान के संस्थापक अप्रसन्न छलाह
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