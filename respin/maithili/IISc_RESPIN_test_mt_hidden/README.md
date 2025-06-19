## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Maithili (MT)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_mt_hidden
- Total Audio Duration (HH:MM:SS): 3:16:10
- Average Sample Duration: 5.427 secs
- Total Unique Text IDs: 975
- Unique Word Count: 2971
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 522 | 112 | 90 | 202 | 40 | 40 | 0.40 | 0.33 | 0.74 |
| D4 | 574 | 93 | 88 | 181 | 40 | 40 | 0.37 | 0.38 | 0.75 |
| D1 | 492 | 138 | 88 | 226 | 40 | 40 | 0.47 | 0.28 | 0.75 |
| D2 | 581 | 190 | 176 | 366 | 40 | 40 | 0.56 | 0.48 | 1.04 |
| Total | 2169 | 533 | 442 | 975 | 160 | 160 | 1.80 | 1.47 | 3.27 |



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

### Metadata File Sample (meta_test_mt_hidden.json) ###

```json
{
    "IISc_RESPIN_mt_D3_80171_NA_M_BANK_814855_80000385": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 5.17,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mt",
        "pincode": "451229",
        "slab": "clean",
        "speaker_id": "80171",
        "speaker_id_reassigned": "80171_1",
        "text": "दैनिक व्यापार के माध्यम सॅ शेयर बजार में निवेश कयल जाइत अछि",
        "text_id": "814855",
        "text_type": "statement",
        "utterance_id": "80000385",
        "wav_path": "D3/80171/IISc_RESPIN_mt_D3_80171_NA_M_BANK_814855_80000385.wav"
    },
    "IISc_RESPIN_mt_D3_80171_NA_M_AGRI_816771_80000564": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 5.48,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mt",
        "pincode": "451229",
        "slab": "clean",
        "speaker_id": "80171",
        "speaker_id_reassigned": "80171_1",
        "text": "बेसी सॅ बेसी दूध उत्पादन होय , एहि बातक चिंता सर्वप्रथम होइत छै",
        "text_id": "816771",
        "text_type": "statement",
        "utterance_id": "80000564",
        "wav_path": "D3/80171/IISc_RESPIN_mt_D3_80171_NA_M_AGRI_816771_80000564.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mt_D3_80171.txt) ###
```
IISc_RESPIN_mt_D3_80171_NA_M_BANK_814855_80000385	दैनिक व्यापार के माध्यम सॅ शेयर बजार में निवेश कयल जाइत अछि
IISc_RESPIN_mt_D3_80171_NA_M_AGRI_816771_80000564	बेसी सॅ बेसी दूध उत्पादन होय , एहि बातक चिंता सर्वप्रथम होइत छै
IISc_RESPIN_mt_D3_80171_NA_M_BANK_815217_80009304	ओ विभिन्न रूप सॅ मुद्रा बचत केनै छलाह
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