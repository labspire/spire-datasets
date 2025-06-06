## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Chhattisgarhi (CH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_ch
- Total Audio Duration (HH:MM:SS): 3:51:01
- Average Sample Duration: 6.205 secs
- Total Unique Text IDs: 695
- Unique Word Count: 2072
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 517 | 75 | 73 | 148 | 40 | 40 | 0.44 | 0.42 | 0.86 |
| D2 | 561 | 93 | 61 | 154 | 40 | 40 | 0.65 | 0.37 | 1.02 |
| D3 | 564 | 96 | 76 | 172 | 40 | 40 | 0.43 | 0.42 | 0.85 |
| D4 | 592 | 124 | 97 | 221 | 40 | 40 | 0.61 | 0.51 | 1.12 |
| Total | 2234 | 388 | 307 | 695 | 160 | 160 | 2.13 | 1.72 | 3.85 |



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

### Metadata File Sample (meta_test_ch.json) ###

```json
{
    "IISc_RESPIN_ch_D1_30104_495009_M_AGRI_300692_30000246": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 6.15,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495009",
        "slab": "clean",
        "speaker_id": "30104",
        "speaker_id_reassigned": "30104_1",
        "text": "अतेक दवई खातू के छिंचे के बाद म घलोक कोनो फसल ह बने होबे नइ करत हे",
        "text_id": "300692",
        "text_type": "statement",
        "utterance_id": "30000246",
        "wav_path": "D1/30104/IISc_RESPIN_ch_D1_30104_495009_M_AGRI_300692_30000246.wav"
    },
    "IISc_RESPIN_ch_D1_30104_495009_M_BANK_303443_30000452": {
        "age_group": "18-24",
        "age_group_reassigned": "18-24",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 7.67,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495009",
        "slab": "clean",
        "speaker_id": "30104",
        "speaker_id_reassigned": "30104_1",
        "text": "आज के समे म तो बरोबर थोक पइसा लगाएच बर परथे बिना पइसा के तो काम बनय नइ",
        "text_id": "303443",
        "text_type": "statement",
        "utterance_id": "30000452",
        "wav_path": "D1/30104/IISc_RESPIN_ch_D1_30104_495009_M_BANK_303443_30000452.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_ch_D1_30104.txt) ###
```
IISc_RESPIN_ch_D1_30104_495009_M_AGRI_300692_30000246	अतेक दवई खातू के छिंचे के बाद म घलोक कोनो फसल ह बने होबे नइ करत हे
IISc_RESPIN_ch_D1_30104_495009_M_BANK_303443_30000452	आज के समे म तो बरोबर थोक पइसा लगाएच बर परथे बिना पइसा के तो काम बनय नइ
IISc_RESPIN_ch_D1_30104_495009_M_AGRI_300040_30000457	बियासी करे के बाद नींदे कोड़े बर खेत ल लगथें का कका ?
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