## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Chhattisgarhi (CH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_ch_clean
- Total Audio Duration (HH:MM:SS): 1009:05:13
- Average Sample Duration: 5.670 secs
- Total Unique Text IDs: 19400
- Unique Word Count: 12786
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 174739 | 2516 | 2518 | 5034 | 493 | 290 | 129.67 | 141.31 | 270.99 |
| D2 | 148574 | 2410 | 2476 | 4886 | 451 | 288 | 119.66 | 130.91 | 250.56 |
| D4 | 152612 | 2487 | 1956 | 4443 | 542 | 441 | 140.51 | 111.84 | 252.35 |
| D3 | 164724 | 2493 | 2549 | 5042 | 596 | 518 | 113.45 | 121.73 | 235.18 |
| Total | 640649 | 9906 | 9499 | 19400 | 2082 | 1534 | 503.30 | 505.79 | 1009.09 |



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

### Metadata File Sample (meta_train_ch_clean.json) ###

```json
{
    "IISc_RESPIN_ch_D1_30088_495115_M_AGRI_301711_30000086": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 9.15,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495115",
        "slab": "clean",
        "speaker_id": "30088",
        "speaker_id_reassigned": "30046_1",
        "text": "एके ढोर डॉक्टर के पाछू म छै सात गॉंव आथे जेकर ले पसु ल बेमारी होगे त समे म इलाज नइ मिल पावय",
        "text_id": "301711",
        "text_type": "statement",
        "utterance_id": "30000086",
        "wav_path": "D1/30088/IISc_RESPIN_ch_D1_30088_495115_M_AGRI_301711_30000086.wav"
    },
    "IISc_RESPIN_ch_D1_30088_495115_M_BANK_303224_30000087": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 7.52,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495115",
        "slab": "clean",
        "speaker_id": "30088",
        "speaker_id_reassigned": "30046_1",
        "text": "जेखर डेबिट कारड के आखरी तारीख खतम होवइया हे तेखर तीर धोखेबाज मन फोन लगाथे",
        "text_id": "303224",
        "text_type": "statement",
        "utterance_id": "30000087",
        "wav_path": "D1/30088/IISc_RESPIN_ch_D1_30088_495115_M_BANK_303224_30000087.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_ch_D1_30088.txt) ###
```
IISc_RESPIN_ch_D1_30088_495115_M_AGRI_301711_30000086	एके ढोर डॉक्टर के पाछू म छै सात गॉंव आथे जेकर ले पसु ल बेमारी होगे त समे म इलाज नइ मिल पावय
IISc_RESPIN_ch_D1_30088_495115_M_BANK_303224_30000087	जेखर डेबिट कारड के आखरी तारीख खतम होवइया हे तेखर तीर धोखेबाज मन फोन लगाथे
IISc_RESPIN_ch_D1_30088_495115_M_AGRI_301213_30000088	दवई छींचे के बाद घलो थोकन दिन बाद म बन दिखे ल धर लेथे
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