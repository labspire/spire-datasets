## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bhojpuri (BH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_bh_noisy
- Total Audio Duration (HH:MM:SS): 68:31:42
- Average Sample Duration: 5.666 secs
- Total Unique Text IDs: 15256
- Unique Word Count: 11613
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 22640 | 3636 | 3081 | 6717 | 475 | 381 | 19.72 | 17.47 | 37.18 |
| D2 | 3705 | 1342 | 1368 | 2710 | 369 | 143 | 2.47 | 2.58 | 5.05 |
| D3 | 17198 | 3322 | 2507 | 5829 | 548 | 336 | 13.94 | 12.36 | 26.30 |
| Total | 43543 | 8300 | 6956 | 15256 | 1392 | 858 | 36.12 | 32.41 | 68.53 |



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

### Metadata File Sample (meta_train_bh_noisy.json) ###

```json
{
    "IISc_RESPIN_bh_D1_10879_560016_F_AGRI_104225_10000001": {
        "age_group": "60-100",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 0.96,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "bh",
        "pincode": "560016",
        "slab": "noisy",
        "speaker_id": "10879",
        "speaker_id_reassigned": "NA",
        "text": "पेड़ से फाइबर मशीन से निकालल जाला",
        "text_id": "104225",
        "text_type": "statement",
        "utterance_id": "10000001",
        "wav_path": "D1/10879/IISc_RESPIN_bh_D1_10879_560016_F_AGRI_104225_10000001.wav"
    },
    "IISc_RESPIN_bh_D1_10846_560102_M_AGRI_104663_10000025": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 5.72,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "560102",
        "slab": "noisy",
        "speaker_id": "10846",
        "speaker_id_reassigned": "10846_1",
        "text": "जब ज्वारभाटा आवेला त उ अपना लहर का साथे मछरी लोग के किनारे फेक देला",
        "text_id": "104663",
        "text_type": "statement",
        "utterance_id": "10000025",
        "wav_path": "D1/10846/IISc_RESPIN_bh_D1_10846_560102_M_AGRI_104663_10000025.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bh_D1_10879.txt) ###
```
IISc_RESPIN_bh_D1_10879_560016_F_AGRI_104225_10000001	पेड़ से फाइबर मशीन से निकालल जाला


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