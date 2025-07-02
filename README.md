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
    * [Datasets (2023-25)](#2023-25)
    * [Timeless](#timeless)
    * [Other](#other-by-year)
* [Hub / Database / Library](#hub--database--library)
    * [Open Source](#open-source)
    * [Closed Source](#closed-source)
    * [Contain Both Open and Closed Sources](#contain-both-open-and-closed-sources)
* [References](#references)

---

## Tables of Datasets

### 2023-25

| Index | Dataset              | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                    | Multilingual | Source             | Version | Paper | Interspeech | Description                                                                                               |
|-------|----------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|-------------------------------------------------------------|--------------|--------------------|---------|-------|-------------|-----------------------------------------------------------------------------------------------------------|
| 1     | Casual Conversations |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                             |              |                    |         |       |             |                                                                                                           |
| 2     | Common Voice         | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [Common Voice](https://commonvoice.mozilla.org/en/datasets) | True         | Mozilla Foundation | 21      |       |             | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed). |
| 3     | Emilia               |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                             |              |                    |         |       |             |                                                                                                           |
| 4     | Vibravox             |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                             |              |                    |         |       |             |                                                                                                           |
| 5     | VoxBlink             |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                             |              |                    |         |       |             |                                                                                                           |
| 6     | VoxTube              |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                             |              |                    |         |       |             |                                                                                                           |
| 7     | YODAS                |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                             |              |                    |         |       |             |                                                                                                           |

### Timeless

| Index | Dataset                                                    | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                                  | Multilingual | Source                              | Version | Paper                                                                                                                                          | Interspeech | Description                                                                                                                                                                                                                                                                                                                        |
|-------|------------------------------------------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|-------------------------------------------------------------------------------------------|--------------|-------------------------------------|---------|------------------------------------------------------------------------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | AMI Corpus                                                 | True                               |                     | True                |                        |                      |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      | True       |                   | True                     |                  |                  | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/index.shtml)                          |              | University of Edinburgh             |         | [RECOGNITION AND UNDERSTANDING OF MEETINGS THE AMI AND AMIDA PROJECTS](https://www.cstr.ed.ac.uk/downloads/publications/2007/ami-asru2007.pdf) |             | The AMI Corpus is a publicly available 100-hour multimodal dataset of English four-person meetings recorded in instrumented rooms with synchronized audio, video, and pen/whiteboard streams, richly annotated for orthographic transcripts, dialogue acts, topic segmentation, summarization, named entities, gestures, and more. |
| 2     | ATIS (Air Travel Information System)                       |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                     |         |                                                                                                                                                |             |                                                                                                                                                                                                                                                                                                                                    |
| 3     | CHiME                                                      | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [CHiME-6](https://openslr.org/150/)                                                       |              | University of Sheffield             | 6       | [CHiME-6 Challenge:Tackling Multispeaker Speech Recognition for Unsegmented Recordings](https://arxiv.org/abs/2004.09249)                      | True        | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research.                                                                                                                                                                    |
| 4     | Europarl (European Parliament Proceedings Parallel Corpus) |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                     |         |                                                                                                                                                |             |                                                                                                                                                                                                                                                                                                                                    |
| 5     | IEMOCAP                                                    |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                     |         |                                                                                                                                                |             |                                                                                                                                                                                                                                                                                                                                    |
| 6     | LibriSpeech                                                | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [LibriSpeech ASR corpus](https://www.openslr.org/12)                                      |              | Johns Hopkins University            |         | [LIBRISPEECH: AN ASR CORPUS BASED ON PUBLIC DOMAIN AUDIO BOOKS](https://www.danielpovey.com/files/2015_icassp_librispeech.pdf)                 |             | LibriSpeech is a 1,000-hour read English speech corpus derived from public-domain audiobooks, freely available under a CC BY 4.0 license for training and evaluating automatic speech recognition systems.                                                                                                                         |
| 7     | LibriVox                                                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [The LibriVox Free Audiobook Collection](https://archive.org/details/librivoxaudio)       |              | Hugh McGuire & Worldwide Volunteers |         |                                                                                                                                                |             | LibriVox is a volunteer-driven project founded in 2005 to make all public domain books freely available in audio format, with recordings read and shared by volunteers worldwide                                                                                                                                                   |
| 8     | Speech Commands                                            |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | True             |                  | [torchaudio.datasets.SPEECHCOMMANDS](https://docs.pytorch.org/audio/stable/datasets.html) |              | Google                              | 2       | [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)                                       |             | The Speech Commands dataset is a publicly available collection of one-second English audio clips of 35 distinct spoken words, designed to train and benchmark small-footprint, on-device keyword-spotting models.                                                                                                                  |
| 9     | VoxCeleb                                                   | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                      | True         | University of Oxford                | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                                | True        | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                                                                                                                                    |
| 10    | MUSAN                                                      |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                     |         |                                                                                                                                                |             |                                                                                                                                                                                                                                                                                                                                    |
| 11    | VCTK (CSTR VCTK Corpus)                                    |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                     |         |                                                                                                                                                |             |                                                                                                                                                                                                                                                                                                                                    |

### Other (by year)

#### 2010-2020

| Index | Dataset  | Main Task                                | Sub-Task(s)                      | Multilingual | Source                               | Year | Derived |
|-------|----------|------------------------------------------|----------------------------------|--------------|--------------------------------------|------|---------|
| 1     | aGender  | Automated age- and gender-classification | Dialog/persona adaptation in IVR |              | Deutsche Telekom AG Laboratories     | 2010 |         |
| 2     | AudioSet | Audio-event recognition / detection      |                                  |              | Google Inc.                          | 2017 |         |
| 3     | AESDD    | Speech Emotion Recognition (SER)         |                                  |              | Aristotle University of Thessaloniki | 2018 |         |

1. aGender

   Published in 2010 by researchers at Deutsche Telekom Laboratories, this paper presents a 47-hour corpus of German
   telephone speech whose 954 speakers are carefully balanced across seven age-and-gender categories (children, young,
   middle-aged, seniors; male/female where applicable). Collected through six mobile-phone calls per participant and
   augmented by a 659-speaker “VoiceClass” IVR set, the database provides short commands, dates, numbers and free
   responses that mirror real customer-service dialogs. Its primary purpose is to train and evaluate automatic age and
   gender detection for voice portals, but the authors also foresee secondary uses such as persona adaptation in dialog
   systems, target-group advertising, market research and game-style applications. As a purpose-built, monolingual
   German resource—yet methodologically compatible with SpeechDat—it supplies the balanced demographic coverage that
   earlier corpora lacked, enabling more reliable speaker-classification research and an open challenge for the
   community. [A Database of Age and Gender Annotated Telephone Speech][1]

2. AudioSet

   Presented at ICASSP 2017 by researchers at Google, Audio Set delivers a 4,971-hour corpus of more than 1.78 million
   human-labeled 10-second YouTube excerpts that span 632 sound-event categories arranged in a carefully designed
   six-level ontology. Built expressly to push the state of large-scale audio-event recognition, the dataset provides a
   balanced train/test split and a baseline benchmark, while its hierarchical labels support research on multi-label
   classification, ontology-aware learning and broader acoustic-scene analysis. Because the clips are drawn from public
   YouTube content, the collection is inherently language-agnostic—speech in many languages appears, but language itself
   is not annotated—making the resource suitable for any task where the acoustic signature, rather than linguistic
   content, is paramount. Audio Set therefore fills for sound the role that ImageNet played for vision, giving the
   community an open, comprehensive foundation from which to train and compare high-performance audio recognition
   systems. [Audio Set: An ontology and human-labeled dataset for audio events][2]

3. AESDD

   Published in 2018 in the Journal of the Audio Engineering Society, the study from Aristotle University of
   Thessaloniki presents the Acted Emotional Speech Dynamic Database (AESDD)—an acted-speech corpus recorded for
   core speech-emotion recognition (SER) research and benchmarked against the English-language SAVEE set. AESDD was
   initially built in Greek, but the authors stress that the “dynamic” repository is already being enriched with
   new recordings in both Greek and English, enabling broader cross-lingual experiments while remaining
   predominantly Greek at this stage. Beyond supplying training data, the paper demonstrates live SER that can drive
   emotion-aware stage lighting, interactive actor training and audience-engagement tools, as well as automated
   archiving and retrieval of theatrical performances, illustrating the dataset’s dual technical and creative
   value. [Speech Emotion Recognition for Performance Interaction][3]

#### 2020-2025

| Index | Dataset   | Main Task                      | Sub-Task(s)	                                             | Multilingual | Source                                        | Year | Derived       |
|-------|-----------|--------------------------------|----------------------------------------------------------|--------------|-----------------------------------------------|------|---------------|
|       |           |                                |                                                          |              |                                               |      |               |
|       | Audiocite | Self-supervised learning (SSL) | Automatic Speech Recognition (ASR), Speaker Verification |              | Univ. Grenoble Alpes, CNRS, Grenoble INP, LIG | 2024 | audiocite.net |
|       |           |                                |                                                          |              |                                               |      |               |
|       |           |                                |                                                          |              |                                               |      |               |

1. Audiocite

Published in 2024, Audiocite.net: A Large Spoken Read Dataset in French introduces a 6,682-hour corpus of
volunteer-read audiobooks harvested from the Audiocité platform by researchers at Université Grenoble Alpes / CNRS /
Grenoble INP / LIG. Created to fuel self-supervised pre-training for French speech models, the monolingual French
dataset also supports downstream tasks such as ASR and speaker verification, and—despite lacking transcriptions—is
suitable for topic modelling, signal reconstruction and speech synthesis research. Entirely sourced from
Creative-Commons licensed audiobooks, Audiocite.net fills the size gap between English and French resources and has
already been used to boost the 14 k-hour LeBenchmark models, demonstrating its practical impact on French speech
technology. [Audiocite.net: A Large Spoken Read Dataset in French][4]

---

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
100. RuLS (Russian LibriSpeech)
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
130. MC Speech Dataset
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
175. Arabic Speech Commands Dataset
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
289. Voicebank DEMAND
290. SLURP
291. Tatoeba
292. CMUDict
293. Switchboard Dialog Act Corpus (SwDA)
294. SGD (Schema-Guided Dialogue)
295. AVSpeech
296. MIT (Moments in Time Dataset)
297. Multilingual LibriSpeech (MLS)
298. AISHELL (4)
299. ESD (Emotional Speech Database)
300. WenetSpeech
301. BEAT (Body-Expression-Audio-Text)
302. BSTC (Baidu Speech Translation Corpus)
303. SOMOS
304. DAPS (Device and Produced Speech)
305. GigaSpeech
306. MS-SNSD (Microsoft Scalable Noisy Speech Dataset)
307. Multilingual TEDx
308. People's Speech
309. Spoken Wikipedia Corpora
310. TED-LIUM
311. VoxConverse
312. VoxPopuli
313. WHAM!
314. Clarin-PL EMU (Studio Corpus)
315. Turkish Speech Corpus
316. Multilingual Spoken Words Corpus
317. Turkish Neural Voice (turkishvoicedataset)
318. VOTE400
319. M-AILABS Speech Dataset
320. FLEURS
321. Czech Parliament Plenary
322. SIWIS French Speech Synthesis Database
323. MELD-ST
324. ETHOS
325. Skit-S2I
326. DailyTalk
327. RedPen
328. ASED (Amharic Speech Emotion Dataset)
329. GreThE
330. HERDPhobia
331. ASMDD (Arabic Speech Mispronunciation Detection Dataset)
332. TEET
333. PodcastMix
334. NHSS
335. HateXplain
336. KeSpeech
337. BembaSpeech
338. Crowd-Sourced Speech Corpora
339. EVBCorpus
340. Modality Corpus
341. SDS-200
342. Lahjoita Puhetta
343. MDCC (Multi-Domain Cantonese Corpus)
344. 3MASSIV
345. MGB
346. QASR
347. LRS2-BBC
348. LRS3-Lang
349. JSpeech
350. L2-ARCTIC
351. MyST Children's Conversational Speech
352. National Speech Corpus
353. DiDiSpeech
354. RVTE database
355. KsponSpeech
356. Fearless Steps
357. Bundestag
358. UserLibri
359. ReazonSpeech
360. Chinese Mandarin Lip Reading (CMLR)
361. ParlaSpeech-HR
362. VoxLingua107
363. JTubeSpeech
364. Primewords
365. ST-CMDS
366. NST Danish ASR Database
367. NST Swedish ASR Database
368. NST Norwegian ASR Database
369. NorGovPCC (The Norwegian Government Press Conference Speech Corpus)
370. ARU Speech Corpus
371. Althingi Parliamentary Speech Corpus
372. Pansori
373. ALFFA (African Languages in the Field: speech Fundamentals and Automation)
374. Hey Snips
375. ACAV100M
376. Mead
377. PACS
378. MAD
379. Speech2Gesture
380. VideoCC
381. DeepMine
382. BookTubeSpeech
383. CSSD
384. Carnatic Varnam Dataset
385. Clotho
386. CFAD: A Chinese Dataset for Fake Audio Detection
387. FestCat
388. USPDATRO
389. FPT Open Speech Dataset (FOSD) - Vietnamese
390. FOSD Female Speech Dataset
391. How2
392. KdConv
393. Libriheavy
394. MuAViC
395. RealMAN
396. WaveFake
397. DECRO
398. Chichewa
399. Middle East Technical University Turkish Microphone Speech
400. Turkish Broadcast News Speech and Transcripts
401. Apollo Corpus
402. Half-Truth
403. LaFresCat
404. Sagalee
405. SMIIP-TV dataset
406. Pragmatic Similarity Judgments
407. Kallaama
408. VietMed
409. Neural Audio Fingerprint Dataset
410. Jam-ALT
411. CAS-VSR-S101
412. CUCO Database
413. Emozionalmente
414. DreamVoice
415. AnglistikVoices
416. MSNER
417. SpeechBrown
418. United-MedSyn
419. Watch Your Mouth: Point Clouds based Speech Recognition Dataset
420. InaGVAD
421. SONICS
422. FakeMusicCaps
423. Granary
424. OpenLID
425. GlotLID
426. MSR-86K
427. KazEmoTTS
428. KBES
429. Dusha
430. M5SER
431. Divide and Remaster v3 (DnR v3)
432. ITALIC
433. FalAI
434. TextrolSpeech
435. MMCSG
436. Lombard-GRID-2mix
437. MCAS
438. TextrolMix
439. Hi, KIA
440. KAN-AV
441. Facestar
442. RVTALL
443. AVE-Speech
444. MSceneSpeech
445. StoryTTS
446. Speak & Improve Corpus
447. Unsupervised People’s Speech
448. Helsinki Speech Challenge 2024 open audio dataset
449. nEMO
450. ODSS
451. TIMIT-TTS
452. BBS-S2T
453. SIFT-50M
454. MIVIA Speech Command
455. TunSwitch
456. DiffSSD
457. OOD-Speech
458. AS-70
459. DisfluencySpeech
460. Boli
461. SPIRE-SIES
462. NaturalVoices
463. ArmanTTS
464. KSoF (Kassel State of Fluency)
465. RIRs (Room Impulse Responses)
466. STAIR Captions
467. EmoSeC
468. RescueSpeech
469. ClArTTS
470. CORAAL
471. Audio-FLAN
472. VocalMind
473. GTSinger
474. Fair-speech Dataset
475. 3D-Speaker
476. EARS
477. EdAcc (Edinburgh International Accents of English Corpus)
478. ShiftySpeech
479. SlideSpeech
480. SpeechCraft
481. COVYT
482. CitySpeechMix

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

## References

> **Note:** Please download the Markdown file to view the full list of references

[1]: http://www.lrec-conf.org/proceedings/lrec2010/pdf/262_Paper.pdf "A Database of Age and Gender Annotated Telephone Speech"

[2]: https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45857.pdf "Audio Set: An ontology and human-labeled dataset for audio events"

[3]: https://www.academia.edu/37375381/Speech_Emotion_Recognition_for_Performance_Interaction "Speech Emotion Recognition for Performance Interaction"

[4]: https://aclanthology.org/2024.lrec-main.159 "Audiocite.net: A Large Spoken Read Dataset in French"

