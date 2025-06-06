## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Magahi (MG)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-test_mg_hidden
- Total Audio Duration (HH:MM:SS): 3:13:32
- Average Sample Duration: 5.305 secs
- Total Unique Text IDs: 647
- Unique Word Count: 2360
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 550 | 97 | 80 | 177 | 40 | 40 | 0.42 | 0.35 | 0.77 |
| D4 | 556 | 99 | 76 | 175 | 40 | 40 | 0.51 | 0.40 | 0.91 |
| D2 | 518 | 72 | 70 | 142 | 40 | 40 | 0.38 | 0.44 | 0.82 |
| D3 | 565 | 73 | 80 | 153 | 40 | 40 | 0.30 | 0.42 | 0.72 |
| Total | 2189 | 341 | 306 | 647 | 160 | 160 | 1.61 | 1.61 | 3.23 |



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

### Metadata File Sample (meta_test_mg_hidden.json) ###

```json
{
    "IISc_RESPIN_mg_D1_60025_823311_M_AGRI_601854_60003947": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 3.62,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "823311",
        "slab": "clean",
        "speaker_id": "60025",
        "speaker_id_reassigned": "60025_1",
        "text": "भारत के बहुत बड़ा आबादी खेती पर निर्भर करऽ हई",
        "text_id": "601854",
        "text_type": "statement",
        "utterance_id": "60003947",
        "wav_path": "D1/60025/IISc_RESPIN_mg_D1_60025_823311_M_AGRI_601854_60003947.wav"
    },
    "IISc_RESPIN_mg_D1_60025_823311_M_AGRI_601996_60004137": {
        "age_group": "25-30",
        "age_group_reassigned": "25-30",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 8.64,
        "gender": "MALE",
        "gender_reassigned": "MALE",
        "lid": "mg",
        "pincode": "823311",
        "slab": "clean",
        "speaker_id": "60025",
        "speaker_id_reassigned": "60025_1",
        "text": "खेत में बहुत बार मादक पौधा हानिकारक खेर पतवार के तरह उगऽ हई",
        "text_id": "601996",
        "text_type": "statement",
        "utterance_id": "60004137",
        "wav_path": "D1/60025/IISc_RESPIN_mg_D1_60025_823311_M_AGRI_601996_60004137.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_mg_D1_60025.txt) ###
```
IISc_RESPIN_mg_D1_60025_823311_M_AGRI_601854_60003947	भारत के बहुत बड़ा आबादी खेती पर निर्भर करऽ हई
IISc_RESPIN_mg_D1_60025_823311_M_AGRI_601996_60004137	खेत में बहुत बार मादक पौधा हानिकारक खेर पतवार के तरह उगऽ हई
IISc_RESPIN_mg_D1_60025_823311_M_AGRI_602052_60004161	धान के खेत में विलक्लोर आदि रसायन के उपयोग कैल जा हई
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