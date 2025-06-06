## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Chhattisgarhi (CH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_ch_hidden
- Total Audio Duration (HH:MM:SS): 3:45:15
- Average Sample Duration: 6.055 secs
- Total Unique Text IDs: 674
- Unique Word Count: 1997
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 603 | 81 | 98 | 179 | 40 | 40 | 0.42 | 0.57 | 0.99 |
| D2 | 559 | 87 | 57 | 144 | 40 | 40 | 0.59 | 0.39 | 0.98 |
| D3 | 556 | 112 | 62 | 174 | 40 | 40 | 0.59 | 0.28 | 0.87 |
| D4 | 514 | 105 | 72 | 177 | 40 | 40 | 0.53 | 0.39 | 0.92 |
| Total | 2232 | 385 | 289 | 674 | 160 | 160 | 2.13 | 1.62 | 3.75 |



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

### Metadata File Sample (meta_test_ch_hidden.json) ###

```json
{
    "IISc_RESPIN_ch_D1_30104_495009_M_BANK_303441_30000056": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 8.55,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495009",
        "slab": "clean",
        "speaker_id": "30104",
        "speaker_id_reassigned": "30104_1",
        "text": "आज काल लोगन मन के सउक ह बनेच हो गए हे अइसन म ओमन ह कतको नसल के पालतू जानवर ल पोसथें",
        "text_id": "303441",
        "text_type": "statement",
        "utterance_id": "30000056",
        "wav_path": "D1/30104/IISc_RESPIN_ch_D1_30104_495009_M_BANK_303441_30000056.wav"
    },
    "IISc_RESPIN_ch_D1_30104_495009_M_AGRI_300519_30000062": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 6.25,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495009",
        "slab": "clean",
        "speaker_id": "30104",
        "speaker_id_reassigned": "30104_1",
        "text": "ले ठीक हे कका , अब मेंहा जावत हँव , मोर सारा ल लानहू तोर तीर",
        "text_id": "300519",
        "text_type": "statement",
        "utterance_id": "30000062",
        "wav_path": "D1/30104/IISc_RESPIN_ch_D1_30104_495009_M_AGRI_300519_30000062.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_ch_D1_30104.txt) ###
```
IISc_RESPIN_ch_D1_30104_495009_M_BANK_303441_30000056	आज काल लोगन मन के सउक ह बनेच हो गए हे अइसन म ओमन ह कतको नसल के पालतू जानवर ल पोसथें
IISc_RESPIN_ch_D1_30104_495009_M_AGRI_300519_30000062	ले ठीक हे कका , अब मेंहा जावत हँव , मोर सारा ल लानहू तोर तीर
IISc_RESPIN_ch_D1_30104_495009_M_AGRI_301367_30000220	कोनों परोसी गॉँव म पसू म छूतहा बेमारी फैले हे त उहॉं के पसू ल उहेंच रहेन देना चाही
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