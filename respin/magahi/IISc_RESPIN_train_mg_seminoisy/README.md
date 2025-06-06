## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Magahi (MG)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_mg_seminoisy
- Total Audio Duration (HH:MM:SS): 91:17:56
- Average Sample Duration: 6.153 secs
- Total Unique Text IDs: 16361
- Unique Word Count: 18851
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D3 | 15057 | 2094 | 2310 | 4404 | 582 | 686 | 10.90 | 11.66 | 22.56 |
| D1 | 7051 | 1858 | 1796 | 3654 | 474 | 351 | 5.85 | 6.23 | 12.08 |
| D4 | 24753 | 2479 | 2514 | 4993 | 517 | 458 | 21.22 | 24.38 | 45.60 |
| D2 | 6553 | 1575 | 1735 | 3310 | 464 | 405 | 5.28 | 5.78 | 11.06 |
| Total | 53414 | 8006 | 8355 | 16361 | 2037 | 1897 | 43.25 | 48.05 | 91.30 |



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

### Metadata File Sample (meta_train_mg_seminoisy.json) ###

```json
{
    "IISc_RESPIN_mg_D3_60256_844121_M_AGRI_615254_60000002": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Agriculture",
        "duration": 10.72,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "844121",
        "slab": "seminoisy",
        "speaker_id": "60256",
        "speaker_id_reassigned": "60222_1",
        "text": "वायवसंवर्धन के तकनीक बाकि सभी तकनीक से किफ़ायती होबा हई",
        "text_id": "615254",
        "text_type": "statement",
        "utterance_id": "60000002",
        "wav_path": "D3/60256/IISc_RESPIN_mg_D3_60256_844121_M_AGRI_615254_60000002.wav"
    },
    "IISc_RESPIN_mg_D3_60256_844121_M_BANK_614258_60000024": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D3",
        "domain": "Banking",
        "duration": 8.01,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "844121",
        "slab": "seminoisy",
        "speaker_id": "60256",
        "speaker_id_reassigned": "60222_1",
        "text": "सेवा शुल्क कर के वसूले ला टोल या परिवहन के इस्तेमाल कइल जाहई",
        "text_id": "614258",
        "text_type": "statement",
        "utterance_id": "60000024",
        "wav_path": "D3/60256/IISc_RESPIN_mg_D3_60256_844121_M_BANK_614258_60000024.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mg_D3_60256.txt) ###
```
IISc_RESPIN_mg_D3_60256_844121_M_AGRI_615254_60000002	वायवसंवर्धन के तकनीक बाकि सभी तकनीक से किफ़ायती होबा हई
IISc_RESPIN_mg_D3_60256_844121_M_BANK_614258_60000024	सेवा शुल्क कर के वसूले ला टोल या परिवहन के इस्तेमाल कइल जाहई
IISc_RESPIN_mg_D3_60256_844121_M_AGRI_614560_60000026	कुछ लकड़ियन हाथ लगावे पर बहुत नाजुक लगा हई
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