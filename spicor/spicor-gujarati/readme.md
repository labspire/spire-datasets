## SPICOR TTS CORPUS

As a part of the SPICOR project, studio-recorded Gujarati Male and Female TTS data is being released. Validated audio and text files are made available to the public. This will potentially open up opportunities for academic researchers, students, small and large-scale industries and research labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages included in the SPICOR project.

---

## File Structure

The corpus is organized into the following directory structure:

```
[Corpus_Root]/
└── [Speaker_1]/
      ├──[wavs]
      │    ├── [IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [...]
      │    └── [IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      ├── [IISc_SPICORProject_<languageTag>_<genderTag>_<speakerTag>_<qualityCheckTag>_Transcripts.json]
      └── [IISc_SPICORProject_<languageTag>_<genderTag>_<speakerTag>_<qualityCheckTag>_readme.txt]
```

---

## Transcription JSON Structure

```
Keys
├── MetaData (Project Information)
├── SpeakersMetaData (Speakers' Metadata)
└── Transcripts
        ├──[IISc_SPICORProject_<languageTag><genderTag><domainTag><uniqueID>]
        │ 			├──Transcript
        │ 			└──Domain
        │ 
        ├──[IISc_SPICORProject<languageTag><genderTag><domainTag>_<uniqueID>]
        │ 			├──Transcript
        │ 			└──Domain
        │
        └──[...]
```

---

## Speakers' MetaData

#### Gujarati Male:

Language: Gujarati  
Gender: Male  
Age: 23  
Experience: 1 Year  
Languages known: English, Hindi, Gujarati  
Mother tongue: Gujarati  

#### Gujarati Female:

Language: Gujarati  
Gender: Female  
Age: 33  
Experience: 1 Year  
Languages known: English, Hindi, Gujarati  
Mother tongue: Gujarati  

---

## Gujarati Male (HC)

#### Data Attributes:

