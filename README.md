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

* [Tables of Datasets](#tables-of-datasets)
    * [Datasets (2023-25)](#datasets-2023-25)
    * [Timeless](#timeless)
    * [Unlisted](#unlisted)
* [Hub / Database / Library](#hub--database--library)
    * [Open Source](#open-source)
    * [Closed Source](#closed-source)
    * [Contain Both Open and Closed Sources](#contain-both-open-and-closed-sources)

---

## Tables of Datasets

### Datasets (2023-25)

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
28. VoxBlink
29. VoxTube
30. MSR-86K
31. 3D-Speaker
32. EmoSet
33. KBES
34. Dusha
35. M5SER
36. Divide and Remaster v3 (DnR v3)
37. ITALIC
38. FalAI
39. TextrolSpeech
40. Audiobox
41. Lombard-GRID-2mix
42. wTIMIT2mix
43. SonicSet (SonicSim)
44. TextrolMix
45. MultiCAT (Multimodal Communication Annotations for Teams)
46. KAN-AV
47. Facestar
48. RVTALL
49. AVE-Speech
50. EARS

### Timeless

| Index | Dataset                                           | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                                  | Multilingual | Source                                                                                     | Version | Paper                                                                                                                                                                                                                                                             | Interspeech | Description                                                                                                                                                                                                                                                                                                                               |
|-------|---------------------------------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|-------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | AMI Corpus                                        | True                               |                     | True                |                        |                      |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      | True       |                   | True                     |                  |                  | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/index.shtml)                          |              | University of Edinburgh                                                                    |         | [RECOGNITION AND UNDERSTANDING OF MEETINGS THE AMI AND AMIDA PROJECTS](https://www.cstr.ed.ac.uk/downloads/publications/2007/ami-asru2007.pdf)                                                                                                                    |             | The AMI Corpus is a publicly available 100-hour multimodal dataset of English four-person meetings recorded in instrumented rooms with synchronized audio, video, and pen/whiteboard streams, richly annotated for orthographic transcripts, dialogue acts, topic segmentation, summarization, named entities, gestures, and more.        |
| 2     | CHiME                                             | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [CHiME-6](https://openslr.org/150/)                                                       |              | University of Sheffield                                                                    | 6       | [CHiME-6 Challenge:Tackling Multispeaker Speech Recognition for Unsegmented Recordings](https://arxiv.org/abs/2004.09249)                                                                                                                                         | True        | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research.                                                                                                                                                                           |
| 3     | DAPS (Device and Produced Speech)                 |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [DAPS (Device and Produced Speech) Dataset](https://zenodo.org/records/4660670)           |              | Adobe Research / Center for Computer Research in Music and Acoustics (Stanford University) |         | [Can we Automatically Transform Speech Recorded on Common Consumer Devices in Real-World Environments into Professional Production Quality Speech? — A Dataset, Insights, and Challenges](https://ccrma.stanford.edu/~gautham/Site/daps_files/mysore-spl2015.pdf) |             | Thought for a couple of seconds The DAPS dataset is an aligned corpus of clean, professionally produced, and consumer-device recorded speech samples designed to train and evaluate algorithms that transform everyday recordings into studio-quality audio.                                                                              |
| 4     | LibriSpeech                                       | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [LibriSpeech ASR corpus](https://www.openslr.org/12)                                      |              | Johns Hopkins University                                                                   |         | [LIBRISPEECH: AN ASR CORPUS BASED ON PUBLIC DOMAIN AUDIO BOOKS](https://www.danielpovey.com/files/2015_icassp_librispeech.pdf)                                                                                                                                    |             | LibriSpeech is a 1,000-hour read English speech corpus derived from public-domain audiobooks, freely available under a CC BY 4.0 license for training and evaluating automatic speech recognition systems.                                                                                                                                |
| 5     | LibriVox                                          | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [The LibriVox Free Audiobook Collection](https://archive.org/details/librivoxaudio)       |              | Hugh McGuire & Worldwide Volunteers                                                        |         |                                                                                                                                                                                                                                                                   |             | LibriVox is a volunteer-driven project founded in 2005 to make all public domain books freely available in audio format, with recordings read and shared by volunteers worldwide                                                                                                                                                          |
| 6     | MS-SNSD (Microsoft Scalable Noisy Speech Dataset) |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [microsoft/MS-SNSD](https://github.com/microsoft/MS-SNSD)                                 |              | Microsoft                                                                                  |         | [A Scalable Noisy Speech Dataset and Online Subjective Test Framework](https://arxiv.org/abs/1909.08050)                                                                                                                                                          | True        | The Microsoft Scalable Noisy Speech Dataset (MS-SNSD) is an open-source collection of paired clean and noisy English speech clips—augmented with diverse noise types and configurable SNR levels—to facilitate scalable training and evaluation of deep learning–based speech enhancement models.                                         |
| 7     | Speech Commands                                   |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | True             |                  | [torchaudio.datasets.SPEECHCOMMANDS](https://docs.pytorch.org/audio/stable/datasets.html) |              | Google                                                                                     | 2       | [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)                                                                                                                                                          |             | The Speech Commands dataset is a publicly available collection of one-second English audio clips of 35 distinct spoken words, designed to train and benchmark small-footprint, on-device keyword-spotting models.                                                                                                                         |
| 8     | Spoken Wikipedia Corpora                          | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [The Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                               | True         | Hamburg University                                                                         | 2       | [Mining the Spoken Wikipedia for Speech Data and Beyond](https://aclanthology.org/L16-1735/)                                                                                                                                                                      |             | The Spoken Wikipedia Corpus is a freely licensed, multilingual dataset of time-aligned audio recordings and text transcripts of Wikipedia articles, produced via an automated scraping and alignment pipeline.                                                                                                                            |
| 9     | VoxCeleb                                          | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                      | True         | University of Oxford                                                                       | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                                                                                                                                                   | True        | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                                                                                                                                           |
| 10    | WHAM!                                             |                                    |                     |                     |                        |                      | True              |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            | True              |                          |                  |                  | [WHAM!](http://wham.whisper.ai/)                                                          |              | Mitsubishi Electric Research Laboratories (MERL) /  Whisper.ai                             |         | [WHAM!: Extending Speech Separation to Noisy Environments](https://arxiv.org/abs/1907.01160)                                                                                                                                                                      | True        | The WHAM! dataset pairs two-speaker WSJ0 mixtures with real ambient noise recorded in San Francisco Bay Area venues to benchmark speech separation and enhancement models under realistic noisy conditions.                                                                                                                               |
| 11    | People's Speech                                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech)      |              | MLCommons                                                                                  | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344)                                                                                                                            |             | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA.                                                                                                                                         |
| 12    | VoxConverse                                       |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                               |              | University of Oxford                                                                       | 0.3     | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                                                                                                                                                        | True        | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                                                                                                                                     |
| 13    | VoxPopuli                                         | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [facebook/voxpopuli](https://huggingface.co/datasets/facebook/voxpopuli)                  | True         | Facebook / Meta                                                                            |         | [VoxPopuli: A Large-Scale Multilingual Speech Corpus for Representation Learning, Semi-Supervised Learning and Interpretation](https://aclanthology.org/2021.acl-long.80/)                                                                                        |             | VoxPopuli is a large-scale multilingual speech corpus comprising 400 000 hours of unlabeled audio in 23 European languages, 1 800 hours of transcribed speech in 15 languages, and 17 300 hours of aligned oral interpretations, designed for unsupervised representation learning, semi-supervised ASR, and speech translation research. |

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
31. GigaSpeech
32. Multilingual LibriSpeech (MLS)
33. AISHELL (4)
34. ESD (Emotional Speech Database)
35. WenetSpeech
36. BEAT (Body-Expression-Audio-Text)
37. BSTC (Baidu Speech Translation Corpus)
38. SOMOS
39. Multilingual TEDx
40. ATIS (Air Travel Information System)

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
82. Mudestreda (Mudestreda Multimodal Device State Recognition Dataset)
83. Multimodal PISA (Multimodal Piano Skills Assessment)
84. MuSe-CAR
85. Nepali Text-to-Speech Data (Male and Female)
86. NTIMIT
87. OGVC
88. ParlamentParla
89. PartialSpoof
90. PC-GITA
91. PCVC (Persian Consonant Vowel Combination)
92. PodcastFillers
93. PromptSpeech
94. PromptTTS
95. Puebla-Nahuatl
96. RECOLA
97. ReefSet
98. Respiratory and Drug Actuation Dataset
99. ReVerb
100. Russian LibriSpeech
101. Samrómur Mimic 22.09
102. SASPEECH
103. SAVEE
104. SEWA
105. SEMAINE
106. SEOUL CORPUS
107. SHALCAS22A
108. ShEMO
109. Silbo Gomero Speech Corpus
110. SINGA:PURA (SINGApore: Polyphonic URban Audio)
111. SingFake
112. SLUE
113. SparseLibriMix
114. SpeechMatrix
115. Speech Accent Archive
116. Speech Wikimedia
117. SPEECH-COCO
118. Speech-MASSIVE
119. Spiking Heidelberg Digits (SHD)
120. Spiking Speech Commands (SSC)
121. SPGISpeech
122. Spotify Podcast Datase
123. Spoken-SQuAD
124. TAU Urban Acoustic Scenes 2019
125. TAU-NIGENS Spatial Sound
126. Tatoeba
127. TESS
128. THCHS-30
129. Thorsten-Voice
130. The MC Speech Dataset
131. TIMIT
132. TUDA
133. UGIF
134. VCTK (CSTR VCTK Corpus)
135. VCTK-2Mix
136. VGG-Sound
137. VGGSound-Sparse
138. VIVAE
139. VocalSound
140. VOICES
141. Yoloxóchitl-Mixtec
142. YouTube-8M
143. Wavix Voicemail
144. WHAMR!
145. Wikimedia Commons
146. XBMU-AMDO31
147. Zeroth-Korean
148. DeToxy
149. EasyCall
150. REAL-M
151. RTASC
152. ReMASC
153. Talking With Hands 16.2M
154. Timers and Such
155. ASR-GLUE
156. EMOVIE
157. LibriVoxDeEn
158. NusaCrowd
159. RESD
160. SpokenSTS
161. TaL Corpus (The Tongue and Lips Corpus)
162. AV Digits Database
163. BD-4SK-ASR
164. CI-AVSR
165. JVS-MuSiC
166. LaboroTVSpeech
167. MASRI-HEADSET
168. MAVS
169. NPSC
170. MultiSV
171. NeuroVoz
172. RyanSpeech
173. SDN (Situated Dialogue Navigation)
174. AVA-Speech
175. AVASpeech-SMAD
176. Arabic Speech Commands Dataset.
177. DR-VCTK
178. EVI
179. EmoSpeech
180. FT Speech
181. Greek Parliament Proceedings
182. JSS Dataset (Jejueo Single Speaker Speech)
183. THVD (Talking Head Video Dataset)
184. Kinect-WSJ
185. LibriS2S
186. MediBeng
187. Persian Preschool Cognition Speech
188. Quechua-SER
189. RUSLAN
190. VedantaNY-10M
191. MCCSD (Mandarin Chinese Cued Speech Dataset)
192. TurkicASR
193. UrbanSound8K
194. CMUARCTIC
195. QUESST 2014
196. SNIPS
197. YESNO
198. AccentDB
199. Free Spoken Digit Dataset (FSDD)
200. Libri-Light
201. LRS3-TED
202. CAS-VSR-W1k (LRW-1000)
203. GLips
204. DIRHA
205. BERSt
206. CANDOR
207. MSP-Podcast
208. EmoDB
209. LSSED
210. Doc2Dial
211. Switchboard-1 Corpus
212. CPED (Chinese Personalized and Emotional Dialogue)
213. LRW (Lip Reading in the Wild)
214. CSS10
215. iKala
216. FKD (Football Keywords Dataset)
217. mDRT
218. BABEL Speech Corpus
219. WiLI-2018
220. Common Language
221. NLI-PT
222. FUSS (Free Universal Sound Separation)
223. Auto-KWS
224. AVMIT (Audiovisual Moments in Time)
225. Lingala Read Speech Corpus
226. Congolese Speech Radio Corpus
227. Zambezi Voice
228. Friends-MMC
229. Laboro-ASV (LaboroTVSpeech-ASV)
230. CAVES (Cantonese Audio-Visual Emotional Speech)
231. BANSpEmo
232. MDER
233. EMOVOME
234. Spanish MEACorpus 2023
235. LibriheavyMix
236. Echo2Mix
237. RATS Low Speech Density
238. BhasaAnuvaad
239. AVMuST-TED
240. RoDia
241. NLSpeech
242. Balinese TTS
243. Rasa
244. IndicVoices-R
245. RASwDA (Re-Aligned Switchboard Dialog Act Corpus)
246. MOCKS
247. WenetPhrase
248. MDSC
249. LIP-RTVE
250. SlideAVSR
251. OLKAVS
252. AVA Datasets
253. DipCo (Dinner Party Corpus)
254. Samanantar
255. SEP-28k (Stuttering Events in Podcasts)
256. GUM
257. speechocean762
258. MagicData-RAMC
259. SwissDials
260. Europarl-ASR
261. Vāksañcayaḥ (Sanskrit Speech Corpus by IIT Bombay)
262. ADIMA
263. Samrómur L2 22.09
264. MediaSpeech
265. Totonac Resources
266. ASCEND
267. NISP
268. NISQA Speech Quality Corpus
269. Silent Speech EMG
270. VESUS
271. DDS (Device-Degraded Speech)

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
* [ELRA Catalogue of Language Resources](https://catalogue.elra.info/)

### Contain Both Open and Closed Sources

* [TalkBank](https://ca.talkbank.org/)
* [Zenodo](https://zenodo.org/)

---
