## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Bengali Male TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Bengali Male Data Attributes

Type: Speech and Text  
Language(s): Bengali  
Linguality: Monolingual  
Catalogue Id: SYSPIN_BENGALI_M_NHC  
Data Size (HH:MM:SS): 6 hours:17 mins:19 secs  
Data Size (# Sentences): 2623  
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
```
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
```

---

## Bengali Male Data Statistics

Total Audio Duration:    6 hours:17 mins:19 secs  
Average Sample Duration: 8.631 secs  
Total Sentences:         2623  
Unique word Count:       17806  

Distribution of domains:
| Domain   | Duration                |   Count | Domain Description     |
|:---------|:------------------------|--------:|:-----------------------|
| AGRI     | 0 hours:14 mins:11 secs |     90  | AGRICULTURE            |
| BOCU     | 1 hours:29 mins:28 secs |     591 | RUNNING TEXT FROM BOOK |
| BOOK     | 0 hours:41 mins:37 secs |     332 | BOOKS                  |
| EDUC     | 1 hours:45 mins:8 secs  |     710 | EDUCATION              |
| EVAL     | 0 hours:2 mins:1 secs   |     17  | EVALUATION             |
| FINA     | 1 hours:28 mins:12 secs |     623 | FINANCE                |
| GENE     | 0 hours:8 mins:3 secs   |     57  | GENERAL                |
| HEAL     | 0 hours:6 mins:2 secs   |     39  | HEALTH                 |
| OTHE     | 0 hours:6 mins:3 secs   |     52  | OTHERS                 |
| POLI     | 0 hours:6 mins:12 secs  |     39  | POLITICS               |
| WEAT     | 0 hours:10 mins:18 secs |     73  | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Bengali  
Gender: Male  
Age: 42  
Experience: 9 Years  
Languages known: Bengali, Hindi, English  
Mother tongue: Bengali  

---

## Recording Setup

Microphone: Neumann TLM-103  
Recording Environment: Professional studio  
Recording Conditions: Studio quality at ~40dB SNR  

---

## Transcription JSON Structure
```
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
```

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
Email: contact.syspin@iisc.ac.in

---