Type: Speech and Text  
Language(s): Gujarati  
Linguality: Monolingual  
Catalogue Id: SPICOR_GUJARATI_M_HC  
Data Size (HH:MM:SS): 23 hours:38 mins:15 secs  
Data Size (# Sentences): 7835  
Data size (# Speakers): Male(1)  
Speaker Tag: Spk0001  
Domains: AGRI, CONV, ENTE, FEST, FINA, GENE, GMIN, HEAL, HIST, INCL, MICR, POLI, RELI, SCFI, SCIE, SPAC,
SPOR, STBK, STOR  
Annotation file availability: YES  
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel  
Validation status: Validated  
Data creator: Indian Institute of Science (IISc), Bengaluru  
Year of publishing: 2024  
Suggested research purpose/ areas: TTS  

#### Data Statistics:

Total Audio Duration:    23 hours:38 mins:15 secs  
Average Sample Duration: 10.862 secs  
Total Sentences:         7835  
Unique word Count:       42534  

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description      |
| ------ | ----------------------- | ----- | ----------------------- |
| AGRI   | 0 hours:21 mins:49 secs | 122   | AGRICULTURE             |
| CONV   | 0 hours:15 mins:33 secs | 189   | CONVERSATIONAL          |
| ENTE   | 1 hours:45 mins:35 secs | 569   | ENTERTAINMENT           |
| FEST   | 0 hours:2 mins:25 secs  | 15    | FESTIVAL                |
| FINA   | 2 hours:43 mins:49 secs | 871   | FINANCE                 |
| GENE   | 1 hours:42 mins:43 secs | 563   | GENERAL                 |
| GMIN   | 0 hours:7 mins:45 secs  | 95    | GRAMMATICALLY INCORRECT |
| HEAL   | 2 hours:30 mins:25 secs | 829   | HEALTH                  |
| HIST   | 0 hours:56 mins:23 secs | 309   | HISTORY                 |
| INCL   | 0 hours:2 mins:34 secs  | 16    | INDIAN CULTURE          |
| MICR   | 0 hours:38 mins:38 secs | 246   | MICROSOFT               |
| POLI   | 0 hours:45 mins:11 secs | 238   | POLITICS                |
| RELI   | 0 hours:45 mins:5 secs  | 253   | RELIGION                |
| SCFI   | 0 hours:2 mins:20 secs  | 14    | SCIENCE AND FICTION     |
| SCIE   | 9 hours:14 mins:49 secs | 2923  | SCIENCE AND TECHNOLOGY  |
| SPAC   | 0 hours:2 mins:56 secs  | 16    | SPACE                   |
| SPOR   | 1 hours:33 mins:20 secs | 531   | SPORTS                  |
| STBK   | 0 hours:1 mins:40 secs  | 8     | STORY BOOK              |
| STOR   | 0 hours:5 mins:4 secs   | 27    | STORIES                 |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Gujarati Female (HC)

#### Data Attributes:

Type: Speech and Text  
Language(s): Gujarati  
Linguality: Monolingual  
Catalogue Id: SPICOR_GUJARATI_F_HC  
Data Size (HH:MM:SS): 33 hours:36 mins:54 secs  
Data Size (# Sentences): 8243  
Data size (# Speakers): Female(1)  
Speaker Tag: Spk0001  
Domains: AGRI, CONV, ENTE, FEST, FINA, GENE, GMIN, HEAL, HIST, INCL, MICR, POLI, RELI, SCFI, SCIE, SPAC,
SPOR, STBK, STOR  
Annotation file availability: YES  
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel  
Validation status: Validated  
Data creator: Indian Institute of Science (IISc), Bengaluru  
Year of publishing: 2024  
Suggested research purpose/ areas: TTS  

#### Data Statistics:

Total Audio Duration:    33 hours:36 mins:54 secs  
Average Sample Duration: 14.683 secs  
Total Sentences:         8243  
Unique word Count:       44369  

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description      |
| ------ | ----------------------- | ----- | ----------------------- |
| AGRI   | 0 hours:30 mins:21 secs | 123   | AGRICULTURE             |
| CONV   | 0 hours:17 mins:38 secs | 199   | CONVERSATIONAL          |
| ENTE   | 2 hours:23 mins:28 secs | 580   | ENTERTAINMENT           |
| FEST   | 0 hours:3 mins:24 secs  | 17    | FESTIVAL                |
| FINA   | 3 hours:59 mins:34 secs | 920   | FINANCE                 |
| GENE   | 2 hours:25 mins:47 secs | 584   | GENERAL                 |
| GMIN   | 0 hours:9 mins:32 secs  | 99    | GRAMMATICALLY INCORRECT |
| HEAL   | 3 hours:39 mins:15 secs | 887   | HEALTH                  |
| HIST   | 1 hours:17 mins:10 secs | 315   | HISTORY                 |
| INCL   | 0 hours:3 mins:4 secs   | 17    | INDIAN CULTURE          |
| MICR   | 0 hours:53 mins:15 secs | 247   | MICROSOFT               |
| POLI   | 1 hours:6 mins:16 secs  | 250   | POLITICS                |
| RELI   | 1 hours:3 mins:11 secs  | 266   | RELIGION                |
| SCFI   | 0 hours:3 mins:41 secs  | 18    | SCIENCE AND FICTION     |
| SCIE   | 13 hours:9 mins:57 secs | 3091  | SCIENCE AND TECHNOLOGY  |
| SPAC   | 0 hours:4 mins:1 secs   | 18    | SPACE                   |
| SPOR   | 2 hours:16 mins:57 secs | 569   | SPORTS                  |
| STBK   | 0 hours:3 mins:33 secs  | 15    | STORY BOOK              |
| STOR   | 0 hours:6 mins:40 secs  | 27    | STORIES                 |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Gujarati Male (NHC)

#### Data Attributes

Type: Speech and Text  
Language(s): Gujarati  
Linguality: Monolingual  
Catalogue Id: SPICOR_GUJARATI_M_NHC  
Data Size (HH:MM:SS): 4 hours:48 mins:20 secs  
Data Size (# Sentences): 1366  
Data size (# Speakers): Male(1)  
Speaker Tag: Spk0001  
Domains: AGRI, CONV, ENTE, FEST, FINA, GENE, GMIN, HEAL, HIST, INCL, MICR, POLI, RELI, SCFI, SCIE, SPAC,
SPOR, STBK, STOR  
Annotation file availability: YES  
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel  
Validation status: Not Validated  
Data creator: Indian Institute of Science (IISc), Bengaluru  
Year of publishing: 2024  
Suggested research purpose/ areas: TTS  

---

#### Data Statistics

Total Audio Duration:    4 hours:48 mins:20 secs  
Average Sample Duration: 12.674 secs  
Total Sentences:         1366  
Unique word Count:       14026  

####Distribution of domains:

| Domain | Duration                | Count | Domain Description      |
| ------ | ----------------------- | ----- | ----------------------- |
| AGRI   | 0 hours:2 mins:48 secs  | 14    | AGRICULTURE             |
| CONV   | 0 hours:0 mins:59 secs  | 11    | CONVERSATIONAL          |
| ENTE   | 0 hours:17 mins:26 secs | 82    | ENTERTAINMENT           |
| FEST   | 0 hours:0 mins:46 secs  | 5     | FESTIVAL                |
| FINA   | 0 hours:37 mins:48 secs | 177   | FINANCE                 |
| GENE   | 0 hours:14 mins:55 secs | 71    | GENERAL                 |
| GMIN   | 0 hours:0 mins:27 secs  | 5     | GRAMMATICALLY INCORRECT |
| HEAL   | 0 hours:34 mins:39 secs | 161   | HEALTH                  |
| HIST   | 0 hours:12 mins:27 secs | 58    | HISTORY                 |
| INCL   | 0 hours:0 mins:31 secs  | 4     | INDIAN CULTURE          |
| MICR   | 0 hours:3 mins:57 secs  | 22    | MICROSOFT               |
| POLI   | 0 hours:9 mins:3 secs   | 40    | POLITICS                |
| RELI   | 0 hours:8 mins:7 secs   | 38    | RELIGION                |
| SCFI   | 0 hours:1 mins:4 secs   | 6     | SCIENCE AND FICTION     |
| SCIE   | 2 hours:0 mins:24 secs  | 553   | SCIENCE AND TECHNOLOGY  |
| SPAC   | 0 hours:0 mins:55 secs  | 4     | SPACE                   |
| SPOR   | 0 hours:18 mins:42 secs | 98    | SPORTS                  |
| STBK   | 0 hours:2 mins:28 secs  | 12    | STORY BOOK              |
| STOR   | 0 hours:0 mins:45 secs  | 4     | STORIES                 |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Gujarati Female (NHC)

#### Data Attributes:

Type: Speech and Text  
Language(s): Gujarati  
Linguality: Monolingual  
Catalogue Id: SPICOR_GUJARATI_F_NHC  
Data Size (HH:MM:SS): 3 hours:56 mins:2 secs  
Data Size (# Sentences): 859  
Data size (# Speakers): Female(1)  
Speaker Tag: Spk0001  
Domains: AGRI, CONV, ENTE, FEST, FINA, GENE, GMIN, HEAL, HIST, INCL, MICR, POLI, RELI, SCFI, SCIE, SPAC,
SPOR, STBK, STOR  
Annotation file availability: YES  
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel  
Validation status: Not Validated  
Data creator: Indian Institute of Science (IISc), Bengaluru  
Year of publishing: 2024  
Suggested research purpose/ areas: TTS  

#### Data Statistics:

Total Audio Duration:    3 hours:56 mins:2 secs  
Average Sample Duration: 16.507 secs  
Total Sentences:         859  
Unique word Count:       9859  

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description      |
| ------ | ----------------------- | ----- | ----------------------- |
| AGRI   | 0 hours:3 mins:10 secs  | 11    | AGRICULTURE             |
| CONV   | 0 hours:0 mins:7 secs   | 1     | CONVERSATIONAL          |
| ENTE   | 0 hours:17 mins:18 secs | 61    | ENTERTAINMENT           |
| FEST   | 0 hours:0 mins:37 secs  | 3     | FESTIVAL                |
| FINA   | 0 hours:33 mins:55 secs | 119   | FINANCE                 |
| GENE   | 0 hours:11 mins:25 secs | 46    | GENERAL                 |
| GMIN   | 0 hours:0 mins:7 secs   | 1     | GRAMMATICALLY INCORRECT |
| HEAL   | 0 hours:25 mins:20 secs | 93    | HEALTH                  |
| HIST   | 0 hours:8 mins:24 secs  | 32    | HISTORY                 |
| INCL   | 0 hours:0 mins:30 secs  | 3     | INDIAN CULTURE          |
| MICR   | 0 hours:3 mins:55 secs  | 17    | MICROSOFT               |
| POLI   | 0 hours:7 mins:28 secs  | 24    | POLITICS                |
| RELI   | 0 hours:6 mins:50 secs  | 24    | RELIGION                |
| SCFI   | 0 hours:0 mins:31 secs  | 2     | SCIENCE AND FICTION     |
| SCIE   | 1 hours:41 mins:13 secs | 362   | SCIENCE AND TECHNOLOGY  |
| SPAC   | 0 hours:0 mins:31 secs  | 2     | SPACE                   |
| SPOR   | 0 hours:12 mins:28 secs | 48    | SPORTS                  |
| STBK   | 0 hours:1 mins:11 secs  | 5     | STORY BOOK              |
| STOR   | 0 hours:0 mins:54 secs  | 4     | STORIES                 |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

## ## Recording Setup

Microphone: ZOOM H6  
Recording Environment: Professional studio  
Recording Conditions: Studio quality at ~40dB SNR  

## Copyright and license

TTS data created under SPICOR project by Indian Institute of Science, Bengaluru is available at ([https://spiredatasets.iisc.ac.in/spicortts20]()) and the copyright in the TTS data belongs to Indian Institute of Science, Bengaluru and the said TTS data is released or distributed under CC-BY-4.0 license ([https://creativecommons.org/licenses/by/4.0/legalcode.en]()). The user of said TTS data is referred to the disclaimer of warranties section in the CC-BY-4.0 license agreement.

## Acknowledgments

We extend our heartfelt gratitude to the talented voice artist whose contributions were
fundamental to this project's success.
We acknowledge the facility of IISc Studio in creating the TTS corpus.

## Citation

@misc{SPICOR TTS_2.0 Corpus,
     	Title = {SPICOR TTS_2.0 Corpus - A 57+ hour domain-rich Gujarati TTS Corpus},
     	Authors = {Abhayjeet Et al.},
     	Year = {2025}
}

## Contact Information

SPIRE Lab, EE Dept., IISc, Bengaluru
Email: spirelab.ee@iisc.ac.in
