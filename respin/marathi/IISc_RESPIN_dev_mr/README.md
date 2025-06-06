## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Marathi (MR)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_mr
- Total Audio Duration (HH:MM:SS): 1:58:34
- Average Sample Duration: 5.133 secs
- Total Unique Text IDs: 509
- Unique Word Count: 2292
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 342 | 67 | 64 | 131 | 20 | 20 | 0.28 | 0.28 | 0.56 |
| D4 | 333 | 60 | 66 | 126 | 20 | 20 | 0.19 | 0.20 | 0.39 |
| D1 | 351 | 60 | 68 | 128 | 20 | 20 | 0.23 | 0.30 | 0.53 |
| D2 | 360 | 64 | 60 | 124 | 20 | 20 | 0.24 | 0.26 | 0.50 |
| Total | 1386 | 251 | 258 | 509 | 80 | 80 | 0.94 | 1.03 | 1.98 |



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

### Metadata File Sample (meta_dev_mr.json) ###

```json
{
    "IISc_RESPIN_mr_D3_70108_411037_M_AGRI_700463_70002229": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.65,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mr",
        "pincode": "411037",
        "slab": "clean",
        "speaker_id": "70108",
        "speaker_id_reassigned": "70108_1",
        "text": "गहू पिकाच्या वाढीसाठी कोणते बी चांगले ?",
        "text_id": "700463",
        "text_type": "question",
        "utterance_id": "70002229",
        "wav_path": "D3/70108/IISc_RESPIN_mr_D3_70108_411037_M_AGRI_700463_70002229.wav"
    },
    "IISc_RESPIN_mr_D3_70108_411037_M_BANK_701212_70002235": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 5.5,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mr",
        "pincode": "411037",
        "slab": "clean",
        "speaker_id": "70108",
        "speaker_id_reassigned": "70108_1",
        "text": "गृहकर्ज घेतल्यास मी आणखी एक कर्ज घेऊ शकत नाही का ?",
        "text_id": "701212",
        "text_type": "question",
        "utterance_id": "70002235",
        "wav_path": "D3/70108/IISc_RESPIN_mr_D3_70108_411037_M_BANK_701212_70002235.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mr_D3_70108.txt) ###
```
IISc_RESPIN_mr_D3_70108_411037_M_AGRI_700463_70002229	गहू पिकाच्या वाढीसाठी कोणते बी चांगले ?
IISc_RESPIN_mr_D3_70108_411037_M_BANK_701212_70002235	गृहकर्ज घेतल्यास मी आणखी एक कर्ज घेऊ शकत नाही का ?
IISc_RESPIN_mr_D3_70108_411037_M_AGRI_700482_70002238	एक एकर शेतजमिनीसाठी एन.पी.के चे प्रमाण किती आहे ?
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