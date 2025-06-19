## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Telugu (TE)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_te_hidden
- Total Audio Duration (HH:MM:SS): 3:28:51
- Average Sample Duration: 5.630 secs
- Total Unique Text IDs: 637
- Unique Word Count: 3019
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 594 | 76 | 100 | 176 | 40 | 40 | 0.36 | 0.52 | 0.88 |
| D2 | 548 | 82 | 77 | 159 | 40 | 40 | 0.47 | 0.45 | 0.93 |
| D4 | 573 | 71 | 76 | 147 | 40 | 40 | 0.38 | 0.48 | 0.86 |
| D3 | 511 | 95 | 61 | 156 | 40 | 40 | 0.49 | 0.32 | 0.81 |
| Total | 2226 | 324 | 314 | 637 | 160 | 160 | 1.71 | 1.77 | 3.48 |



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

### Metadata File Sample (meta_test_te_hidden.json) ###

```json
{
    "IISc_RESPIN_te_D1_90050_522412_M_AGRI_900693_90000059": {
        "age_group": "31-35",
        "age_group_reassigned": "31-35",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 6.97,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "te",
        "pincode": "522412",
        "slab": "clean",
        "speaker_id": "90050",
        "speaker_id_reassigned": "90050_1",
        "text": "మామూలు యవసాయం మాదిరిగానే ఉద్యాన పంటలకి కూడా నీళ్ళు , అన్ని పోషకాల దావనాలను వెయ్యాలి",
        "text_id": "900693",
        "text_type": "statement",
        "utterance_id": "90000059",
        "wav_path": "D1/90050/IISc_RESPIN_te_D1_90050_522412_M_AGRI_900693_90000059.wav"
    },
    "IISc_RESPIN_te_D1_90050_522412_M_BANK_902547_90000062": {
        "age_group": "31-35",
        "age_group_reassigned": "31-35",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 4.59,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "te",
        "pincode": "522412",
        "slab": "clean",
        "speaker_id": "90050",
        "speaker_id_reassigned": "90050_1",
        "text": "లోక్ సభలో కేంద్ర బడ్జెట్ను ఎప్పుడూ ముందుగానే సమర్పిస్తారు",
        "text_id": "902547",
        "text_type": "statement",
        "utterance_id": "90000062",
        "wav_path": "D1/90050/IISc_RESPIN_te_D1_90050_522412_M_BANK_902547_90000062.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_te_D1_90050.txt) ###
```
IISc_RESPIN_te_D1_90050_522412_M_AGRI_900693_90000059	మామూలు యవసాయం మాదిరిగానే ఉద్యాన పంటలకి కూడా నీళ్ళు , అన్ని పోషకాల దావనాలను వెయ్యాలి
IISc_RESPIN_te_D1_90050_522412_M_BANK_902547_90000062	లోక్ సభలో కేంద్ర బడ్జెట్ను ఎప్పుడూ ముందుగానే సమర్పిస్తారు
IISc_RESPIN_te_D1_90050_522412_M_AGRI_900733_90000090	మా బుడ్డోడికి మేక తలకాయ మాసం అంటే పాణం చానా ఇష్టంగా తింటాడు
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