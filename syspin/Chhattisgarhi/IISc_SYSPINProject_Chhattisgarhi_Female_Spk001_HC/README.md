## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Chhattisgarhi Female TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Chhattisgarhi Female Data Attributes

Type: Speech and Text
Language(s): Chhattisgarhi
Linguality: Monolingual
Catalogue Id: SYSPIN_CHHATTISGARHI_F_HC
Data Size (HH:MM:SS): 54 hours:48 mins:50 secs
Data Size (# Sentences): 27595
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EVAL, FINA, FOOD, GENE, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH, WEBS
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

## Chhattisgarhi Female Data Statistics

Total Audio Duration:    54 hours:48 mins:50 secs
Average Sample Duration: 7.151 secs
Total Sentences:         27595
Unique word Count:       50169
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 3 hours:23 mins:53 secs |    1612 | AGRICULTURE            |
| BOCU     | 4 hours:29 mins:40 secs |    2086 | RUNNING TEXT FROM BOOK |
| BOOK     | 3 hours:14 mins:11 secs |    1694 | BOOKS                  |
| EVAL     | 0 hours:33 mins:38 secs |    345  | EVALUATION             |
| FINA     | 2 hours:28 mins:9 secs  |    1121 | FINANCE                |
| FOOD     | 4 hours:55 mins:10 secs |    2451 | FOOD                   |
| GENE     | 4 hours:53 mins:44 secs |    2632 | GENERAL                |
| HEAL     | 3 hours:39 mins:5 secs  |    1981 | HEALTH                 |
| INDI     | 5 hours:21 mins:25 secs |    2733 | INDIA RELATED          |
| LOCA     | 5 hours:16 mins:33 secs |    2461 | LOCAL CONVERSATION     |
| POLI     | 2 hours:46 mins:47 secs |    1280 | POLITICS               |
| SOCI     | 3 hours:21 mins:40 secs |    1787 | SOCIAL                 |
| SPOR     | 2 hours:43 mins:37 secs |    1587 | SPORTS                 |
| TECH     | 4 hours:5 mins:56 secs  |    2077 | TECHNOLOGY             |
| WEBS     | 3 hours:35 mins:16 secs |    1748 | WEBSITE SCRAPED        |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Chhattisgarhi
Gender: Female
Age: 52
Experience: 25 Years
Languages known: Chhattisgarhi, Hindi
Mother tongue: Chhattisgarhi

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
