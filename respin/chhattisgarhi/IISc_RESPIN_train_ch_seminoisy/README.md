## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Chhattisgarhi (CH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_ch_seminoisy
- Total Audio Duration (HH:MM:SS): 161:16:39
- Average Sample Duration: 7.355 secs
- Total Unique Text IDs: 17334
- Unique Word Count: 12383
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 13266 | 2073 | 2236 | 4309 | 484 | 280 | 11.38 | 15.46 | 26.84 |
| D2 | 8523 | 1764 | 1909 | 3673 | 432 | 281 | 8.21 | 9.74 | 17.94 |
| D4 | 24592 | 2429 | 1927 | 4356 | 542 | 440 | 28.96 | 24.06 | 53.02 |
| D3 | 32561 | 2467 | 2533 | 5000 | 590 | 513 | 29.40 | 34.07 | 63.47 |
| Total | 78942 | 8733 | 8605 | 17334 | 2048 | 1511 | 77.95 | 83.33 | 161.28 |



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

### Metadata File Sample (meta_train_ch_seminoisy.json) ###

```json
{
    "IISc_RESPIN_ch_D1_30161_495115_M_AGRI_300706_30000140": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 7.85,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495115",
        "slab": "seminoisy",
        "speaker_id": "30161",
        "speaker_id_reassigned": "30065_1",
        "text": "कोनो भी काम बूता ला एक मुस्त करे बर , दाम फोर के देवइ ल ठेका देवई कथें",
        "text_id": "300706",
        "text_type": "statement",
        "utterance_id": "30000140",
        "wav_path": "D1/30161/IISc_RESPIN_ch_D1_30161_495115_M_AGRI_300706_30000140.wav"
    },
    "IISc_RESPIN_ch_D1_30161_495115_M_AGRI_301550_30000143": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 10.69,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495115",
        "slab": "seminoisy",
        "speaker_id": "30161",
        "speaker_id_reassigned": "30065_1",
        "text": "ग्रीन हाउस ह अइसने कांच भर के नइ बने हे एकर भीतरी म पेड़ पउधा मन ल जतका ताप चाही मिल जाथे",
        "text_id": "301550",
        "text_type": "statement",
        "utterance_id": "30000143",
        "wav_path": "D1/30161/IISc_RESPIN_ch_D1_30161_495115_M_AGRI_301550_30000143.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_ch_D1_30161.txt) ###
```
IISc_RESPIN_ch_D1_30161_495115_M_AGRI_300706_30000140	कोनो भी काम बूता ला एक मुस्त करे बर , दाम फोर के देवइ ल ठेका देवई कथें
IISc_RESPIN_ch_D1_30161_495115_M_AGRI_301550_30000143	ग्रीन हाउस ह अइसने कांच भर के नइ बने हे एकर भीतरी म पेड़ पउधा मन ल जतका ताप चाही मिल जाथे
IISc_RESPIN_ch_D1_30161_495115_M_AGRI_300978_30000595	बन ही अतके झटकुन बाढ़थे अउ बगरथे कि देरी नइ लागय
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