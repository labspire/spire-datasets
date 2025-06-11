---
### VAANI

VAANI is an India-representative multi-modal multi-lingual dataset. 
The current version (phase 1- 80 districts, phase 2- 40 districts) contains ~21,500 hours of spontaenous,image-prompted speech by 112.4K speakers across 120 districts, talking about 210K images covering 86 languages.
From this audio data, 835 hours of transcribed data(text) is available, spanning almost evenly across the 120 districts. 

Project Vaani, by [IISc, Bangalore](https://iisc.ac.in/) and [ARTPARK](https://artpark.in/), is capturing the true diversity of India’s spoken languages to propel language AI technologies for a truly inclusive Digital India.
It was started with a vision to boost ML research and application capabilities in all Indian languages.
We expect to create data corpora of over 150,000 hours of speech, part of which will be transcribed in local scripts, while ensuring linguistic, educational, urban-rural, age, and gender diversity (among other potential diversity characteristics). These diligently collected and curated datasets of natural speech and text from about 1 million people across all 773 districts of India will be open-sourced. The current version of the dataset that is open-sourced contains is from Phase 1. This unique dataset is also available through prestigious platforms such as Bhashini (under the National Language Translation Mission, MeiTY).

This initiative has been funded by Google.
![alt text](https://storage.googleapis.com/image-for-displaying-huggingface-page/district_map_new.png)

|	District	|	Audio Duration(Hrs)	|	Trans. Duration(Hrs)	|	Audio Language-wise Duration(Hrs)	|	Trans. Language-wise Duration(Hrs)	|
|-----------------|----------------------|------------------------|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|										
|	Alipurduar	|	111.87	|	0.92	|	Bengali: 87.798, English: 0.628, Hindi: 11.881, Nepali: 11.565	|	Bengali: 0.902, English: 0.0, Hindi: 0.021, Nepali: 0.0	|
|	Anantpur	|	227.07	|	10.66	|	Kannada: 0.131, Tamil: 1.167, Marathi: 1.378, Bengali: 1.188, Telugu: 161.407, Urdu: 9.869, Hindi: 51.933	|	Kannada: 0.0, Tamil: 0.029, Marathi: 0.005, Bengali: 0.014, Telugu: 8.344, Urdu: 0.52, Hindi: 1.744	|
|	Araria	|	193.34	|	10.24	|	Maithili: 22.732, Bhojpuri: 0.216, Bengali: 0.254, Telugu: 0.096, Angika: 1.678, Hindi: 167.755, Urdu: 0.612	|	Maithili: 0.556, Bhojpuri: 0.006, Bengali: 0.005, Telugu: 0.0, Angika: 0.131, Hindi: 9.522, Urdu: 0.023	|
|	Aurangabad	|	185.93	|	9.93	|	Hindi: 79.5, Bengali: 0.132, Telugu: 0.14, Marathi: 106.157	|	Hindi: 3.808, Bengali: 0.001, Telugu: 0.0, Marathi: 6.118	|
|	Balrampur	|	186.69	|	11.84	|	Chhattisgarhi: 8.294, Hindi: 172.646, Awadhi: 5.753	|	Chhattisgarhi: 0.551, Hindi: 11.13, Awadhi: 0.16	|
|	Bangalore	|	99.56	|	0.77	|	English: 8.337, Hindi: 11.636, Kannada: 74.787, Punjabi: 2.445, Sumi: 0.168, Tamil: 1.969, Urdu: 0.221	|	English: 0.138, Hindi: 0.0, Kannada: 0.607, Punjabi: 0.0, Sumi: 0.0, Tamil: 0.029, Urdu: 0.0	|
|	Bastar	|	197.95	|	9.45	|	Gondi: 0.101, Chhattisgarhi: 24.205, Bengali: 0.241, Bhatri: 1.029, Halbi: 41.791, Oriya: 0.554, Hindi: 130.032	|	Gondi: 0.002, Chhattisgarhi: 0.485, Bengali: 0.005, Bhatri: 0.048, Halbi: 1.93, Oriya: 0.0, Hindi: 6.978	|
|	Begusarai	|	194.28	|	8.32	|	Magahi: 0.082, Bhojpuri: 1.217, Angika: 12.869, Hindi: 131.54, Maithili: 32.628, Telugu: 0.12, Urdu: 15.825	|	Magahi: 0.005, Bhojpuri: 0.071, Angika: 0.86, Hindi: 5.745, Maithili: 1.608, Telugu: 0.0, Urdu: 0.026	|
|	Belgaum	|	195.52	|	11.44	|	Urdu: 0.204, Marathi: 34.809, Hindi: 12.865, Malayalam: 0.273, Kannada: 143.791, Telugu: 3.582	|	Urdu: 0.0, Marathi: 1.695, Hindi: 0.067, Malayalam: 0.0, Kannada: 9.624, Telugu: 0.056	|
|	Bellary	|	210.2	|	10.89	|	Tamil: 0.716, Kannada: 153.043, Hindi: 8.392, English: 0.388, Telugu: 44.414, Urdu: 2.593, Bearybashe: 0.489, Malayalam: 0.165	|	Tamil: 0.002, Kannada: 10.157, Hindi: 0.092, English: 0.0, Telugu: 0.623, Urdu: 0.004, Bearybashe: 0.012, Malayalam: 0.0	|
|	Bhagalpur	|	198.71	|	8.8	|	Urdu: 0.284, Bengali: 0.582, Bhojpuri: 0.157, Magahi: 0.275, Hindi: 141.861, Maithili: 9.685, Telugu: 0.193, Angika: 45.029, Marathi: 0.647	|	Urdu: 0.0, Bengali: 0.009, Bhojpuri: 0.002, Magahi: 0.028, Hindi: 6.713, Maithili: 0.523, Telugu: 0.005, Angika: 1.486, Marathi: 0.03	|
|	Bhopal	|	223.48	|	0	|	English: 0.307, Hindi: 220.142, Sindhi: 2.44, Urdu: 0.592	|	English: 0.0, Hindi: 0.0, Sindhi: 0.0, Urdu: 0.0	|
|	Bidar	|	87.24	|	0.99	|	Kannada: 86.908, Marathi: 0.337	|	Kannada: 0.992, Marathi: 0.0	|
|	Bijapur	|	189.48	|	7.59	|	Hindi: 10.735, English: 0.146, Kannada: 173.44, Urdu: 3.193, Malayalam: 0.283, Bengali: 1.393, Telugu: 0.288	|	Hindi: 0.023, English: 0.0, Kannada: 7.555, Urdu: 0.0, Malayalam: 0.0, Bengali: 0.008, Telugu: 0.0	|
|	Bilaspur	|	205.75	|	10.45	|	Bengali: 0.837, Marathi: 0.567, Maithili: 0.304, Hindi: 191.55, Chhattisgarhi: 12.491	|	Bengali: 0.003, Marathi: 0.048, Maithili: 0.006, Hindi: 9.633, Chhattisgarhi: 0.758	|
|	Budaun	|	202.7	|	11.08	|	Khariboli: 4.662, Bundeli: 2.898, Bengali: 0.248, Hindi: 192.439, Awadhi: 0.331, Urdu: 1.784, Marathi: 0.343	|	Khariboli: 0.402, Bundeli: 0.212, Bengali: 0.0, Hindi: 10.217, Awadhi: 0.018, Urdu: 0.225, Marathi: 0.004	|
|	Chamarajanagar	|	192.3	|	9.15	|	Hindi: 5.65, Malayalam: 0.322, Telugu: 0.213, Tamil: 4.423, Kannada: 181.695	|	Hindi: 0.009, Malayalam: 0.0, Telugu: 0.003, Tamil: 0.295, Kannada: 8.842	|
|	Chandigarh	|	74.53	|	8.9	|	English: 5.087, Hindi: 64.795, Punjabi: 4.653	|	English: 0.0, Hindi: 8.744, Punjabi: 0.154	|
|	Chandrapur	|	186.38	|	9.03	|	Hindi: 80.426, Marathi: 105.643, Malvani: 0.313	|	Hindi: 3.929, Marathi: 5.068, Malvani: 0.03	|
|	Chennai	|	176.97	|	0	|	Tamil: 176.966	|	Tamil: 0.0	|
|	Chittoor	|	200	|	11.02	|	Telugu: 169.261, Hindi: 27.124, Bengali: 1.02, Tamil: 2.476, Santali: 0.116	|	Telugu: 9.8, Hindi: 1.185, Bengali: 0.0, Tamil: 0.033, Santali: 0.0	|
|	Churu	|	194.12	|	11.92	|	Mewati: 0.016, Hindi: 63.517, Harauti: 0.29, Rajasthani: 89.46, Bagri: 0.579, Mewari: 0.318, Marwari: 36.964, Jaipuri: 0.803, Wagdi: 0.366, Bengali: 0.461, Gujarati: 0.238, English: 0.168, Shekhawati: 0.934	|	Mewati: 0.0, Hindi: 3.455, Harauti: 0.022, Rajasthani: 5.237, Bagri: 0.062, Mewari: 0.04, Marwari: 2.91, Jaipuri: 0.074, Wagdi: 0.006, Bengali: 0.022, Gujarati: 0.011, English: 0.0, Shekhawati: 0.084	|
|	CoochBehar	|	153.83	|	0.91	|	Bengali: 153.385, Hindi: 0.448	|	Bengali: 0.913, Hindi: 0.0	|
|	DakshinDinajpur	|	204.4	|	10.27	|	Hindi: 10.241, Bengali: 194.158	|	Hindi: 0.623, Bengali: 9.649	|
|	DakshinaKannada	|	183.52	|	10.2	|	Bearybashe: 6.472, Malayalam: 0.475, Telugu: 0.212, Tulu: 39.943, Urdu: 6.674, Hindi: 13.423, Kannada: 116.32	|	Bearybashe: 0.162, Malayalam: 0.0, Telugu: 0.0, Tulu: 3.093, Urdu: 0.029, Hindi: 0.06, Kannada: 6.855	|
|	Darbhanga	|	199.18	|	8.91	|	Marathi: 0.301, Hindi: 176.606, Maithili: 20.816, Kannada: 0.147, Urdu: 1.314	|	Marathi: 0.018, Hindi: 7.87, Maithili: 1.015, Kannada: 0.002, Urdu: 0.0	|
|	Darjeeling	|	180.57	|	0.75	|	Bengali: 5.115, English: 1.843, Hindi: 1.417, Nepali: 172.197	|	Bengali: 0.482, English: 0.0, Hindi: 0.0, Nepali: 0.268	|
|	Deoghar	|	186.1	|	9.87	|	English: 0.919, Hindi: 178.241, Khorth: 3.001, KhorthKhotta: 3.943	|	English: 0.0, Hindi: 9.415, Khorth: 0.165, KhorthKhotta: 0.292	|
|	Deoria	|	192.71	|	8.87	|	Marathi: 0.356, Hindi: 102.05, Bhojpuri: 89.671, Awadhi: 0.112, Maithili: 0.294, Khariboli: 0.228	|	Marathi: 0.017, Hindi: 4.359, Bhojpuri: 4.436, Awadhi: 0.001, Maithili: 0.028, Khariboli: 0.026	|
|	Dhalai	|	163.78	|	0	|	Bengali: 5.853, Chakma: 151.793, Hindi: 0.711, Kokborok: 5.424	|	Bengali: 0.0, Chakma: 0.0, Hindi: 0.0, Kokborok: 0.0	|
|	Dhar	|	56.32	|	0	|	Bhili: 0.256, Hindi: 34.099, Malvi: 1.817, Nimadi: 20.152	|	Bhili: 0.0, Hindi: 0.0, Malvi: 0.0, Nimadi: 0.0	|
|	Dharwad	|	198.74	|	9.9	|	Telugu: 9.98, Bhojpuri: 0.291, Kannada: 178.79, Malayalam: 0.279, Urdu: 0.453, Hindi: 8.95	|	Telugu: 0.16, Bhojpuri: 0.0, Kannada: 9.731, Malayalam: 0.0, Urdu: 0.0, Hindi: 0.011	|
|	Dhule	|	193.87	|	11.79	|	Hindi: 52.372, Marathi: 132.888, Bhili: 2.879, Khandeshi: 5.731	|	Hindi: 3.036, Marathi: 8.598, Bhili: 0.157, Khandeshi: 0.0	|
|	Dimapur	|	103.96	|	0	|	Ao: 0.428, Chakhesang: 0.569, English: 42.215, Hindi: 0.745, Lotha: 0.133, Nagamese: 58.608, Sangtam: 0.451, Sumi: 0.644, Tenyidie: 0.169	|	Ao: 0.0, Chakhesang: 0.0, English: 0.0, Hindi: 0.0, Lotha: 0.0, Nagamese: 0.0, Sangtam: 0.0, Sumi: 0.0, Tenyidie: 0.0	|
|	EastChamparan	|	212.87	|	8.74	|	Bhojpuri: 39.012, Bengali: 1.15, Marathi: 0.708, Hindi: 168.973, Urdu: 0.539, Maithili: 2.491	|	Bhojpuri: 1.587, Bengali: 0.012, Marathi: 0.018, Hindi: 7.003, Urdu: 0.0, Maithili: 0.118	|
|	Etah	|	197.21	|	10.9	|	Khariboli: 2.844, English: 0.088, Marathi: 0.442, Hindi: 193.835	|	Khariboli: 0.227, English: 0.0, Marathi: 0.0, Hindi: 10.678	|
|	Garhwa	|	223.79	|	0.8	|	English: 2.449, Hindi: 220.598, Magadhi: 0.533, Sadri: 0.213	|	English: 0.0, Hindi: 0.799, Magadhi: 0.0, Sadri: 0.0	|
|	Gaya	|	227.33	|	9.18	|	Bhojpuri: 0.343, Hindi: 187.242, Magahi: 35.393, Bengali: 0.126, Maithili: 3.048, Marwari: 0.039, Marathi: 1.142	|	Bhojpuri: 0.008, Hindi: 6.812, Magahi: 2.195, Bengali: 0.002, Maithili: 0.119, Marwari: 0.004, Marathi: 0.039	|
|	Ghazipur	|	189.85	|	7.91	|	Hindi: 112.38, Khariboli: 0.36, Tamil: 0.286, Awadhi: 0.34, Marathi: 0.473, Urdu: 0.284, Bhojpuri: 75.199, Chhattisgarhi: 0.271, Bengali: 0.254	|	Hindi: 4.436, Khariboli: 0.024, Tamil: 0.0, Awadhi: 0.003, Marathi: 0.015, Urdu: 0.0, Bhojpuri: 3.419, Chhattisgarhi: 0.01, Bengali: 0.0	|
|	Gopalganj	|	230.4	|	9.5	|	Marathi: 0.46, Maithili: 2.226, Bhojpuri: 35.267, Hindi: 192.245, Bengali: 0.201	|	Marathi: 0.004, Maithili: 0.078, Bhojpuri: 1.924, Hindi: 7.481, Bengali: 0.009	|
|	Gorakhpur	|	194.71	|	7.86	|	Khariboli: 0.829, Hindi: 118.869, Marathi: 1.061, Bhojpuri: 73.951	|	Khariboli: 0.058, Hindi: 4.052, Marathi: 0.013, Bhojpuri: 3.734	|
|	Gulbarga	|	183.49	|	5.29	|	Kannada: 130.248, Telugu: 15.542, Urdu: 20.037, Malayalam: 0.237, Hindi: 17.424	|	Kannada: 5.061, Telugu: 0.156, Urdu: 0.0, Malayalam: 0.008, Hindi: 0.061	|
|	Guntur	|	217.53	|	11.66	|	English: 0.074, Telugu: 188.831, Urdu: 9.723, Bengali: 0.532, Tamil: 0.394, Marathi: 0.851, Hindi: 17.125	|	English: 0.0, Telugu: 10.754, Urdu: 0.0, Bengali: 0.003, Tamil: 0.008, Marathi: 0.017, Hindi: 0.881	|
|	Hamirpur	|	206.96	|	11.19	|	Bundeli: 3.65, Hindi: 200.863, Urdu: 0.049, Bengali: 0.187, Awadhi: 0.059, Marathi: 0.586, Khariboli: 1.567	|	Bundeli: 0.284, Hindi: 10.831, Urdu: 0.0, Bengali: 0.0, Awadhi: 0.003, Marathi: 0.01, Khariboli: 0.062	|
|	Hyderabad	|	125.77	|	0.75	|	English: 2.874, Hindi: 4.137, Telugu: 118.764	|	English: 0.0, Hindi: 0.0, Telugu: 0.752	|
|	Jahanabad	|	202.44	|	8.96	|	Bengali: 0.651, Magahi: 12.912, Marathi: 0.77, Urdu: 0.761, Maithili: 2.89, Hindi: 184.454	|	Bengali: 0.004, Magahi: 0.337, Marathi: 0.015, Urdu: 0.0, Maithili: 0.074, Hindi: 8.53	|
|	Jaipur	|	223.06	|	0	|	English: 3.126, Hindi: 205.918, Marwadi: 2.497, Marwari: 10.109, Punjabi: 0.193, Rajasthani: 1.219	|	English: 0.0, Hindi: 0.0, Marwadi: 0.0, Marwari: 0.0, Punjabi: 0.0, Rajasthani: 0.0	|
|	Jalaun	|	227.16	|	11.3	|	Marathi: 0.619, Khariboli: 1.122, Awadhi: 0.179, Hindi: 222.448, Gujarati: 0.094, Assamese: 0.233, Bundeli: 2.468	|	Marathi: 0.005, Khariboli: 0.096, Awadhi: 0.002, Hindi: 10.971, Gujarati: 0.0, Assamese: 0.0, Bundeli: 0.222	|
|	Jalpaiguri	|	198.96	|	8.49	|	Hindi: 7.207, Bengali: 190.021, Sadri: 0.585, Marathi: 1.149	|	Hindi: 0.268, Bengali: 8.16, Sadri: 0.0, Marathi: 0.066	|
|	Jamtara	|	210.66	|	13.84	|	Marathi: 0.572, Bengali: 21.924, Hindi: 165.005, Khortha: 22.436, Bhojpuri: 0.26, Maithili: 0.458	|	Marathi: 0.038, Bengali: 2.232, Hindi: 10.023, Khortha: 1.493, Bhojpuri: 0.022, Maithili: 0.036	|
|	Jamui	|	209.32	|	9.36	|	Magahi: 6.467, Hindi: 186.895, Maithili: 4.571, Tamil: 0.155, Angika: 10.953, Bengali: 0.275	|	Magahi: 0.398, Hindi: 8.748, Maithili: 0.121, Tamil: 0.0, Angika: 0.088, Bengali: 0.0	|
|	Jashpur	|	183.39	|	7.21	|	Agariya: 0.063, Hindi: 94.596, Kurukh: 7.439, Chhattisgarhi: 55.097, Bengali: 0.428, Sadri: 25.616, Oriya: 0.149	|	Agariya: 0.0, Hindi: 2.904, Kurukh: 0.219, Chhattisgarhi: 3.227, Bengali: 0.005, Sadri: 0.853, Oriya: 0.0	|
|	Jhargram	|	182.4	|	8.62	|	Marathi: 0.653, Bengali: 177.872, Hindi: 3.611, Bhojpuri: 0.261	|	Marathi: 0.019, Bengali: 8.484, Hindi: 0.113, Bhojpuri: 0.006	|
|	JyotibaPhuleNagar	|	195.24	|	10.73	|	Hindi: 191.227, Urdu: 1.447, Khariboli: 1.813, Marathi: 0.623, English: 0.126	|	Hindi: 10.421, Urdu: 0.117, Khariboli: 0.172, Marathi: 0.023, English: 0.0	|
|	Kabirdham	|	199.59	|	8.33	|	Maithili: 0.257, Hindi: 174.052, Marathi: 0.185, Chhattisgarhi: 25.098	|	Maithili: 0.018, Hindi: 7.104, Marathi: 0.003, Chhattisgarhi: 1.205	|
|	Kaimur	|	63.91	|	0	|	Bengali: 0.201, Bhojpuri: 2.209, Bihari: 0.197, English: 0.734, Hindi: 60.306, Urdu: 0.263	|	Bengali: 0.0, Bhojpuri: 0.0, Bihari: 0.0, English: 0.0, Hindi: 0.0, Urdu: 0.0	|
|	KamrupMetropolitan	|	163.97	|	5.75	|	Assamese: 90.522, Bengali: 4.282, English: 34.888, Hindi: 34.281	|	Assamese: 3.802, Bengali: 0.0, English: 0.871, Hindi: 1.077	|
|	Kanyakumari	|	174.44	|	0	|	English: 0.41, Tamil: 174.031	|	English: 0.0, Tamil: 0.0	|
|	Karimnagar	|	224.51	|	7.42	|	Hindi: 6.151, Urdu: 1.999, Bengali: 0.526, English: 0.683, Telugu: 215.153	|	Hindi: 0.065, Urdu: 0.0, Bengali: 0.0, English: 0.006, Telugu: 7.353	|
|	Katihar	|	118.84	|	0	|	Angika: 9.34, Bengali: 26.906, Bhojpuri: 1.494, Bihari: 0.453, English: 0.715, Hindi: 75.799, Maithili: 2.483, Thethi: 0.268, Urdu: 1.377	|	Angika: 0.0, Bengali: 0.0, Bhojpuri: 0.0, Bihari: 0.0, English: 0.0, Hindi: 0.0, Maithili: 0.0, Thethi: 0.0, Urdu: 0.0	|
|	Katni	|	51.17	|	0	|	Bagheli: 0.06, Hindi: 51.106	|	Bagheli: 0.0, Hindi: 0.0	|
|	Khordha	|	90.73	|	7.09	|	Bengali: 4.075, English: 0.206, Hindi: 21.856, Odia: 64.24, Telugu: 0.348	|	Bengali: 0.263, English: 0.014, Hindi: 5.093, Odia: 1.72, Telugu: 0.0	|
|	Kishanganj	|	202.5	|	8.54	|	Hindi: 165.249, Urdu: 3.238, Magahi: 0.242, Maithili: 4.121, Bengali: 3.529, Marathi: 0.199, Surjapuri: 25.919	|	Hindi: 7.779, Urdu: 0.24, Magahi: 0.0, Maithili: 0.208, Bengali: 0.05, Marathi: 0.008, Surjapuri: 0.255	|
|	Kohima	|	63.33	|	0	|	Angami: 9.912, Ao: 0.153, Chakhesang: 0.733, English: 6.571, Lotha: 25.299, Nagamese: 19.319, Rengma: 0.579, Sangtam: 0.24, Sumi: 0.525	|	Angami: 0.0, Ao: 0.0, Chakhesang: 0.0, English: 0.0, Lotha: 0.0, Nagamese: 0.0, Rengma: 0.0, Sangtam: 0.0, Sumi: 0.0	|
|	Kolkata	|	211.86	|	12.22	|	Bengali: 201.036, Hindi: 10.829	|	Bengali: 11.8, Hindi: 0.421	|
|	Koppal	|	57.28	|	0.99	|	Hindi: 1.562, Kannada: 55.717	|	Hindi: 0.0, Kannada: 0.987	|
|	Korba	|	195.08	|	8.44	|	Chhattisgarhi: 32.501, Hindi: 162.584	|	Chhattisgarhi: 1.552, Hindi: 6.884	|
|	Krishna	|	176.9	|	10.16	|	Marathi: 0.18, Hindi: 19.702, English: 0.296, Telugu: 155.909, Bengali: 0.297, Tamil: 0.515	|	Marathi: 0.0, Hindi: 0.553, English: 0.0, Telugu: 9.587, Bengali: 0.0, Tamil: 0.024	|
|	Lakhisarai	|	193.66	|	8.59	|	Telugu: 0.117, Konkani: 0.245, Magahi: 28.746, Maithili: 3.331, Hindi: 159.678, Bhojpuri: 1.157, Marathi: 0.383	|	Telugu: 0.002, Konkani: 0.019, Magahi: 1.358, Maithili: 0.131, Hindi: 7.027, Bhojpuri: 0.051, Marathi: 0.005	|
|	Lalitpur	|	116.85	|	0	|	Bundeli: 0.873, Hindi: 115.975	|	Bundeli: 0.0, Hindi: 0.0	|
|	Longding	|	179.58	|	0	|	English: 3.145, Hindi: 69.786, Wancho: 106.65	|	English: 0.0, Hindi: 0.0, Wancho: 0.0	|
|	Lucknow	|	124.53	|	0	|	English: 0.897, Hindi: 115.908, Urdu: 7.724	|	English: 0.0, Hindi: 0.0, Urdu: 0.0	|
|	Madhepura	|	194.33	|	7.45	|	Khortha: 0.239, Maithili: 77.053, Angika: 3.113, Marathi: 0.187, Telugu: 0.176, Magahi: 0.24, Hindi: 112.652, Bengali: 0.673	|	Khortha: 0.01, Maithili: 2.201, Angika: 0.235, Marathi: 0.014, Telugu: 0.001, Magahi: 0.019, Hindi: 4.966, Bengali: 0.002	|
|	Mahabubabad	|	50.3	|	0	|	Telugu: 50.296	|	Telugu: 0.0	|
|	Malda	|	207.15	|	10.51	|	Marathi: 0.193, Hindi: 7.75, Bengali: 199.205	|	Marathi: 0.019, Hindi: 0.285, Bengali: 10.203	|
|	Muzaffarnagar	|	198.96	|	11.29	|	Kannada: 0.229, Hindi: 193.405, Awadhi: 0.128, Marathi: 1.12, Khariboli: 3.668, Urdu: 0.411	|	Kannada: 0.003, Hindi: 10.933, Awadhi: 0.0, Marathi: 0.029, Khariboli: 0.301, Urdu: 0.024	|
|	Muzaffarpur	|	197.23	|	9.91	|	Angika: 0.143, Bhojpuri: 28.504, Bajjika: 12.282, Hindi: 146.714, Kurmali: 0.99, Maithili: 8.447, Bengali: 0.147	|	Angika: 0.01, Bhojpuri: 2.388, Bajjika: 0.029, Hindi: 7.07, Kurmali: 0.021, Maithili: 0.386, Bengali: 0.003	|
|	Mysore	|	206.77	|	11.34	|	Lambani: 0.226, Tamil: 0.068, Hindi: 12.808, Malayalam: 0.215, Telugu: 0.243, Kannada: 188.37, Bengali: 0.498, Urdu: 4.342	|	Lambani: 0.0, Tamil: 0.0, Hindi: 0.018, Malayalam: 0.0, Telugu: 0.0, Kannada: 11.286, Bengali: 0.035, Urdu: 0.0	|
|	Nagaur	|	196.47	|	12.39	|	Hindi: 57.511, Rajasthani: 71.975, Jaipuri: 1.44, Mewari: 0.288, Marwari: 64.981, Marathi: 0.063, Bengali: 0.217	|	Hindi: 2.728, Rajasthani: 4.421, Jaipuri: 0.117, Mewari: 0.04, Marwari: 5.079, Marathi: 0.005, Bengali: 0.0	|
|	Nagpur	|	193.55	|	11.25	|	Chhattisgarhi: 0.193, Hindi: 84.323, Malvani: 0.291, Gujarati: 0.123, Marathi: 108.616	|	Chhattisgarhi: 0.017, Hindi: 4.731, Malvani: 0.029, Gujarati: 0.001, Marathi: 6.474	|
|	Nalgonda	|	216.38	|	7.52	|	Malayalam: 0.172, Bengali: 0.245, Lambani: 0.442, Hindi: 6.183, Telugu: 209.335	|	Malayalam: 0.0, Bengali: 0.003, Lambani: 0.0, Hindi: 0.069, Telugu: 7.446	|
|	Namakkal	|	198.88	|	0	|	Tamil: 198.884	|	Tamil: 0.0	|
|	NewDelhi	|	206.72	|	3.08	|	Bengali: 0.22, English: 0.872, Hindi: 203.019, Odia: 0.481, Punjabi: 2.129	|	Bengali: 0.0, English: 0.0, Hindi: 2.87, Odia: 0.0, Punjabi: 0.212	|
|	Nilgiris	|	86.38	|	0	|	English: 0.387, Tamil: 85.997	|	English: 0.0, Tamil: 0.0	|
|	North24Parganas	|	214	|	12.1	|	Bengali: 210.305, Hindi: 3.5, Marathi: 0.193	|	Bengali: 11.96, Hindi: 0.127, Marathi: 0.012	|
|	NorthSouthGoa	|	189.71	|	9.57	|	English: 0.113, Hindi: 97.382, Kannada: 0.316, Gujarati: 0.245, Bengali: 0.601, Konkani: 68.399, Marathi: 22.651	|	English: 0.0, Hindi: 5.344, Kannada: 0.0, Gujarati: 0.0, Bengali: 0.032, Konkani: 3.323, Marathi: 0.872	|
|	Palamu	|	171.32	|	0.78	|	Bhojpuri: 3.877, Hindi: 157.621, KhorthKhotta: 0.231, Magadhi: 6.364, MagadhiMagahi: 0.442, Magahi: 2.788	|	Bhojpuri: 0.269, Hindi: 0.222, KhorthKhotta: 0.018, Magadhi: 0.0, MagadhiMagahi: 0.036, Magahi: 0.237	|
|	PapumPare	|	197.17	|	0	|	English: 5.525, Galo: 0.32, Hindi: 183.736, NissiDafla: 0.344, Nyishi: 4.777, Tagin: 1.991, Wancho: 0.474	|	English: 0.0, Galo: 0.0, Hindi: 0.0, NissiDafla: 0.0, Nyishi: 0.0, Tagin: 0.0, Wancho: 0.0	|
|	PaschimMedinipur	|	199.81	|	8.51	|	Bengali: 197.688, Hindi: 2.122	|	Bengali: 8.43, Hindi: 0.079	|
|	Patna	|	171.24	|	0	|	Bajjika: 0.046, Bhojpuri: 1.639, Bihari: 0.084, English: 0.895, Hindi: 165.202, Magahi: 2.152, Maithili: 0.692, Meitei: 0.528	|	Bajjika: 0.0, Bhojpuri: 0.0, Bihari: 0.0, English: 0.0, Hindi: 0.0, Magahi: 0.0, Maithili: 0.0, Meitei: 0.0	|
|	Pune	|	201.09	|	13.73	|	Marathi: 163.223, Urdu: 0.049, Maithili: 0.502, Hindi: 37.32	|	Marathi: 10.689, Urdu: 0.0, Maithili: 0.01, Hindi: 3.036	|
|	Purnia	|	205.61	|	9.61	|	Chhattisgarhi: 0.065, Hindi: 175.595, Urdu: 0.496, Maithili: 19.789, Angika: 9.669	|	Chhattisgarhi: 0.005, Hindi: 8.565, Urdu: 0.0, Maithili: 0.852, Angika: 0.191	|
|	Purulia	|	198.46	|	9.39	|	Bengali: 178.953, Hindi: 19.097, Rajbanshi: 0.191, Santali: 0.223	|	Bengali: 8.674, Hindi: 0.716, Rajbanshi: 0.003, Santali: 0.0	|
|	Raichur	|	195.09	|	10.18	|	Urdu: 1.804, Kannada: 162.703, Bhojpuri: 0.277, Telugu: 21.205, Hindi: 8.855, Malayalam: 0.241	|	Urdu: 0.0, Kannada: 10.042, Bhojpuri: 0.0, Telugu: 0.074, Hindi: 0.068, Malayalam: 0.0	|
|	Raigarh	|	187.36	|	10.06	|	Chhattisgarhi: 29.899, Hindi: 156.895, Oriya: 0.565	|	Chhattisgarhi: 2.527, Hindi: 7.529, Oriya: 0.0	|
|	Rajnandgaon	|	188.13	|	7.96	|	English: 0.099, Hindi: 113.163, Marathi: 0.252, Bengali: 0.272, Kannada: 0.131, Chhattisgarhi: 74.216	|	English: 0.0, Hindi: 4.159, Marathi: 0.008, Bengali: 0.003, Kannada: 0.0, Chhattisgarhi: 3.791	|
|	Ranchi	|	245.01	|	1.16	|	Bengali: 0.196, Bhojpuri: 0.117, Hindi: 244.692	|	Bengali: 0.02, Bhojpuri: 0.014, Hindi: 1.126	|
|	Saharanpur	|	127.82	|	0	|	Hindi: 127.821	|	Hindi: 0.0	|
|	Saharsa	|	189.89	|	8.67	|	Kannada: 0.243, Magahi: 0.269, Hindi: 129.425, Maithili: 37.877, Bengali: 0.135, Angika: 2.03, Urdu: 19.717, Chhattisgarhi: 0.193	|	Kannada: 0.002, Magahi: 0.002, Hindi: 5.996, Maithili: 2.204, Bengali: 0.003, Angika: 0.11, Urdu: 0.339, Chhattisgarhi: 0.01	|
|	Sahebganj	|	195.65	|	9.09	|	Angika: 0.769, Bhojpuri: 1.171, Kurmali: 0.157, Magahi: 0.489, Bengali: 20.25, Hindi: 162.87, Khortha: 3.524, English: 0.046, Chhattisgarhi: 0.14, Marathi: 0.55, Santali: 5.687	|	Angika: 0.049, Bhojpuri: 0.104, Kurmali: 0.013, Magahi: 0.041, Bengali: 1.108, Hindi: 7.427, Khortha: 0.234, English: 0.0, Chhattisgarhi: 0.0, Marathi: 0.031, Santali: 0.086	|
|	Samastipur	|	221.85	|	10.59	|	Angika: 2.87, Magahi: 15.456, Bhojpuri: 0.832, Bajjika: 0.116, Urdu: 0.205, Maithili: 91.061, Hindi: 111.313	|	Angika: 0.207, Magahi: 1.17, Bhojpuri: 0.057, Bajjika: 0.013, Urdu: 0.0, Maithili: 5.34, Hindi: 3.8	|
|	Saran	|	228.76	|	11.2	|	Bhojpuri: 61.655, Maithili: 3.343, Hindi: 162.94, Marathi: 0.823	|	Bhojpuri: 2.618, Maithili: 0.104, Hindi: 8.416, Marathi: 0.058	|
|	Sarguja	|	180.2	|	7.52	|	Surgujia: 16.684, Bengali: 0.247, Chhattisgarhi: 58.539, Kurukh: 3.961, Hindi: 100.768	|	Surgujia: 0.637, Bengali: 0.003, Chhattisgarhi: 2.877, Kurukh: 0.0, Hindi: 4.005	|
|	Shimoga	|	196.35	|	10.01	|	Urdu: 1.118, Hindi: 5.931, Telugu: 0.153, Bengali: 0.054, Tamil: 0.302, Malayalam: 0.262, Kannada: 188.526	|	Urdu: 0.0, Hindi: 0.014, Telugu: 0.003, Bengali: 0.0, Tamil: 0.0, Malayalam: 0.0, Kannada: 9.994	|
|	Sindhudurg	|	185.83	|	11.35	|	Malvani: 14.973, Hindi: 48.225, Marathi: 122.63	|	Malvani: 0.992, Hindi: 2.595, Marathi: 7.767	|
|	Sitamarhi	|	220.75	|	10.15	|	Tamil: 0.182, Bajjika: 1.145, Hindi: 208.209, Angika: 0.405, Bengali: 0.016, Urdu: 3.936, Maithili: 4.256, Khortha: 0.391, Sadri: 0.284, Bhojpuri: 1.928	|	Tamil: 0.0, Bajjika: 0.086, Hindi: 9.752, Angika: 0.004, Bengali: 0.0, Urdu: 0.0, Maithili: 0.187, Khortha: 0.0, Sadri: 0.0, Bhojpuri: 0.124	|
|	Solapur	|	208.04	|	9.95	|	Maithili: 0.156, Hindi: 49.983, Bengali: 0.19, Marathi: 157.331, Kannada: 0.248, Malvani: 0.133	|	Maithili: 0.012, Hindi: 3.121, Bengali: 0.0, Marathi: 6.811, Kannada: 0.0, Malvani: 0.006	|
|	Sonitpur	|	140.61	|	0	|	Assamese: 132.962, Bengali: 0.559, English: 1.596, Hindi: 5.049, Odia: 0.218, Sadri: 0.221	|	Assamese: 0.0, Bengali: 0.0, English: 0.0, Hindi: 0.0, Odia: 0.0, Sadri: 0.0	|
|	Srikakulam	|	233.85	|	11.35	|	Telugu: 221.554, Marathi: 0.173, Bhojpuri: 0.219, Kannada: 0.293, Hindi: 11.606	|	Telugu: 11.197, Marathi: 0.0, Bhojpuri: 0.0, Kannada: 0.0, Hindi: 0.148	|
|	Sukma	|	135.94	|	7.73	|	Gondi: 3.495, Dorli: 1.363, Oriya: 0.478, Duruwa: 0.521, Chhattisgarhi: 32.299, Hindi: 97.468, Bengali: 0.311	|	Gondi: 0.438, Dorli: 0.0, Oriya: 0.0, Duruwa: 0.0, Chhattisgarhi: 0.598, Hindi: 6.678, Bengali: 0.014	|
|	Supaul	|	186.73	|	8.84	|	Angika: 1.932, Urdu: 0.281, Hindi: 111.46, Bhojpuri: 1.498, Maithili: 71.558	|	Angika: 0.155, Urdu: 0.0, Hindi: 5.495, Bhojpuri: 0.075, Maithili: 3.119	|
|	TehriGarhwal	|	207.47	|	11.95	|	Garhwali: 49.979, Bengali: 0.559, Kumaoni: 12.974, Hindi: 143.682, Marathi: 0.277	|	Garhwali: 4.667, Bengali: 0.006, Kumaoni: 1.056, Hindi: 6.208, Marathi: 0.01	|
|	Unakoti	|	156.12	|	0.9	|	Bengali: 14.832, Chakma: 138.336, Hindi: 2.364, Kokborok: 0.59	|	Bengali: 0.0, Chakma: 0.902, Hindi: 0.0, Kokborok: 0.0	|
|	Uttarkashi	|	196.15	|	9.43	|	Marathi: 0.365, Garhwali: 85.368, Hindi: 95.773, Bengali: 0.261, Kumaoni: 13.735, Maithili: 0.647	|	Marathi: 0.01, Garhwali: 2.573, Hindi: 5.656, Bengali: 0.0, Kumaoni: 1.155, Maithili: 0.035	|
|	Vaishali	|	201.36	|	11.3	|	Bajjika: 58.804, Bhojpuri: 1.484, Nepali: 0.182, Bengali: 0.226, Maithili: 13.264, Marathi: 0.393, Hindi: 127.011	|	Bajjika: 3.382, Bhojpuri: 0.07, Nepali: 0.004, Bengali: 0.004, Maithili: 0.575, Marathi: 0.013, Hindi: 7.251	|
|	Varanasi	|	192.1	|	8.38	|	Khariboli: 0.632, Hindi: 163.8, Bhojpuri: 25.842, Awadhi: 0.948, Marathi: 0.649, Bengali: 0.232	|	Khariboli: 0.026, Hindi: 7.1, Bhojpuri: 1.187, Awadhi: 0.058, Marathi: 0.012, Bengali: 0.0	|
|	Vishakapattanam	|	176.95	|	11.59	|	Bengali: 0.278, Kannada: 0.28, Marathi: 0.314, Telugu: 164.229, Maithili: 0.101, Tamil: 0.28, Hindi: 11.466	|	Bengali: 0.0, Kannada: 0.0, Marathi: 0.0, Telugu: 11.141, Maithili: 0.004, Tamil: 0.0, Hindi: 0.444	|
|	WestChamparan	|	130.4	|	0	|	Bengali: 0.506, Bhojpuri: 7.365, Hindi: 122.361, Urdu: 0.165	|	Bengali: 0.0, Bhojpuri: 0.0, Hindi: 0.0, Urdu: 0.0	|
|	WestGaroHills	|	86.62	|	1.42	|	Bengali: 0.819, Garo: 85.414, Hajong: 0.169, Hindi: 0.218	|	Bengali: 0.0, Garo: 1.416, Hajong: 0.0, Hindi: 0.0	|
|	WestTripura	|	175.24	|	0.95	|	Bengali: 84.824, Chakma: 59.735, English: 0.185, Hindi: 5.612, Kokborok: 24.88	|	Bengali: 0.903, Chakma: 0.0, English: 0.0, Hindi: 0.046, Kokborok: 0.0	|
This table represents the audio and transcription duration data for various languages.

|                      |   Agariya |   Angami |    Angika |       Ao |   Assamese |   Awadhi |   Bagheli |    Bagri |   Bajjika |   Bearybashe |   Bengali |    Bhatri |    Bhili |   Bhojpuri |   Bihari |   Bundeli |   Chakhesang |     Chakma |   Chhattisgarhi |   Dorli |   Duruwa |   English |     Galo |   Garhwali |     Garo |    Gondi |   Gujarati |   Hajong |    Halbi |   Harauti |     Hindi |   Jaipuri |   Kannada |   Khandeshi |   Khariboli |   Khorth |   KhorthKhotta |   Khortha |   Kokborok |   Konkani |   Kumaoni |   Kurmali |    Kurukh |   Lambani |   Lotha |   Magadhi |   MagadhiMagahi |   Magahi |   Maithili |   Malayalam |   Malvani |   Malvi |   Marathi |   Marwadi |   Marwari |   Meitei |   Mewari |    Mewati |   Nagamese |     Nepali |   Nimadi |   NissiDafla |   Nyishi |     Odia |   Oriya |   Punjabi |   Rajasthani |   Rajbanshi |   Rengma |     Sadri |   Sangtam |   Santali |   Shekhawati |   Sindhi |    Sumi |   Surgujia |   Surjapuri |   Tagin |      Tamil |    Telugu |   Tenyidie |   Thethi |     Tulu |      Urdu |      Wagdi |   Wancho |
|:---------------------|----------:|---------:|----------:|---------:|-----------:|---------:|----------:|---------:|----------:|-------------:|----------:|----------:|---------:|-----------:|---------:|----------:|-------------:|-----------:|----------------:|--------:|---------:|----------:|---------:|-----------:|---------:|---------:|-----------:|---------:|---------:|----------:|----------:|----------:|----------:|------------:|------------:|---------:|---------------:|----------:|-----------:|----------:|----------:|----------:|----------:|----------:|--------:|----------:|----------------:|---------:|-----------:|------------:|----------:|--------:|----------:|----------:|----------:|---------:|---------:|----------:|-----------:|-----------:|---------:|-------------:|---------:|---------:|--------:|----------:|-------------:|------------:|---------:|----------:|----------:|----------:|-------------:|---------:|--------:|-----------:|------------:|--------:|-----------:|----------:|-----------:|---------:|---------:|----------:|-----------:|---------:|
| Audio Duration(Hrs)  | 0.0632631 |  9.91177 | 100.801   | 0.580526 |  223.717   | 7.84972  | 0.0599206 | 0.579031 |  72.3937  |     6.96098  | 2000.65   | 1.02858   | 3.13479  |   457.114  | 0.734553 |  9.88964  |      1.30256 | 349.864    |        353.503  | 1.36326 | 0.520801 | 127.037   | 0.320421 |  135.346   | 85.4139  | 3.59611  |  0.699285  | 0.168772 | 41.7908  | 0.290435  | 10490.5   |  2.24244  | 1836.36   |     5.73109 |    17.7265  | 3.0005   |       4.17482  |  26.5895  |    30.8947 |  68.6433  |  26.7085  | 1.14692   | 11.3993   |  0.667256 | 25.4321 |   6.89658 |       0.441788  | 105.509  |   441.082  |  2.92524    |  15.7096  | 1.81661 |  974.482  |   2.49738 |  112.094  | 0.527946 | 0.606216 | 0.0161572 |    77.9269 | 183.944    |  20.1516 |     0.343717 |  4.77721 | 64.9398  | 1.74602 |  9.41893  |    162.654   |  0.190988   | 0.578643 | 26.9195   |  0.691031 | 6.02665   |    0.934412  |  2.44002 | 1.33736 |  16.6838   |   25.9191   | 1.99106 | 648.812    | 1751.76   |   0.168767 | 0.268268 | 39.9432  | 123.584   | 0.365609   |  107.124 |
| Trans. Duration(Hrs) | 0         |  0       |   3.52681 | 0        |    3.80238 | 0.244665 | 0         | 0.061615 |   3.50942 |     0.174416 |   84.4453 | 0.0479003 | 0.156969 |    22.1717 | 0        |  0.717375 |      0       |   0.901616 |         17.6133 | 0       | 0        |   1.02836 | 0        |    7.24027 |  1.41562 | 0.440207 |  0.0119822 | 0        |  1.92977 | 0.0224436 |   398.197 |  0.190742 |   91.7418 |     0       |     1.39322 | 0.165307 |       0.309778 |   1.73785 |     0      |   3.34215 |   2.21032 | 0.0339622 |  0.218693 |  0        |  0      |   0       |       0.0364511 |   5.7921 |    19.6667 |  0.00796611 |   1.05753 | 0       |   54.7292 |   0       |    7.9934 | 0        | 0.079755 | 0         |     0      |   0.271122 |   0      |     0        |  0       |  1.72007 | 0       |  0.365897 |      9.65789 |  0.00281361 | 0        |  0.852675 |  0        | 0.0864886 |    0.0840644 |  0       | 0       |   0.637492 |    0.254763 | 0       |   0.420592 |   77.4588 |   0        | 0        |  3.09287 |   1.54629 | 0.00551278 |    0     |

To learn more about the project, please click [here](https://vaani.iisc.ac.in/)

# How to use the data 
You can load the dataset using the load_dataset function from the datasets library. When loading the dataset, you can specify which subset (formatted as {State}_{District}) you would like to access. Please refer to the dataset card to explore the available subsets. Additionally, you will need to use an access token, which you can obtain [here](https://huggingface.co/settings/tokens), to access the dataset.
```pyhton
from datasets import load_dataset
dataset_subset = load_dataset("ARTPARK-IISc/VAANI", "Goa_NorthSouthGoa",token=<access_token>)
```
To download associated images 
```pyhton
from datasets import load_dataset
dataset_subset = load_dataset("ARTPARK-IISc/VAANI", "images",token=<access_token>)
```
# Citation

If you use this data, please cite the following:
```
@misc{vaani2025,
  author       = {VAANI Team},
  title        = {VAANI: Capturing the Language Landscape for an Inclusive Digital India (Phase 1)},
  howpublished = {\url{https://vaani.iisc.ac.in/}},
  year         = {2025}
}
```
# Contact Us
We are eager to hear your feedback about the dataset and are open to new ideas for collaborations as well.
Feel free to reach out to us at vaanicontact@gmail.com
