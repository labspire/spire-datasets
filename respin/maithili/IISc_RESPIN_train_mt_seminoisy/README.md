## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Maithili (MT)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mt_seminoisy
- Total Audio Duration (HH:MM:SS): 400:02:34
- Average Sample Duration: 6.064 secs
- Total Unique Text IDs: 23154
- Unique Word Count: 18399
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 86416 | 4069 | 2682 | 6751 | 527 | 452 | 78.29 | 56.93 | 135.21 |
| D1 | 48332 | 3111 | 2517 | 5628 | 411 | 401 | 51.42 | 41.60 | 93.01 |
| D2 | 58511 | 2445 | 2743 | 5188 | 492 | 464 | 45.31 | 51.37 | 96.68 |
| D4 | 44225 | 3017 | 2570 | 5587 | 486 | 518 | 38.42 | 36.72 | 75.14 |
| Total | 237484 | 12642 | 10512 | 23154 | 1916 | 1832 | 213.43 | 186.61 | 400.04 |



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

### Metadata File Sample (meta_train_mt_seminoisy.json) ###

```json
{
    "IISc_RESPIN_mt_D3_80002_847304_F_AGRI_817385_80000003": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 7.43,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mt",
        "pincode": "847304",
        "slab": "seminoisy",
        "speaker_id": "80002",
        "speaker_id_reassigned": "80002_1",
        "text": "हरोथ बाँस मोट , निस्सन आ मजगुत होइत अछि",
        "text_id": "817385",
        "text_type": "statement",
        "utterance_id": "80000003",
        "wav_path": "D3/80002/IISc_RESPIN_mt_D3_80002_847304_F_AGRI_817385_80000003.wav"
    },
    "IISc_RESPIN_mt_D3_80002_847304_F_AGRI_812762_80000004": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 7.32,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mt",
        "pincode": "847304",
        "slab": "seminoisy",
        "speaker_id": "80002",
        "speaker_id_reassigned": "80002_1",
        "text": "धनअभावक कारणेँ ओ समय सॅ कीटनाशक के उपयोग नै कअ सकला",
        "text_id": "812762",
        "text_type": "statement",
        "utterance_id": "80000004",
        "wav_path": "D3/80002/IISc_RESPIN_mt_D3_80002_847304_F_AGRI_812762_80000004.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mt_D3_80002.txt) ###
```
IISc_RESPIN_mt_D3_80002_847304_F_AGRI_817385_80000003	हरोथ बाँस मोट , निस्सन आ मजगुत होइत अछि
IISc_RESPIN_mt_D3_80002_847304_F_AGRI_812762_80000004	धनअभावक कारणेँ ओ समय सॅ कीटनाशक के उपयोग नै कअ सकला
IISc_RESPIN_mt_D3_80002_847304_F_AGRI_812639_80000022	हेम सिंह प्रुथी बहुत प्रसिद्ध कृषि वैज्ञानिक छलाह
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