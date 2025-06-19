## SPICOR TTS CORPUS

As a part of the SPICOR project, studio-recorded English Male and Female TTS data is being released. Validated audio and text files are made available to the public. This will potentially open up opportunities for academic researchers, students, small and large-scale industries and research labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages included in the SPICOR project.

---

## File Structure

The corpus is organized into the following directory structure:

```
[Corpus_Root]/
└── [Speaker_1]/
      ├──[wavs]
      │    ├── [IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [...]
      │    └── [IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      ├── [IISc_SPICORProject_<languageTag>_<genderTag>_<speakerTag>_<qualityCheckTag>_Transcripts.json]
      └── [IISc_SPICORProject_<languageTag>_<genderTag>_<speakerTag>_<qualityCheckTag>_readme.txt]
```


## Transcription JSON Structure

```
├── MetaData (Project Information)
├── SpeakersMetaData (Speakers' Metadata)
└── Transcripts
        ├──[IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>]
        │             ├──Transcript
        │             └──Domain
        │
        ├──[IISc_SPICORProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>]
        │             ├──Transcript
        │             └──Domain
        │
        └──[...]
```


## Speakers' MetaData

#### English Male:

- Language: English
- Gender: Male
- Age: 44
- Experience: 6 Years
- Languages known: English, Hindi, Maithilli
- Mother tongue: Maithili

#### English Female:

- Language: English
- Gender: Female
- Age: 33
- Experience: 7 Years
- Languages known: English, Hindi, Kannada, Tamil
- Mother tongue: Tamil

---

## English Male (HC)

#### Data Attributes:

