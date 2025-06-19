## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Telugu Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Telugu Male Data Attributes

Type: Speech and Text
Language(s): Telugu
Linguality: Monolingual
Catalogue Id: SYSPIN_TELUGU_M_NHC
Data Size (HH:MM:SS): 8 hours:19 mins:31 secs
Data Size (# Sentences): 3509
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
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

## Telugu Male Data Statistics

Total Audio Duration:    8 hours:19 mins:31 secs
Average Sample Duration: 8.541 secs
Total Sentences:         3509
Unique word Count:       23890
Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 0 hours:19 mins:32 secs |    120  | AGRICULTURE            |
| BOCU     | 1 hours:37 mins:51 secs |    597  | RUNNING TEXT FROM BOOK |
| BOOK     | 2 hours:59 mins:19 secs |    1328 | BOOKS                  |
| EDUC     | 0 hours:57 mins:44 secs |    350  | EDUCATION              |
| EVAL     | 0 hours:36 mins:24 secs |    400  | EVALUATION             |
| FINA     | 0 hours:28 mins:44 secs |    189  | FINANCE                |
| GENE     | 0 hours:18 mins:9 secs  |    114  | GENERAL                |
| HEAL     | 0 hours:5 mins:9 secs   |    35   | HEALTH                 |
| OTHE     | 0 hours:12 mins:20 secs |    88   | OTHERS                 |
| POLI     | 0 hours:25 mins:13 secs |    158  | POLITICS               |
| WEAT     | 0 hours:19 mins:1 secs  |    130  | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Telugu
Gender: Male
Age: 63
Experience: 25 Years
Languages known: Telugu, Kannada
Mother tongue: Telugu

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
