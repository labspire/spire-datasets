## SYSPIN TTS CORPUS

As a part of the SYSPIN project, studio-recorded TTS data is being released for 9 Indian languages with 2 speakers each (Male and Female). Validated audio and text files are made available to the public. This will potentially open up opportunities for academic researchers, students, small and large-scale industries and research labs to innovate and develop algorithms and text-to-speech synthesizers in all the Indian languages included in the SYSPIN project.

---

## Directory Structure

The corpus is organized into the following directory structure:

```
[Corpus_Root]/
└── [Speaker_1]/
      ├──[wavs]
      │    ├── [IISc_SYSPINProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [IISc_SYSPINProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [IISc_SYSPINProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      │    ├── [...]
      │    └── [IISc_SYSPINProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>.wav]
      ├── [IISc_SYSPINProject_<languageTag>_<genderTag>_<speakerTag>_<qualityCheckTag>_Transcripts.json]
      └── [IISc_SYSPINProject_<languageTag>_<genderTag>_<speakerTag>_<qualityCheckTag>_readme.txt]
```

## Transcription JSON Structure

```
├── MetaData (Project Information)
├── SpeakersMetaData (Speakers' Metadata)
└── Transcripts
        ├──[IISc_SYSPINProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>]
        │             ├──Transcript
        │             └──Domain
        │
        ├──[IISc_SYSPINProject_<languageTag>_<genderTag>_<domainTag>_<uniqueID>]
        │             ├──Transcript
        │             └──Domain
        │
        └──[...]
```

## Speakers' MetaData

| Language       | Gender | Age | Experience | Mother Tongue | Languages Known                   |
|----------------|--------|-----|------------|----------------|------------------------------------|
| Bhojpuri       | Male   | 35  | 10 Years   | —              | Bhojpuri, Hindi                    |
| Bhojpuri       | Female | 35  | 12 Years   | Bhojpuri       | Bhojpuri, Hindi                    |
| Bengali        | Male   | 42  | 9 Years    | Bengali        | Bengali, Hindi, English           |
| Bengali        | Female | 27  | 10 Years   | Bengali        | Bengali, Hindi, English           |
| Chhattisgarhi  | Male   | 23  | 5 Years    | Chhattisgarhi  | Chhattisgarhi, Hindi              |
| Chhattisgarhi  | Female | 52  | 25 Years   | Chhattisgarhi  | Chhattisgarhi, Hindi              |
| Hindi          | Male   | 38  | 10 Years   | Hindi          | Hindi, English                    |
| Hindi          | Female | 42  | 21 Years   | Hindi          | Hindi, English, Tamil             |
| Kannada        | Male   | 39  | 13 Years   | Kannada        | Kannada, English                  |
| Kannada        | Female | 39  | 16 Years   | Kannada        | Kannada, English                  |
| Magahi         | Male   | 54  | 5 Years    | Magahi         | Magahi, Hindi, English            |
| Magahi         | Female | 37  | 6 Years    | Magahi         | Magahi, Hindi                     |
| Maithili       | Male   | 43  | 11 Years   | Maithili       | Maithili, Hindi                   |
| Maithili       | Female | 30  | 1 Year     | Maithili       | Maithili, Hindi                   |
| Marathi        | Male   | 52  | 5 Years    | Marathi        | Marathi, Hindi                    |
| Marathi        | Female | 37  | 2 Years    | Marathi        | Marathi, Hindi, English           |
| Telugu         | Male   | 63  | 25 Years   | Telugu         | Telugu, Kannada                   |
| Telugu         | Female | 37  | 1 Year     | Telugu         | Telugu, English                   |

#### Bhojpuri Male
Language: Bhojpuri
Gender: Male
Age: 35
Experience: 10 Years
Languages known: Bhojpuri, Hindi

#### Bhojpuri Female
Language: Bhojpuri
Gender: Female
Age: 35
Experience: 12 Years
Languages known: Bhojpuri, Hindi
Mother tongue: Bhojpuri

#### Bengali Male
Language: Bengali
Gender: Male
Age: 42
Experience: 9 Years
Languages known: Bengali, Hindi, English
Mother tongue: Bengali

#### Bengali Female
Language: Bengali
Gender: Female
Age: 27
Experience: 10 Years
Languages known: Bengali, Hindi, English
Mother tongue: Bengali

#### Chhattisgarhi Male
Language: Chhattisgarhi
Gender: Male
Age: 23
Experience: 5 Years
Languages known: Chhattisgarhi, Hindi
Mother tongue: Chhattisgarhi

#### Chhattisgarhi Female
Language: Chhattisgarhi
Gender: Female
Age: 52
Experience: 25 Years
Languages known: Chhattisgarhi, Hindi
Mother tongue: Chhattisgarhi

#### Hindi Male
Language: Hindi
Gender: Male
Age: 38
Experience: 10 Years
Languages known: Hindi, English
Mother tongue: Hindi

#### Hindi Female
Language: Hindi
Gender: Female
Age: 42
Experience: 21 Years
Languages known: Hindi, English, Tamil
Mother tongue: Hindi

#### Kannada Male
Language: Kannada
Gender: Male
Age: 39
Experience: 13 Years
Languages known: Kannada, English
Mother tongue: Kannada

#### Kannada Female
Language: Kannada
Gender: Female
Age: 39
Experience: 16 Years
Languages known: Kannada, English
Mother tongue: Kannada

#### Magahi Male
Language: Magahi
Gender: Male
Age: 54
Experience: 5 years
Languages known: Magahi, Hindi, English
Mother tongue: Magahi

#### Magahi Female
Language: Magahi
Gender: Female
Age: 37
Experience: 6 yrs
Languages known: Magahi, Hindi
Mother tongue: Magahi

#### Maithili Male
Language: Maithili
Gender: Male
Age: 43
Experience: 11 Years
Languages known: Maithili, Hindi
Mother tongue: Maithili

#### Maithili Female
Language: Maithili
Gender: Female
Age: 30
Experience: 1 Year
Languages known: Maithili, Hindi
Mother tongue: Maithili

#### Marathi Male
Language: Marathi
Gender: Male
Age: 52
Experience: 5 Years
Languages known: Marathi, Hindi
Mother tongue: Marathi

#### Marathi Female
Language: Marathi
Gender: Female
Age: 37
Experience: 2 Years
Languages known: Marathi, Hindi, English
Mother tongue: Marathi

#### Telugu Male
Language: Telugu
Gender: Male
Age: 63
Experience: 25 Years
Languages known: Telugu, Kannada
Mother tongue: Telugu

#### Telugu Female
Language: Telugu
Gender: Female
Age: 37
Experience: 1 Year
Languages known: Telugu, English
Mother tongue: Telugu

---

## Bhojpuri Male (HC)

#### Bhojpuri Male Data Attributes

