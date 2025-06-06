## RESPIN S1.0 CORPUS ##

As a part of the RESPIN project, crowdsource read-speech data is being released. Audio and text files
are made available to the public, promoting innovation in Automatic Speech Recognition for Indian languages.

## Data Statistics ##

- Type: Parallel Speech and Text
- Language(s): Telugu (TE)
- Linguality: Monolingual
- Catalogue Id: RESPIN-S1.0-train_te_clean
- Total Audio Duration (HH:MM:SS): 1021:09:49
- Average Sample Duration: 5.230 secs
- Total Unique Text IDs: 19978
- Unique Word Count: 37585
- Recording Specifications: 16 kHz, 16 bits per sample, Mono
- Recording Format: WAV
- Recording Environment: Natural
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purposes / areas: ASR, Language Identification, Dialect Identification, etc.

### Dialect-Wise Summary ###
| DID   | #utt | #sent (Agri) | #sent (Bank) | #sent | #spk | #re-spk | Agri (hrs) | Bank (hrs) | Total (hrs) |
|-------|------|--------------|--------------|-------|------|---------|------------|------------|-------------|
| D1 | 198856 | 2319 | 2512 | 4831 | 639 | 441 | 135.32 | 142.10 | 277.41 |
| D2 | 171447 | 2606 | 2570 | 5176 | 634 | 507 | 132.35 | 129.10 | 261.45 |
| D4 | 153698 | 2553 | 2574 | 5127 | 459 | 429 | 106.07 | 114.39 | 220.46 |
| D3 | 178882 | 2560 | 2379 | 4939 | 555 | 445 | 129.53 | 132.31 | 261.84 |
| Total | 702883 | 10038 | 10035 | 19978 | 2287 | 1819 | 503.27 | 517.90 | 1021.16 |



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

### Metadata File Sample (meta_train_te_clean.json) ###

```json
{
    "IISc_RESPIN_te_D1_90001_517297_M_BANK_900548_90000002": {
        "age_group": "56-60",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Banking",
        "duration": 10.81,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "te",
        "pincode": "517297",
        "slab": "clean",
        "speaker_id": "90001",
        "speaker_id_reassigned": "NA",
        "text": "కరెంటు బిల్లుల్ని కూడా సులువుగా ఆండ్రాయిడ్ ఫోన్ ఉంటే జీపే ద్వారా చెయ్యొచ్చు",
        "text_id": "900548",
        "text_type": "statement",
        "utterance_id": "90000002",
        "wav_path": "D1/90001/IISc_RESPIN_te_D1_90001_517297_M_BANK_900548_90000002.wav"
    },
    "IISc_RESPIN_te_D1_90001_517297_M_AGRI_902078_90000006": {
        "age_group": "56-60",
        "age_group_reassigned": "NA",
        "dialect": "D1",
        "domain": "Agriculture",
        "duration": 7.44,
        "gender": "MALE",
        "gender_reassigned": "NA",
        "lid": "te",
        "pincode": "517297",
        "slab": "clean",
        "speaker_id": "90001",
        "speaker_id_reassigned": "NA",
        "text": "వైద్యపరంగా ఉసిరికలో ఔషధగుణాలెక్కువంట , అందుకే రకరకాల ఉత్పత్తుల్లో ఉసిరి కాయలను వాడతారు",
        "text_id": "902078",
        "text_type": "statement",
        "utterance_id": "90000006",
        "wav_path": "D1/90001/IISc_RESPIN_te_D1_90001_517297_M_AGRI_902078_90000006.wav"
    }
}
```

### Text File Sample (IISc_RESPIN_te_D1_90001.txt) ###
```
IISc_RESPIN_te_D1_90001_517297_M_BANK_900548_90000002	కరెంటు బిల్లుల్ని కూడా సులువుగా ఆండ్రాయిడ్ ఫోన్ ఉంటే జీపే ద్వారా చెయ్యొచ్చు
IISc_RESPIN_te_D1_90001_517297_M_AGRI_902078_90000006	వైద్యపరంగా ఉసిరికలో ఔషధగుణాలెక్కువంట , అందుకే రకరకాల ఉత్పత్తుల్లో ఉసిరి కాయలను వాడతారు

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