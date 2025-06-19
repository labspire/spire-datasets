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
Catalogue Id: SYSPIN_MAITHILI_M_HC
Data Size (HH:MM:SS): 55 hours:50 mins:19 secs
Data Size (# Sentences): 32156
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
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

Total Audio Duration:    55 hours:50 mins:19 secs
Average Sample Duration: 6.251 secs
Total Sentences:         32156
Unique word Count:       72581
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description   |
|:---------|:------------------------|--------:|:---------------------|
| AGRI     | 4 hours:22 mins:12 secs |    2495 | AGRICULTURE          |
| BOOK     | 13 hours:8 mins:27 secs |    8479 | BOOKS                |
| EVAL     | 0 hours:33 mins:13 secs |    400  | EVALUATION           |
| FINA     | 3 hours:44 mins:51 secs |    2292 | FINANCE              |
| FOOD     | 4 hours:12 mins:49 secs |    2165 | FOOD                 |
| HEAL     | 4 hours:27 mins:21 secs |    2331 | HEALTH               |
| INDI     | 4 hours:35 mins:24 secs |    2604 | INDIA RELATED        |
| LOCA     | 5 hours:52 mins:47 secs |    3236 | LOCAL CONVERSATION   |
| POLI     | 4 hours:12 mins:10 secs |    2364 | POLITICS             |
| SOCI     | 4 hours:43 mins:26 secs |    2533 | SOCIAL               |
| SPOR     | 3 hours:45 mins:49 secs |    2139 | SPORTS               |
| TECH     | 2 hours:11 mins:46 secs |    1118 | TECHNOLOGY           |

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
