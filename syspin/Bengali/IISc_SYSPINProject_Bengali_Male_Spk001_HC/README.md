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
Catalogue Id: SYSPIN_BENGALI_M_HC  
Data Size (HH:MM:SS): 54 hours:29 mins:52 secs  
Data Size (# Sentences): 25234  
Data size (# Speakers): Male(1)  
Speaker Tag: Spk0001  
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT  
Annotation file availability: YES  
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel  
Validation status: Validated  
Data creator: Indian Institute of Sciences (IISc), Bengaluru  
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

Total Audio Duration:    54 hours:29 mins:52 secs  
Average Sample Duration: 7.775 secs  
Total Sentences:         25234  
Unique word Count:       76564  

Distribution of domains:
| Domain   | Duration                 |   Count | Domain Description     |
|:---------|:-------------------------|--------:|:-----------------------|
| AGRI     | 5 hours:35 mins:0 secs   |   2239  | AGRICULTURE            |
| BOCU     | 4 hours:50 mins:19 secs  |   2287  | RUNNING TEXT FROM BOOK |
| BOOK     | 20 hours:10 mins:29 secs |   10315 | BOOKS                  |
| EDUC     | 3 hours:44 mins:43 secs  |   1480  | EDUCATION              |
| EVAL     | 0 hours:34 mins:48 secs  |   383   | EVALUATION             |
| FINA     | 4 hours:1 mins:49 secs   |   1753  | FINANCE                |
| GENE     | 3 hours:6 mins:10 secs   |   1315  | GENERAL                |
| HEAL     | 2 hours:50 mins:43 secs  |   1191  | HEALTH                 |
| OTHE     | 3 hours:6 mins:4 secs    |   1510  | OTHERS                 |
| POLI     | 3 hours:22 mins:23 secs  |   1400  | POLITICS               |
| WEAT     | 3 hours:7 mins:18 secs   |   1361  | WEATHER                |

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
