## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Maithili (MT)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mt_noisy
- Total Audio Duration (HH:MM:SS): 314:12:18
- Average Sample Duration: 6.489 secs
- Total Unique Text IDs: 22609
- Unique Word Count: 18303
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 29994 | 3843 | 2531 | 6374 | 531 | 448 | 28.13 | 19.65 | 47.77 |
| D1 | 28164 | 3014 | 2474 | 5488 | 417 | 395 | 30.65 | 26.96 | 57.61 |
| D2 | 67543 | 2444 | 2743 | 5187 | 496 | 465 | 57.16 | 65.58 | 122.74 |
| D4 | 48612 | 2999 | 2561 | 5560 | 490 | 519 | 43.65 | 42.43 | 86.08 |
| Total | 174313 | 12300 | 10309 | 22609 | 1934 | 1824 | 159.58 | 154.63 | 314.21 |



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

### Metadata File Sample (meta_train_mt_noisy.json) ###

```json
{
    "IISc_RESPIN_mt_D3_80002_847304_F_AGRI_816934_80000013": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 9.17,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mt",
        "pincode": "847304",
        "slab": "noisy",
        "speaker_id": "80002",
        "speaker_id_reassigned": "80002_1",
        "text": "जाड़क मास मे जनमल भेंड़क बच्चा के बेसी सुरक्षित राखय पड़ैत छै",
        "text_id": "816934",
        "text_type": "statement",
        "utterance_id": "80000013",
        "wav_path": "D3/80002/IISc_RESPIN_mt_D3_80002_847304_F_AGRI_816934_80000013.wav"
    },
    "IISc_RESPIN_mt_D3_80002_847304_F_AGRI_817114_80000014": {
        "age_group": "18-24",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 8.77,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mt",
        "pincode": "847304",
        "slab": "noisy",
        "speaker_id": "80002",
        "speaker_id_reassigned": "80002_1",
        "text": "जल संसाधन प्रबंधनक लेल विभिन्न प्रकारक उपकरणक बेगरता होइत अछि",
        "text_id": "817114",
        "text_type": "statement",
        "utterance_id": "80000014",
        "wav_path": "D3/80002/IISc_RESPIN_mt_D3_80002_847304_F_AGRI_817114_80000014.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mt_D3_80002.txt) ###
```
IISc_RESPIN_mt_D3_80002_847304_F_AGRI_816934_80000013	जाड़क मास मे जनमल भेंड़क बच्चा के बेसी सुरक्षित राखय पड़ैत छै
IISc_RESPIN_mt_D3_80002_847304_F_AGRI_817114_80000014	जल संसाधन प्रबंधनक लेल विभिन्न प्रकारक उपकरणक बेगरता होइत अछि
IISc_RESPIN_mt_D3_80002_847304_F_AGRI_817281_80000028	पटुआक उत्पादन आब कम होमय लागल अछि
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