## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Telugu (TE)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_te_noisy
- Total Audio Duration (HH:MM:SS): 127:39:26
- Average Sample Duration: 6.262 secs
- Total Unique Text IDs: 17914
- Unique Word Count: 35357
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 20739 | 2224 | 2374 | 4598 | 630 | 424 | 18.20 | 17.40 | 35.60 |
| D2 | 16288 | 2323 | 2317 | 4640 | 630 | 484 | 14.35 | 15.10 | 29.45 |
| D4 | 10261 | 1988 | 1992 | 3980 | 445 | 409 | 8.37 | 8.14 | 16.52 |
| D3 | 26102 | 2460 | 2317 | 4777 | 553 | 433 | 22.26 | 23.83 | 46.09 |
| Total | 73390 | 8995 | 9000 | 17914 | 2258 | 1747 | 63.19 | 64.47 | 127.66 |



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

### Metadata File Sample (meta_train_te_noisy.json) ###

```json
{
    "IISc_RESPIN_te_D1_90001_517297_M_BANK_900365_90000001": {
        "age_group": "56-60",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 14.5,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "te",
        "pincode": "517297",
        "slab": "noisy",
        "speaker_id": "90001",
        "speaker_id_reassigned": "NA",
        "text": "ప్రతికూల వడ్డీ రేట్ల సమయాల్లో తప్ప , ప్రస్తుత విలువ భవిష్యత్తు కంటే ఎక్కువగా ఉంటుంది",
        "text_id": "900365",
        "text_type": "statement",
        "utterance_id": "90000001",
        "wav_path": "D1/90001/IISc_RESPIN_te_D1_90001_517297_M_BANK_900365_90000001.wav"
    },
    "IISc_RESPIN_te_D1_90001_517297_M_BANK_900255_90000003": {
        "age_group": "56-60",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 5.01,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "te",
        "pincode": "517297",
        "slab": "noisy",
        "speaker_id": "90001",
        "speaker_id_reassigned": "NA",
        "text": "కొన్ని పన్నుల్ని మనం ప్రత్యక్షంగా కొన్నిటిని పరోక్షంగా చెల్లిస్తాం",
        "text_id": "900255",
        "text_type": "statement",
        "utterance_id": "90000003",
        "wav_path": "D1/90001/IISc_RESPIN_te_D1_90001_517297_M_BANK_900255_90000003.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_te_D1_90001.txt) ###
```
IISc_RESPIN_te_D1_90001_517297_M_BANK_900365_90000001	ప్రతికూల వడ్డీ రేట్ల సమయాల్లో తప్ప , ప్రస్తుత విలువ భవిష్యత్తు కంటే ఎక్కువగా ఉంటుంది
IISc_RESPIN_te_D1_90001_517297_M_BANK_900255_90000003	కొన్ని పన్నుల్ని మనం ప్రత్యక్షంగా కొన్నిటిని పరోక్షంగా చెల్లిస్తాం
IISc_RESPIN_te_D1_90001_517297_M_BANK_902212_90000004	మిలిటరీకి కావాల్సిన ఆయుధాలని యేరే దేశాల నుంచి కొంటానికే చానా బడ్జెట్ను కేటాయిత్తారు
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