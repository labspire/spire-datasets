## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Bengali (BN)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_bn_seminoisy
- Total Audio Duration (HH:MM:SS): 162:50:29
- Average Sample Duration: 6.358 secs
- Total Unique Text IDs: 17766
- Unique Word Count: 17184
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 10605 | 2103 | 1368 | 3471 | 289 | 225 | 11.96 | 8.67 | 20.63 |
| D2 | 6670 | 1523 | 1400 | 2923 | 238 | 198 | 5.85 | 5.64 | 11.49 |
| D4 | 27349 | 1902 | 1753 | 3655 | 345 | 291 | 26.63 | 24.58 | 51.21 |
| D5 | 12313 | 2571 | 1210 | 3781 | 279 | 258 | 15.59 | 8.50 | 24.09 |
| D1 | 35271 | 2126 | 1810 | 3936 | 328 | 297 | 30.36 | 25.06 | 55.43 |
| Total | 92208 | 10225 | 7541 | 17766 | 1479 | 1265 | 90.39 | 72.45 | 162.84 |



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

### Metadata File Sample (meta_train_bn_seminoisy.json) ###

```json
{
    "IISc_RESPIN_bn_D3_21825_221001_F_AGRI_208421_20000008": {
        "age_group": "41-45",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 6.32,
        "gender": "FEMALE",
        "gender_reassigned": "NA",
        "lid": "bn",
        "pincode": "221001",
        "slab": "seminoisy",
        "speaker_id": "21825",
        "speaker_id_reassigned": "NA",
        "text": "চাষিরা চাষবাসের জন্য ক্রেডিট কার্ডের মাধ্যমে টাকা ধার নিতে পারে",
        "text_id": "208421",
        "text_type": "statement",
        "utterance_id": "20000008",
        "wav_path": "D3/21825/IISc_RESPIN_bn_D3_21825_221001_F_AGRI_208421_20000008.wav"
    },
    "IISc_RESPIN_bn_D3_21193_784526_M_BANK_210704_20000071": {
        "age_group": "<18",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 5.04,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "bn",
        "pincode": "784526",
        "slab": "seminoisy",
        "speaker_id": "21193",
        "speaker_id_reassigned": "NA",
        "text": "সারা বছর ধরে যে টাকা রোজগার হয় তাকে বার্ষিক আয় বা ইনকাম বলে",
        "text_id": "210704",
        "text_type": "statement",
        "utterance_id": "20000071",
        "wav_path": "D3/21193/IISc_RESPIN_bn_D3_21193_784526_M_BANK_210704_20000071.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_bn_D3_21825.txt) ###
```
IISc_RESPIN_bn_D3_21825_221001_F_AGRI_208421_20000008	চাষিরা চাষবাসের জন্য ক্রেডিট কার্ডের মাধ্যমে টাকা ধার নিতে পারে


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