## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Hindi Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Hindi Male Data Attributes

Type: Speech and Text
Language(s): Hindi
Linguality: Monolingual
Catalogue Id: SYSPIN_HINDI_M_HC
Data Size (HH:MM:SS): 54 hours:57 mins:49 secs
Data Size (# Sentences): 24699
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCT, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
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

## Hindi Male Data Statistics

Total Audio Duration:    54 hours:57 mins:49 secs
Average Sample Duration: 8.011 secs
Total Sentences:         24699
Unique word Count:       55610
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 1 hours:29 mins:11 secs |    683  | AGRICULTURE            |
| BOCT     | 4 hours:32 mins:30 secs |    2200 | RUNNING TEXT FROM BOOK |
| BOOK     | 21 hours:7 mins:55 secs |    9567 | BOOKS                  |
| EDUC     | 4 hours:32 mins:46 secs |    1865 | EDUCATION              |
| EVAL     | 0 hours:38 mins:3 secs  |    351  | EVALUATION             |
| FINA     | 1 hours:16 mins:53 secs |    592  | FINANCE                |
| GENE     | 6 hours:26 mins:14 secs |    2959 | GENERAL                |
| HEAL     | 1 hours:58 mins:25 secs |    886  | HEALTH                 |
| OTHE     | 8 hours:2 mins:29 secs  |    3505 | OTHERS                 |
| POLI     | 2 hours:59 mins:38 secs |    1255 | POLITICS               |
| WEAT     | 1 hours:53 mins:40 secs |    836  | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Hindi
Gender: Male
Age: 38
Experience: 10 Years
Languages known: Hindi, English
Mother tongue: Hindi

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
