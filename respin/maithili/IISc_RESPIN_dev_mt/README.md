## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Maithili (MT)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-dev_mt
- Total Audio Duration (HH:MM:SS): 2:03:33
- Average Sample Duration: 5.261 secs
- Total Unique Text IDs: 693
- Unique Word Count: 2372
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 360 | 97 | 55 | 152 | 20 | 20 | 0.32 | 0.21 | 0.54 |
| D2 | 356 | 156 | 108 | 264 | 20 | 20 | 0.39 | 0.28 | 0.67 |
| D3 | 351 | 75 | 60 | 135 | 20 | 20 | 0.25 | 0.19 | 0.44 |
| D4 | 342 | 77 | 65 | 142 | 20 | 20 | 0.20 | 0.21 | 0.41 |
| Total | 1409 | 405 | 288 | 693 | 80 | 80 | 1.17 | 0.89 | 2.06 |



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

### Metadata File Sample (meta_dev_mt.json) ###

```json
{
    "IISc_RESPIN_mt_D1_80218_852112_M_BANK_804004_80002378": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 9.1,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mt",
        "pincode": "852112",
        "slab": "clean",
        "speaker_id": "80218",
        "speaker_id_reassigned": "80218_1",
        "text": "गाड़ीक बीमा एकटा समझौता छै गाड़ी मालिक आ इंश्योरेंस कंपनी केर बीचक",
        "text_id": "804004",
        "text_type": "statement",
        "utterance_id": "80002378",
        "wav_path": "D1/80218/IISc_RESPIN_mt_D1_80218_852112_M_BANK_804004_80002378.wav"
    },
    "IISc_RESPIN_mt_D2_80602_852122_F_BANK_808330_80004562": {
        "age_group": "46-50",
        "age_group_reassigned": "46-50",
        "dialect": "D2",
        "domain": "Banking",
        "duration": 10.29,
        "gender": "FEMALE",
        "gender_reassigned": "FEMALE",
        "lid": "mt",
        "pincode": "852122",
        "slab": "seminoisy",
        "speaker_id": "80602",
        "speaker_id_reassigned": "80602_1",
        "text": "क्रेडिट कार्ड सामान खरीदै या धन निकासी लेल एक सीमा धरि उधारक अनुमति दै छै",
        "text_id": "808330",
        "text_type": "statement",
        "utterance_id": "80004562",
        "wav_path": "D2/80602/IISc_RESPIN_mt_D2_80602_852122_F_BANK_808330_80004562.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mt_D1_80218.txt) ###
```
IISc_RESPIN_mt_D1_80218_852112_M_BANK_804004_80002378	गाड़ीक बीमा एकटा समझौता छै गाड़ी मालिक आ इंश्योरेंस कंपनी केर बीचक
IISc_RESPIN_mt_D1_80218_852112_M_AGRI_800299_80009138	उमर बढ़ला के साथे कोलाजीन कम होए लगइ छइ
IISc_RESPIN_mt_D1_80218_852112_M_BANK_804368_80009339	आइ काल्हि भारत मे लघु उद्योग केँ बेसी बढ़ाएल जा रहल छै
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