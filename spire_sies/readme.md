## SPIRE-SIES CORPUS

SPIRE-SIES provides 166 hours of annotated Indian English spontaneous speech data. This corpus is crowd-sourced from 1567 speakers belonging to varied 18 Indian nativities, genders and age groups. Traditional spontaneous speech collection strategies involve capturing of speech during interviewing or conversations. But, we use images as stimuli to induce spontaneity in speech. Transcripts are intially generated from WHISPER and then validated manually over multiple rounds.

---

## Data Attributes

- Type: Speech and Text
- Speech Type: Spontaneous
- Language(s): English
- Linguality: Monolingual
- Data Size (HH:MM:SS): 166 hours:28 mins:54 secs
- Data Size (# Sentences): 41295
- Data size (# Speakers): Male (815), Female (743), Other (9)
- Annotation file availability: YES
- Recording Specifications: 48 kHz, 16 bits per sample, Mono channel
- Validation status: Validated
- Data creator: Indian Institute of Science (IISc), Bengaluru
- Year of publishing: 2023
- Suggested research purpose/ areas: Speech Recongnition

---

## File Structure

The corpus is organized into the following directory structure:
```
[Corpus_Root]/
      ├──[IISc_SPIRE_SIES_Transcripts.csv]
      ├──[IISc_SPIRE_SIES_Image_Captions.csv]
      └── [Speaker_1]/
            ├── [IISc_SPIRE_SIES_<speakerID>_<imageID>_<uniqueID>.wav]
            ├── [IISc_SPIRE_SIES_<speakerID>_<imageID>_<uniqueID>.wav]
            ├── [IISc_SPIRE_SIES_<speakerID>_<imageID>_<uniqueID>.wav]
            ├── [...]
            └── [IISc_SPIRE_SIES_<speakerID>_<imageID>_<uniqueID>.wav]
```
---

## Data Statistics

- Total Audio Duration:    166 hours:28 mins:54 secs
- Average Sample Duration: 14.51 secs
- Total Sentences:         41295
- Unique word Count:       27057

Distribution over Speakers' nativity and genders:

| Nativity  | Duration                 | Genders        |
|:----------|:-------------------------|:---------------|
| Bengali   | 10 hrs :24 mins :30 secs | F: 32, M: 58   |
| Dogri     | 00 hrs :16 mins :14 secs | F: 3, M: 0     |
| Gujarati  | 00 hrs :41 mins :27 secs | F: 6, M: 1     |
| Hindi     | 29 hrs :41 mins :52 secs | F: 139, M: 186 |
| Kannada   | 10 hrs :42 mins :09 secs | F: 38, M: 73   |
| Kashmiri  | 00 hrs :01 mins :53 secs | F: 1, M: 2     |
| Konkani   | 02 hrs :11 mins :49 secs | F: 12, M: 9    |
| Maithili  | 00 hrs :36 mins :44 secs | F: 5, M: 1     |
| Malayalam | 13 hrs :32 mins :12 secs | F: 59, M: 68   |
| Marathi   | 25 hrs :17 mins :06 secs | F: 84, M: 139  |
| Nepali    | 00 hrs :06 mins :15 secs | F: 0, M: 1     |
| Odia      | 03 hrs :16 mins :16 secs | F: 14, M: 20   |
| Other     | 02 hrs :29 mins :11 secs | F: 11, M: 16   |
| Punjabi   | 00 hrs :40 mins :29 secs | F: 1, M: 6     |
| Sindhi    | 00 hrs :05 mins :57 secs | F: 1, M: 0     |
| Tamil     | 13 hrs :58 mins :13 secs | F: 36, M: 95   |
| Telugu    | 49 hrs :06 mins :41 secs | F: 285, M: 127 |
| Urdu      | 03 hrs :18 mins :54 secs | F: 16, M: 13   |

---

## Transcription CSV Structure

File_Name, Transcript
[IISc_SPIRE_SIES_<speakerID>_<imageID>_<uniqueID>.wav], Transcript_1

---

## Tags in Transcription

In our transcription there are 2 types of tags:
1. paried : `<tag></tag>`
2. unpaired : `<tag>`  
Here is a comprehensive list of all transcription tags used to annotate speech spontaneity, vocalizations, and environmental sounds. Tags are grouped by category for clarity:

### Human Vocalizations
1. `[humming]`
2. `[breathing]`
3. `[burping]`
4. `[coughing]`
5. `[exhaling]`
6. `[helium]`
7. `[inaudible]`
8. `[inhaling]`
9. `[laughing]`
10. `[lip_smacking]`
11. `[nose_blowing]`
12. `[sneezing]`
13. `[spitting]`
14. `[throat_clearing]`
15. `[unintelligible]`
16. `[yawning]`

### Baby Sounds
1. `<baby_crying>`
2. `<baby_laughing>`
3. `<baby_noise>`

### Environmental Noises
1. `<bell_ringing>`
2. `<bird_noise>`
3. `<children_noise>`
4. `<clapping_noise>`
5. `<dog_barking>`
6. `<door_creaking>`
7. `<door_knocking>`
8. `<horn_noise>`
9. `<insect_noise>`
10. `<mobile_noise>`
11. `<music_noise>`
12. `<static_noise>`
13. `<television_noise>`
14. `<traffic_noise>`
15. `<water_noise>`
16. `<whistle_noise>`
17. `<wind_noise>`

### Speech Tags
1. `<human_talking>` (background speech from another speaker)
2. `<ESIL>` (Silence at the end of audio sample)
3. `<NE>` (Non-English speech)
4. `<PAUSE>`
5. `<SSIL>` (Silence at the start of audio sample)

---

## Images (Stimuli): IISc_SPIRE_SIES_Images

This is a subset of flicker-40k image captioning database. We take 1k images from 
flicker-40k which were given to the speakers as stimuli inducing spontaneity in speech.
Five variations of captions for images are provided under: IISc_SPIRE_SIES_Image_Captions.csv

---

## Copyright and license

SPIRE-SIES Corpus is created by Indian Institute of Science, Bengaluru is available
at (https://spiredatasets.ee.iisc.ac.in/spiresiescorpus) and the copyright belongs to
Indian Institute of Science, Bengaluru and the said corpus is released or distributed under
CC-BY-4.0 license (https://creativecommons.org/licenses/by/4.0/legalcode.en). The user of
said corpus is referred to the disclaimer of warranties section in the CC-BY-4.0 license
agreement.

---

## Acknowledgments

We extend our heartfelt gratitude to the speakers and volunteers whose contributions were
fundamental to this project's success.

---

## Citation
```bibtex
@inproceedings{DBLP:conf/ococosda/SinghSVCG23,
  author={Abhayjeet Singh and Charu Shah and Rajashri Varadaraj and Sonakshi Chauhan and Prasanta Kumar Ghosh},
  title={SPIRE-SIES: A Spontaneous Indian English Speech Corpus},
  year={2023},
  cdate={1672531200000},
  pages={1-6},
  url={https://doi.org/10.1109/O-COCOSDA60357.2023.10482940},
  booktitle={O-COCOSDA},
  crossref={conf/ococosda/2023}
}
```

---

## Contact Information

SPIRE Lab, EE Dept., IISc, Bengaluru
Email: spirelab.ee@iisc.ac.in

---