- Type: Speech and Text
- Language(s): Bhojpuri
- Linguality: Monolingual
- Catalogue Id: SYSPIN_BHOJPURI_M_HC
- Data Size (HH:MM:SS): 47 hours:59 mins:1 secs
- Data Size (# Sentences): 26012
- Data size (# Speakers): Male(1)
- Speaker Tag: Spk0001
- Domains: AGRI, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
- Annotation file availability: YES
- Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
- Validation status: Validated
- Data creator: Indian Institute of Sciences (IISc), Bengaluru
- Year of publishing: 2024
- Suggested research purpose/ areas: TTS

#### Bhojpuri Male Data Statistics

Total Audio Duration:    47 hours:59 mins:1 secs
Average Sample Duration: 6.641 secs
Total Sentences:         26012
Unique word Count:       37958

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 5 hours:5 mins:48 secs  | 2859  | AGRICULTURE        |
| EVAL   | 0 hours:29 mins:10 secs | 299   | EVALUATION         |
| FINA   | 5 hours:16 mins:10 secs | 2854  | FINANCE            |
| FOOD   | 4 hours:54 mins:37 secs | 2569  | FOOD               |
| HEAL   | 5 hours:31 mins:18 secs | 2821  | HEALTH             |
| INDI   | 5 hours:4 mins:53 secs  | 2774  | INDIA RELATED      |
| LOCA   | 3 hours:2 mins:54 secs  | 1803  | LOCAL CONVERSATION |
| POLI   | 3 hours:11 mins:49 secs | 1749  | POLITICS           |
| SOCI   | 4 hours:37 mins:59 secs | 2383  | SOCIAL             |
| SPOR   | 5 hours:9 mins:59 secs  | 2995  | SPORTS             |
| TECH   | 5 hours:34 mins:20 secs | 2906  | TECHNOLOGY         |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Bhojpuri Male (NHC)

#### Bhojpuri Male Data Attributes

Type: Speech and Text
Language(s): Bhojpuri
Linguality: Monolingual
Catalogue Id: SYSPIN_BHOJPURI_M_NHC
Data Size (HH:MM:SS): 11 hours:38 mins:58 secs
Data Size (# Sentences): 6096
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Bhojpuri Male Data Statistics

Total Audio Duration:    11 hours:38 mins:58 secs
Average Sample Duration: 6.88 secs
Total Sentences:         6096
Unique word Count:       17700

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 1 hours:20 mins:13 secs | 648   | AGRICULTURE        |
| EVAL   | 0 hours:8 mins:49 secs  | 101   | EVALUATION         |
| FINA   | 1 hours:18 mins:33 secs | 675   | FINANCE            |
| FOOD   | 1 hours:34 mins:57 secs | 776   | FOOD               |
| HEAL   | 0 hours:57 mins:21 secs | 482   | HEALTH             |
| INDI   | 1 hours:7 mins:10 secs  | 584   | INDIA RELATED      |
| LOCA   | 1 hours:20 mins:47 secs | 768   | LOCAL CONVERSATION |
| POLI   | 0 hours:49 mins:6 secs  | 448   | POLITICS           |
| SOCI   | 1 hours:26 mins:14 secs | 737   | SOCIAL             |
| SPOR   | 0 hours:44 mins:36 secs | 418   | SPORTS             |
| TECH   | 0 hours:51 mins:7 secs  | 459   | TECHNOLOGY         |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Bhojpuri Female (HC)

#### Bhojpuri Female Data Attributes

Type: Speech and Text
Language(s): Bhojpuri
Linguality: Monolingual
Catalogue Id: SYSPIN_BHOJPURI_F_HC
Data Size (HH:MM:SS): 49 hours:3 mins:22 secs
Data Size (# Sentences): 27322
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Bhojpuri Female Data Statistics

Total Audio Duration:    49 hours:3 mins:22 secs
Average Sample Duration: 6.464 secs
Total Sentences:         27322
Unique word Count:       39484

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 5 hours:9 mins:12 secs  | 2687  | AGRICULTURE        |
| EVAL   | 0 hours:30 mins:7 secs  | 297   | EVALUATION         |
| FINA   | 4 hours:32 mins:47 secs | 2433  | FINANCE            |
| FOOD   | 4 hours:40 mins:48 secs | 2378  | FOOD               |
| HEAL   | 5 hours:17 mins:57 secs | 2894  | HEALTH             |
| INDI   | 5 hours:34 mins:26 secs | 3041  | INDIA RELATED      |
| LOCA   | 4 hours:32 mins:43 secs | 2909  | LOCAL CONVERSATION |
| POLI   | 4 hours:35 mins:49 secs | 2693  | POLITICS           |
| SOCI   | 4 hours:23 mins:56 secs | 2566  | SOCIAL             |
| SPOR   | 4 hours:46 mins:54 secs | 2789  | SPORTS             |
| TECH   | 4 hours:58 mins:39 secs | 2635  | TECHNOLOGY         |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Bhojpuri Female (NHC)

#### Bhojpuri Female Data Attributes

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

#### Bhojpuri Female Data Statistics

Total Audio Duration:    11 hours:59 mins:11 secs
Average Sample Duration: 6.769 secs
Total Sentences:         6375
Unique word Count:       18093

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 1 hours:35 mins:43 secs | 818   | AGRICULTURE        |
| EVAL   | 0 hours:10 mins:57 secs | 103   | EVALUATION         |
| FINA   | 1 hours:11 mins:33 secs | 606   | FINANCE            |
| FOOD   | 1 hours:25 mins:53 secs | 691   | FOOD               |
| HEAL   | 0 hours:27 mins:39 secs | 240   | HEALTH             |
| INDI   | 0 hours:59 mins:7 secs  | 506   | INDIA RELATED      |
| LOCA   | 0 hours:54 mins:58 secs | 570   | LOCAL CONVERSATION |
| POLI   | 1 hours:15 mins:37 secs | 717   | POLITICS           |
| SOCI   | 1 hours:24 mins:57 secs | 785   | SOCIAL             |
| SPOR   | 1 hours:12 mins:20 secs | 649   | SPORTS             |
| TECH   | 1 hours:20 mins:22 secs | 690   | TECHNOLOGY         |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Bengali Male (HC)

#### Bengali Male Data Attributes

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

#### Bengali Male Data Statistics

Total Audio Duration:    54 hours:29 mins:52 secs
Average Sample Duration: 7.775 secs
Total Sentences:         25234
Unique word Count:       76564

#### Distribution of domains:

| Domain | Duration                 | Count | Domain Description     |
| ------ | ------------------------ | ----- | ---------------------- |
| AGRI   | 5 hours:35 mins:0 secs   | 2239  | AGRICULTURE            |
| BOCU   | 4 hours:50 mins:19 secs  | 2287  | RUNNING TEXT FROM BOOK |
| BOOK   | 20 hours:10 mins:29 secs | 10315 | BOOKS                  |
| EDUC   | 3 hours:44 mins:43 secs  | 1480  | EDUCATION              |
| EVAL   | 0 hours:34 mins:48 secs  | 383   | EVALUATION             |
| FINA   | 4 hours:1 mins:49 secs   | 1753  | FINANCE                |
| GENE   | 3 hours:6 mins:10 secs   | 1315  | GENERAL                |
| HEAL   | 2 hours:50 mins:43 secs  | 1191  | HEALTH                 |
| OTHE   | 3 hours:6 mins:4 secs    | 1510  | OTHERS                 |
| POLI   | 3 hours:22 mins:23 secs  | 1400  | POLITICS               |
| WEAT   | 3 hours:7 mins:18 secs   | 1361  | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Bengali Male (NHC)

#### Bengali Male Data Attributes

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
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Bengali Male Data Statistics

Total Audio Duration:    6 hours:17 mins:19 secs
Average Sample Duration: 8.631 secs
Total Sentences:         2623
Unique word Count:       17806

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:14 mins:11 secs | 90    | AGRICULTURE            |
| BOCU   | 1 hours:29 mins:28 secs | 591   | RUNNING TEXT FROM BOOK |
| BOOK   | 0 hours:41 mins:37 secs | 332   | BOOKS                  |
| EDUC   | 1 hours:45 mins:8 secs  | 710   | EDUCATION              |
| EVAL   | 0 hours:2 mins:1 secs   | 17    | EVALUATION             |
| FINA   | 1 hours:28 mins:12 secs | 623   | FINANCE                |
| GENE   | 0 hours:8 mins:3 secs   | 57    | GENERAL                |
| HEAL   | 0 hours:6 mins:2 secs   | 39    | HEALTH                 |
| OTHE   | 0 hours:6 mins:3 secs   | 52    | OTHERS                 |
| POLI   | 0 hours:6 mins:12 secs  | 39    | POLITICS               |
| WEAT   | 0 hours:10 mins:18 secs | 73    | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Bengali Female (HC)

#### Bengali Female Data Attributes

Type: Speech and Text
Language(s): Bengali
Linguality: Monolingual
Catalogue Id: SYSPIN_BENGALI_F_HC
Data Size (HH:MM:SS): 50 hours:44 mins:39 secs
Data Size (# Sentences): 21152
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Bengali Female Data Statistics

Total Audio Duration:    50 hours:44 mins:39 secs
Average Sample Duration: 8.637 secs
Total Sentences:         21152
Unique word Count:       68952

#### Distribution of domains:

| Domain | Duration                 | Count | Domain Description     |
| ------ | ------------------------ | ----- | ---------------------- |
| AGRI   | 6 hours:1 mins:37 secs   | 2218  | AGRICULTURE            |
| BOCU   | 4 hours:21 mins:25 secs  | 1877  | RUNNING TEXT FROM BOOK |
| BOOK   | 15 hours:31 mins:17 secs | 7061  | BOOKS                  |
| EDUC   | 4 hours:50 mins:44 secs  | 1693  | EDUCATION              |
| EVAL   | 0 hours:33 mins:41 secs  | 329   | EVALUATION             |
| FINA   | 5 hours:26 mins:48 secs  | 2254  | FINANCE                |
| GENE   | 3 hours:17 mins:6 secs   | 1337  | GENERAL                |
| HEAL   | 2 hours:57 mins:41 secs  | 1174  | HEALTH                 |
| OTHE   | 2 hours:3 mins:12 secs   | 933   | OTHERS                 |
| POLI   | 3 hours:11 mins:8 secs   | 1249  | POLITICS               |
| WEAT   | 2 hours:29 mins:55 secs  | 1027  | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Bengali Female (NHC)

#### Bengali Female Data Attributes

Type: Speech and Text
Language(s): Bengali
Linguality: Monolingual
Catalogue Id: SYSPIN_BENGALI_F_NHC
Data Size (HH:MM:SS): 9 hours:29 mins:27 secs
Data Size (# Sentences): 3853
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Bengali Female Data Statistics

Total Audio Duration:    9 hours:29 mins:27 secs
Average Sample Duration: 8.868 secs
Total Sentences:         3853
Unique word Count:       22719

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:18 mins:59 secs | 110   | AGRICULTURE            |
| BOCU   | 1 hours:11 mins:23 secs | 443   | RUNNING TEXT FROM BOOK |
| BOOK   | 5 hours:29 mins:35 secs | 2334  | BOOKS                  |
| EDUC   | 1 hours:21 mins:10 secs | 503   | EDUCATION              |
| EVAL   | 0 hours:8 mins:22 secs  | 71    | EVALUATION             |
| FINA   | 0 hours:18 mins:34 secs | 123   | FINANCE                |
| GENE   | 0 hours:10 mins:31 secs | 69    | GENERAL                |
| HEAL   | 0 hours:11 mins:17 secs | 70    | HEALTH                 |
| OTHE   | 0 hours:5 mins:23 secs  | 37    | OTHERS                 |
| POLI   | 0 hours:7 mins:18 secs  | 48    | POLITICS               |
| WEAT   | 0 hours:6 mins:51 secs  | 45    | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Chhattisgarhi Male (HC)

#### Chhattisgarhi Male Data Attributes

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

#### Chhattisgarhi Male Data Statistics

Total Audio Duration:    49 hours:45 mins:25 secs
Average Sample Duration: 7.827 secs
Total Sentences:         22885
Unique word Count:       41161

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 3 hours:17 mins:13 secs | 1464  | AGRICULTURE            |
| BOCU   | 3 hours:41 mins:43 secs | 1458  | RUNNING TEXT FROM BOOK |
| BOOK   | 1 hours:28 mins:42 secs | 680   | BOOKS                  |
| EVAL   | 0 hours:36 mins:57 secs | 346   | EVALUATION             |
| FINA   | 2 hours:54 mins:44 secs | 1229  | FINANCE                |
| FOOD   | 4 hours:56 mins:20 secs | 2266  | FOOD                   |
| GENE   | 4 hours:25 mins:48 secs | 2098  | GENERAL                |
| HEAL   | 3 hours:47 mins:2 secs  | 1771  | HEALTH                 |
| INDI   | 5 hours:9 mins:20 secs  | 2476  | INDIA RELATED          |
| LOCA   | 5 hours:3 mins:48 secs  | 2205  | LOCAL CONVERSATION     |
| POLI   | 2 hours:17 mins:28 secs | 1087  | POLITICS               |
| SOCI   | 2 hours:25 mins:5 secs  | 1198  | SOCIAL                 |
| SPOR   | 2 hours:36 mins:59 secs | 1346  | SPORTS                 |
| TECH   | 3 hours:50 mins:59 secs | 1849  | TECHNOLOGY             |
| WEBS   | 3 hours:13 mins:10 secs | 1412  | WEBSITE SCRAPED        |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Chhattisgarhi Male (NHC)

#### Chhattisgarhi Male Data Attributes

Type: Speech and Text
Language(s): Chhattisgarhi
Linguality: Monolingual
Catalogue Id: SYSPIN_CHHATTISGARHI_M_NHC
Data Size (HH:MM:SS): 10 hours:58 mins:15 secs
Data Size (# Sentences): 4797
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EVAL, FINA, FOOD, GENE, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH, WEBS
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Chhattisgarhi Male Data Statistics

Total Audio Duration:    10 hours:58 mins:15 secs
Average Sample Duration: 8.233 secs
Total Sentences:         4797
Unique word Count:       17461

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:44 mins:11 secs | 316   | AGRICULTURE            |
| BOCU   | 1 hours:2 mins:10 secs  | 362   | RUNNING TEXT FROM BOOK |
| BOOK   | 0 hours:26 mins:37 secs | 191   | BOOKS                  |
| EVAL   | 0 hours:6 mins:19 secs  | 54    | EVALUATION             |
| FINA   | 0 hours:31 mins:46 secs | 219   | FINANCE                |
| FOOD   | 0 hours:36 mins:58 secs | 275   | FOOD                   |
| GENE   | 1 hours:25 mins:37 secs | 655   | GENERAL                |
| HEAL   | 0 hours:46 mins:55 secs | 348   | HEALTH                 |
| INDI   | 0 hours:50 mins:37 secs | 395   | INDIA RELATED          |
| LOCA   | 0 hours:50 mins:50 secs | 351   | LOCAL CONVERSATION     |
| POLI   | 0 hours:36 mins:13 secs | 286   | POLITICS               |
| SOCI   | 0 hours:34 mins:23 secs | 268   | SOCIAL                 |
| SPOR   | 0 hours:37 mins:43 secs | 306   | SPORTS                 |
| TECH   | 0 hours:41 mins:45 secs | 318   | TECHNOLOGY             |
| WEBS   | 1 hours:6 mins:3 secs   | 453   | WEBSITE SCRAPED        |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Chhattisgarhi Female (HC)

#### Chhattisgarhi Female Data Attributes

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

#### Chhattisgarhi Female Data Statistics

Total Audio Duration:    54 hours:48 mins:50 secs
Average Sample Duration: 7.151 secs
Total Sentences:         27595
Unique word Count:       50169

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 3 hours:23 mins:53 secs | 1612  | AGRICULTURE            |
| BOCU   | 4 hours:29 mins:40 secs | 2086  | RUNNING TEXT FROM BOOK |
| BOOK   | 3 hours:14 mins:11 secs | 1694  | BOOKS                  |
| EVAL   | 0 hours:33 mins:38 secs | 345   | EVALUATION             |
| FINA   | 2 hours:28 mins:9 secs  | 1121  | FINANCE                |
| FOOD   | 4 hours:55 mins:10 secs | 2451  | FOOD                   |
| GENE   | 4 hours:53 mins:44 secs | 2632  | GENERAL                |
| HEAL   | 3 hours:39 mins:5 secs  | 1981  | HEALTH                 |
| INDI   | 5 hours:21 mins:25 secs | 2733  | INDIA RELATED          |
| LOCA   | 5 hours:16 mins:33 secs | 2461  | LOCAL CONVERSATION     |
| POLI   | 2 hours:46 mins:47 secs | 1280  | POLITICS               |
| SOCI   | 3 hours:21 mins:40 secs | 1787  | SOCIAL                 |
| SPOR   | 2 hours:43 mins:37 secs | 1587  | SPORTS                 |
| TECH   | 4 hours:5 mins:56 secs  | 2077  | TECHNOLOGY             |
| WEBS   | 3 hours:35 mins:16 secs | 1748  | WEBSITE SCRAPED        |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Chhattisgarhi Female (NHC)

#### Chhattisgarhi Female Data Attributes

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
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Chhattisgarhi Female Data Statistics

Total Audio Duration:    5 hours:47 mins:18 secs
Average Sample Duration: 7.822 secs
Total Sentences:         2664
Unique word Count:       13151

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:22 mins:36 secs | 171   | AGRICULTURE            |
| BOCU   | 1 hours:22 mins:32 secs | 544   | RUNNING TEXT FROM BOOK |
| BOOK   | 0 hours:34 mins:51 secs | 281   | BOOKS                  |
| EVAL   | 0 hours:5 mins:5 secs   | 55    | EVALUATION             |
| FINA   | 0 hours:43 mins:51 secs | 329   | FINANCE                |
| FOOD   | 0 hours:15 mins:18 secs | 121   | FOOD                   |
| GENE   | 0 hours:17 mins:13 secs | 145   | GENERAL                |
| HEAL   | 0 hours:15 mins:58 secs | 137   | HEALTH                 |
| INDI   | 0 hours:17 mins:50 secs | 145   | INDIA RELATED          |
| LOCA   | 0 hours:13 mins:1 secs  | 97    | LOCAL CONVERSATION     |
| POLI   | 0 hours:13 mins:20 secs | 99    | POLITICS               |
| SOCI   | 0 hours:24 mins:55 secs | 206   | SOCIAL                 |
| SPOR   | 0 hours:6 mins:35 secs  | 62    | SPORTS                 |
| TECH   | 0 hours:10 mins:49 secs | 88    | TECHNOLOGY             |
| WEBS   | 0 hours:23 mins:18 secs | 184   | WEBSITE SCRAPED        |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Hindi Male (HC)

#### Hindi Male Data Attributes

Type: Speech and Text
Language(s): Hindi
Linguality: Monolingual
Catalogue Id: SYSPIN_HINDI_M_HC
Data Size (HH:MM:SS): 54 hours:57 mins:49 secs
Data Size (# Sentences): 24699
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCT, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Hindi Male Data Statistics

Total Audio Duration:    54 hours:57 mins:49 secs
Average Sample Duration: 8.011 secs
Total Sentences:         24699
Unique word Count:       55610

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 1 hours:29 mins:11 secs | 683   | AGRICULTURE            |
| BOCT   | 4 hours:32 mins:30 secs | 2200  | RUNNING TEXT FROM BOOK |
| BOOK   | 21 hours:7 mins:55 secs | 9567  | BOOKS                  |
| EDUC   | 4 hours:32 mins:46 secs | 1865  | EDUCATION              |
| EVAL   | 0 hours:38 mins:3 secs  | 351   | EVALUATION             |
| FINA   | 1 hours:16 mins:53 secs | 592   | FINANCE                |
| GENE   | 6 hours:26 mins:14 secs | 2959  | GENERAL                |
| HEAL   | 1 hours:58 mins:25 secs | 886   | HEALTH                 |
| OTHE   | 8 hours:2 mins:29 secs  | 3505  | OTHERS                 |
| POLI   | 2 hours:59 mins:38 secs | 1255  | POLITICS               |
| WEAT   | 1 hours:53 mins:40 secs | 836   | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Hindi Male (NHC)

#### Hindi Male Data Attributes

Type: Speech and Text
Language(s): Hindi
Linguality: Monolingual
Catalogue Id: SYSPIN_HINDI_M_NHC
Data Size (HH:MM:SS): 4 hours:7 mins:49 secs
Data Size (# Sentences): 1777
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCT, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Hindi Male Data Statistics

Total Audio Duration:    4 hours:7 mins:49 secs
Average Sample Duration: 8.368 secs
Total Sentences:         1777
Unique word Count:       9596

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:35 mins:38 secs | 261   | AGRICULTURE            |
| BOCT   | 0 hours:11 mins:41 secs | 87    | RUNNING TEXT FROM BOOK |
| BOOK   | 0 hours:25 mins:37 secs | 181   | BOOKS                  |
| EDUC   | 1 hours:11 mins:12 secs | 466   | EDUCATION              |
| EVAL   | 0 hours:5 mins:45 secs  | 49    | EVALUATION             |
| FINA   | 0 hours:47 mins:25 secs | 362   | FINANCE                |
| GENE   | 0 hours:4 mins:6 secs   | 34    | GENERAL                |
| HEAL   | 0 hours:24 mins:35 secs | 181   | HEALTH                 |
| OTHE   | 0 hours:9 mins:41 secs  | 71    | OTHERS                 |
| POLI   | 0 hours:6 mins:10 secs  | 44    | POLITICS               |
| WEAT   | 0 hours:5 mins:54 secs  | 41    | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Hindi Female (HC)

#### Hindi Female Data Attributes

Type: Speech and Text
Language(s): Hindi
Linguality: Monolingual
Catalogue Id: SYSPIN_HINDI_F_HC
Data Size (HH:MM:SS): 54 hours:54 mins:44 secs
Data Size (# Sentences): 22058
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Hindi Female Data Statistics

Total Audio Duration:    54 hours:54 mins:44 secs
Average Sample Duration: 8.962 secs
Total Sentences:         22058
Unique word Count:       47328

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 1 hours:48 mins:18 secs | 848   | AGRICULTURE        |
| BOOK   | 23 hours:3 mins:20 secs | 8358  | BOOKS              |
| EDUC   | 5 hours:4 mins:10 secs  | 2060  | EDUCATION          |
| EVAL   | 0 hours:40 mins:38 secs | 396   | EVALUATION         |
| FINA   | 1 hours:46 mins:45 secs | 832   | FINANCE            |
| GENE   | 6 hours:0 mins:43 secs  | 2540  | GENERAL            |
| HEAL   | 1 hours:48 mins:31 secs | 835   | HEALTH             |
| OTHE   | 7 hours:21 mins:25 secs | 3081  | OTHERS             |
| POLI   | 2 hours:57 mins:51 secs | 1235  | POLITICS           |
| WEAT   | 4 hours:22 mins:58 secs | 1873  | WEATHER            |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Hindi Female (NHC)

#### Hindi Female Data Attributes

Type: Speech and Text
Language(s): Hindi
Linguality: Monolingual
Catalogue Id: SYSPIN_HINDI_F_NHC
Data Size (HH:MM:SS): 5 hours:17 mins:11 secs
Data Size (# Sentences): 2063
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Hindi Female Data Statistics

Total Audio Duration:    5 hours:17 mins:11 secs
Average Sample Duration: 9.225 secs
Total Sentences:         2063
Unique word Count:       12453

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 0 hours:12 mins:47 secs | 92    | AGRICULTURE        |
| BOOK   | 1 hours:12 mins:40 secs | 413   | BOOKS              |
| EDUC   | 0 hours:41 mins:2 secs  | 260   | EDUCATION          |
| EVAL   | 0 hours:0 mins:29 secs  | 4     | EVALUATION         |
| FINA   | 0 hours:15 mins:59 secs | 119   | FINANCE            |
| GENE   | 1 hours:7 mins:26 secs  | 454   | GENERAL            |
| HEAL   | 0 hours:16 mins:23 secs | 123   | HEALTH             |
| OTHE   | 1 hours:13 mins:35 secs | 489   | OTHERS             |
| POLI   | 0 hours:9 mins:17 secs  | 61    | POLITICS           |
| WEAT   | 0 hours:7 mins:29 secs  | 48    | WEATHER            |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Kannada Male (HC)

#### Kannada Male Data Attributes

Type: Speech and Text
Language(s): Kannada
Linguality: Monolingual
Catalogue Id: SYSPIN_KANNADA_M_HC
Data Size (HH:MM:SS): 49 hours:19 mins:17 secs
Data Size (# Sentences): 20694
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Kannada Male Data Statistics

Total Audio Duration:    49 hours:19 mins:17 secs
Average Sample Duration: 8.58 secs
Total Sentences:         20694
Unique word Count:       85485

#### Distribution of domains:

| Domain | Duration                 | Count | Domain Description     |
| ------ | ------------------------ | ----- | ---------------------- |
| AGRI   | 3 hours:6 mins:58 secs   | 1093  | AGRICULTURE            |
| BOCU   | 3 hours:26 mins:55 secs  | 1283  | RUNNING TEXT FROM BOOK |
| BOOK   | 18 hours:23 mins:49 secs | 8834  | BOOKS                  |
| EDUC   | 3 hours:14 mins:48 secs  | 1130  | EDUCATION              |
| EVAL   | 0 hours:29 mins:42 secs  | 320   | EVALUATION             |
| FINA   | 3 hours:47 mins:59 secs  | 1500  | FINANCE                |
| GENE   | 4 hours:4 mins:57 secs   | 1574  | GENERAL                |
| HEAL   | 4 hours:0 mins:13 secs   | 1556  | HEALTH                 |
| OTHE   | 2 hours:39 mins:49 secs  | 1073  | OTHERS                 |
| POLI   | 2 hours:35 mins:52 secs  | 969   | POLITICS               |
| WEAT   | 3 hours:28 mins:9 secs   | 1362  | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Kannada Male (NHC)

#### Kannada Male Data Attributes

Type: Speech and Text
Language(s): Kannada
Linguality: Monolingual
Catalogue Id: SYSPIN_KANNADA_M_NHC
Data Size (HH:MM:SS): 9 hours:14 mins:45 secs
Data Size (# Sentences): 3453
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Kannada Male Data Statistics

Total Audio Duration:    9 hours:14 mins:45 secs
Average Sample Duration: 9.639 secs
Total Sentences:         3453
Unique word Count:       23925

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:26 mins:39 secs | 145   | AGRICULTURE            |
| BOCU   | 2 hours:16 mins:15 secs | 740   | RUNNING TEXT FROM BOOK |
| BOOK   | 3 hours:18 mins:2 secs  | 1376  | BOOKS                  |
| EDUC   | 0 hours:16 mins:11 secs | 93    | EDUCATION              |
| EVAL   | 0 hours:11 mins:14 secs | 80    | EVALUATION             |
| FINA   | 0 hours:28 mins:48 secs | 173   | FINANCE                |
| GENE   | 0 hours:29 mins:6 secs  | 179   | GENERAL                |
| HEAL   | 0 hours:18 mins:55 secs | 116   | HEALTH                 |
| OTHE   | 0 hours:28 mins:44 secs | 185   | OTHERS                 |
| POLI   | 0 hours:23 mins:29 secs | 131   | POLITICS               |
| WEAT   | 0 hours:37 mins:17 secs | 235   | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Kannada Female (HC)

#### Kannada Female Data Attributes

Type: Speech and Text
Language(s): Kannada
Linguality: Monolingual
Catalogue Id: SYSPIN_KANNADA_F_HC
Data Size (HH:MM:SS): 52 hours:21 mins:46 secs
Data Size (# Sentences): 17203
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCO, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Kannada Female Data Statistics

Total Audio Duration:    52 hours:21 mins:46 secs
Average Sample Duration: 10.958 secs
Total Sentences:         17203
Unique word Count:       75942

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 3 hours:13 mins:43 secs | 1057  | AGRICULTURE            |
| BOCO   | 2 hours:49 mins:0 secs  | 770   | RUNNING TEXT FROM BOOK |
| BOOK   | 17 hours:16 mins:2 secs | 6064  | BOOKS                  |
| EDUC   | 3 hours:21 mins:4 secs  | 1113  | EDUCATION              |
| EVAL   | 0 hours:49 mins:15 secs | 342   | EVALUATION             |
| FINA   | 4 hours:32 mins:29 secs | 1472  | FINANCE                |
| GENE   | 4 hours:56 mins:17 secs | 1522  | GENERAL                |
| HEAL   | 4 hours:35 mins:58 secs | 1447  | HEALTH                 |
| OTHE   | 3 hours:26 mins:33 secs | 1095  | OTHERS                 |
| POLI   | 2 hours:59 mins:31 secs | 928   | POLITICS               |
| WEAT   | 4 hours:21 mins:48 secs | 1393  | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Kannada Female (NHC)

#### Kannada Female Data Attributes

Type: Speech and Text
Language(s): Kannada
Linguality: Monolingual
Catalogue Id: SYSPIN_KANNADA_F_NHC
Data Size (HH:MM:SS): 9 hours:10 mins:33 secs
Data Size (# Sentences): 2740
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCO, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Kannada Female Data Statistics

Total Audio Duration:    9 hours:10 mins:33 secs
Average Sample Duration: 12.056 secs
Total Sentences:         2741
Unique word Count:       20492

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:32 mins:16 secs | 178   | AGRICULTURE            |
| BOCO   | 1 hours:17 mins:55 secs | 302   | RUNNING TEXT FROM BOOK |
| BOOK   | 2 hours:47 mins:49 secs | 870   | BOOKS                  |
| EDUC   | 0 hours:19 mins:34 secs | 110   | EDUCATION              |
| EVAL   | 0 hours:9 mins:47 secs  | 58    | EVALUATION             |
| FINA   | 0 hours:39 mins:6 secs  | 199   | FINANCE                |
| GENE   | 0 hours:46 mins:15 secs | 230   | GENERAL                |
| HEAL   | 0 hours:43 mins:26 secs | 223   | HEALTH                 |
| OTHE   | 0 hours:39 mins:18 secs | 196   | OTHERS                 |
| POLI   | 0 hours:36 mins:9 secs  | 172   | POLITICS               |
| WEAT   | 0 hours:38 mins:53 secs | 202   | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Magahi Male (HC)

#### Magahi Male Data Attributes

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
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Magahi Male Data Statistics

Total Audio Duration:    54 hours:39 mins:48 secs
Average Sample Duration: 6.05 secs
Total Sentences:         32529
Unique word Count:       51443

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 4 hours:42 mins:53 secs | 2647  | AGRICULTURE            |
| BOCU   | 5 hours:5 mins:7 secs   | 3192  | RUNNING TEXT FROM BOOK |
| BOOK   | 6 hours:1 mins:30 secs  | 3263  | BOOKS                  |
| EVAL   | 0 hours:16 mins:52 secs | 188   | EVALUATION             |
| FINA   | 5 hours:14 mins:21 secs | 2900  | FINANCE                |
| FOOD   | 4 hours:44 mins:16 secs | 2945  | FOOD                   |
| HEAL   | 4 hours:30 mins:11 secs | 2961  | HEALTH                 |
| INDI   | 5 hours:30 mins:52 secs | 3211  | INDIA RELATED          |
| POLI   | 4 hours:16 mins:7 secs  | 2566  | POLITICS               |
| SOCI   | 5 hours:1 mins:30 secs  | 2868  | SOCIAL                 |
| SPOR   | 4 hours:43 mins:14 secs | 2860  | SPORTS                 |
| TECH   | 4 hours:32 mins:49 secs | 2928  | TECHNOLOGY             |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Magahi Male (NHC)

#### Magahi Male Data Attributes

Type: Speech and Text
Language(s): Magahi
Linguality: Monolingual
Catalogue Id: SYSPIN_MAGAHI_M_NHC
Data Size (HH:MM:SS): 6 hours:6 mins:36 secs
Data Size (# Sentences): 3436
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EVAL, FINA, FOOD, HEAL, INDI, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Magahi Male Data Statistics

Total Audio Duration:    6 hours:6 mins:36 secs
Average Sample Duration: 6.402 secs
Total Sentences:         3436
Unique word Count:       12945

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:19 mins:32 secs | 120   | AGRICULTURE            |
| BOCU   | 1 hours:37 mins:51 secs | 597   | RUNNING TEXT FROM BOOK |
| BOOK   | 2 hours:59 mins:19 secs | 1328  | BOOKS                  |
| EDUC   | 0 hours:57 mins:44 secs | 350   | EDUCATION              |
| EVAL   | 0 hours:36 mins:24 secs | 400   | EVALUATION             |
| FINA   | 0 hours:28 mins:44 secs | 189   | FINANCE                |
| GENE   | 0 hours:18 mins:9 secs  | 114   | GENERAL                |
| HEAL   | 0 hours:5 mins:9 secs   | 35    | HEALTH                 |
| OTHE   | 0 hours:12 mins:20 secs | 88    | OTHERS                 |
| POLI   | 0 hours:25 mins:13 secs | 158   | POLITICS               |
| WEAT   | 0 hours:19 mins:1 secs  | 130   | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong tovarious domain specific sentences, conversational sentences and erroneous sentences.

---

## Magahi Female (HC)

#### Magahi Female Data Attributes

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

#### Magahi Female Data Statistics

Total Audio Duration:    51 hours:25 mins:22 secs
Average Sample Duration: 6.007 secs
Total Sentences:         30818
Unique word Count:       49358

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 5 hours:9 mins:37 secs  | 2782  | AGRICULTURE            |
| BOCU   | 5 hours:14 mins:32 secs | 3296  | RUNNING TEXT FROM BOOK |
| BOOK   | 6 hours:0 mins:28 secs  | 3271  | BOOKS                  |
| EVAL   | 0 hours:27 mins:38 secs | 298   | EVALUATION             |
| FINA   | 4 hours:58 mins:26 secs | 2641  | FINANCE                |
| FOOD   | 4 hours:29 mins:55 secs | 2686  | FOOD                   |
| HEAL   | 4 hours:19 mins:11 secs | 2743  | HEALTH                 |
| INDI   | 4 hours:19 mins:11 secs | 2626  | INDIA RELATED          |
| POLI   | 4 hours:6 mins:46 secs  | 2535  | POLITICS               |
| SOCI   | 3 hours:36 mins:33 secs | 2181  | SOCIAL                 |
| SPOR   | 4 hours:24 mins:24 secs | 2874  | SPORTS                 |
| TECH   | 4 hours:18 mins:34 secs | 2885  | TECHNOLOGY             |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Magahi Female (NHC)

#### Magahi Female Data Attributes

Type: Speech and Text
Language(s): Magahi
Linguality: Monolingual
Catalogue Id: SYSPIN_MAGAHI_F_NHC
Data Size (HH:MM:SS): 10 hours:7 mins:30 secs
Data Size (# Sentences): 5755
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EVAL, FINA, FOOD, HEAL, INDI, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Magahi Female Data Statistics

Total Audio Duration:    10 hours:7 mins:30 secs
Average Sample Duration: 6.334 secs
Total Sentences:         5755
Unique word Count:       18925

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:57 mins:55 secs | 524   | AGRICULTURE            |
| BOCU   | 0 hours:33 mins:23 secs | 306   | RUNNING TEXT FROM BOOK |
| BOOK   | 1 hours:46 mins:49 secs | 856   | BOOKS                  |
| EVAL   | 0 hours:9 mins:23 secs  | 102   | EVALUATION             |
| FINA   | 0 hours:48 mins:55 secs | 437   | FINANCE                |
| FOOD   | 0 hours:30 mins:7 secs  | 306   | FOOD                   |
| HEAL   | 0 hours:27 mins:6 secs  | 287   | HEALTH                 |
| INDI   | 1 hours:24 mins:39 secs | 806   | INDIA RELATED          |
| POLI   | 0 hours:49 mins:24 secs | 492   | POLITICS               |
| SOCI   | 1 hours:38 mins:36 secs | 977   | SOCIAL                 |
| SPOR   | 0 hours:33 mins:24 secs | 354   | SPORTS                 |
| TECH   | 0 hours:27 mins:43 secs | 308   | TECHNOLOGY             |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Maithili Male (HC)

#### Maithili Male Data Attributes

Type: Speech and Text
Language(s): Maithili
Linguality: Monolingual
Catalogue Id: SYSPIN_MAITHILI_M_HC
Data Size (HH:MM:SS): 55 hours:50 mins:19 secs
Data Size (# Sentences): 32156
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Maithili Male Data Statistics

Total Audio Duration:    55 hours:50 mins:19 secs
Average Sample Duration: 6.251 secs
Total Sentences:         32156
Unique word Count:       72581

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 4 hours:22 mins:12 secs | 2495  | AGRICULTURE        |
| BOOK   | 13 hours:8 mins:27 secs | 8479  | BOOKS              |
| EVAL   | 0 hours:33 mins:13 secs | 400   | EVALUATION         |
| FINA   | 3 hours:44 mins:51 secs | 2292  | FINANCE            |
| FOOD   | 4 hours:12 mins:49 secs | 2165  | FOOD               |
| HEAL   | 4 hours:27 mins:21 secs | 2331  | HEALTH             |
| INDI   | 4 hours:35 mins:24 secs | 2604  | INDIA RELATED      |
| LOCA   | 5 hours:52 mins:47 secs | 3236  | LOCAL CONVERSATION |
| POLI   | 4 hours:12 mins:10 secs | 2364  | POLITICS           |
| SOCI   | 4 hours:43 mins:26 secs | 2533  | SOCIAL             |
| SPOR   | 3 hours:45 mins:49 secs | 2139  | SPORTS             |
| TECH   | 2 hours:11 mins:46 secs | 1118  | TECHNOLOGY         |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Maithili Male (NHC)

#### Maithili Male Data Attributes

Type: Speech and Text
Language(s): Maithili
Linguality: Monolingual
Catalogue Id: SYSPIN_MAITHILI_M_NHC
Data Size (HH:MM:SS): 3 hours:27 mins:47 secs
Data Size (# Sentences): 2060
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Maithili Male Data Statistics

Total Audio Duration:    3 hours:27 mins:47 secs
Average Sample Duration: 6.052 secs
Total Sentences:         2060
Unique word Count:       11397

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 0 hours:11 mins:16 secs | 107   | AGRICULTURE        |
| BOOK   | 1 hours:29 mins:10 secs | 997   | BOOKS              |
| FINA   | 0 hours:15 mins:7 secs  | 148   | FINANCE            |
| FOOD   | 0 hours:17 mins:20 secs | 147   | FOOD               |
| HEAL   | 0 hours:19 mins:15 secs | 163   | HEALTH             |
| INDI   | 0 hours:12 mins:49 secs | 114   | INDIA RELATED      |
| LOCA   | 0 hours:12 mins:49 secs | 120   | LOCAL CONVERSATION |
| POLI   | 0 hours:1 mins:47 secs  | 16    | POLITICS           |
| SOCI   | 0 hours:16 mins:46 secs | 150   | SOCIAL             |
| SPOR   | 0 hours:8 mins:10 secs  | 71    | SPORTS             |
| TECH   | 0 hours:3 mins:13 secs  | 27    | TECHNOLOGY         |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Maithili Female (HC)

#### Maithili Female Data Attributes

Type: Speech and Text
Language(s): Maithili
Linguality: Monolingual
Catalogue Id: SYSPIN_MAITHILI_F_HC
Data Size (HH:MM:SS): 59 hours:40 mins:32 secs
Data Size (# Sentences): 34412
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Maithili Female Data Statistics

Total Audio Duration:    59 hours:40 mins:32 secs
Average Sample Duration: 6.243 secs
Total Sentences:         34412
Unique word Count:       73522

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 4 hours:20 mins:27 secs | 2584  | AGRICULTURE        |
| BOOK   | 13 hours:7 mins:17 secs | 7867  | BOOKS              |
| EVAL   | 0 hours:34 mins:52 secs | 392   | EVALUATION         |
| FINA   | 4 hours:16 mins:21 secs | 2409  | FINANCE            |
| FOOD   | 5 hours:4 mins:26 secs  | 2611  | FOOD               |
| HEAL   | 4 hours:46 mins:7 secs  | 2683  | HEALTH             |
| INDI   | 4 hours:40 mins:33 secs | 2718  | INDIA RELATED      |
| LOCA   | 5 hours:3 mins:48 secs  | 2793  | LOCAL CONVERSATION |
| POLI   | 4 hours:28 mins:28 secs | 2672  | POLITICS           |
| SOCI   | 4 hours:56 mins:22 secs | 2830  | SOCIAL             |
| SPOR   | 4 hours:24 mins:20 secs | 2765  | SPORTS             |
| TECH   | 3 hours:57 mins:26 secs | 2088  | TECHNOLOGY         |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Maithili Female (NHC)

#### Maithili Female Data Attributes

Type: Speech and Text
Language(s): Maithili
Linguality: Monolingual
Catalogue Id: SYSPIN_MAITHILI_F_NHC
Data Size (HH:MM:SS): 0 hours:54 mins:9 secs
Data Size (# Sentences): 532
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EVAL, FINA, FOOD, HEAL, INDI, LOCA, POLI, SOCI, SPOR, TECH
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Maithili Female Data Statistics

Total Audio Duration:    0 hours:54 mins:9 secs
Average Sample Duration: 6.108 secs
Total Sentences:         532
Unique word Count:       3523

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 0 hours:1 mins:15 secs  | 12    | AGRICULTURE        |
| BOOK   | 0 hours:13 mins:47 secs | 160   | BOOKS              |
| EVAL   | 0 hours:0 mins:43 secs  | 8     | EVALUATION         |
| FINA   | 0 hours:2 mins:45 secs  | 24    | FINANCE            |
| FOOD   | 0 hours:2 mins:40 secs  | 25    | FOOD               |
| HEAL   | 0 hours:6 mins:30 secs  | 62    | HEALTH             |
| INDI   | 0 hours:1 mins:10 secs  | 11    | INDIA RELATED      |
| LOCA   | 0 hours:0 mins:35 secs  | 5     | LOCAL CONVERSATION |
| POLI   | 0 hours:0 mins:14 secs  | 2     | POLITICS           |
| SOCI   | 0 hours:10 mins:34 secs | 105   | SOCIAL             |
| SPOR   | 0 hours:0 mins:13 secs  | 2     | SPORTS             |
| TECH   | 0 hours:13 mins:37 secs | 116   | TECHNOLOGY         |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Marathi Male (HC)

#### Marathi Male Data Attributes

Type: Speech and Text
Language(s): Marathi
Linguality: Monolingual
Catalogue Id: SYSPIN_MARATHI_M_HC
Data Size (HH:MM:SS): 48 hours:38 mins:20 secs
Data Size (# Sentences): 20763
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Marathi Male Data Statistics

Total Audio Duration:    48 hours:38 mins:20 secs
Average Sample Duration: 8.433 secs
Total Sentences:         20763
Unique word Count:       69867

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 3 hours:7 mins:20 secs  | 1431  | AGRICULTURE            |
| BOCU   | 6 hours:12 mins:36 secs | 2399  | RUNNING TEXT FROM BOOK |
| BOOK   | 21 hours:8 mins:43 secs | 9203  | BOOKS                  |
| EDUC   | 2 hours:37 mins:48 secs | 1066  | EDUCATION              |
| EVAL   | 0 hours:32 mins:53 secs | 327   | EVALUATION             |
| FINA   | 2 hours:35 mins:37 secs | 1111  | FINANCE                |
| GENE   | 2 hours:35 mins:43 secs | 1029  | GENERAL                |
| HEAL   | 3 hours:40 mins:35 secs | 1617  | HEALTH                 |
| OTHE   | 1 hours:40 mins:49 secs | 736   | OTHERS                 |
| POLI   | 2 hours:18 mins:31 secs | 915   | POLITICS               |
| WEAT   | 2 hours:7 mins:41 secs  | 929   | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Marathi Male (NHC)

#### Marathi Male Data Attributes

Type: Speech and Text
Language(s): Marathi
Linguality: Monolingual
Catalogue Id: SYSPIN_MARATHI_M_NHC
Data Size (HH:MM:SS): 13 hours:8 mins:25 secs
Data Size (# Sentences): 5202
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Marathi Male Data Statistics

Total Audio Duration:    13 hours:8 mins:25 secs
Average Sample Duration: 9.094 secs
Total Sentences:         5202
Unique word Count:       30316

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 1 hours:6 mins:13 secs  | 450   | AGRICULTURE            |
| BOCU   | 0 hours:41 mins:18 secs | 219   | RUNNING TEXT FROM BOOK |
| BOOK   | 3 hours:36 mins:26 secs | 1403  | BOOKS                  |
| EDUC   | 0 hours:59 mins:8 secs  | 389   | EDUCATION              |
| EVAL   | 0 hours:10 mins:59 secs | 73    | EVALUATION             |
| FINA   | 0 hours:48 mins:29 secs | 321   | FINANCE                |
| GENE   | 1 hours:8 mins:26 secs  | 419   | GENERAL                |
| HEAL   | 1 hours:30 mins:26 secs | 637   | HEALTH                 |
| OTHE   | 1 hours:15 mins:33 secs | 545   | OTHERS                 |
| POLI   | 0 hours:54 mins:46 secs | 354   | POLITICS               |
| WEAT   | 0 hours:56 mins:34 secs | 392   | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Marathi Female (HC)

#### Marathi Female Data Attributes

Type: Speech and Text
Language(s): Marathi
Linguality: Monolingual
Catalogue Id: SYSPIN_MARATHI_F_HC
Data Size (HH:MM:SS): 51 hours:3 mins:32 secs
Data Size (# Sentences): 21790
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Marathi Female Data Statistics

Total Audio Duration:    51 hours:3 mins:32 secs
Average Sample Duration: 8.436 secs
Total Sentences:         21790
Unique word Count:       73547

#### Distribution of domains:

| Domain | Duration                 | Count | Domain Description |
| ------ | ------------------------ | ----- | ------------------ |
| AGRI   | 5 hours:30 mins:37 secs  | 2384  | AGRICULTURE        |
| BOOK   | 10 hours:37 mins:48 secs | 4890  | BOOKS              |
| EDUC   | 3 hours:53 mins:41 secs  | 1475  | EDUCATION          |
| EVAL   | 0 hours:30 mins:45 secs  | 340   | EVALUATION         |
| FINA   | 5 hours:2 mins:22 secs   | 2092  | FINANCE            |
| GENE   | 4 hours:38 mins:34 secs  | 1818  | GENERAL            |
| HEAL   | 5 hours:21 mins:54 secs  | 2291  | HEALTH             |
| OTHE   | 4 hours:51 mins:17 secs  | 2090  | OTHERS             |
| POLI   | 4 hours:6 mins:15 secs   | 1644  | POLITICS           |
| WEAT   | 6 hours:30 mins:14 secs  | 2766  | WEATHER            |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Marathi Female (NHC)

#### Marathi Female Data Attributes

Type: Speech and Text
Language(s): Marathi
Linguality: Monolingual
Catalogue Id: SYSPIN_MARATHI_F_NHC
Data Size (HH:MM:SS): 7 hours:53 mins:44 secs
Data Size (# Sentences): 3077
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOOK, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Marathi Female Data Statistics

Total Audio Duration:    7 hours:53 mins:44 secs
Average Sample Duration: 9.238 secs
Total Sentences:         3077
Unique word Count:       20816

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description |
| ------ | ----------------------- | ----- | ------------------ |
| AGRI   | 0 hours:35 mins:51 secs | 230   | AGRICULTURE        |
| BOOK   | 1 hours:39 mins:20 secs | 668   | BOOKS              |
| EDUC   | 1 hours:35 mins:43 secs | 606   | EDUCATION          |
| EVAL   | 0 hours:6 mins:51 secs  | 59    | EVALUATION         |
| FINA   | 0 hours:6 mins:47 secs  | 44    | FINANCE            |
| GENE   | 0 hours:32 mins:33 secs | 207   | GENERAL            |
| HEAL   | 0 hours:39 mins:54 secs | 264   | HEALTH             |
| OTHE   | 0 hours:38 mins:31 secs | 264   | OTHERS             |
| POLI   | 1 hours:34 mins:34 secs | 572   | POLITICS           |
| WEAT   | 0 hours:23 mins:36 secs | 163   | WEATHER            |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to
various domain specific sentences, conversational sentences and erroneous sentences.

---

## Telugu Male (HC)

#### Telugu Male Data Attributes

Type: Speech and Text
Language(s): Telugu
Linguality: Monolingual
Catalogue Id: SYSPIN_TELUGU_M_HC
Data Size (HH:MM:SS): 48 hours:20 mins:26 secs
Data Size (# Sentences): 21463
Data size (# Speakers): Male(1)
Speaker Tag: Spk0001
Domains: AGRI, BOCU, BOOK, EDUC, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

## Telugu Male Data Statistics

Total Audio Duration:    48 hours:20 mins:26 secs
Average Sample Duration: 8.108 secs
Total Sentences:         21463
Unique word Count:       89155

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 1 hours:56 mins:31 secs | 747   | AGRICULTURE            |
| BOCU   | 6 hours:52 mins:42 secs | 3000  | RUNNING TEXT FROM BOOK |
| BOOK   | 19 hours:5 mins:33 secs | 9406  | BOOKS                  |
| EDUC   | 4 hours:10 mins:30 secs | 1578  | EDUCATION              |
| FINA   | 3 hours:46 mins:35 secs | 1568  | FINANCE                |
| GENE   | 3 hours:1 mins:24 secs  | 1252  | GENERAL                |
| HEAL   | 1 hours:39 mins:38 secs | 686   | HEALTH                 |
| OTHE   | 1 hours:36 mins:30 secs | 721   | OTHERS                 |
| POLI   | 4 hours:31 mins:44 secs | 1798  | POLITICS               |
| WEAT   | 1 hours:39 mins:15 secs | 707   | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Telugu Male (NHC)

#### Telugu Male Data Attributes

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
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Telugu Male Data Statistics

Total Audio Duration:    8 hours:19 mins:31 secs
Average Sample Duration: 8.541 secs
Total Sentences:         3509
Unique word Count:       23890

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description     |
| ------ | ----------------------- | ----- | ---------------------- |
| AGRI   | 0 hours:19 mins:32 secs | 120   | AGRICULTURE            |
| BOCU   | 1 hours:37 mins:51 secs | 597   | RUNNING TEXT FROM BOOK |
| BOOK   | 2 hours:59 mins:19 secs | 1328  | BOOKS                  |
| EDUC   | 0 hours:57 mins:44 secs | 350   | EDUCATION              |
| EVAL   | 0 hours:36 mins:24 secs | 400   | EVALUATION             |
| FINA   | 0 hours:28 mins:44 secs | 189   | FINANCE                |
| GENE   | 0 hours:18 mins:9 secs  | 114   | GENERAL                |
| HEAL   | 0 hours:5 mins:9 secs   | 35    | HEALTH                 |
| OTHE   | 0 hours:12 mins:20 secs | 88    | OTHERS                 |
| POLI   | 0 hours:25 mins:13 secs | 158   | POLITICS               |
| WEAT   | 0 hours:19 mins:1 secs  | 130   | WEATHER                |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Telugu Female (HC)

#### Telugu Female Data Attributes

Type: Speech and Text
Language(s): Telugu
Linguality: Monolingual
Catalogue Id: SYSPIN_TELUGU_F_HC
Data Size (HH:MM:SS): 57 hours:21 mins:9 secs
Data Size (# Sentences): 22077
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOSC, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Telugu Female Data Statistics

Total Audio Duration:    57 hours:21 mins:9 secs
Average Sample Duration: 9.352 secs
Total Sentences:         22077
Unique word Count:       79261

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description       |
| ------ | ----------------------- | ----- | ------------------------ |
| AGRI   | 2 hours:28 mins:16 secs | 860   | AGRICULTURE              |
| BOSC   | 27 hours:15 mins:3 secs | 11566 | SOCIAL SCIENCE BOOK TEXT |
| EDUC   | 5 hours:56 mins:33 secs | 1909  | EDUCATION                |
| EVAL   | 0 hours:44 mins:27 secs | 389   | EVALUATION               |
| FINA   | 4 hours:56 mins:33 secs | 1712  | FINANCE                  |
| GENE   | 3 hours:53 mins:5 secs  | 1347  | GENERAL                  |
| HEAL   | 1 hours:57 mins:53 secs | 717   | HEALTH                   |
| OTHE   | 2 hours:11 mins:21 secs | 808   | OTHERS                   |
| POLI   | 5 hours:36 mins:42 secs | 1938  | POLITICS                 |
| WEAT   | 2 hours:21 mins:12 secs | 831   | WEATHER                  |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Telugu Female (NHC)

#### Telugu Female Data Attributes

Type: Speech and Text
Language(s): Telugu
Linguality: Monolingual
Catalogue Id: SYSPIN_TELUGU_F_NHC
Data Size (HH:MM:SS): 1 hours:8 mins:31 secs
Data Size (# Sentences): 367
Data size (# Speakers): Female(1)
Speaker Tag: Spk0001
Domains: AGRI, BOSC, EDUC, EVAL, FINA, GENE, HEAL, OTHE, POLI, WEAT
Annotation file availability: YES
Recording Specifications: 48 kHz, 24 bits per sample, Mono channel
Validation status: Not Validated
Data creator: Indian Institute of Sciences (IISc), Bengaluru
Year of publishing: 2024
Suggested research purpose/ areas: TTS

#### Telugu Female Data Statistics

Total Audio Duration:    1 hours:8 mins:31 secs
Average Sample Duration: 11.203 secs
Total Sentences:         367
Unique word Count:       4181

#### Distribution of domains:

| Domain | Duration                | Count | Domain Description       |
| ------ | ----------------------- | ----- | ------------------------ |
| AGRI   | 0 hours:3 mins:48 secs  | 20    | AGRICULTURE              |
| BOSC   | 0 hours:39 mins:32 secs | 201   | SOCIAL SCIENCE BOOK TEXT |
| EDUC   | 0 hours:4 mins:4 secs   | 22    | EDUCATION                |
| EVAL   | 0 hours:1 mins:7 secs   | 11    | EVALUATION               |
| FINA   | 0 hours:7 mins:25 secs  | 41    | FINANCE                  |
| GENE   | 0 hours:5 mins:31 secs  | 31    | GENERAL                  |
| HEAL   | 0 hours:1 mins:30 secs  | 8     | HEALTH                   |
| OTHE   | 0 hours:1 mins:22 secs  | 8     | OTHERS                   |
| POLI   | 0 hours:3 mins:6 secs   | 19    | POLITICS                 |
| WEAT   | 0 hours:1 mins:2 secs   | 6     | WEATHER                  |

Samples in EVALUATION domain are recommended for testing TTS models. These samples belong to various domain specific sentences, conversational sentences and erroneous sentences.

---

## Recording Setup

Microphone: Neumann TLM-103
Recording Environment: Professional studio
Recording Conditions: Studio quality at ~40dB SNR

---

## Copyright and license

TTS data created under SYSPIN project by Indian Institute of Science, Bengaluru is available at (https://spiredatasets.iisc.ac.in/syspinCorpus) and the copyright in the TTS data belongs to Indian Institute of Science, Bengaluru and the said TTS data is released or distributed under CC-BY-4.0 license (https://creativecommons.org/licenses/by/4.0/legalcode.en). The user of said TTS data is referred to the disclaimer of warranties section in the CC-BY-4.0 license agreement.

---

## Acknowledgments

We extend our heartfelt gratitude to the talented voice artist whose contributions were fundamental to this project's success.
We are particularly grateful to the project of German Development Cooperation 'FAIR Forward - AI for All' for their financial support in developing this TTS corpus, and Bhashini AI Solutions Private Limited for their financial support for part of the corpus beyond 44 hours for every voice artist in developing this TTS corpus.

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
