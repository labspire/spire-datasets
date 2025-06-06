## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Maithili (MT)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_mt
- Total Audio Duration (HH:MM:SS): 3:19:54
- Average Sample Duration: 5.522 secs
- Total Unique Text IDs: 993
- Unique Word Count: 2972
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 556 | 127 | 99 | 226 | 40 | 40 | 0.46 | 0.34 | 0.80 |
| D4 | 532 | 91 | 84 | 175 | 40 | 40 | 0.33 | 0.33 | 0.66 |
| D1 | 548 | 148 | 110 | 258 | 40 | 40 | 0.49 | 0.38 | 0.87 |
| D2 | 536 | 169 | 165 | 334 | 40 | 40 | 0.52 | 0.49 | 1.01 |
| Total | 2172 | 535 | 458 | 993 | 160 | 160 | 1.80 | 1.53 | 3.33 |



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

### Metadata File Sample (meta_test_mt.json) ###

```json
{
    "IISc_RESPIN_mt_D3_80171_NA_M_AGRI_814288_80000353": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 4.33,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mt",
        "pincode": "451229",
        "slab": "clean",
        "speaker_id": "80171",
        "speaker_id_reassigned": "80171_1",
        "text": "गामक चरवाहा जाड़ में बहुत धन प्राप्त कयलक",
        "text_id": "814288",
        "text_type": "statement",
        "utterance_id": "80000353",
        "wav_path": "D3/80171/IISc_RESPIN_mt_D3_80171_NA_M_AGRI_814288_80000353.wav"
    },
    "IISc_RESPIN_mt_D3_80171_NA_M_AGRI_817837_80000354": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.64,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mt",
        "pincode": "451229",
        "slab": "clean",
        "speaker_id": "80171",
        "speaker_id_reassigned": "80171_1",
        "text": "घसकट्टा मशीन सॅ कम समय मे बहुत दूर धरि घास के काटल जा सकैत छै",
        "text_id": "817837",
        "text_type": "statement",
        "utterance_id": "80000354",
        "wav_path": "D3/80171/IISc_RESPIN_mt_D3_80171_NA_M_AGRI_817837_80000354.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mt_D3_80171.txt) ###
```
IISc_RESPIN_mt_D3_80171_NA_M_AGRI_814288_80000353	गामक चरवाहा जाड़ में बहुत धन प्राप्त कयलक
IISc_RESPIN_mt_D3_80171_NA_M_AGRI_817837_80000354	घसकट्टा मशीन सॅ कम समय मे बहुत दूर धरि घास के काटल जा सकैत छै
IISc_RESPIN_mt_D3_80171_NA_M_BANK_814949_80000400	सामग्री आयात भेला पर किछ कर दिअ पड़ैत अछि
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