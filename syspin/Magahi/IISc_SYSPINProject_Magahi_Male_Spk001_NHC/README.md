## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Magahi Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Magahi Male Data Attributes

Type: Speech and Text
Language(s): Magahi
Linguality: Monolingual
Catalogue Id: SYSPIN_MAGAHI_M_NHC
Data Size (HH:MM:SS): 6 hours:6 mins:36 secs
Data Size (# Sentences): 3436
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EVAL, FINA, FOOD, HEAL, INDI, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Science (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

---

## File Structure

The corpus is organized into the following directory structure:
[Corpus_Root]/
└── [Speaker_1]/
      ├──[wavs]
      │    ├── [IISc_SYSPINProject_<languageTag><genderTag><domainTag><uniqueID>.wav]
      │    ├── [IISc_SYSPINProject<languageTag><genderTag><domainTag><uniqueID>.wav]
      │    ├── [IISc_SYSPINProject<languageTag><genderTag><domainTag><uniqueID>.wav]
      │    ├── [...]
      │    └── [IISc_SYSPINProject<languageTag><genderTag><domainTag><uniqueID>.wav]
      ├── [IISc_SYSPINProject<languageTag><genderTag><speakerTag><qualityCheckTag>Transcripts.json]
      └── [IISc_SYSPINProject<languageTag><genderTag><speakerTag><qualityCheckTag>_readme.txt]

---

## Magahi Male Data Statistics

Total Audio Duration:    6 hours:6 mins:36 secs
Average Sample Duration: 6.402 secs
Total Sentences:         3436
Unique word Count:       12945
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 1 hours:15 mins:54 secs |     664 | AGRICULTURE            |
| BOCU     | 0 hours:19 mins:1 secs  |     167 | RUNNING TEXT FROM BOOK |
| BOOK     | 0 hours:51 mins:32 secs |     411 | BOOKS                  |
| EVAL     | 0 hours:19 mins:35 secs |     212 | EVALUATION             |
| FINA     | 0 hours:22 mins:30 secs |     205 | FINANCE                |
| FOOD     | 0 hours:7 mins:4 secs   |     77  | FOOD                   |
| HEAL     | 0 hours:8 mins:55 secs  |     94  | HEALTH                 |
| INDI     | 0 hours:24 mins:32 secs |     228 | INDIA RELATED          |
| POLI     | 0 hours:46 mins:19 secs |     463 | POLITICS               |
| SOCI     | 0 hours:30 mins:48 secs |     288 | SOCIAL                 |
| SPOR     | 0 hours:36 mins:26 secs |     360 | SPORTS                 |
| TECH     | 0 hours:23 mins:54 secs |     267 | TECHNOLOGY             |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Magahi
Gender: Male
Age: 54
Experience: 5 years
Languages known: Magahi, Hindi, English
Mother tongue: Magahi

---

## Recording Setup

Microphone: Neumann TLM-103
Recording Environment: Professional studio
Recording Conditions: Studio quality at ~40dB SNR

---

## Transcription JSON Structure

Keys
├── MetaData (Project Information)
├── SpeakersMetaData (Speakers' Metadata)
└── Transcripts
        ├──[IISc_SYSPINProject_<languageTag><genderTag><domainTag><uniqueID>]
        │ 			├──Transcript
        │ 			└──Domain
        │ 		
        ├──[IISc_SYSPINProject<languageTag><genderTag><domainTag>_<uniqueID>]
        │ 			├──Transcript
        │ 			└──Domain
        │
        └──[...]

---

## Copyright and license

TTS data created under SYSPIN project by Indian Institute of Science, Bengaluru is available
at (https://spiredatasets.iisc.ac.in/syspinCorpus) and the copyright in the TTS data belongs to
Indian Institute of Science, Bengaluru and the said TTS data is released or distributed under
CC-BY-4.0 license (https://creativecommons.org/licenses/by/4.0/legalcode.en). The user of
said TTS data is referred to the disclaimer of warranties section in the CC-BY-4.0 license
agreement.

---

## Acknowledgments

We extend our heartfelt gratitude to the talented voice artist whose contributions were
fundamental to this project's success.
We are particularly grateful to the project of German Development Cooperation "FAIR Forward - AI
for All" for their financial support in developing this TTS corpus, and Bhashini AI Solutions 
Private Limited for their financial support for part of the corpus beyond 44 hours for every 
voice artist in developing this TTS corpus.

---

## Citation

@misc{SYSPIN_S1.0 Corpus,
     	Title = {SYSPIN_S1.0 Corpus - A TTS Corpus of 900+ hours in nine Indian Languages},
     	Authors = {Abhayjeet Et al.},
     	Year = {2025}
}

---

## Contact Information

SPIRE Lab, EE Dept., IISc, Bengaluru
Email: contact.syspin@iisc.ac.in>

---
