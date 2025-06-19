## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Chhattisgarhi (CH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_ch_noisy
- Total Audio Duration (HH:MM:SS): 73:57:25
- Average Sample Duration: 7.297 secs
- Total Unique Text IDs: 14456
- Unique Word Count: 11456
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 9148 | 1810 | 1946 | 3756 | 480 | 276 | 8.01 | 10.05 | 18.05 |
| D2 | 4995 | 1335 | 1407 | 2742 | 425 | 264 | 4.40 | 5.33 | 9.73 |
| D4 | 12180 | 2148 | 1732 | 3880 | 538 | 413 | 14.78 | 12.20 | 26.98 |
| D3 | 10163 | 2024 | 2058 | 4082 | 581 | 474 | 8.94 | 10.26 | 19.20 |
| Total | 36486 | 7317 | 7143 | 14456 | 2024 | 1424 | 36.12 | 37.84 | 73.96 |



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

### Metadata File Sample (meta_train_ch_noisy.json) ###

```json
{
    "IISc_RESPIN_ch_D1_30003_670143_F_AGRI_301865_30000002": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 1.15,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "ch",
        "pincode": "670143",
        "slab": "noisy",
        "speaker_id": "30003",
        "speaker_id_reassigned": "NA",
        "text": "तरिया डबरी म भराए पानी ल घलौ किसान मन अपन जरूरत हिसाब ले मोटर ले पानी खींच के अपन खेत ल पलो डारथें",
        "text_id": "301865",
        "text_type": "statement",
        "utterance_id": "30000002",
        "wav_path": "D1/30003/IISc_RESPIN_ch_D1_30003_670143_F_AGRI_301865_30000002.wav"
    },
    "IISc_RESPIN_ch_D1_30003_670143_F_AGRI_300685_30000003": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 0.55,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "ch",
        "pincode": "670143",
        "slab": "noisy",
        "speaker_id": "30003",
        "speaker_id_reassigned": "NA",
        "text": "सतही सिंचई म पूरा खेत म पानी भराथे त फसल के संघरा बन कचरा घलोक ह जामथे",
        "text_id": "300685",
        "text_type": "statement",
        "utterance_id": "30000003",
        "wav_path": "D1/30003/IISc_RESPIN_ch_D1_30003_670143_F_AGRI_300685_30000003.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_ch_D1_30003.txt) ###
```
IISc_RESPIN_ch_D1_30003_670143_F_AGRI_301865_30000002	तरिया डबरी म भराए पानी ल घलौ किसान मन अपन जरूरत हिसाब ले मोटर ले पानी खींच के अपन खेत ल पलो डारथें
IISc_RESPIN_ch_D1_30003_670143_F_AGRI_300685_30000003	सतही सिंचई म पूरा खेत म पानी भराथे त फसल के संघरा बन कचरा घलोक ह जामथे
IISc_RESPIN_ch_D1_30003_670143_F_AGRI_300122_30000004	ओ बात ह तो बने हे भइया फेर आज काल किसानी बूता बर बनिहार कहॉं मिलथे ?
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