## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Marathi (MR)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mr_clean
- Total Audio Duration (HH:MM:SS): 1026:03:24
- Average Sample Duration: 4.561 secs
- Total Unique Text IDs: 23069
- Unique Word Count: 34349
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 208850 | 3003 | 3074 | 6077 | 608 | 463 | 124.80 | 130.99 | 255.79 |
| D1 | 203651 | 2429 | 3409 | 5838 | 732 | 498 | 108.59 | 138.73 | 247.31 |
| D4 | 198873 | 2718 | 2612 | 5330 | 747 | 655 | 128.82 | 128.88 | 257.70 |
| D2 | 198560 | 3026 | 2799 | 5825 | 557 | 535 | 137.56 | 127.69 | 265.25 |
| Total | 809934 | 11176 | 11894 | 23069 | 2644 | 2148 | 499.77 | 526.29 | 1026.06 |



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

### Metadata File Sample (meta_train_mr_clean.json) ###

```json
{
    "IISc_RESPIN_mr_D3_70002_416510_F_BANK_700803_70000006": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 5.48,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "mr",
        "pincode": "416510",
        "slab": "clean",
        "speaker_id": "70002",
        "speaker_id_reassigned": "NA",
        "text": "तुम्ही माझ्या पगारातून पैसे कापून घेऊ शकता का ?",
        "text_id": "700803",
        "text_type": "question",
        "utterance_id": "70000006",
        "wav_path": "D3/70002/IISc_RESPIN_mr_D3_70002_416510_F_BANK_700803_70000006.wav"
    },
    "IISc_RESPIN_mr_D3_70002_416510_F_AGRI_700241_70000007": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 4.77,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "mr",
        "pincode": "416510",
        "slab": "clean",
        "speaker_id": "70002",
        "speaker_id_reassigned": "NA",
        "text": "कांदा किती वेळ गोदामात ठेवता येतो ?",
        "text_id": "700241",
        "text_type": "question",
        "utterance_id": "70000007",
        "wav_path": "D3/70002/IISc_RESPIN_mr_D3_70002_416510_F_AGRI_700241_70000007.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mr_D3_70002.txt) ###
```
IISc_RESPIN_mr_D3_70002_416510_F_BANK_700803_70000006	तुम्ही माझ्या पगारातून पैसे कापून घेऊ शकता का ?
IISc_RESPIN_mr_D3_70002_416510_F_AGRI_700241_70000007	कांदा किती वेळ गोदामात ठेवता येतो ?
IISc_RESPIN_mr_D3_70002_416510_F_AGRI_700427_70000022	कृषी क्षेत्रात ब्लॉकचेन तंत्रज्ञानाचे काय फायदे आहेत ?
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