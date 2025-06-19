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
Catalogue Id: SYSPIN_CHHATTISGARHI_F_NHC
Data Size (HH:MM:SS): 5 hours:47 mins:18 secs
Data Size (# Sentences): 2664
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EVAL, FINA, FOOD, GENE, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH, WEBS
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

## Chhattisgarhi Female Data Statistics

Total Audio Duration:    5 hours:47 mins:18 secs
Average Sample Duration: 7.822 secs
Total Sentences:         2664
Unique word Count:       13151
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 0 hours:22 mins:36 secs |     171 | AGRICULTURE            |
| BOCU     | 1 hours:22 mins:32 secs |     544 | RUNNING TEXT FROM BOOK |
| BOOK     | 0 hours:34 mins:51 secs |     281 | BOOKS                  |
| EVAL     | 0 hours:5 mins:5 secs   |     55  | EVALUATION             |
| FINA     | 0 hours:43 mins:51 secs |     329 | FINANCE                |
| FOOD     | 0 hours:15 mins:18 secs |     121 | FOOD                   |
| GENE     | 0 hours:17 mins:13 secs |     145 | GENERAL                |
| HEAL     | 0 hours:15 mins:58 secs |     137 | HEALTH                 |
| INDI     | 0 hours:17 mins:50 secs |     145 | INDIA RELATED          |
| LOCA     | 0 hours:13 mins:1 secs  |     97  | LOCAL CONVERSATION     |
| POLI     | 0 hours:13 mins:20 secs |     99  | POLITICS               |
| SOCI     | 0 hours:24 mins:55 secs |     206 | SOCIAL                 |
| SPOR     | 0 hours:6 mins:35 secs  |     62  | SPORTS                 |
| TECH     | 0 hours:10 mins:49 secs |     88  | TECHNOLOGY             |
| WEBS     | 0 hours:23 mins:18 secs |     184 | WEBSITE SCRAPED        |

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
