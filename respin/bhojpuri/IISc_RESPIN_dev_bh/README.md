## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bhojpuri (BH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_bh
- Total Audio Duration (HH:MM:SS): 2:08:35
- Average Sample Duration: 5.144 secs
- Total Unique Text IDs: 575
- Unique Word Count: 1811
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 500 | 108 | 83 | 191 | 20 | 20 | 0.41 | 0.33 | 0.73 |
| D2 | 500 | 98 | 87 | 185 | 20 | 20 | 0.39 | 0.31 | 0.69 |
| D1 | 500 | 128 | 71 | 199 | 20 | 20 | 0.41 | 0.31 | 0.72 |
| Total | 1500 | 334 | 241 | 575 | 60 | 60 | 1.20 | 0.94 | 2.14 |



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

### Metadata File Sample (meta_dev_bh.json) ###

```json
{
    "IISc_RESPIN_bh_D3_11194_845401_M_BANK_117614_10000696": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 7.61,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "845401",
        "slab": "clean",
        "speaker_id": "11194",
        "speaker_id_reassigned": "11194_2",
        "text": "एकरा में इक्विटी अउरी डेट इंस्ट्रूमेंट दुनो के सम्पति शामिल रहेला",
        "text_id": "117614",
        "text_type": "statement",
        "utterance_id": "10000696",
        "wav_path": "D3/11194/IISc_RESPIN_bh_D3_11194_845401_M_BANK_117614_10000696.wav"
    },
    "IISc_RESPIN_bh_D3_11194_845401_M_AGRI_118863_10000697": {
        "age_group": "36-40",
        "age_group_reassigned": "36-40",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 8.33,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "bh",
        "pincode": "845401",
        "slab": "clean",
        "speaker_id": "11194",
        "speaker_id_reassigned": "11194_2",
        "text": "मांस खातिर जवन मुर्गी पोसाली सन ओकनी के ब्रॉयलर कहाला",
        "text_id": "118863",
        "text_type": "statement",
        "utterance_id": "10000697",
        "wav_path": "D3/11194/IISc_RESPIN_bh_D3_11194_845401_M_AGRI_118863_10000697.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bh_D3_11194.txt) ###
```
IISc_RESPIN_bh_D3_11194_845401_M_BANK_117614_10000696	एकरा में इक्विटी अउरी डेट इंस्ट्रूमेंट दुनो के सम्पति शामिल रहेला
IISc_RESPIN_bh_D3_11194_845401_M_AGRI_118863_10000697	मांस खातिर जवन मुर्गी पोसाली सन ओकनी के ब्रॉयलर कहाला
IISc_RESPIN_bh_D3_11194_845401_M_BANK_117253_10000703	सेविंग बैंक अकाउंट में जामा कईल पइसा पर छौ प्रतिशत के ब्याज दीहल जाला
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