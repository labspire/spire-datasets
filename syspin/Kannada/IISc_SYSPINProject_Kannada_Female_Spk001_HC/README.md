## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Kannada Female TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Kannada Female Data Attributes

Type: Speech and Text
Language(s): Kannada
Linguality: Monolingual
Catalogue Id: SYSPIN_KANNADA_F_HC
Data Size (HH:MM:SS): 52 hours:21 mins:46 secs
Data Size (# Sentences): 17203
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCO, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
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

## Kannada Female Data Statistics

Total Audio Duration:    52 hours:21 mins:46 secs
Average Sample Duration: 10.958 secs
Total Sentences:         17203
Unique word Count:       75942
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 3 hours:13 mins:43 secs |    1057 | AGRICULTURE            |
| BOCO     | 2 hours:49 mins:0 secs  |    770  | RUNNING TEXT FROM BOOK |
| BOOK     | 17 hours:16 mins:2 secs |    6064 | BOOKS                  |
| EDUC     | 3 hours:21 mins:4 secs  |    1113 | EDUCATION              |
| EVAL     | 0 hours:49 mins:15 secs |    342  | EVALUATION             |
| FINA     | 4 hours:32 mins:29 secs |    1472 | FINANCE                |
| GENE     | 4 hours:56 mins:17 secs |    1522 | GENERAL                |
| HEAL     | 4 hours:35 mins:58 secs |    1447 | HEALTH                 |
| OTHE     | 3 hours:26 mins:33 secs |    1095 | OTHERS                 |
| POLI     | 2 hours:59 mins:31 secs |    928  | POLITICS               |
| WEAT     | 4 hours:21 mins:48 secs |    1393 | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Kannada
Gender: Female
Age: 39
Experience: 16 Years
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
