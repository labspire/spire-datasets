## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Bengali Female TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Bengali Female Data Attributes

Type: Speech and Text
Language(s): Bengali
Linguality: Monolingual
Catalogue Id: SYSPIN_BENGALI_F_HC
Data Size (HH:MM:SS): 50 hours:44 mins:39 secs
Data Size (# Sentences): 21152
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
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

## Bengali Female Data Statistics

Total Audio Duration:    50 hours:44 mins:39 secs
Average Sample Duration: 8.637 secs
Total Sentences:         21152
Unique word Count:       68952
Distribution of domains:
| Domain   | Duration                 |   Count | Domain Description     |
|:---------|:-------------------------|--------:|:-----------------------|
| AGRI     | 6 hours:1 mins:37 secs   |    2218 | AGRICULTURE            |
| BOCU     | 4 hours:21 mins:25 secs  |    1877 | RUNNING TEXT FROM BOOK |
| BOOK     | 15 hours:31 mins:17 secs |    7061 | BOOKS                  |
| EDUC     | 4 hours:50 mins:44 secs  |    1693 | EDUCATION              |
| EVAL     | 0 hours:33 mins:41 secs  |    329  | EVALUATION             |
| FINA     | 5 hours:26 mins:48 secs  |    2254 | FINANCE                |
| GENE     | 3 hours:17 mins:6 secs   |    1337 | GENERAL                |
| HEAL     | 2 hours:57 mins:41 secs  |    1174 | HEALTH                 |
| OTHE     | 2 hours:3 mins:12 secs   |    933  | OTHERS                 |
| POLI     | 3 hours:11 mins:8 secs   |    1249 | POLITICS               |
| WEAT     | 2 hours:29 mins:55 secs  |    1027 | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Bengali
Gender: Female
Age: 27
Experience: 10 Years
Languages known: Bengali, Hindi, English
Mother tongue: Bengali

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
