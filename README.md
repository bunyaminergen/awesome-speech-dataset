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

| Index | Dataset                                                    | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                                  | Multilingual | Source                                                                                     | Version | Paper                                                                                                                                                                                                                                                             | Interspeech | Description                                                                                                                                                                                                                                                                                                                               |
|-------|------------------------------------------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|-------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | AMI Corpus                                                 | True                               |                     | True                |                        |                      |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      | True       |                   | True                     |                  |                  | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/index.shtml)                          |              | University of Edinburgh                                                                    |         | [RECOGNITION AND UNDERSTANDING OF MEETINGS THE AMI AND AMIDA PROJECTS](https://www.cstr.ed.ac.uk/downloads/publications/2007/ami-asru2007.pdf)                                                                                                                    |             | The AMI Corpus is a publicly available 100-hour multimodal dataset of English four-person meetings recorded in instrumented rooms with synchronized audio, video, and pen/whiteboard streams, richly annotated for orthographic transcripts, dialogue acts, topic segmentation, summarization, named entities, gestures, and more.        |
| 2     | ATIS (Air Travel Information System)                       |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                           |
| 3     | CHiME                                                      | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [CHiME-6](https://openslr.org/150/)                                                       |              | University of Sheffield                                                                    | 6       | [CHiME-6 Challenge:Tackling Multispeaker Speech Recognition for Unsegmented Recordings](https://arxiv.org/abs/2004.09249)                                                                                                                                         | True        | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research.                                                                                                                                                                           |
| 4     | DAPS (Device and Produced Speech)                          |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [DAPS (Device and Produced Speech) Dataset](https://zenodo.org/records/4660670)           |              | Adobe Research / Center for Computer Research in Music and Acoustics (Stanford University) |         | [Can we Automatically Transform Speech Recorded on Common Consumer Devices in Real-World Environments into Professional Production Quality Speech? — A Dataset, Insights, and Challenges](https://ccrma.stanford.edu/~gautham/Site/daps_files/mysore-spl2015.pdf) |             | Thought for a couple of seconds The DAPS dataset is an aligned corpus of clean, professionally produced, and consumer-device recorded speech samples designed to train and evaluate algorithms that transform everyday recordings into studio-quality audio.                                                                              |
| 5     | Europarl (European Parliament Proceedings Parallel Corpus) |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                           |
| 6     | GigaSpeech                                                 |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                           |
| 7     | IEMOCAP                                                    |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                           |
| 8     | LibriSpeech                                                | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [LibriSpeech ASR corpus](https://www.openslr.org/12)                                      |              | Johns Hopkins University                                                                   |         | [LIBRISPEECH: AN ASR CORPUS BASED ON PUBLIC DOMAIN AUDIO BOOKS](https://www.danielpovey.com/files/2015_icassp_librispeech.pdf)                                                                                                                                    |             | LibriSpeech is a 1,000-hour read English speech corpus derived from public-domain audiobooks, freely available under a CC BY 4.0 license for training and evaluating automatic speech recognition systems.                                                                                                                                |
| 9     | LibriVox                                                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [The LibriVox Free Audiobook Collection](https://archive.org/details/librivoxaudio)       |              | Hugh McGuire & Worldwide Volunteers                                                        |         |                                                                                                                                                                                                                                                                   |             | LibriVox is a volunteer-driven project founded in 2005 to make all public domain books freely available in audio format, with recordings read and shared by volunteers worldwide                                                                                                                                                          |
| 10    | MS-SNSD (Microsoft Scalable Noisy Speech Dataset)          |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [microsoft/MS-SNSD](https://github.com/microsoft/MS-SNSD)                                 |              | Microsoft                                                                                  |         | [A Scalable Noisy Speech Dataset and Online Subjective Test Framework](https://arxiv.org/abs/1909.08050)                                                                                                                                                          | True        | The Microsoft Scalable Noisy Speech Dataset (MS-SNSD) is an open-source collection of paired clean and noisy English speech clips—augmented with diverse noise types and configurable SNR levels—to facilitate scalable training and evaluation of deep learning–based speech enhancement models.                                         |
| 11    | Multilingual TEDx                                          |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                           |
| 12    | People's Speech                                            | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech)      |              | MLCommons                                                                                  | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344)                                                                                                                            |             | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA.                                                                                                                                         |
| 13    | Speech Commands                                            |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | True             |                  | [torchaudio.datasets.SPEECHCOMMANDS](https://docs.pytorch.org/audio/stable/datasets.html) |              | Google                                                                                     | 2       | [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)                                                                                                                                                          |             | The Speech Commands dataset is a publicly available collection of one-second English audio clips of 35 distinct spoken words, designed to train and benchmark small-footprint, on-device keyword-spotting models.                                                                                                                         |
| 14    | Spoken Wikipedia Corpora                                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [The Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                               | True         | Hamburg University                                                                         | 2       | [Mining the Spoken Wikipedia for Speech Data and Beyond](https://aclanthology.org/L16-1735/)                                                                                                                                                                      |             | The Spoken Wikipedia Corpus is a freely licensed, multilingual dataset of time-aligned audio recordings and text transcripts of Wikipedia articles, produced via an automated scraping and alignment pipeline.                                                                                                                            |
| 15    | TED-LIUM                                                   |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                           |
| 16    | VoxCeleb                                                   | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                      | True         | University of Oxford                                                                       | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                                                                                                                                                   | True        | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                                                                                                                                           |
| 17    | VoxConverse                                                |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                               |              | University of Oxford                                                                       | 0.3     | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                                                                                                                                                        | True        | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                                                                                                                                     |
| 18    | VoxPopuli                                                  | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [facebook/voxpopuli](https://huggingface.co/datasets/facebook/voxpopuli)                  | True         | Facebook / Meta                                                                            |         | [VoxPopuli: A Large-Scale Multilingual Speech Corpus for Representation Learning, Semi-Supervised Learning and Interpretation](https://aclanthology.org/2021.acl-long.80/)                                                                                        |             | VoxPopuli is a large-scale multilingual speech corpus comprising 400 000 hours of unlabeled audio in 23 European languages, 1 800 hours of transcribed speech in 15 languages, and 17 300 hours of aligned oral interpretations, designed for unsupervised representation learning, semi-supervised ASR, and speech translation research. |
| 19    | WHAM!                                                      |                                    |                     |                     |                        |                      | True              |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            | True              |                          |                  |                  | [WHAM!](http://wham.whisper.ai/)                                                          |              | Mitsubishi Electric Research Laboratories (MERL) /  Whisper.ai                             |         | [WHAM!: Extending Speech Separation to Noisy Environments](https://arxiv.org/abs/1907.01160)                                                                                                                                                                      | True        | The WHAM! dataset pairs two-speaker WSJ0 mixtures with real ambient noise recorded in San Francisco Bay Area venues to benchmark speech separation and enhancement models under realistic noisy conditions.                                                                                                                               |
| 20    | MUSAN                                                      |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                           |
| 21    | VCTK (CSTR VCTK Corpus)                                    |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                           |

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
134. VCTK-2Mix
135. VGG-Sound
136. VGGSound-Sparse
137. VIVAE
138. VocalSound
139. VOICES
140. Yoloxóchitl-Mixtec
141. YouTube-8M
142. Wavix Voicemail
143. WHAMR!
144. Wikimedia Commons
145. XBMU-AMDO31
146. Zeroth-Korean
147. DeToxy
148. EasyCall
149. REAL-M
150. RTASC
151. ReMASC
152. Talking With Hands 16.2M
153. Timers and Such
154. ASR-GLUE
155. EMOVIE
156. LibriVoxDeEn
157. NusaCrowd
158. RESD
159. SpokenSTS
160. TaL Corpus (The Tongue and Lips Corpus)
161. AV Digits Database
162. BD-4SK-ASR
163. CI-AVSR
164. JVS-MuSiC
165. LaboroTVSpeech
166. MASRI-HEADSET
167. MAVS
168. NPSC
169. MultiSV
170. NeuroVoz
171. RyanSpeech
172. SDN (Situated Dialogue Navigation)
173. AVA-Speech
174. AVASpeech-SMAD
175. Arabic Speech Commands Dataset.
176. DR-VCTK
177. EVI
178. EmoSpeech
179. FT Speech
180. Greek Parliament Proceedings
181. JSS Dataset (Jejueo Single Speaker Speech)
182. THVD (Talking Head Video Dataset)
183. Kinect-WSJ
184. LibriS2S
185. MediBeng
186. Persian Preschool Cognition Speech
187. Quechua-SER
188. RUSLAN
189. VedantaNY-10M
190. MCCSD (Mandarin Chinese Cued Speech Dataset)
191. TurkicASR
192. UrbanSound8K
193. CMUARCTIC
194. QUESST 2014
195. SNIPS
196. YESNO
197. AccentDB
198. Free Spoken Digit Dataset (FSDD)
199. Libri-Light
200. LRS3-TED
201. CAS-VSR-W1k (LRW-1000)
202. GLips
203. DIRHA
204. BERSt
205. CANDOR
206. MSP-Podcast
207. EmoDB
208. LSSED
209. Doc2Dial
210. Switchboard-1
211. CPED (Chinese Personalized and Emotional Dialogue)
212. LRW (Lip Reading in the Wild)
213. CSS10
214. iKala
215. FKD (Football Keywords Dataset)
216. mDRT
217. BABEL Speech Corpus
218. WiLI-2018
219. Common Language
220. NLI-PT
221. FUSS (Free Universal Sound Separation)
222. Auto-KWS
223. AVMIT (Audiovisual Moments in Time)
224. Lingala Read Speech Corpus
225. Congolese Speech Radio Corpus
226. Zambezi Voice
227. Friends-MMC
228. Laboro-ASV (LaboroTVSpeech-ASV)
229. CAVES (Cantonese Audio-Visual Emotional Speech)
230. BANSpEmo
231. MDER
232. EMOVOME
233. Spanish MEACorpus 2023
234. LibriheavyMix
235. Echo2Mix
236. RATS Low Speech Density
237. BhasaAnuvaad
238. AVMuST-TED
239. RoDia
240. NLSpeech
241. Balinese TTS
242. Rasa
243. IndicVoices-R
244. RASwDA (Re-Aligned Switchboard Dialog Act Corpus)
245. MOCKS
246. WenetPhrase
247. MDSC
248. LIP-RTVE
249. SlideAVSR
250. OLKAVS
251. AVA Datasets
252. DipCo (Dinner Party Corpus)
253. Samanantar
254. SEP-28k (Stuttering Events in Podcasts)
255. GUM
256. speechocean762
257. MagicData-RAMC
258. SwissDials
259. Europarl-ASR
260. Vāksañcayaḥ (Sanskrit Speech Corpus by IIT Bombay)
261. ADIMA
262. Samrómur L2 22.09
263. MediaSpeech
264. Totonac Resources
265. ASCEND
266. NISP
267. NISQA Speech Quality Corpus
268. Silent Speech EMG
269. VESUS
270. DDS (Device-Degraded Speech)
271. WSJ0-2mix
272. VoxForge
273. VOCASET
274. JVS corpus
275. GRID
276. CMU Wilderness Multilingual Speech Dataset
277. MuST-C
278. LRS2 (Lip Reading Sentences 2)
279. MELD (Multimodal EmotionLines Dataset)
280. MSP-IMPROV
281. CREMA-D
282. RAVDESS
283. AVA (Atomic Visual Actions)
284. Fluent Speech Commands
285. MIR Corpora
286. NIST SRE (SRE Data)
287. SITW
288. DIHARD
289. DIHARD
290. Voicebank DEMAND
291. SLURP
292. Tatoeba
293. CMUDict
294. Switchboard Dialog Act Corpus (SwDA)
295. SGD (Schema-Guided Dialogue)
296. AVSpeech
297. MIT (Moments in Time Dataset)
298. Multilingual LibriSpeech (MLS)
299. AISHELL (4)
300. ESD (Emotional Speech Database)
301. WenetSpeech
302. BEAT (Body-Expression-Audio-Text)
303. BSTC (Baidu Speech Translation Corpus)
304. SOMOS

---

## Hub / Database / Library

### Open Source

* [European Language Grid](https://live.european-language-grid.eu/)
* [Freesound](https://freesound.org/)
* [ISCA Archive](https://www.isca-archive.org/)
* [Magic Data](https://www.magicdatatech.com/)
* [OpenSLR.org](http://www.openslr.org)
* [TorchAudio](https://github.com/pytorch/audio)
* [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/overview)
* [Voicebank](https://www.voicebank.ie/)

### Closed Source

* [ELRA Catalogue of Language Resources](https://catalogue.elra.info/)
* [Linguistic Data Consortium](https://www.ldc.upenn.edu/)

### Contain Both Open and Closed Sources

* [TalkBank](https://ca.talkbank.org/)
* [Zenodo](https://zenodo.org/)

---
