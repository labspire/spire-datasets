## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Telugu (TE)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_te_seminoisy
- Total Audio Duration (HH:MM:SS): 186:05:53
- Average Sample Duration: 6.010 secs
- Total Unique Text IDs: 19370
- Unique Word Count: 36949
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 26088 | 2265 | 2455 | 4720 | 637 | 439 | 21.19 | 21.55 | 42.74 |
| D2 | 35982 | 2581 | 2555 | 5136 | 632 | 507 | 30.66 | 31.78 | 62.44 |
| D4 | 20972 | 2370 | 2403 | 4773 | 453 | 430 | 16.76 | 15.77 | 32.53 |
| D3 | 28429 | 2488 | 2343 | 4831 | 551 | 446 | 22.72 | 25.66 | 48.39 |
| Total | 111471 | 9704 | 9756 | 19370 | 2273 | 1819 | 91.33 | 94.77 | 186.10 |



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

### Metadata File Sample (meta_train_te_seminoisy.json) ###

```json
{
    "IISc_RESPIN_te_D1_90007_636005_F_BANK_900172_90000008": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 7.05,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "te",
        "pincode": "636005",
        "slab": "seminoisy",
        "speaker_id": "90007",
        "speaker_id_reassigned": "NA",
        "text": "మార్కెట్ ప్రభావం అనేది తరచుగా మార్కెట్ లిక్విడిటీకి దగ్గరి సంబంధం కలిగి ఉంటుంది",
        "text_id": "900172",
        "text_type": "statement",
        "utterance_id": "90000008",
        "wav_path": "D1/90007/IISc_RESPIN_te_D1_90007_636005_F_BANK_900172_90000008.wav"
    },
    "IISc_RESPIN_te_D1_90007_636005_F_AGRI_901589_90000015": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 8.61,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "te",
        "pincode": "636005",
        "slab": "seminoisy",
        "speaker_id": "90007",
        "speaker_id_reassigned": "90007_1",
        "text": "కూరగాయ పంటల యొక్క సరైన నాణ్యతను అభివృద్ధి చేయడంలో పంటకు ముందు ఉత్పత్తి పద్ధతులు కీలకం",
        "text_id": "901589",
        "text_type": "statement",
        "utterance_id": "90000015",
        "wav_path": "D1/90007/IISc_RESPIN_te_D1_90007_636005_F_AGRI_901589_90000015.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_te_D1_90007.txt) ###
```
IISc_RESPIN_te_D1_90007_636005_F_BANK_900172_90000008	మార్కెట్ ప్రభావం అనేది తరచుగా మార్కెట్ లిక్విడిటీకి దగ్గరి సంబంధం కలిగి ఉంటుంది
IISc_RESPIN_te_D1_90007_636005_F_AGRI_901589_90000015	కూరగాయ పంటల యొక్క సరైన నాణ్యతను అభివృద్ధి చేయడంలో పంటకు ముందు ఉత్పత్తి పద్ధతులు కీలకం
IISc_RESPIN_te_D1_90007_636005_F_BANK_902425_90000037	మన అవసరాల కోసం బ్యేంకుల నుంచి తీసుకునే లోన్లను పర్సనల్ లోన్లు అంటారు
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