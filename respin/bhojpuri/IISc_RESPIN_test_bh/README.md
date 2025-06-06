## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bhojpuri (BH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_bh
- Total Audio Duration (HH:MM:SS): 3:05:53
- Average Sample Duration: 5.024 secs
- Total Unique Text IDs: 694
- Unique Word Count: 1988
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D2 | 722 | 118 | 85 | 203 | 40 | 40 | 0.56 | 0.42 | 0.98 |
| D1 | 759 | 119 | 111 | 230 | 40 | 40 | 0.57 | 0.51 | 1.08 |
| D3 | 739 | 153 | 108 | 261 | 40 | 40 | 0.54 | 0.49 | 1.03 |
| Total | 2220 | 390 | 304 | 694 | 120 | 120 | 1.68 | 1.42 | 3.10 |



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

### Metadata File Sample (meta_test_bh.json) ###

```json
{
    "IISc_RESPIN_bh_D2_11018_221008_M_AGRI_112500_10001680": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D2",
        "domain": "Agriculture",
        "duration": 6.95,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "221008",
        "slab": "clean",
        "speaker_id": "11018",
        "speaker_id_reassigned": "11018_1",
        "text": "बायोगैस जीव जंतु के अपघटन से बनत बाटे",
        "text_id": "112500",
        "text_type": "statement",
        "utterance_id": "10001680",
        "wav_path": "D2/11018/IISc_RESPIN_bh_D2_11018_221008_M_AGRI_112500_10001680.wav"
    },
    "IISc_RESPIN_bh_D2_11018_221008_M_AGRI_110873_10001693": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D2",
        "domain": "Agriculture",
        "duration": 5.82,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "221008",
        "slab": "clean",
        "speaker_id": "11018",
        "speaker_id_reassigned": "11018_1",
        "text": "दौरी छिट्टा मड़ई बनावे में बांस के परियोग करल जाला",
        "text_id": "110873",
        "text_type": "statement",
        "utterance_id": "10001693",
        "wav_path": "D2/11018/IISc_RESPIN_bh_D2_11018_221008_M_AGRI_110873_10001693.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bh_D2_11018.txt) ###
```
IISc_RESPIN_bh_D2_11018_221008_M_AGRI_112500_10001680	बायोगैस जीव जंतु के अपघटन से बनत बाटे
IISc_RESPIN_bh_D2_11018_221008_M_AGRI_110873_10001693	दौरी छिट्टा मड़ई बनावे में बांस के परियोग करल जाला
IISc_RESPIN_bh_D2_11018_221008_M_BANK_112988_10002034	ई कुल कब प्राकृतिक आपदा से हो सकला
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