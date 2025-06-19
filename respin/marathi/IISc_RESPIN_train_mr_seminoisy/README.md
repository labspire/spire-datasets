## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Marathi (MR)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mr_seminoisy
- Total Audio Duration (HH:MM:SS): 285:27:24
- Average Sample Duration: 5.378 secs
- Total Unique Text IDs: 21669
- Unique Word Count: 33836
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 40195 | 2504 | 2449 | 4953 | 601 | 460 | 28.16 | 25.33 | 53.50 |
| D1 | 36190 | 2362 | 3349 | 5711 | 729 | 497 | 22.10 | 30.07 | 52.17 |
| D4 | 85217 | 2720 | 2612 | 5332 | 745 | 656 | 69.91 | 62.92 | 132.82 |
| D2 | 29496 | 2955 | 2718 | 5673 | 554 | 532 | 24.35 | 22.61 | 46.97 |
| Total | 191098 | 10541 | 11128 | 21669 | 2629 | 2142 | 144.52 | 140.94 | 285.46 |



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

### Metadata File Sample (meta_train_mr_seminoisy.json) ###

```json
{
    "IISc_RESPIN_mr_D3_70002_416510_F_BANK_700731_70000004": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 1.21,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "mr",
        "pincode": "416510",
        "slab": "seminoisy",
        "speaker_id": "70002",
        "speaker_id_reassigned": "NA",
        "text": "बँकेत खाते उघडण्यासाठी काय गरजेचे आहे ?",
        "text_id": "700731",
        "text_type": "question",
        "utterance_id": "70000004",
        "wav_path": "D3/70002/IISc_RESPIN_mr_D3_70002_416510_F_BANK_700731_70000004.wav"
    },
    "IISc_RESPIN_mr_D3_70002_416510_F_BANK_701044_70000008": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 6.07,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "mr",
        "pincode": "416510",
        "slab": "seminoisy",
        "speaker_id": "70002",
        "speaker_id_reassigned": "NA",
        "text": "डिसेंबर महिन्याच्या बावीस तारखेला खात्यामध्ये किती बॅलन्स होता ?",
        "text_id": "701044",
        "text_type": "question",
        "utterance_id": "70000008",
        "wav_path": "D3/70002/IISc_RESPIN_mr_D3_70002_416510_F_BANK_701044_70000008.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mr_D3_70002.txt) ###
```
IISc_RESPIN_mr_D3_70002_416510_F_BANK_700731_70000004	बँकेत खाते उघडण्यासाठी काय गरजेचे आहे ?
IISc_RESPIN_mr_D3_70002_416510_F_BANK_701044_70000008	डिसेंबर महिन्याच्या बावीस तारखेला खात्यामध्ये किती बॅलन्स होता ?
IISc_RESPIN_mr_D3_70002_416510_F_BANK_700924_70000013	मी माझी कोणकोणती बिले भरू शकतो ?
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