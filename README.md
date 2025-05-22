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

1. Sagalee
2. SMIIP-TV dataset
3. Pragmatic Similarity Judgments
4. Kallaama
5. SlideSpeech
6. Emilia
7. SpeechInstruct
8. VietMed
9. GTSinger
10. EdAcc (Edinburgh International Accents of English Corpus)
11. Neural Audio Fingerprint Dataset
12. Jam-ALT
13. CAS-VSR-S101
14. CUCO Database
15. DreamVoice
16. LongVALE
17. MSNER
18. SpeechBrown
19. United-MedSyn
20. Vibravox
21. Watch Your Mouth: Point Clouds based Speech Recognition Dataset
22. inaGVAD
23. SONICS
24. FakeMusicCaps
25. Granary
26. OpenLID
27. GlotLID

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
28. SGD (Schema-Guided Dialogue)
29. AVSpeech
30. MIT (Moments in Time Dataset)

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
10. BAVED
11. BibleTTS
12. CALLHOME American English Speech
13. Café
14. ClovaCall
15. CML-TTS
16. CMU-MOSEI
17. CN-CELEB
18. Common Phone
19. Coswara
20. CoVoST
21. CoVoST2
22. CVSS
23. DAPS
24. DCASE 2014
25. DEEP-VOICE
26. DEMoS
27. Earnings-21
28. EasyCom
29. Europarl-ST
30. EMOVO
31. Emo-DB
32. EmoSynth
33. EmoV-DB
34. EPIC-KITCHENS-100
35. EPIC-SOUNDS
36. EMNS
37. EmoFilm
38. eNTERFACE05
39. Fisher English Training Speech
40. Flickr Audio Caption Corpus
41. FMFCC-A
42. Free Spoken Digit Dataset
43. FSD50K
44. GEMEP corpus
45. GigaST
46. Golos
47. Hi-Fi TTS (Hi-Fi Multi-Speaker English TTS Dataset)
48. HowTo100M
49. Hume-VB
50. HumBug Zooniverse
51. IBM Voicemail Corpus
52. ICSI Corpus
53. IISc-MILE Kannada ASR Corpus
54. IISc-MILE Tamil ASR Corpus
55. InfantMarmosetsVox
56. Infobip AMD
57. Interview
58. ISOLET
59. JL corpus
60. KazakhTTS
61. KSC (Kazakh Speech Corpus)
62. Keio-ESD
63. Kosp2e
64. LEGO Spoken Dialogue Corpus
65. Libri-Adapt
66. Libri-Mixed-Speakers
67. LibriCSS
68. LibriMix
69. LibriTTS
70. LibriTTS-R
71. LJSpeech
72. LJSpeech-1.1
73. MaSS
74. MeerKAT: Meerkat Kalahari Audio Transcripts
75. Mini LibriSpeech
76. MobvoiHotwords
77. Mohammed
78. MOSI
79. MRDA (ICSI Meeting Recorder Dialog Act Corpus)
80. MSP Podcast Corpus
81. MSNER
82. MSR-86K
83. Mudestreda (Mudestreda Multimodal Device State Recognition Dataset)
84. Multimodal PISA (Multimodal Piano Skills Assessment)
85. MuSe-CAR
86. Nepali Text-to-Speech Data (Male and Female)
87. NTIMIT
88. OGVC
89. ParlamentParla
90. PartialSpoof
91. PC-GITA
92. PCVC (Persian Consonant Vowel Combination)
93. PodcastFillers
94. PromptSpeech
95. PromptTTS
96. Puebla-Nahuatl
97. RECOLA
98. ReefSet
99. Respiratory and Drug Actuation Dataset
100. ReVerb
101. Russian LibriSpeech
102. Samrómur Mimic 22.09
103. SASPEECH
104. SAVEE
105. SEWA
106. SEMAINE
107. SEOUL CORPUS
108. SHALCAS22A
109. ShEMO
110. Silbo Gomero Speech Corpus
111. SINGA:PURA (SINGApore: Polyphonic URban Audio)
112. SingFake
113. SLUE
114. SparseLibriMix
115. SpeechMatrix
116. Speech Accent Archive
117. Speech Wikimedia
118. SPEECH-COCO
119. Speech-MASSIVE
120. Spiking Heidelberg Digits (SHD)
121. Spiking Speech Commands (SSC)
122. SPGISpeech
123. Spotify Podcast Datase
124. Spoken-SQuAD
125. TAU Urban Acoustic Scenes 2019
126. TAU-NIGENS Spatial Sound
127. Tatoeba
128. TESS
129. THCHS-30
130. Thorsten-Voice
131. The MC Speech Dataset
132. TIMIT
133. TUDA
134. UGIF
135. VCTK (CSTR VCTK Corpus)
136. VCTK-2Mix
137. VGG-Sound
138. VGGSound-Sparse
139. VIVAE
140. VocalSound
141. VOICES
142. VoxBlink
143. Yoloxóchitl-Mixtec
144. YouTube-8M
145. Wavix Voicemail
146. WHAMR!
147. Wikimedia Commons
148. XBMU-AMDO31
149. Zeroth-Korean
150. DeToxy
151. EasyCall
152. REAL-M
153. RTASC
154. ReMASC
155. Talking With Hands 16.2M
156. Timers and Such
157. ASR-GLUE
158. EMOVIE
159. LibriVoxDeEn
160. NusaCrowd
161. RESD
162. SpokenSTS
163. TaL Corpus (The Tongue and Lips Corpus)
164. AV Digits Database
165. BD-4SK-ASR
166. CI-AVSR
167. JVS-MuSiC
168. LaboroTVSpeech
169. MASRI-HEADSET
170. MAVS
171. NPSC
172. MultiSV
173. NeuroVoz
174. RyanSpeech
175. SDN (Situated Dialogue Navigation)
176. AVA-Speech
177. AVASpeech-SMAD
178. Arabic Speech Commands Dataset.
179. DR-VCTK
180. EVI
181. EmoSpeech
182. FT Speech
183. Greek Parliament Proceedings
184. JSS Dataset (Jejueo Single Speaker Speech)
185. THVD (Talking Head Video Dataset)
186. Kinect-WSJ
187. LibriS2S
188. MediBeng
189. Persian Preschool Cognition Speech
190. Quechua-SER
191. RUSLAN
192. VedantaNY-10M
193. MCCSD (Mandarin Chinese Cued Speech Dataset)
194. TurkicASR
195. UrbanSound8K
196. CMUARCTIC
197. QUESST 2014
198. SNIPS
199. YESNO
200. AccentDB
201. Free Spoken Digit Dataset (FSDD)
202. Libri-Light
203. LRS3-TED
204. CAS-VSR-W1k (LRW-1000)
205. GLips
206. DIRHA
207. BERSt
208. CANDOR
209. MSP-Podcast
210. EmoDB
211. LSSED
212. Doc2Dial
213. Switchboard-1 Corpus
214. CPED (Chinese Personalized and Emotional Dialogue)
215. LRW (Lip Reading in the Wild)
216. CSS10
217. iKala
218. FKD (Football Keywords Dataset)
219. mDRT
220. BABEL Speech Corpus
221. WiLI-2018
222. Common Language
223. NLI-PT
224. FUSS (Free Universal Sound Separation)
225. Auto-KWS
226. AVMIT (Audiovisual Moments in Time)

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
