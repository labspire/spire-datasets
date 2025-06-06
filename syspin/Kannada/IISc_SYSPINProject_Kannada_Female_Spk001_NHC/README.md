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
Catalogue Id: SYSPIN_KANNADA_F_NHC
Data Size (HH:MM:SS): 9 hours:10 mins:33 secs
Data Size (# Sentences): 2740
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCO, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
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

## Kannada Female Data Statistics

Total Audio Duration:    9 hours:10 mins:33 secs
Average Sample Duration: 12.056 secs
Total Sentences:         2740
Unique word Count:       20492
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 0 hours:32 mins:16 secs |     178 | AGRICULTURE            |
| BOCO     | 1 hours:17 mins:55 secs |     302 | RUNNING TEXT FROM BOOK |
| BOOK     | 2 hours:47 mins:49 secs |     870 | BOOKS                  |
| EDUC     | 0 hours:19 mins:34 secs |     110 | EDUCATION              |
| EVAL     | 0 hours:9 mins:47 secs  |     58  | EVALUATION             |
| FINA     | 0 hours:39 mins:6 secs  |     199 | FINANCE                |
| GENE     | 0 hours:46 mins:15 secs |     230 | GENERAL                |
| HEAL     | 0 hours:43 mins:26 secs |     223 | HEALTH                 |
| OTHE     | 0 hours:39 mins:18 secs |     196 | OTHERS                 |
| POLI     | 0 hours:36 mins:9 secs  |     172 | POLITICS               |
| WEAT     | 0 hours:38 mins:53 secs |     202 | WEATHER                |

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
