## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Kannada Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Kannada Male Data Attributes

Type: Speech and Text
Language(s): Kannada
Linguality: Monolingual
Catalogue Id: SYSPIN_KANNADA_M_HC
Data Size (HH:MM:SS): 49 hours:19 mins:17 secs
Data Size (# Sentences): 20694
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
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

## Kannada Male Data Statistics

Total Audio Duration:    49 hours:19 mins:17 secs
Average Sample Duration: 8.58 secs
Total Sentences:         20694
Unique word Count:       85485
Distribution of domains:
| Domain   | Duration                 |   Count | Domain Description     |
|:---------|:-------------------------|--------:|:-----------------------|
| AGRI     | 3 hours:6 mins:58 secs   |    1093 | AGRICULTURE            |
| BOCU     | 3 hours:26 mins:55 secs  |    1283 | RUNNING TEXT FROM BOOK |
| BOOK     | 18 hours:23 mins:49 secs |    8834 | BOOKS                  |
| EDUC     | 3 hours:14 mins:48 secs  |    1130 | EDUCATION              |
| EVAL     | 0 hours:29 mins:42 secs  |    320  | EVALUATION             |
| FINA     | 3 hours:47 mins:59 secs  |    1500 | FINANCE                |
| GENE     | 4 hours:4 mins:57 secs   |    1574 | GENERAL                |
| HEAL     | 4 hours:0 mins:13 secs   |    1556 | HEALTH                 |
| OTHE     | 2 hours:39 mins:49 secs  |    1073 | OTHERS                 |
| POLI     | 2 hours:35 mins:52 secs  |    969  | POLITICS               |
| WEAT     | 3 hours:28 mins:9 secs   |    1362 | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Kannada
Gender: Male
Age: 39
Experience: 13 Years
Languages known: Kannada, English
Mother tongue: Kannada

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
