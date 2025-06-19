## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Chhattisgarhi (CH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_ch
- Total Audio Duration (HH:MM:SS): 2:24:06
- Average Sample Duration: 6.119 secs
- Total Unique Text IDs: 511
- Unique Word Count: 1715
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 360 | 65 | 67 | 132 | 20 | 20 | 0.30 | 0.33 | 0.63 |
| D2 | 360 | 75 | 55 | 130 | 20 | 20 | 0.41 | 0.26 | 0.67 |
| D3 | 351 | 73 | 54 | 127 | 20 | 20 | 0.31 | 0.23 | 0.54 |
| D4 | 342 | 68 | 54 | 122 | 20 | 20 | 0.30 | 0.26 | 0.56 |
| Total | 1413 | 281 | 230 | 511 | 80 | 80 | 1.32 | 1.08 | 2.40 |



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

### Metadata File Sample (meta_dev_ch.json) ###

```json
{
    "IISc_RESPIN_ch_D1_30060_495001_M_BANK_303070_30000010": {
        "age_group": "41-45",
        "age_group_reassigned": "41-45",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 12.07,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495001",
        "slab": "clean",
        "speaker_id": "30060",
        "speaker_id_reassigned": "30060_2",
        "text": "सब्जी भाजी के भाव ह आज जेन हे तेन ह सब्बो दिन नइ राहय , दू चार दिन बाद जाबे त अलगे भाव म मिलही",
        "text_id": "303070",
        "text_type": "statement",
        "utterance_id": "30000010",
        "wav_path": "D1/30060/IISc_RESPIN_ch_D1_30060_495001_M_BANK_303070_30000010.wav"
    },
    "IISc_RESPIN_ch_D1_30100_495001_F_BANK_302090_30000282": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 11.29,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "ch",
        "pincode": "495001",
        "slab": "clean",
        "speaker_id": "30100",
        "speaker_id_reassigned": "30100_1",
        "text": "बैंक के ऐप म गराहक ह ऑनलाईन नेट बैंकिंग म जतका सुबिधा के फायदा उठात रहिस ओला तो वो हर लेबे करही",
        "text_id": "302090",
        "text_type": "statement",
        "utterance_id": "30000282",
        "wav_path": "D1/30100/IISc_RESPIN_ch_D1_30100_495001_F_BANK_302090_30000282.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_ch_D1_30060.txt) ###
```
IISc_RESPIN_ch_D1_30060_495001_M_BANK_303070_30000010	सब्जी भाजी के भाव ह आज जेन हे तेन ह सब्बो दिन नइ राहय , दू चार दिन बाद जाबे त अलगे भाव म मिलही
IISc_RESPIN_ch_D1_30060_495001_M_BANK_303330_30001930	कोनो कंपनी या सरकार ह कम बियाज देके बांड के माध्यम ले पइसा के जुगाड़ कर लेथे जरुरत के पड़ब म
IISc_RESPIN_ch_D1_30060_495001_M_BANK_303547_30001941	पइसा के राहब म कतको झन कोनो सरकारी बेंक म सुरक्छा के हिसाब ले फिक्स डिपोजिट करके रखथे
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