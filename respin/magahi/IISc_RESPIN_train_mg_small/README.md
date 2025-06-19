## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Magahi (MG)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mg_small
- Total Audio Duration (HH:MM:SS): 157:46:00
- Average Sample Duration: 5.961 secs
- Total Unique Text IDs: 19056
- Unique Word Count: 19744
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 23820 | 2382 | 2382 | 4764 | 380 | 402 | 18.13 | 18.59 | 36.72 |
| D1 | 23820 | 2382 | 2382 | 4764 | 347 | 291 | 18.83 | 21.11 | 39.94 |
| D2 | 23820 | 2382 | 2382 | 4764 | 317 | 299 | 19.66 | 19.40 | 39.06 |
| D4 | 23820 | 2382 | 2382 | 4764 | 449 | 368 | 20.67 | 21.38 | 42.05 |
| Total | 95280 | 9528 | 9528 | 19056 | 1493 | 1357 | 77.29 | 80.47 | 157.77 |



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

### Metadata File Sample (meta_train_mg_small.json) ###

```json
{
    "IISc_RESPIN_mg_D3_60218_844121_F_BANK_615764_60000463": {
        "age_group": "31-35",
        "age_group_reassigned": "31-35",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 4.74,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mg",
        "pincode": "844121",
        "slab": "clean",
        "speaker_id": "60218",
        "speaker_id_reassigned": "60218_1",
        "text": "पूजा पुछलई कि कर माफी पर रउअर कि विचार हए",
        "text_id": "615764",
        "text_type": "statement",
        "utterance_id": "60000463",
        "wav_path": "D3/60218/IISc_RESPIN_mg_D3_60218_844121_F_BANK_615764_60000463.wav"
    },
    "IISc_RESPIN_mg_D3_60218_844121_F_BANK_615400_60000481": {
        "age_group": "31-35",
        "age_group_reassigned": "31-35",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 4.28,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mg",
        "pincode": "844121",
        "slab": "clean",
        "speaker_id": "60218",
        "speaker_id_reassigned": "60218_1",
        "text": "धन समय के साथ अपन मूल्य के बरकरार रखल जा हई",
        "text_id": "615400",
        "text_type": "statement",
        "utterance_id": "60000481",
        "wav_path": "D3/60218/IISc_RESPIN_mg_D3_60218_844121_F_BANK_615400_60000481.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mg_D3_60218.txt) ###
```
IISc_RESPIN_mg_D3_60218_844121_F_BANK_615764_60000463	पूजा पुछलई कि कर माफी पर रउअर कि विचार हए
IISc_RESPIN_mg_D3_60218_844121_F_BANK_615400_60000481	धन समय के साथ अपन मूल्य के बरकरार रखल जा हई

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