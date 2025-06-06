# Indic TIMIT: A Phonetically Rich Indian English Speech Corpus

With the rapid advancements in speech technology, there is a growing demand for large-scale speech corpora, especially those featuring non-native English speakers. To address this need in the Indian context, we present **Indic TIMIT**, a phonetically rich Indian English speech corpus.

## Key Features
- Approximately 240 hours of English speech data from 81 Indian speakers, representing diverse regional backgrounds across India.
- Each speaker recorded 2,342 stimuli derived from the TIMIT corpus.
- Includes a subset of recordings with manually annotated phoneme transcriptions by two expert linguists.
- Captures speaker-specific pronunciation patterns, making it a valuable resource for studying non-native English speech.
### Audio Specifications

The audio data in the Indic TIMIT corpus adheres to the following specifications:
- **Channels**: Mono (1 channel)
- **Sample Rate**: 44,100 Hz
- **Precision**: 16-bit

These specifications ensure high-quality audio suitable for speech processing and analysis tasks.


## Data information

### Tar File Information

The dataset is organized into the following 18 tar files, each corresponding to natives belonging to a common native specific language or regional variant. Below is the detailed information:

| Tar File Name                  | Size  | Duration (hrs) | NUMBER OF SPEAKERS | REGION            | SPEAKER NAME AND ID                                                                 | Grouping  |
|--------------------------------|-------|----------------|---------------------|-------------------|------------------------------------------------------------------------------------|-----------|
| IISc_IndicTIMIT_ASS.tar.gz     | 687M  | 3.02           | 1                   | East + North-East | F_BITASTA_ASS (F30)                                                               | Group-1   |
| IISc_IndicTIMIT_BEN.tar.gz     | 4.8G  | 23.52          | 8                   | East + North-East | F_ANANYA_BEN (F14), F_KASTURI_BEN (F33), F_RIDDHI_BEN (F13), F_ROHINI_BEN (F38), M_ANURAG_BEN (M14), M_ANWOY_BEN (M24), M_ARITRA_BEN (M1), M_ARKA_BEN (M18) | Group-1   |
| IISc_IndicTIMIT_DIM.tar.gz     | 635M  | 2.93           | 1                   | East + North-East | F_YASHNA_DIM (F23)                                                                | Group-1   |
| IISc_IndicTIMIT_GUJ.tar.gz     | 1.4G  | 6.90           | 2                   | West             | M_SUMANKUMAR_GUJ (M39), M_URV_GUJ (M7)                                            | Group-3   |
| IISc_IndicTIMIT_HIN.tar.gz     | 7.8G  | 35.30          | 13                  | North            | F_ASTHA_HIN (F25), F_AVNI_HIN (F6), F_RITU_HIN (F40), F_RUP_HIN (F11), F_SHIVANI_HIN (F2), M_ABHYUDAY_HIN (M29), M_ALISHAN_HIN (M6), M_GAUTAM_HIN (M10), M_HIMANSHU_HIN (M9), M_NITIN_HIN (M17), M_RAVEESH_HIN (M12), M_SATYAM_MAI (M28), M_AVI_HIN (M33) | Group-2   |
| IISc_IndicTIMIT_KAN.tar.gz     | 5.2G  | 24.54          | 8                   | South1           | F_BVKALPANA_KAN (F21), F_KAUSTOBHA_KAN (F26), F_NAGARATHNA_KAN (F4), F_NITYASHREE_KAN (F19), F_SHILPA_KAN (F17), M_PRAMATH_KAN (M22), M_RAKESH_KAN (M30), M_VIGGY_KAN (M8) | Group-4   |
| IISc_IndicTIMIT_KON.tar.gz     | 1.2G  | 6.12           | 2                   | West             | F_ASHWINI_KON (F9), F_TANVI_KON (F15)                                             | Group-3   |
| IISc_IndicTIMIT_MAI.tar.gz     | 562M  | 2.74           | 1                   | East + North-East | M_SATYAM_MAI (M28)                                                                | Group-1   |
| IISc_IndicTIMIT_MAL.tar.gz     | 697M  | 24.40          | 1                   | North            | M_HITENDRA_MAL (M19)                                                              | Group-2   |
| IISc_IndicTIMIT_MLY.tar.gz     | 5.3G  | 28.02          | 8                   | South2           | F_AKSHARA_MLY (F39), F_DEEPTHI_MLY (F36), F_GAYATRI_MLY (F35), F_KTRASEENA_MLY (F29), F_NAZREEN_MLY (F27), M_ANURENJAN_MLY (M2), M_ELDHOSE_MLY (M3), M_SUVIN_MLY (M40) | Group-5   |
| IISc_IndicTIMIT_MAR.tar.gz     | 5.8G  | 3.32           | 10                  | West             | F_BANGAL_MAR (F1), F_DHRUTI_MAR (F5), F_ISHITA_MAR (F20), F_KRIPA_MAR (F22), F_RADHIKA_MAR (F24), M_ABHI_MAR (M32), M_ADVAIT_MAR (M31), M_GAURAV_MAR (M13), M_HARISH_MAR (M5), M_RUTURAJ_MAR (M36) | Group-3   |
| IISc_IndicTIMIT_MOG.tar.gz     | 604M  | 3.10           | 1                   | East + North-East | M_KUNJARI_MOG (M21)                                                               | Group-1   |
| IISc_IndicTIMIT_NEP.tar.gz     | 573M  | 2.96           | 1                   | East + North-East | F_BHUTIA_NEP (F12)                                                                | Group-1   |
| IISc_IndicTIMIT_ODI.tar.gz     | 1.3G  | 5.24           | 2                   | East + North-East | F_BABITHA_ODI (F32), M_SEKHAR_ODI (M16)                                           | Group-1   |
| IISc_IndicTIMIT_PUN.tar.gz     | 1.3G  | 5.59           | 2                   | North            | F_KRITI_PUN (F37), F_NAVJOT_PUN (F41)                                             | Group-2   |
| IISc_IndicTIMIT_SAU.tar.gz     | 1.2G  | 6.16           | 2                   | West             | F_DIVYA_SAU (F7), M_BASKAR_SAU (M23)                                              | Group-3   |
| IISc_IndicTIMIT_TAM.tar.gz     | 5.8G  | 26.23          | 9                   | South2           | F_CHAITRA_TAM (F18), F_GEETHA_TAM (F8), F_POOJYA_TAM (F16), F_SHINY_TAM (F10), M_BALAJEE_TAM (M26), M_KAU_TAM (M38), M_SHARMA_TAM (M27), M_SRINATH_TAM (M4), M_VIGNESH_TAM (M15) | Group-5   |
| IISc_IndicTIMIT_TEL.tar.gz     | 5.3G  | 24.37          | 8                   | South1           | F_POOJAS_TEL (F28), F_RMONICA_TEL (F3), F_SUSEELA_TEL (F34), M_MURTY_TEL (M11), M_RAVI_TEL (M34), M_SATYENDAR_TEL (M25), M_SRI_TEL (M20), M_YASWANT_TEL (M35) | Group-4   |

Each tar file contains speech data and associated metadata for the respective language or dialect.

### Citation
If you use this corpus, please cite the following paper:

C. Yarra, R. Aggarwal, A. Rajpal, and P. K. Ghosh, "Indic TIMIT and Indic English lexicon: A speech database of Indian speakers using TIMIT stimuli and a lexicon from their mispronunciations," *2019 22nd Conference of the Oriental COCOSDA International Committee for the Co-ordination and Standardisation of Speech Databases and Assessment Techniques (O-COCOSDA)*, Cebu, Philippines, 2019, pp. 1-6, doi: [10.1109/O-COCOSDA46868.2019.9041230](https://doi.org/10.1109/O-COCOSDA46868.2019.9041230).

### Keywords
- IndicTIMIT
- Indian spoken English data
