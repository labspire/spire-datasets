## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Magahi Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Magahi Male Data Attributes

Type: Speech and Text
Language(s): Magahi
Linguality: Monolingual
Catalogue Id: SYSPIN_MAGAHI_M_HC
Data Size (HH:MM:SS): 54 hours:39 mins:48 secs
Data Size (# Sentences): 32529
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EVAL, FINA, FOOD, HEAL, INDI, POLI, SOCI, SPOR, TECH
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

## Magahi Male Data Statistics

Total Audio Duration:    54 hours:39 mins:48 secs
Average Sample Duration: 6.05 secs
Total Sentences:         32529
Unique word Count:       51443
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 4 hours:42 mins:53 secs |    2647 | AGRICULTURE            |
| BOCU     | 5 hours:5 mins:7 secs   |    3192 | RUNNING TEXT FROM BOOK |
| BOOK     | 6 hours:1 mins:30 secs  |    3263 | BOOKS                  |
| EVAL     | 0 hours:16 mins:52 secs |    188  | EVALUATION             |
| FINA     | 5 hours:14 mins:21 secs |    2900 | FINANCE                |
| FOOD     | 4 hours:44 mins:16 secs |    2945 | FOOD                   |
| HEAL     | 4 hours:30 mins:11 secs |    2961 | HEALTH                 |
| INDI     | 5 hours:30 mins:52 secs |    3211 | INDIA RELATED          |
| POLI     | 4 hours:16 mins:7 secs  |    2566 | POLITICS               |
| SOCI     | 5 hours:1 mins:30 secs  |    2868 | SOCIAL                 |
| SPOR     | 4 hours:43 mins:14 secs |    2860 | SPORTS                 |
| TECH     | 4 hours:32 mins:49 secs |    2928 | TECHNOLOGY             |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Magahi
Gender: Male
Age: 54
Experience: 5 years
Languages known: Magahi, Hindi, English
Mother tongue: Magahi

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
