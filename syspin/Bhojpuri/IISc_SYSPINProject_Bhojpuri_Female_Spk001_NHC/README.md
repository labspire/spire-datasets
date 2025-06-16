## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded Bhojpuri Female TTS data is being released.
Validated audio and text files are made available to the public. This will potentially open up
opportunities for academic researchers, students, small and large-scale industries and research
labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages
included in the SYSPIN project.

---

## Bhojpuri Female Data Attributes

Type: Speech and Text  
Language(s): Bhojpuri  
Linguality: Monolingual  
Catalogue Id: SYSPIN_BHOJPURI_F_NHC  
Data Size (HH:MM:SS): 11 hours:59 mins:11 secs  
Data Size (# Sentences): 6375  
Data size (# Speakers): Female(1)  
Speaker Tag: Spk0001  
Domains: AGRI, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH  
Annotation file availability: YES  
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel  
Validation status: Not Validated  
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

## Bhojpuri Female Data Statistics

Total Audio Duration:    11 hours:59 mins:11 secs  
Average Sample Duration: 6.769 secs  
Total Sentences:         6375  
Unique word Count:       18093  

Distribution of domains:
| Domain   | Duration                |   Count | Domain Description   |
|:---------|:------------------------|--------:|:---------------------|
| AGRI     | 1 hours:35 mins:43 secs |     818 | AGRICULTURE          |
| EVAL     | 0 hours:10 mins:57 secs |     103 | EVALUATION           |
| FINA     | 1 hours:11 mins:33 secs |     606 | FINANCE              |
| FOOD     | 1 hours:25 mins:53 secs |     691 | FOOD                 |
| HEAL     | 0 hours:27 mins:39 secs |     240 | HEALTH               |
| INDI     | 0 hours:59 mins:7 secs  |     506 | INDIA RELATED        |
| LOCA     | 0 hours:54 mins:58 secs |     570 | LOCAL CONVERSATION   |
| POLI     | 1 hours:15 mins:37 secs |     717 | POLITICS             |
| SOCI     | 1 hours:24 mins:57 secs |     785 | SOCIAL               |
| SPOR     | 1 hours:12 mins:20 secs |     649 | SPORTS               |
| TECH     | 1 hours:20 mins:22 secs |     690 | TECHNOLOGY           |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Speaker MetaData

Language: Bhojpuri  
Gender: Female  
Age: 35  
Experience: 12 Years  
Languages known: Bhojpuri, Hindi  
Mother tongue: Bhojpuri  

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
