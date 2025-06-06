## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Magahi Female TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Magahi Female Data Attributes

Type: Speech and Text
Language(s): Magahi
Linguality: Monolingual
Catalogue Id: SYSPIN_MAGAHI_F_HC
Data Size (HH:MM:SS): 51 hours:25 mins:22 secs
Data Size (# Sentences): 30818
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EVAL, FINA, FOOD, HEAL, INDI, POLI, SOCI, SPOR, TECH
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

## Magahi Female Data Statistics

Total Audio Duration:    51 hours:25 mins:22 secs
Average Sample Duration: 6.007 secs
Total Sentences:         30818
Unique word Count:       49358
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 5 hours:9 mins:37 secs  |    2782 | AGRICULTURE            |
| BOCU     | 5 hours:14 mins:32 secs |    3296 | RUNNING TEXT FROM BOOK |
| BOOK     | 6 hours:0 mins:28 secs  |    3271 | BOOKS                  |
| EVAL     | 0 hours:27 mins:38 secs |    298  | EVALUATION             |
| FINA     | 4 hours:58 mins:26 secs |    2641 | FINANCE                |
| FOOD     | 4 hours:29 mins:55 secs |    2686 | FOOD                   |
| HEAL     | 4 hours:19 mins:11 secs |    2743 | HEALTH                 |
| INDI     | 4 hours:19 mins:11 secs |    2626 | INDIA RELATED          |
| POLI     | 4 hours:6 mins:46 secs  |    2535 | POLITICS               |
| SOCI     | 3 hours:36 mins:33 secs |    2181 | SOCIAL                 |
| SPOR     | 4 hours:24 mins:24 secs |    2874 | SPORTS                 |
| TECH     | 4 hours:18 mins:34 secs |    2885 | TECHNOLOGY             |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Magahi
Gender: Female
Age: 37
Experience: 6 yrs
Languages known: Magahi, Hindi
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
