## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Marathi Female TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Marathi Female Data Attributes

Type: Speech and Text
Language(s): Marathi
Linguality: Monolingual
Catalogue Id: SYSPIN_MARATHI_F_HC
Data Size (HH:MM:SS): 51 hours:3 mins:32 secs
Data Size (# Sentences): 21790
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

## Marathi Female Data Statistics

Total Audio Duration:    51 hours:3 mins:32 secs
Average Sample Duration: 8.436 secs
Total Sentences:         21790
Unique word Count:       73547
Distribution of domains:
| Domain   | Duration                 |   Count | Domain Description   |
|:---------|:-------------------------|--------:|:---------------------|
| AGRI     | 5 hours:30 mins:37 secs  |    2384 | AGRICULTURE          |
| BOOK     | 10 hours:37 mins:48 secs |    4890 | BOOKS                |
| EDUC     | 3 hours:53 mins:41 secs  |    1475 | EDUCATION            |
| EVAL     | 0 hours:30 mins:45 secs  |    340  | EVALUATION           |
| FINA     | 5 hours:2 mins:22 secs   |    2092 | FINANCE              |
| GENE     | 4 hours:38 mins:34 secs  |    1818 | GENERAL              |
| HEAL     | 5 hours:21 mins:54 secs  |    2291 | HEALTH               |
| OTHE     | 4 hours:51 mins:17 secs  |    2090 | OTHERS               |
| POLI     | 4 hours:6 mins:15 secs   |    1644 | POLITICS             |
| WEAT     | 6 hours:30 mins:14 secs  |    2766 | WEATHER              |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Marathi
Gender: Female
Age: 37
Experience: 2 Years
Languages known: Marathi, Hindi, English
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
