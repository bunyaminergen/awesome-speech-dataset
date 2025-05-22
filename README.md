<div align="center">

# Awesome Speech Dataset

*This repository provides information and resources related to open source speech datasets. These datasets provide
diverse and high-quality speech data covering various domains such as conversational, academic, political, and more.
They are widely used for tasks like automatic speech recognition (ASR), speaker identification, emotion recognition, and
other speech processing applications.*

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

</div>

---

## Table of Contents

- [Overview Table of Datasets](#overview-tables-of-datasets)
    - [Datasets between 2023-25](#datasets-between-2023-25)
    - [Datasets between 2020-23](#datasets-between-2020-23)
    - [Timeless](#timeless)
    - [Unlisted](#unlisted)
- [Hub / Database / Library](#hub--database--library)
    - [Open Source](#open-source)
    - [Closed Source](#closed-source)
    - [Contain Both Open and Closed Sources](#contain-both-open-and-closed-sources)

---

## Overview Tables of Datasets

### Datasets between 2023-25

| Index | Dataset      | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                     | Multilingual | Source                     | Version | Paper                                                                           | Interspeech | Description                                                                                                                                                                                                                                                                                                                  |
|-------|--------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|--------------------------------------------------------------|--------------|----------------------------|---------|---------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Common Voice | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [Common Voice](https://commonvoice.mozilla.org/en/datasets)  | True         | Mozilla Foundation         | 21      |                                                                                 |             | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed).                                                                                                                                                                                                                    |
| 2     | nEMO         | True                               |                     | True                |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [amu-cai/nEMO](https://huggingface.co/datasets/amu-cai/nEMO) |              | Adam Mickiewicz University |         | [nEMO: Dataset of Emotional Speech in Polish](https://arxiv.org/abs/2404.06292) |             | nEMO is a Creative Commons-licensed corpus of 4,481 Polish speech recordings by nine actors portraying six emotions (anger, fear, happiness, sadness, surprise, neutral), each with audio, orthographic and normalized transcriptions, and speaker metadata, designed for speech emotion recognition, ASR, and TTS research. |

* Sagalee
* SMIIP-TV dataset
* Pragmatic Similarity Judgments
* Kallaama
* SlideSpeech
* Emilia
* SpeechInstruct
* VietMed
* GTSinger
* EdAcc (Edinburgh International Accents of English Corpus)
* Neural Audio Fingerprint Dataset
* Jam-ALT
* CAS-VSR-S101
* CUCO Database
* DreamVoice
* LongVALE
* MSNER
* SpeechBrown
* United-MedSyn
* Vibravox
* Watch Your Mouth: Point Clouds based Speech Recognition Dataset
* inaGVAD
* SONICS
* FakeMusicCaps
* Granary
* OpenLID
* GlotLID

### Datasets between 2020-23

| Index | Dataset                     | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                             | Multilingual | Source               | Version | Paper                                                                                                                                                                      | Interspeech | Description                                                                                                                                                                                                                                                                                                                               |
|-------|-----------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|--------------------------------------------------------------------------------------|--------------|----------------------|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | DipCo (Dinner Party Corpus) | True                               |                     |                     | True                   |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            | True              |                          |                  |                  | [DiPCo -- Dinner Party Corpus](https://zenodo.org/records/8122551)                   |              | Amazon               |         | [DiPCo -- Dinner Party Corpus](https://arxiv.org/abs/1909.13447)                                                                                                           | True        | The Dinner Party Corpus (DiPCo) is a multi-microphone dataset of natural English dinner-table conversations designed for benchmarking noise-robust and distant speech processing tasks.                                                                                                                                                   |
| 2     | People's Speech             | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech) |              | MLCommons            | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344)                                     |             | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA.                                                                                                                                         |
| 3     | VoxConverse                 |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                          |              | University of Oxford | 0.3     | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                                                                 | True        | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                                                                                                                                     |
| 4     | VoxPopuli                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [facebook/voxpopuli](https://huggingface.co/datasets/facebook/voxpopuli)             | True         | Facebook / Meta      |         | [VoxPopuli: A Large-Scale Multilingual Speech Corpus for Representation Learning, Semi-Supervised Learning and Interpretation](https://aclanthology.org/2021.acl-long.80/) |             | VoxPopuli is a large-scale multilingual speech corpus comprising 400 000 hours of unlabeled audio in 23 European languages, 1 800 hours of transcribed speech in 15 languages, and 17 300 hours of aligned oral interpretations, designed for unsupervised representation learning, semi-supervised ASR, and speech translation research. |

1. GigaSpeech
2. Multilingual LibriSpeech (MLS)
3. AISHELL (4)
4. ESD (Emotional Speech Database)
5. WenetSpeech
6. BEAT (Body-Expression-Audio-Text)
7. Samanantar
8. SEP-28k (Stuttering Events in Podcasts)
9. GUM
10. speechocean762
11. BSTC (Baidu Speech Translation Corpus)
12. MagicData-RAMC
13. SOMOS
14. EARS
15. SwissDial
16. Europarl-ASR
17. ADIMA
18. Samrómur L2 22.09
19. MediaSpeech
20. Totonac Resources
21. Multilingual TEDx
22. ASCEND
23. NISP
24. NISQA Speech Quality Corpus
25. Silent Speech EMG
26. VESUS
27. Vāksañcayaḥ (Sanskrit Speech Corpus by IIT Bombay)
28. DDS (Device-Degraded Speech)
29. ATIS (Air Travel Information System)

### Timeless

| Index | Dataset                                           | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                                  | Multilingual | Source                                                                                     | Version | Paper                                                                                                                                                                                                                                                             | Interspeech | Description                                                                                                                                                                                                                                                                                                                        |
|-------|---------------------------------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|-------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | AMI Corpus                                        | True                               |                     | True                |                        |                      |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      | True       |                   | True                     |                  |                  | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/index.shtml)                          |              | University of Edinburgh                                                                    |         | [RECOGNITION AND UNDERSTANDING OF MEETINGS THE AMI AND AMIDA PROJECTS](https://www.cstr.ed.ac.uk/downloads/publications/2007/ami-asru2007.pdf)                                                                                                                    |             | The AMI Corpus is a publicly available 100-hour multimodal dataset of English four-person meetings recorded in instrumented rooms with synchronized audio, video, and pen/whiteboard streams, richly annotated for orthographic transcripts, dialogue acts, topic segmentation, summarization, named entities, gestures, and more. |
| 2     | CHiME                                             | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [CHiME-6](https://openslr.org/150/)                                                       |              | University of Sheffield                                                                    | 6       | [CHiME-6 Challenge:Tackling Multispeaker Speech Recognition for Unsegmented Recordings](https://arxiv.org/abs/2004.09249)                                                                                                                                         | True        | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research.                                                                                                                                                                    |
| 3     | DAPS (Device and Produced Speech)                 |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [DAPS (Device and Produced Speech) Dataset](https://zenodo.org/records/4660670)           |              | Adobe Research / Center for Computer Research in Music and Acoustics (Stanford University) |         | [Can we Automatically Transform Speech Recorded on Common Consumer Devices in Real-World Environments into Professional Production Quality Speech? — A Dataset, Insights, and Challenges](https://ccrma.stanford.edu/~gautham/Site/daps_files/mysore-spl2015.pdf) |             | Thought for a couple of seconds The DAPS dataset is an aligned corpus of clean, professionally produced, and consumer-device recorded speech samples designed to train and evaluate algorithms that transform everyday recordings into studio-quality audio.                                                                       |
| 4     | LibriSpeech                                       | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [LibriSpeech ASR corpus](https://www.openslr.org/12)                                      |              | Johns Hopkins University                                                                   |         | [LIBRISPEECH: AN ASR CORPUS BASED ON PUBLIC DOMAIN AUDIO BOOKS](https://www.danielpovey.com/files/2015_icassp_librispeech.pdf)                                                                                                                                    |             | LibriSpeech is a 1,000-hour read English speech corpus derived from public-domain audiobooks, freely available under a CC BY 4.0 license for training and evaluating automatic speech recognition systems.                                                                                                                         |
| 5     | LibriVox                                          | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [The LibriVox Free Audiobook Collection](https://archive.org/details/librivoxaudio)       |              | Hugh McGuire & Worldwide Volunteers                                                        |         |                                                                                                                                                                                                                                                                   |             | LibriVox is a volunteer-driven project founded in 2005 to make all public domain books freely available in audio format, with recordings read and shared by volunteers worldwide                                                                                                                                                   |
| 6     | MS-SNSD (Microsoft Scalable Noisy Speech Dataset) |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [microsoft/MS-SNSD](https://github.com/microsoft/MS-SNSD)                                 |              | Microsoft                                                                                  |         | [A Scalable Noisy Speech Dataset and Online Subjective Test Framework](https://arxiv.org/abs/1909.08050)                                                                                                                                                          | True        | The Microsoft Scalable Noisy Speech Dataset (MS-SNSD) is an open-source collection of paired clean and noisy English speech clips—augmented with diverse noise types and configurable SNR levels—to facilitate scalable training and evaluation of deep learning–based speech enhancement models.                                  |
| 7     | Speech Commands                                   |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | True             |                  | [torchaudio.datasets.SPEECHCOMMANDS](https://docs.pytorch.org/audio/stable/datasets.html) |              | Google                                                                                     | 2       | [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)                                                                                                                                                          |             | The Speech Commands dataset is a publicly available collection of one-second English audio clips of 35 distinct spoken words, designed to train and benchmark small-footprint, on-device keyword-spotting models.                                                                                                                  |
| 8     | Spoken Wikipedia Corpora                          | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [The Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                               | True         | Hamburg University                                                                         | 2       | [Mining the Spoken Wikipedia for Speech Data and Beyond](https://aclanthology.org/L16-1735/)                                                                                                                                                                      |             | The Spoken Wikipedia Corpus is a freely licensed, multilingual dataset of time-aligned audio recordings and text transcripts of Wikipedia articles, produced via an automated scraping and alignment pipeline.                                                                                                                     |
| 9     | VoxCeleb                                          | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                      | True         | University of Oxford                                                                       | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                                                                                                                                                   | True        | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                                                                                                                                    |
| 10    | WHAM!                                             |                                    |                     |                     |                        |                      | True              |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            | True              |                          |                  |                  | [WHAM!](http://wham.whisper.ai/)                                                          |              | Mitsubishi Electric Research Laboratories (MERL) /  Whisper.ai                             |         | [WHAM!: Extending Speech Separation to Noisy Environments](https://arxiv.org/abs/1907.01160)                                                                                                                                                                      | True        | The WHAM! dataset pairs two-speaker WSJ0 mixtures with real ambient noise recorded in San Francisco Bay Area venues to benchmark speech separation and enhancement models under realistic noisy conditions.                                                                                                                        |

1. MUSAN
2. WSJ0-2mix
3. TED-LIUM
4. VoxForge
5. VOCASET
6. JVS corpus
7. GRID
8. CMU Wilderness Multilingual Speech Dataset
9. MuST-C
10. Europarl (European Parliament Proceedings Parallel Corpus)
11. LRS2 (Lip Reading Sentences 2)
12. IEMOCAP
13. MELD (Multimodal EmotionLines Dataset)
14. MSP-IMPROV
15. CREMA-D
16. RAVDESS
17. AVA (Atomic Visual Actions)
18. Fluent Speech Commands
19. MIR Corpora
20. NIST SRE (SRE Data)
21. SITW
22. DIHARD
23. Voicebank DEMAND
24. SLURP
25. Tatoeba
26. CMUDict
27. Switchboard Dialog Act Corpus (SwDA)

### Unlisted

_Reasons: Insufficient information, extracted/derived from another dataset, not open source, out of date, specific
tasks, etc._

* **Insufficient information:** Lack of accompanying research paper, missing downloading steps, absence of metadata or
  data dictionary, and unclear or unspecified annotation, dataset sources, or recording/collecting details.

* **Extracted/Derived from another dataset:** Dataset has been derived or extracted from another pre-existing dataset.

* **Not open source:** Limited access due to insufficient publicly available information, many aspects being
  confidential, or availability restricted only to paid access.

* **Out of date:** Dataset is older than five years, indicating potential obsolescence.

* **Specific tasks:** Dataset is tailored for highly specialized subtasks or very specific applications.

| Index | Dataset | Description |
|-------|---------|-------------|
| 1     | AESDD   |             |

1. AESDD
2. Audiocite
3. AudioSet
4. aGender
5. AliMeeting
6. ANAD
7. Arabic Speech Corpus
8. Att-HACK
9. AudioMNIST
10. AVSpeech
11. BAVED
12. BibleTTS
13. CALLHOME American English Speech
14. Café
15. ClovaCall
16. CML-TTS
17. CMU-MOSEI
18. CN-CELEB
19. Common Phone
20. Coswara
21. CoVoST
22. CoVoST2
23. CVSS
24. DAPS
25. DCASE 2014
26. DEEP-VOICE
27. DEMoS
28. Earnings-21
29. EasyCom
30. Europarl-ST
31. EMOVO
32. Emo-DB
33. EmoSynth
34. EmoV-DB
35. EPIC-KITCHENS-100
36. EPIC-SOUNDS
37. EMNS
38. EmoFilm
39. eNTERFACE05
40. Fisher English Training Speech
41. Flickr Audio Caption Corpus
42. FMFCC-A
43. Free Spoken Digit Dataset
44. FSD50K
45. GEMEP corpus
46. GigaST
47. Golos
48. Hi-Fi TTS (Hi-Fi Multi-Speaker English TTS Dataset)
49. HowTo100M
50. Hume-VB
51. HumBug Zooniverse
52. IBM Voicemail Corpus
53. ICSI Corpus
54. IISc-MILE Kannada ASR Corpus
55. IISc-MILE Tamil ASR Corpus
56. InfantMarmosetsVox
57. Infobip AMD
58. Interview
59. ISOLET
60. JL corpus
61. KazakhTTS
62. KSC (Kazakh Speech Corpus)
63. Keio-ESD
64. Kosp2e
65. LEGO Spoken Dialogue Corpus
66. Libri-Adapt
67. Libri-Mixed-Speakers
68. LibriCSS
69. LibriMix
70. LibriTTS
71. LibriTTS-R
72. LJSpeech
73. LJSpeech-1.1
74. MaSS
75. MeerKAT: Meerkat Kalahari Audio Transcripts
76. Mini LibriSpeech
77. MobvoiHotwords
78. Mohammed
79. MOSI
80. MRDA (ICSI Meeting Recorder Dialog Act Corpus)
81. MSP Podcast Corpus
82. MSNER
83. MSR-86K
84. Mudestreda (Mudestreda Multimodal Device State Recognition Dataset)
85. Multimodal PISA (Multimodal Piano Skills Assessment)
86. MuSe-CAR
87. Nepali Text-to-Speech Data (Male and Female)
88. NTIMIT
89. OGVC
90. ParlamentParla
91. PartialSpoof
92. PC-GITA
93. PCVC (Persian Consonant Vowel Combination)
94. PodcastFillers
95. PromptSpeech
96. PromptTTS
97. Puebla-Nahuatl
98. RECOLA
99. ReefSet
100. Respiratory and Drug Actuation Dataset
101. ReVerb
102. Russian LibriSpeech
103. Samrómur Mimic 22.09
104. SASPEECH
105. SAVEE
106. SEWA
107. SEMAINE
108. SEOUL CORPUS
109. SHALCAS22A
110. ShEMO
111. Silbo Gomero Speech Corpus
112. SINGA:PURA (SINGApore: Polyphonic URban Audio)
113. SingFake
114. SLUE
115. SparseLibriMix
116. SpeechMatrix
117. Speech Accent Archive
118. Speech Wikimedia
119. SPEECH-COCO
120. Speech-MASSIVE
121. Spiking Heidelberg Digits (SHD)
122. Spiking Speech Commands (SSC)
123. SPGISpeech
124. Spotify Podcast Datase
125. Spoken-SQuAD
126. TAU Urban Acoustic Scenes 2019
127. TAU-NIGENS Spatial Sound
128. Tatoeba
129. TESS
130. THCHS-30
131. Thorsten-Voice
132. The MC Speech Dataset
133. TIMIT
134. TUDA
135. UGIF
136. VCTK (CSTR VCTK Corpus)
137. VCTK-2Mix
138. VGG-Sound
139. VGGSound-Sparse
140. VIVAE
141. VocalSound
142. VOICES
143. VoxBlink
144. Yoloxóchitl-Mixtec
145. YouTube-8M
146. Wavix Voicemail
147. WHAMR!
148. Wikimedia Commons
149. XBMU-AMDO31
150. Zeroth-Korean
151. DeToxy
152. EasyCall
153. REAL-M
154. RTASC
155. ReMASC
156. Talking With Hands 16.2M
157. Timers and Such
158. ASR-GLUE
159. EMOVIE
160. LibriVoxDeEn
161. NusaCrowd
162. RESD
163. SpokenSTS
164. TaL Corpus (The Tongue and Lips Corpus)
165. AV Digits Database
166. BD-4SK-ASR
167. CI-AVSR
168. JVS-MuSiC
169. LaboroTVSpeech
170. MASRI-HEADSET
171. MAVS
172. NPSC
173. MultiSV
174. NeuroVoz
175. RyanSpeech
176. SDN (Situated Dialogue Navigation)
177. AVA-Speech
178. AVASpeech-SMAD
179. Arabic Speech Commands Dataset.
180. DR-VCTK
181. EVI
182. EmoSpeech
183. FT Speech
184. Greek Parliament Proceedings
185. JSS Dataset (Jejueo Single Speaker Speech)
186. THVD (Talking Head Video Dataset)
187. Kinect-WSJ
188. LibriS2S
189. MediBeng
190. Persian Preschool Cognition Speech
191. Quechua-SER
192. RUSLAN
193. VedantaNY-10M
194. MCCSD (Mandarin Chinese Cued Speech Dataset)
195. TurkicASR
196. UrbanSound8K
197. CMUARCTIC
198. QUESST 2014
199. SNIPS
200. YESNO
201. AccentDB
202. Free Spoken Digit Dataset (FSDD)
203. Libri-Light
204. LRS3-TED
205. CAS-VSR-W1k (LRW-1000)
206. GLips
207. DIRHA
208. BERSt
209. CANDOR
210. MSP-Podcast
211. EmoDB
212. LSSED
213. Doc2Dial
214. Switchboard-1 Corpus
215. CPED
216. LRW (Lip Reading in the Wild)
217. CSS10
218. iKala
219. FKD (Football Keywords Dataset)
220. mDRT
221. BABEL Speech Corpus
222. WiLI-2018
223. Common Language
224. NLI-PT

---

## Hub / Database / Library

### Open Source

* [ISCA Archive](https://www.isca-archive.org/)
* [OpenSLR.org](http://www.openslr.org)
* [Voicebank](https://www.voicebank.ie/)
* [TorchAudio](https://github.com/pytorch/audio)
* [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/overview)
* [Magic Data](https://www.magicdatatech.com/)
* [European Language Grid](https://live.european-language-grid.eu/)
* [Freesound](https://freesound.org/)

### Closed Source

* [Linguistic Data Consortium](https://www.ldc.upenn.edu/)

### Contain Both Open and Closed Sources

* [TalkBank](https://ca.talkbank.org/)
* [Zenodo](https://zenodo.org/)

---
