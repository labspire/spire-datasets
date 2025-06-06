## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Magahi (MG)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_mg
- Total Audio Duration (HH:MM:SS): 2:05:48
- Average Sample Duration: 5.275 secs
- Total Unique Text IDs: 494
- Unique Word Count: 1924
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D4 | 360 | 51 | 67 | 118 | 20 | 20 | 0.26 | 0.34 | 0.59 |
| D3 | 360 | 53 | 67 | 120 | 20 | 20 | 0.19 | 0.24 | 0.43 |
| D1 | 351 | 67 | 60 | 127 | 20 | 20 | 0.26 | 0.26 | 0.52 |
| D2 | 360 | 64 | 65 | 129 | 20 | 20 | 0.25 | 0.30 | 0.55 |
| Total | 1431 | 235 | 259 | 494 | 80 | 80 | 0.96 | 1.14 | 2.10 |



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

### Metadata File Sample (meta_dev_mg.json) ###

```json
{
    "IISc_RESPIN_mg_D4_60426_855107_F_AGRI_617489_60004380": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D4",
        "domain": "Agriculture",
        "duration": 9.53,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mg",
        "pincode": "855107",
        "slab": "clean",
        "speaker_id": "60426",
        "speaker_id_reassigned": "60426_1",
        "text": "रतालू फसलक बहुत बिमारी आर कीड़ा स बचव्वा हछेक",
        "text_id": "617489",
        "text_type": "statement",
        "utterance_id": "60004380",
        "wav_path": "D4/60426/IISc_RESPIN_mg_D4_60426_855107_F_AGRI_617489_60004380.wav"
    },
    "IISc_RESPIN_mg_D3_60370_844128_F_BANK_613317_60010801": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 5.02,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mg",
        "pincode": "844128",
        "slab": "clean",
        "speaker_id": "60370",
        "speaker_id_reassigned": "60370_1",
        "text": "कमोडिटी मनी समान विनिमय के जइसन होइ छइ",
        "text_id": "613317",
        "text_type": "statement",
        "utterance_id": "60010801",
        "wav_path": "D3/60370/IISc_RESPIN_mg_D3_60370_844128_F_BANK_613317_60010801.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mg_D4_60426.txt) ###
```
IISc_RESPIN_mg_D4_60426_855107_F_AGRI_617489_60004380	रतालू फसलक बहुत बिमारी आर कीड़ा स बचव्वा हछेक
IISc_RESPIN_mg_D4_60426_855107_F_AGRI_617969_60016338	नेहा अलग अलग किस्मेर चावलेर बारे बताले
IISc_RESPIN_mg_D4_60426_855107_F_AGRI_620450_60016352	रामप्रसाद रेशमेर कीरार पालनेर बार बता ले
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