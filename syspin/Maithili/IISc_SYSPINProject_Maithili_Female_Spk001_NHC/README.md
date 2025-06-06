## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Maithili Female TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Maithili Female Data Attributes

Type: Speech and Text
Language(s): Maithili
Linguality: Monolingual
Catalogue Id: SYSPIN_MAITHILI_F_NHC
Data Size (HH:MM:SS): 0 hours:54 mins:9 secs
Data Size (# Sentences): 532
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
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

## Maithili Female Data Statistics

Total Audio Duration:    0 hours:54 mins:9 secs
Average Sample Duration: 6.108 secs
Total Sentences:         532
Unique word Count:       3523
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description   |
|:---------|:------------------------|--------:|:---------------------|
| AGRI     | 0 hours:1 mins:15 secs  |     12  | AGRICULTURE          |
| BOOK     | 0 hours:13 mins:47 secs |     160 | BOOKS                |
| EVAL     | 0 hours:0 mins:43 secs  |     8   | EVALUATION           |
| FINA     | 0 hours:2 mins:45 secs  |     24  | FINANCE              |
| FOOD     | 0 hours:2 mins:40 secs  |     25  | FOOD                 |
| HEAL     | 0 hours:6 mins:30 secs  |     62  | HEALTH               |
| INDI     | 0 hours:1 mins:10 secs  |     11  | INDIA RELATED        |
| LOCA     | 0 hours:0 mins:35 secs  |     5   | LOCAL CONVERSATION   |
| POLI     | 0 hours:0 mins:14 secs  |     2   | POLITICS             |
| SOCI     | 0 hours:10 mins:34 secs |     105 | SOCIAL               |
| SPOR     | 0 hours:0 mins:13 secs  |     2   | SPORTS               |
| TECH     | 0 hours:13 mins:37 secs |     116 | TECHNOLOGY           |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Maithili
Gender: Female
Age: 30
Experience: 1 Year
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
