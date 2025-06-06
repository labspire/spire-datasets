## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bhojpuri (BH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_bh_hidden
- Total Audio Duration (HH:MM:SS): 3:08:46
- Average Sample Duration: 5.102 secs
- Total Unique Text IDs: 680
- Unique Word Count: 1940
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D2 | 758 | 133 | 85 | 218 | 40 | 40 | 0.61 | 0.46 | 1.06 |
| D3 | 741 | 144 | 108 | 252 | 40 | 40 | 0.56 | 0.46 | 1.02 |
| D1 | 721 | 112 | 98 | 210 | 40 | 40 | 0.55 | 0.51 | 1.06 |
| Total | 2220 | 389 | 291 | 680 | 120 | 120 | 1.72 | 1.43 | 3.15 |



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

### Metadata File Sample (meta_test_bh_hidden.json) ###

```json
{
    "IISc_RESPIN_bh_D2_11079_221005_M_AGRI_111524_10001063": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D2",
        "domain": "Agriculture",
        "duration": 5.01,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "221005",
        "slab": "clean",
        "speaker_id": "11079",
        "speaker_id_reassigned": "11079_2",
        "text": "मुरगा के येसे पकड़े में घाव चोट भी नाही लगेला",
        "text_id": "111524",
        "text_type": "statement",
        "utterance_id": "10001063",
        "wav_path": "D2/11079/IISc_RESPIN_bh_D2_11079_221005_M_AGRI_111524_10001063.wav"
    },
    "IISc_RESPIN_bh_D2_11018_221008_M_AGRI_110148_10001682": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D2",
        "domain": "Agriculture",
        "duration": 8.45,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "221008",
        "slab": "clean",
        "speaker_id": "11018",
        "speaker_id_reassigned": "11018_1",
        "text": "थाईलैंड आउर इंडोनेशिया इ दूनो देस रबर उगावे वाला देस हौ",
        "text_id": "110148",
        "text_type": "statement",
        "utterance_id": "10001682",
        "wav_path": "D2/11018/IISc_RESPIN_bh_D2_11018_221008_M_AGRI_110148_10001682.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bh_D2_11079.txt) ###
```
IISc_RESPIN_bh_D2_11079_221005_M_AGRI_111524_10001063	मुरगा के येसे पकड़े में घाव चोट भी नाही लगेला
IISc_RESPIN_bh_D2_11079_221005_M_AGRI_111568_10005277	जौन पौधा एक खाद पे पलला ओके एक खाद देवल जाला
IISc_RESPIN_bh_D2_11079_221005_M_AGRI_113363_10005290	बांस क रंग भी कई तरह के होखेला
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