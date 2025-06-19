## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Maithili (MT)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mt_clean
- Total Audio Duration (HH:MM:SS): 552:09:26
- Average Sample Duration: 5.061 secs
- Total Unique Text IDs: 23108
- Unique Word Count: 18339
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 115305 | 4065 | 2680 | 6745 | 529 | 452 | 89.94 | 66.62 | 156.55 |
| D1 | 92311 | 3113 | 2520 | 5633 | 415 | 401 | 79.77 | 66.18 | 145.94 |
| D2 | 66086 | 2412 | 2710 | 5122 | 485 | 457 | 40.35 | 46.91 | 87.26 |
| D4 | 119037 | 3033 | 2575 | 5608 | 488 | 518 | 84.61 | 77.79 | 162.40 |
| Total | 392739 | 12623 | 10485 | 23108 | 1917 | 1825 | 294.66 | 257.49 | 552.16 |



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

### Metadata File Sample (meta_train_mt_clean.json) ###

```json
{
    "IISc_RESPIN_mt_D3_80002_847304_F_AGRI_816840_80000001": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 8.63,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mt",
        "pincode": "847304",
        "slab": "clean",
        "speaker_id": "80002",
        "speaker_id_reassigned": "80002_1",
        "text": "अपना देश मे अनेको प्रकारक प्रजातिक पशु पाओल जाइत अछि",
        "text_id": "816840",
        "text_type": "statement",
        "utterance_id": "80000001",
        "wav_path": "D3/80002/IISc_RESPIN_mt_D3_80002_847304_F_AGRI_816840_80000001.wav"
    },
    "IISc_RESPIN_mt_D3_80002_847304_F_BANK_816225_80000002": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 5.3,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "mt",
        "pincode": "847304",
        "slab": "clean",
        "speaker_id": "80002",
        "speaker_id_reassigned": "NA",
        "text": "येस बैंक वाणिज्य बैंक के श्रेणी में अबैत अछि",
        "text_id": "816225",
        "text_type": "statement",
        "utterance_id": "80000002",
        "wav_path": "D3/80002/IISc_RESPIN_mt_D3_80002_847304_F_BANK_816225_80000002.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mt_D3_80002.txt) ###
```
IISc_RESPIN_mt_D3_80002_847304_F_AGRI_816840_80000001	अपना देश मे अनेको प्रकारक प्रजातिक पशु पाओल जाइत अछि
IISc_RESPIN_mt_D3_80002_847304_F_BANK_816225_80000002	येस बैंक वाणिज्य बैंक के श्रेणी में अबैत अछि
IISc_RESPIN_mt_D3_80002_847304_F_BANK_816008_80000005	बैंक धोखाधड़ी एकटा गंभीर अपराध होइत अछि
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