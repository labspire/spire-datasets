# WSPIRE Dataset

## About

The **Wspire corpus** is an extensive multi-device speech database specifically designed to capture recordings in both **neutral** and **whispered** modes. It encompasses recordings from 92 speakers, utilizing 5 different devices to ensure diverse audio capture scenarios. The corpus features parallel recordings in both neutral and whispered speech, allowing for detailed comparative analysis. All recordings were meticulously conducted in a soundproof recording room at the Electrical Engineering Department of the Indian Institute of Science (IISc), Bangalore. The participants, who contributed to this dataset, are primarily graduate students, interns, or employees affiliated with IISc. This dataset is a valuable resource for research in speech processing and acoustic analysis, offering high-quality recordings across neutral and whispered speech modes and consistent environmental conditions using multiple recording devices.

- **Speakers:** 92 total
- **Devices:** 5 distinct devices for diverse audio conditions
- **Speech Modes:** Parallel recordings in **neutral** and **whispered** modes
- **Environment:** Soundproof studio at the **Electrical Engineering Department**, Indian Institute of Science (IISc), Bangalore

---

## Recording and Setup

### Audio Specs
- **Original Sample Rate:** 44.1 kHz  
- **Downsampled To:** 16 kHz

### Devices Used
1. **Zoom H6 Handy Recorder** with XYH-6 microphone  
2. [**Philips SHP-1900/97 Stereo Headphones**](https://www.philips.co.in/c-p/SHP1900_97/stereo-headphones)  
3. [**Apple iPhone 7**](https://www.gsmarena.com/apple_iphone_7-8064.php)  
4. **Nokia 5.1**  
5. [**Motorola Moto E5 Plus**](https://www.motorola.in/smartphones-moto-e5-plus/p)  

### Recording Procedure

- At first, every speaker was asked to speak all the sentences in the assigned set in neutral mode and then in the whispered mode.
- Three different tones, each having a duration of 1 second, were used while recording.
- Further, to indicate the beginning of each sentence, a tone of constant frequency of 1kHz was played.
- An up-tone of 1-second duration, with frequency increasing from 1kHz to 2kHz, was played when the speaker pronounced the sentence correctly. Similarly, a down-tone of 1-second duration with frequency decreasing from 2kHz to 1kHz was played if the sentence was mispronounced.
- In case of wrong pronunciation, speakers were asked to repeat the sentence

---

## Data Description

- **Sentences:** First **450 sentences** from the [**MOCHA-TIMIT corpus**](https://data.cstr.ed.ac.uk/mocha/mocha-timit.txt) (phonetically balanced) 
- **Division:** 450 sentences split into **9 sets**, each with **50 sentences**

---

## File Naming Convention

Each audio and timestamp file is uniquely named using the following structure:

```
ID0[ID]_00[SET]_[GENDER]_[MODE]_[DEVICE]_[SENTNUM]
```

### Examples
- **Audio:**  
  `ID06_006_F_Neutral_Headset_11.wav`
- **Timestamp:**  
  `ID06_006_F_Neutral_Headset_11.lab`

### Fields
- **ID:** Speaker ID (e.g., `06`)
- **SET:** Sentence set number (1–9)
- **GENDER:** `M` for Male, `F` for Female
- **MODE:** `Neutral` or `Whisper`
- **DEVICE:** One of `Headset`, `Zoom`, `iPhone`, `Moto`, `Nokia`
- **SENTNUM:** Sentence number in that set (1–50)

---

## Speaker Information

| ID  | Age | Gender | Set |
|-----|-----|--------|-----|
| 4   | 24  | Male   | 4   |
| 5   | 24  | Male   | 5   |
| 6   | 21  | Female | 6   |
| 7   | 24  | Male   | 7   |
| 8   | 22  | Male   | 8   |
| 12  | 30  | Female | 2   |
| 13  | 24  | Male   | 3   |
| 14  | 26  | Male   | 4   |
| 16  | 23  | Male   | 6   |
| 17  | 24  | Female | 7   |
| 18  | 28  | Female | 8   |
| 19  | 23  | Female | 9   |
| 21  | 20  | Female | 3   |
| 22  | 25  | Female | 4   |
| 23  | 27  | Male   | 5   |
| 24  | 24  | Male   | 6   |
| 25  | 22  | Male   | 7   |
| 26  | 23  | Male   | 8   |
| 27  | 22  | Male   | 9   |
| 28  | 31  | Male   | 1   |
| 29  | 22  | Female | 2   |
| 30  | 22  | Female | 3   |
| 31  | 22  | Female | 4   |
| 32  | 22  | Female | 5   |
| 33  | 23  | Male   | 6   |
| 34  | 28  | Female | 7   |
| 35  | 23  | Male   | 8   |
| 36  | 26  | Female | 9   |
| 37  | 21  | Male   | 1   |
| 38  | 23  | Male   | 2   |
| 39  | 24  | Male   | 3   |
| 40  | 25  | Female | 4   |
| 41  | 28  | Male   | 5   |
| 42  | 21  | Female | 6   |
| 43  | 30  | Male   | 7   |
| 44  | 23  | Female | 9   |
| 45  | 24  | Male   | 1   |
| 46  | 37  | Female | 2   |
| 47  | 23  | Female | 3   |
| 48  | 30  | Male   | 4   |
| 49  | 23  | Male   | 5   |
| 50  | 31  | Female | 6   |
| 51  | 22  | Female | 7   |
| 52  | 24  | Male   | 8   |
| 53  | 21  | Male   | 9   |
| 54  | 25  | Male   | 1   |
| 55  | 24  | Male   | 2   |
| 56  | 28  | Female | 3   |
| 57  | 25  | Female | 4   |
| 58  | 32  | Male   | 5   |
| 59  | 25  | Male   | 6   |
| 60  | 23  | Male   | 7   |
| 62  | 22  | Male   | 9   |
| 63  | 22  | Male   | 1   |
| 64  | 24  | Male   | 2   |
| 65  | 20  | Male   | 3   |
| 66  | 23  | Male   | 4   |
| 67  | 24  | Female | 5   |
| 68  | 23  | Female | 6   |
| 69  | 21  | Female | 7   |
| 70  | 22  | Male   | 8   |
| 71  | 27  | Female | 9   |
| 72  | 24  | Male   | 1   |
| 73  | 24  | Male   | 2   |
| 74  | 22  | Female | 3   |
| 75  | 29  | Male   | 4   |
| 76  | 26  | Female | 5   |
| 77  | 29  | Male   | 6   |
| 79  | 23  | Male   | 8   |
| 80  | 27  | Female | 9   |
| 83  | 23  | Female | 3   |
| 84  | 30  | Female | 4   |
| 85  | 23  | Male   | 5   |
| 86  | 26  | Female | 6   |
| 87  | 23  | Male   | 7   |
| 88  | 25  | Male   | 8   |
| 89  | 23  | Male   | 9   |
| 90  | 23  | Female | 1   |
| 92  | 27  | Male   | 2   |
| 93  | 28  | Male   | 3   |
| 95  | 24  | Male   | 5   |
| 96  | 23  | Male   | 6   |
| 97  | 22  | Male   | 7   |
| 98  | 22  | Male   | 8   |
| 99  | 23  | Male   | 9   |
| 100 | 22  | Female | 1   |
| 101 | 25  | Male   | 2   |
| 102 | 24  | Male   | 3   |
| 103 | -   | Female | 4   | 
| 104 | -   | Male   | 5   |
| 105 | -   | Male   | 6   |
| 106 | -   | Male   | 7   |    


---


## License
wSPIRE data collected by Spire lab, Indian Institute of Science, Bengaluru is available at https://spiredatasets.ee.iisc.ac.in/wspirecorpus and the copyright for this data belongs to Indian Institute of Science, Bengaluru and the said data is released or distributed under CC-BY-4.0 license (https://creativecommons.org/licenses/by/4.0/legalcode.en). Users are advised to refer to the "Disclaimer of Warranties" section in the license agreement before using the dataset.

## Citation

*If you use the **wSPIRE corpus** in your research, please cite the following publication:*

*Singhal, Bhavuk, Abinay Reddy Naini, and Prasanta Kumar Ghosh. ["wSPIRE: A parallel multi-device corpus in neutral and whispered speech."](https://ieeexplore.ieee.org/document/9660449) In 2021 24th Conference of the Oriental COCOSDA International Committee for the Co-ordination and Standardisation of Speech Databases and Assessment Techniques (O-COCOSDA), pp. 146-151. IEEE, 2021.*


For more details, visit the [wSPIRE Corpus](https://spiredatasets.ee.iisc.ac.in/wspirecorpus) page.
