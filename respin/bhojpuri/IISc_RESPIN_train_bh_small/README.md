## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bhojpuri (BH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_bh_small
- Total Audio Duration (HH:MM:SS): 142:58:50
- Average Sample Duration: 5.402 secs
- Total Unique Text IDs: 19056
- Unique Word Count: 12641
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 31760 | 3176 | 3176 | 6352 | 451 | 411 | 24.00 | 25.06 | 49.07 |
| D2 | 31760 | 3176 | 3176 | 6352 | 450 | 311 | 22.67 | 25.06 | 47.73 |
| D3 | 31760 | 3408 | 2944 | 6352 | 544 | 359 | 23.65 | 22.53 | 46.18 |
| Total | 95280 | 9760 | 9296 | 19056 | 1445 | 1079 | 70.33 | 72.65 | 142.98 |



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

### Metadata File Sample (meta_train_bh_small.json) ###

```json
{
    "IISc_RESPIN_bh_D1_10846_560102_M_BANK_102756_10000002": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 5.37,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "560102",
        "slab": "clean",
        "speaker_id": "10846",
        "speaker_id_reassigned": "10846_1",
        "text": "कार्गो से भारत मसाला भी दूसरा देस में भेजत बाटे",
        "text_id": "102756",
        "text_type": "statement",
        "utterance_id": "10000002",
        "wav_path": "D1/10846/IISc_RESPIN_bh_D1_10846_560102_M_BANK_102756_10000002.wav"
    },
    "IISc_RESPIN_bh_D1_10846_560102_M_AGRI_103394_10000003": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 4.96,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "560102",
        "slab": "clean",
        "speaker_id": "10846",
        "speaker_id_reassigned": "10846_1",
        "text": "दुसरका कृषि कीट खेती के नुकसान पहुंचावे लन",
        "text_id": "103394",
        "text_type": "statement",
        "utterance_id": "10000003",
        "wav_path": "D1/10846/IISc_RESPIN_bh_D1_10846_560102_M_AGRI_103394_10000003.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bh_D1_10846.txt) ###
```
IISc_RESPIN_bh_D1_10846_560102_M_BANK_102756_10000002	कार्गो से भारत मसाला भी दूसरा देस में भेजत बाटे
IISc_RESPIN_bh_D1_10846_560102_M_AGRI_103394_10000003	दुसरका कृषि कीट खेती के नुकसान पहुंचावे लन
IISc_RESPIN_bh_D1_10846_560102_M_BANK_101844_10000005	बैंक खाता से बैंक अउरी खाता धारक के बीच लेनदेन होत बाटे
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