- Type: Speech and Text
- Language(s): English
- Linguality: Monolingual
- Catalogue Id: SPICOR_ENGLISH_M_HC
- Data Size (HH:MM:SS): 47 hours:52 mins:18 secs
- Data Size (# Sentences): 25159
- Data size (# Speakers): Male(1)
- Speaker Tag: Spk0001
- Domains: AGRI, ENTE, EVAL, FOOD, HEAL, LIBR, LJSP, OTHE, POLI, WEAT
- Annotation file availability: YES
- Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
- Validation status: Validated
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purpose/ areas: TTS

#### Data Statistics:

- Total Audio Duration:    47 hours:52 mins:18 secs
- Average Sample Duration: 6.85 secs
- Total Sentences:         25159
- Unique word Count:       50273

#### Distribution of Domains:

| Domain | Duration                 | Count | Domain Description |
| ------ | ------------------------ | ----- | ------------------ |
| AGRI   | 5 hours:18 mins:21 secs  | 2,393 | AGRICULTURE        |
| ENTE   | 10 hours:36 mins:15 secs | 4,713 | ENTERTAINMENT      |
| EVAL   | 0 hours:4 mins:55 secs   | 75    | EVALUATION         |
| FOOD   | 1 hours:19 mins:55 secs  | 615   | FOOD               |
| HEAL   | 5 hours:4 mins:32 secs   | 2,289 | HEALTH             |
| LIBR   | 3 hours:55 mins:42 secs  | 2,278 | LIBRI              |
| LJSP   | 9 hours:12 mins:21 secs  | 4,734 | LJSPEECH           |
| OTHE   | 3 hours:23 mins:14 secs  | 2,244 | OTHERS             |
| POLI   | 4 hours:44 mins:14 secs  | 2,163 | POLITICS           |
| WEAT   | 5 hours:25 mins:42 secs  | 2,553 | WEATHER            |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## English Female (HC)

#### Data Attributes:

- Type: Speech and Text
- Language(s): English
- Linguality: Monolingual
- Catalogue Id: SPICOR_ENGLISH_F_HC
- Data Size (HH:MM:SS): 49 hours:5 mins:16 secs
- Data Size (# Sentences): 24058
- Data size (# Speakers): Female(1)
- Speaker Tag: Spk0001
- Domains: AGRI, ENTE, EVAL, FOOD, HEAL, LIBR, LJSP, OTHE, POLI, WEAT
- Annotation file availability: YES
- Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
- Validation status: Validated
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purpose/ areas: TTS

#### Data Statistics:

- Total Audio Duration:    49 hours:5 mins:16 secs
- Average Sample Duration: 7.346 secs
- Total Sentences:         24058
- Unique word Count:       49448

#### Distribution of Domains:

| Domain | Duration                 | Count | Domain Description |
| ------ | ------------------------ | ----- | ------------------ |
| AGRI   | 5 hours:18 mins:21 secs  | 2,393 | AGRICULTURE        |
| ENTE   | 10 hours:36 mins:15 secs | 4,713 | ENTERTAINMENT      |
| EVAL   | 0 hours:4 mins:55 secs   | 75    | EVALUATION         |
| FOOD   | 1 hours:19 mins:55 secs  | 615   | FOOD               |
| HEAL   | 5 hours:4 mins:32 secs   | 2,289 | HEALTH             |
| LIBR   | 3 hours:55 mins:42 secs  | 2,278 | LIBRI              |
| LJSP   | 9 hours:12 mins:21 secs  | 4,734 | LJSPEECH           |
| OTHE   | 3 hours:23 mins:14 secs  | 2,244 | OTHERS             |
| POLI   | 4 hours:44 mins:14 secs  | 2,163 | POLITICS           |
| WEAT   | 5 hours:25 mins:42 secs  | 2,553 | WEATHER            |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## English Female (NHC)

#### Data Attributes:

- Type: Speech and Text
- Language(s): English
- Linguality: Monolingual
- Catalogue Id: SPICOR_ENGLISH_F_NHC
- Data Size (HH:MM:SS): 2 hours:20 mins:31 secs
- Data Size (# Sentences): 1178
- Data size (# Speakers): Female(1)
- Speaker Tag: Spk0001
- Domains: AGRI, ENTE, EVAL, FOOD, HEAL, LIBR, LJSP, OTHE, POLI, WEAT
- Annotation file availability: YES
- Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
- Validation status: Not Validated
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purpose/ areas: TTS

#### Data Statistics:

- Total Audio Duration:    2 hours:20 mins:31 secs
- Average Sample Duration: 7.163 secs
- Total Sentences:         1178
- Unique word Count:       7030

#### Distribution of Domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 0 hours:6 mins:58 secs  | 49    | AGRICULTURE        |
| ENTE   | 0 hours:25 mins:46 secs | 176   | ENTERTAINMENT      |
| EVAL   | 0 hours:31 mins:7 secs  | 325   | EVALUATION         |
| FOOD   | 0 hours:2 mins:34 secs  | 18    | FOOD               |
| HEAL   | 0 hours:16 mins:8 secs  | 111   | HEALTH             |
| LIBR   | 0 hours:3 mins:29 secs  | 39    | LIBRI              |
| LJSP   | 0 hours:31 mins:14 secs | 260   | LJSPEECH           |
| OTHE   | 0 hours:8 mins:29 secs  | 92    | OTHERS             |
| POLI   | 0 hours:8 mins:33 secs  | 59    | POLITICS           |
| WEAT   | 0 hours:6 mins:7 secs   | 48    | WEATHER            |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## English Male (NHC)

#### Data Attributes:

- Type: Speech and Text
- Language(s): English
- Linguality: Monolingual
- Catalogue Id: SPICOR_ENGLISH_M_NHC
- Data Size (HH:MM:SS): 0 hours:8 mins:3 secs
- Data Size (# Sentences): 77
- Data size (# Speakers): Male(1)
- Speaker Tag: Spk0001
- Domains: AGRI, ENTE, HEAL, LIBR, LJSP, OTHE, POLI, WEAT
- Annotation file availability: YES
- Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
- Validation status: Not Validated
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purpose/ areas: TTS

#### Data Statistics:

- Total Audio Duration:    0 hours:8 mins:3 secs
- Average Sample Duration: 6.368 secs
- Total Sentences:         77
- Unique word Count:       920

#### Distribution of Domains:

| Domain | Duration               | Count | Domain Description |
| ------ | ---------------------- | ----- | ------------------ |
| AGRI   | 0 hours:0 mins:9 secs  | 1     | AGRICULTURE        |
| ENTE   | 0 hours:1 mins:11 secs | 10    | ENTERTAINMENT      |
| HEAL   | 0 hours:0 mins:27 secs | 6     | HEALTH             |
| LIBR   | 0 hours:1 mins:24 secs | 10    | LIBRI              |
| LJSP   | 0 hours:0 mins:34 secs | 5     | LJSPEECH           |
| OTHE   | 0 hours:3 mins:11 secs | 35    | OTHERS             |
| POLI   | 0 hours:0 mins:30 secs | 4     | POLITICS           |
| WEAT   | 0 hours:0 mins:34 secs | 5     | WEATHER            |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Recording Setup

- Microphone: ZOOM H6
- Recording Environment: Professional studio
- Recording Conditions: Studio quality at ~40dB SNR

## Copyright and license

TTS data created under SPICOR project by Indian Institute of Science, Bengaluru is available
at ([https://spiredatasets.iisc.ac.in/spicortts10]()) and the copyright in the TTS data belongs to
Indian Institute of Science, Bengaluru and the said TTS data is released or distributed under
CC-BY-4.0 license ([https://creativecommons.org/licenses/by/4.0/legalcode.en]()). The user of
said TTS data is referred to the disclaimer of warranties section in the CC-BY-4.0 license
agreement.

## Acknowledgments

We extend our heartfelt gratitude to the talented voice artist whose contributions were
fundamental to this project's success.
We acknowledge the facility of IISc Studio in creating the TTS corpus.

## Citation

@misc{SPICOR TTS_1.0 Corpus,
     	Title = {SPICOR TTS_1.0 Corpus - A 97+ hour domain-rich Indian English TTS Corpus},
     	Authors = {Abhayjeet Et al.},
     	Year = {2025}
}

## Contact Information

SPIRE Lab, EE Dept., IISc, Bengaluru
Email: spirelab.ee@iisc.ac.in>
