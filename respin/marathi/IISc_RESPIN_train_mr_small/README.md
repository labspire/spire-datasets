## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Marathi (MR)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mr_small
- Total Audio Duration (HH:MM:SS): 140:29:14
- Average Sample Duration: 5.308 secs
- Total Unique Text IDs: 19056
- Unique Word Count: 30682
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 23816 | 2382 | 2382 | 4764 | 557 | 411 | 15.53 | 14.73 | 30.26 |
| D1 | 23820 | 2382 | 2382 | 4764 | 623 | 398 | 17.43 | 18.47 | 35.89 |
| D4 | 23820 | 2382 | 2382 | 4764 | 673 | 543 | 18.25 | 18.73 | 36.99 |
| D2 | 23824 | 2382 | 2383 | 4765 | 452 | 393 | 18.71 | 18.63 | 37.34 |
| Total | 95280 | 9528 | 9529 | 19056 | 2305 | 1742 | 69.92 | 70.56 | 140.49 |



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

### Metadata File Sample (meta_train_mr_small.json) ###

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
IISc_RESPIN_mr_D3_70002_416510_F_AGRI_700683_70000025	शेतकऱ्यांसाठी रोजगार योजना आहेत का ?
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