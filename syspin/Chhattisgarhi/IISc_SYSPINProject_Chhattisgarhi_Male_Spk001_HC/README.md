## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Chhattisgarhi Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Chhattisgarhi Male Data Attributes

Type: Speech and Text
Language(s): Chhattisgarhi
Linguality: Monolingual
Catalogue Id: SYSPIN_CHHATTISGARHI_M_HC
Data Size (HH:MM:SS): 49 hours:45 mins:25 secs
Data Size (# Sentences): 22885
Data size (# Speakers): Male(1)
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

## Chhattisgarhi Male Data Statistics

Total Audio Duration:    49 hours:45 mins:25 secs
Average Sample Duration: 7.827 secs
Total Sentences:         22885
Unique word Count:       41161
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 3 hours:17 mins:13 secs |    1464 | AGRICULTURE            |
| BOCU     | 3 hours:41 mins:43 secs |    1458 | RUNNING TEXT FROM BOOK |
| BOOK     | 1 hours:28 mins:42 secs |    680  | BOOKS                  |
| EVAL     | 0 hours:36 mins:57 secs |    346  | EVALUATION             |
| FINA     | 2 hours:54 mins:44 secs |    1229 | FINANCE                |
| FOOD     | 4 hours:56 mins:20 secs |    2266 | FOOD                   |
| GENE     | 4 hours:25 mins:48 secs |    2098 | GENERAL                |
| HEAL     | 3 hours:47 mins:2 secs  |    1771 | HEALTH                 |
| INDI     | 5 hours:9 mins:20 secs  |    2476 | INDIA RELATED          |
| LOCA     | 5 hours:3 mins:48 secs  |    2205 | LOCAL CONVERSATION     |
| POLI     | 2 hours:17 mins:28 secs |    1087 | POLITICS               |
| SOCI     | 2 hours:25 mins:5 secs  |    1198 | SOCIAL                 |
| SPOR     | 2 hours:36 mins:59 secs |    1346 | SPORTS                 |
| TECH     | 3 hours:50 mins:59 secs |    1849 | TECHNOLOGY             |
| WEBS     | 3 hours:13 mins:10 secs |    1412 | WEBSITE SCRAPED        |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Chhattisgarhi
Gender: Male
Age: 23
Experience: 5 Years
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
