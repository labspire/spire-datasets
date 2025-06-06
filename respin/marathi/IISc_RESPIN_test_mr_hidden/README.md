## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Marathi (MR)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_mr_hidden
- Total Audio Duration (HH:MM:SS): 3:02:45
- Average Sample Duration: 5.053 secs
- Total Unique Text IDs: 717
- Unique Word Count: 2990
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 523 | 82 | 65 | 147 | 40 | 40 | 0.40 | 0.28 | 0.68 |
| D1 | 533 | 112 | 98 | 210 | 40 | 40 | 0.47 | 0.37 | 0.84 |
| D4 | 548 | 79 | 114 | 193 | 40 | 40 | 0.33 | 0.44 | 0.77 |
| D2 | 566 | 80 | 87 | 167 | 40 | 40 | 0.41 | 0.35 | 0.76 |
| Total | 2170 | 353 | 364 | 717 | 160 | 160 | 1.61 | 1.44 | 3.05 |



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

### Metadata File Sample (meta_test_mr_hidden.json) ###

```json
{
    "IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700675_70000261": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 8.57,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mr",
        "pincode": "411011",
        "slab": "clean",
        "speaker_id": "70093",
        "speaker_id_reassigned": "70093_1",
        "text": "कापूस लागवडीसाठी प्रति एकर किती किलोग्रॅम युरिया वापरावा ?",
        "text_id": "700675",
        "text_type": "question",
        "utterance_id": "70000261",
        "wav_path": "D3/70093/IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700675_70000261.wav"
    },
    "IISc_RESPIN_mr_D3_70071_411037_F_AGRI_700580_70000330": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.87,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mr",
        "pincode": "411037",
        "slab": "clean",
        "speaker_id": "70071",
        "speaker_id_reassigned": "70071_1",
        "text": "ज्वारीवर कीड पडू नये यासाठी कोणती फवारणी करावी ?",
        "text_id": "700580",
        "text_type": "question",
        "utterance_id": "70000330",
        "wav_path": "D3/70071/IISc_RESPIN_mr_D3_70071_411037_F_AGRI_700580_70000330.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mr_D3_70093.txt) ###
```
IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700675_70000261	कापूस लागवडीसाठी प्रति एकर किती किलोग्रॅम युरिया वापरावा ?
IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700317_70000520	हिमीकरणामुळे पिकांवर कोणता परिणाम होतो ?
IISc_RESPIN_mr_D3_70093_411011_F_AGRI_700613_70000523	इ कॉमर्स म्हणजे काय आणि ते महत्त्वाचे का आहे ?
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