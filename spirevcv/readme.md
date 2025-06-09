# SPIRE VCV

**SPIRE VCV** is a comprehensive speech production database that includes simultaneous **acoustic** and **electromagnetic articulography (EMA)** data collected from non-native Indian English speakers. This corpus, named [SPIRE VCV](https://spire.ee.iisc.ac.in/spire/spire-vcv.php), provides valuable resources for acoustic-articulatory studies, particularly for investigations involving speaking rate variations.

### Key Features of the SPIRE VCV Corpus:
- **Simultaneous Acoustic and Articulatory Data:**  
	The database includes synchronized recordings of speech audio and articulatory movements.

- **VCV Stimuli:**  
	Symmetrical **Vowel-Consonant-Vowel (VCV)** sequences comprising:
	- **Vowels (5):** `/a/, /e/, /i/, /o/, /u/`
	- **Consonants (17):** `/b/, /ch/, /d/, /f/, /g/, /jh/, /k/, /l/, /m/, /n/, /ng/, /p/, /r/, /s/, /t/, /v/, /z/`

- **Speaking Rates:**  
	Recordings were conducted at three distinct speaking rates:
	- **Slow**
	- **Normal**
	- **Fast**

- **Articulatory Data:**  
	Movements of six key speech articulators were tracked in a 3D coordinate system:
	- Upper Lip
	- Lower Lip
	- Jaw
	- Tongue Tip
	- Tongue Body
	- Tongue Dorsum

- **Manual Boundary Annotations:**  
	Precise boundaries for vowels and consonants were manually annotated using spectrograms, waveforms, and glottal pulses.

- **Speaker Demographics:**  
	Data was collected from 10 speakers (5 male, 5 female) aged 18–27, fluent in English, and from diverse Indian language backgrounds.

### Applications:
The SPIRE VCV corpus is ideal for:
- Acoustic-articulatory studies
- Speaking rate-specific investigations
- Analysis of articulatory movement patterns across different speech rates

This database also includes a basic articulatory analysis of consonants, highlighting how articulatory movements vary with speaking rate. Researchers can leverage this resource for a wide range of speech production and phonetic studies.

The stimuli consist of **nonsense, symmetrical VCV (Vowel-Consonant-Vowel) utterances** embedded in the sentence:  
**"Speak VCV today"**  
These are spoken at **three different speaking rates** — slow, normal, and fast — with **three repetitions** each.

### Phonetic Inventory
- **Consonants (17):**  
  `/b/, /ch/, /d/, /f/, /g/, /jh/, /k/, /l/, /m/, /n/, /ng/, /p/, /r/, /s/, /t/, /v/, /z/`
- **Vowels (5):**  
  `/a/, /e/, /i/, /o/, /u/`

### Speakers
- **Total:** 10 non-native Indian English speakers (5 male, 5 female)  
- **Age Range:** 18–27 years  
- **Health:** No speech-related disorders  
- **Background:** Fluent in English (reading, writing, speaking); from various Indian native language backgrounds

---

## Recording and Setup

### Equipment
- **Articulatory data:**  
  Recorded using **AG501 3D Electromagnetic Articulograph (EMA)**
- **Audio data:**  
  Captured with **t.bone EM9600 shotgun unidirectional electret condenser microphone**

### Sampling
- **Audio:** Originally at **48 kHz**, then downsampled to **16 kHz**
- **Articulatory:** Sampled at **250 Hz**

### Preprocessing
- **Filter:**  
  A **10th-order Chebyshev Type II lowpass filter**  
  - Cut-off: **40 Hz**  
  - Stopband attenuation: **40 dB**  
  - Purpose: To remove high-frequency noise from EMA

---

## Sensor Placement

Six sensors were attached to articulators to track 3D movement:
- Upper Lip  
- Lower Lip  
- Jaw  
- Tongue Tip  
- Tongue Body  
- Tongue Dorsum

Additional sensors were placed **behind the left and right ear** to enable head movement correction.

Each of the 6 articulator sensors records movement in 3D, resulting in **18 articulatory features** (6 sensors × 3 axes).

---

## Speaker Instructions

- All speakers were trained prior to recording.
- A GUI displayed each stimulus word on screen.
- Each speaker pronounced the word at:
  - **Slow**
  - **Normal/Habitual**
  - **Fast** rates  
- Each rate had **three repetitions** per stimulus.

---

## VCV Boundary Annotation

VCV boundaries were manually annotated using an in-house **MATLAB tool**, based on:
- **Wideband spectrogram**
- **Raw waveform**
- **Glottal pulses (Praat)**

#### For Unvoiced Consonants:
- Start of C-region: **Last glottal pulse in V1**
- End of C-region: **First glottal pulse at start of V2**

#### For Voiced Consonants:
- Start and end boundaries based on:
  - **Formants** in spectrogram
  - **Time-domain waveform**

In ambiguous cases, annotators discussed and made a **unanimous decision**.

---
### Dataset loading instructions (example)

```matlab
%% Load EMA Data
load ('0.mat');
disp("Size for matrix:"); disp(size(ema));
% Extract articulatory sensor positions
EL1 = ema(1:3,:);   %Right earlobe for head movement correction
EL2 = ema(4:6,:);   %Left earlobe for head movement correction
UL  = ema(7:9,:);   %Upper Lip
LL  = ema(10:12,:); %Lower Lip
Jaw = ema(13:15,:); %Jaw
TT  = ema(16:18,:); %Tongue Tip
TB  = ema(19:21,:); %Tongue Body
TD  = ema(22:24,:); %Tongue Dorsum
% Plot: 3D Trajectories of All Sensors
figure;
plot3(UL(1,:), UL(2,:), UL(3,:), 'r--', 'MarkerSize', 4, 'LineWidth',1.5); hold on;
plot3(LL(1,:), LL(2,:), LL(3,:), 'b--', 'MarkerSize', 4, 'LineWidth',1.5); hold on;
plot3(Jaw(1,:), Jaw(2,:), Jaw(3,:), 'g--', 'MarkerSize', 4, 'LineWidth',1.5); hold on;
plot3(TT(1,:), TT(2,:), TT(3,:), 'm--', 'MarkerSize', 4, 'LineWidth',1.5); hold on;
plot3(TB(1,:), TB(2,:), TB(3,:), 'k--', 'MarkerSize', 4, 'LineWidth',1.5); hold on;
plot3(TD(1,:), TD(2,:), TD(3,:), '--','Color',[0.9290 0.6940 0.1250], 'MarkerSize', 4, 'LineWidth',1.5); hold on;
hold off;
legend({'UL', 'LL', 'Jaw', 'TT', 'TB', 'TD'}, 'Location', 'northeastoutside');
title("3D Trajectories of Articulatory Sensors");
xlabel("x-axis"); ylabel("y-axis"); zlabel("z-axis");
view(45, 30); grid on; box on;
```


Below is an example plot generated from the articulatory data:

![3D Trajectories of Articulatory Sensors](images/image1.png)

## Speaker Information

| #  | Subject | Age | Gender | Native Language | Name       |
|----|---------|-----|--------|-----------------|------------|
| 1  | F1      | 22  | Female | Bengali         | Anvesha    |
| 2  | M1      | 21  | Male   | Tulu            | Vignesh    |
| 3  | F2      | 27  | Female | Bengali         | Tanuka     |
| 4  | M2      | 20  | Male   | Bengali         | Abhinav    |
| 5  | F3      | 23  | Female | Tamil           | AparnaS    |
| 6  | M3      | 21  | Male   | Tamil           | Shankar    |
| 7  | F4      | 20  | Female | Kannada         | Aparna     |
| 8  | M4      | 23  | Male   | Tamil           | Siddharth  |
| 9  | F5      | 21  | Female | Malayalam       | Aishwarya  |
| 10 | M5      | 20  | Male   | Hindi           | Gaurav     |

**Keywords:** VCV, speaking rate, EMA, corpus 

### Citation

If you use the SPIRE VCV corpus in your research, please cite the following paper:

T. Purohit, T. Umesh, S. Narayanan, M. S., and P. K. Ghosh, "SPIRE VCV: An Acoustic-Articulatory Corpus with Three Different Speaking Rates," *2021 24th Conference of the Oriental COCOSDA International Committee for the Co-ordination and Standardisation of Speech Databases and Assessment Techniques (O-COCOSDA)*, Singapore, 2021, pp. 116-121.  
DOI: [10.1109/O-COCOSDA202152914.2021.9660422](https://doi.org/10.1109/O-COCOSDA202152914.2021.9660422)


