## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Chhattisgarhi (CH)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_ch_small
- Total Audio Duration (HH:MM:SS): 175:12:56
- Average Sample Duration: 7.352 secs
- Total Unique Text IDs: 17160
- Unique Word Count: 12075
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 21448 | 2145 | 2146 | 4291 | 355 | 242 | 19.55 | 23.17 | 42.73 |
| D2 | 21450 | 2146 | 2146 | 4292 | 352 | 240 | 20.82 | 23.24 | 44.05 |
| D4 | 21452 | 2368 | 1923 | 4291 | 423 | 346 | 25.39 | 21.14 | 46.53 |
| D3 | 21450 | 2145 | 2146 | 4291 | 456 | 412 | 19.88 | 22.03 | 41.91 |
| Total | 85800 | 8804 | 8361 | 17160 | 1586 | 1237 | 85.64 | 89.58 | 175.22 |



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

### Metadata File Sample (meta_train_ch_small.json) ###

```json
{
    "IISc_RESPIN_ch_D1_30088_495115_M_BANK_302319_30000112": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 8.15,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495115",
        "slab": "clean",
        "speaker_id": "30088",
        "speaker_id_reassigned": "30046_1",
        "text": "आज के बेरा म मारकेटिंग मन के स्व सहायता समूह मन ल सरकार घलौ ह समूह बरोबर सहयोग करत रथे",
        "text_id": "302319",
        "text_type": "statement",
        "utterance_id": "30000112",
        "wav_path": "D1/30088/IISc_RESPIN_ch_D1_30088_495115_M_BANK_302319_30000112.wav"
    },
    "IISc_RESPIN_ch_D1_30088_495115_M_AGRI_301393_30000125": {
        "age_group": "25-30",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 7.4,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "ch",
        "pincode": "495115",
        "slab": "clean",
        "speaker_id": "30088",
        "speaker_id_reassigned": "30046_1",
        "text": "बड़का नसल के बछिया ह जब जनमथे त ओकर पिला हर बने रथे अउ दूद घलौ बने देथे",
        "text_id": "301393",
        "text_type": "statement",
        "utterance_id": "30000125",
        "wav_path": "D1/30088/IISc_RESPIN_ch_D1_30088_495115_M_AGRI_301393_30000125.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_ch_D1_30088.txt) ###
```
IISc_RESPIN_ch_D1_30088_495115_M_BANK_302319_30000112	आज के बेरा म मारकेटिंग मन के स्व सहायता समूह मन ल सरकार घलौ ह समूह बरोबर सहयोग करत रथे
IISc_RESPIN_ch_D1_30088_495115_M_AGRI_301393_30000125	बड़का नसल के बछिया ह जब जनमथे त ओकर पिला हर बने रथे अउ दूद घलौ बने देथे

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