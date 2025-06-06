## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Hindi Female TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Hindi Female Data Attributes

Type: Speech and Text
Language(s): Hindi
Linguality: Monolingual
Catalogue Id: SYSPIN_HINDI_F_HC
Data Size (HH:MM:SS): 54 hours:54 mins:44 secs
Data Size (# Sentences): 22058
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
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

## Hindi Female Data Statistics

Total Audio Duration:    54 hours:54 mins:44 secs
Average Sample Duration: 8.962 secs
Total Sentences:         22058
Unique word Count:       47328
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description   |
|:---------|:------------------------|--------:|:---------------------|
| AGRI     | 1 hours:48 mins:18 secs |    848  | AGRICULTURE          |
| BOOK     | 23 hours:3 mins:20 secs |    8358 | BOOKS                |
| EDUC     | 5 hours:4 mins:10 secs  |    2060 | EDUCATION            |
| EVAL     | 0 hours:40 mins:38 secs |    396  | EVALUATION           |
| FINA     | 1 hours:46 mins:45 secs |    832  | FINANCE              |
| GENE     | 6 hours:0 mins:43 secs  |    2540 | GENERAL              |
| HEAL     | 1 hours:48 mins:31 secs |    835  | HEALTH               |
| OTHE     | 7 hours:21 mins:25 secs |    3081 | OTHERS               |
| POLI     | 2 hours:57 mins:51 secs |    1235 | POLITICS             |
| WEAT     | 4 hours:22 mins:58 secs |    1873 | WEATHER              |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Hindi
Gender: Female
Age: 42
Experience: 21 Years
Languages known: Hindi, English, Tamil
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
