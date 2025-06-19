## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Marathi Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Marathi Male Data Attributes

Type: Speech and Text
Language(s): Marathi
Linguality: Monolingual
Catalogue Id: SYSPIN_MARATHI_M_NHC
Data Size (HH:MM:SS): 13 hours:8 mins:25 secs
Data Size (# Sentences): 5202
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
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

## Marathi Male Data Statistics

Total Audio Duration:    13 hours:8 mins:25 secs
Average Sample Duration: 9.094 secs
Total Sentences:         5202
Unique word Count:       30316
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 1 hours:6 mins:13 secs  |    450  | AGRICULTURE            |
| BOCU     | 0 hours:41 mins:18 secs |    219  | RUNNING TEXT FROM BOOK |
| BOOK     | 3 hours:36 mins:26 secs |    1403 | BOOKS                  |
| EDUC     | 0 hours:59 mins:8 secs  |    389  | EDUCATION              |
| EVAL     | 0 hours:10 mins:59 secs |    73   | EVALUATION             |
| FINA     | 0 hours:48 mins:29 secs |    321  | FINANCE                |
| GENE     | 1 hours:8 mins:26 secs  |    419  | GENERAL                |
| HEAL     | 1 hours:30 mins:26 secs |    637  | HEALTH                 |
| OTHE     | 1 hours:15 mins:33 secs |    545  | OTHERS                 |
| POLI     | 0 hours:54 mins:46 secs |    354  | POLITICS               |
| WEAT     | 0 hours:56 mins:34 secs |    392  | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Marathi
Gender: Male
Age: 52
Experience: 5 Years
Languages known: Marathi, Hindi
Mother tongue: Marathi

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
