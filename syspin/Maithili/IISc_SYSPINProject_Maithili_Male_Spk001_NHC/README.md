## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Maithili Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Maithili Male Data Attributes

Type: Speech and Text
Language(s): Maithili
Linguality: Monolingual
Catalogue Id: SYSPIN_MAITHILI_M_NHC
Data Size (HH:MM:SS): 3 hours:27 mins:47 secs
Data Size (# Sentences): 2060
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
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

## Maithili Male Data Statistics

Total Audio Duration:    3 hours:27 mins:47 secs
Average Sample Duration: 6.052 secs
Total Sentences:         2060
Unique word Count:       11397
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description   |
|:---------|:------------------------|--------:|:---------------------|
| AGRI     | 0 hours:11 mins:16 secs |     107 | AGRICULTURE          |
| BOOK     | 1 hours:29 mins:10 secs |     997 | BOOKS                |
| FINA     | 0 hours:15 mins:7 secs  |     148 | FINANCE              |
| FOOD     | 0 hours:17 mins:20 secs |     147 | FOOD                 |
| HEAL     | 0 hours:19 mins:15 secs |     163 | HEALTH               |
| INDI     | 0 hours:12 mins:49 secs |     114 | INDIA RELATED        |
| LOCA     | 0 hours:12 mins:49 secs |     120 | LOCAL CONVERSATION   |
| POLI     | 0 hours:1 mins:47 secs  |     16  | POLITICS             |
| SOCI     | 0 hours:16 mins:46 secs |     150 | SOCIAL               |
| SPOR     | 0 hours:8 mins:10 secs  |     71  | SPORTS               |
| TECH     | 0 hours:3 mins:13 secs  |     27  | TECHNOLOGY           |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Maithili
Gender: Male
Age: 43
Experience: 11 Years
Languages known: Maithili, Hindi
Mother tongue: Maithili

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
