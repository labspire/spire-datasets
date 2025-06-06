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
Catalogue Id: SYSPIN_MAITHILI_F_HC
Data Size (HH:MM:SS): 59 hours:40 mins:32 secs
Data Size (# Sentences): 34412
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
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

Total Audio Duration:    59 hours:40 mins:32 secs
Average Sample Duration: 6.243 secs
Total Sentences:         34412
Unique word Count:       73522
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description   |
|:---------|:------------------------|--------:|:---------------------|
| AGRI     | 4 hours:20 mins:27 secs |    2584 | AGRICULTURE          |
| BOOK     | 13 hours:7 mins:17 secs |    7867 | BOOKS                |
| EVAL     | 0 hours:34 mins:52 secs |    392  | EVALUATION           |
| FINA     | 4 hours:16 mins:21 secs |    2409 | FINANCE              |
| FOOD     | 5 hours:4 mins:26 secs  |    2611 | FOOD                 |
| HEAL     | 4 hours:46 mins:7 secs  |    2683 | HEALTH               |
| INDI     | 4 hours:40 mins:33 secs |    2718 | INDIA RELATED        |
| LOCA     | 5 hours:3 mins:48 secs  |    2793 | LOCAL CONVERSATION   |
| POLI     | 4 hours:28 mins:28 secs |    2672 | POLITICS             |
| SOCI     | 4 hours:56 mins:22 secs |    2830 | SOCIAL               |
| SPOR     | 4 hours:24 mins:20 secs |    2765 | SPORTS               |
| TECH     | 3 hours:57 mins:26 secs |    2088 | TECHNOLOGY           |

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
