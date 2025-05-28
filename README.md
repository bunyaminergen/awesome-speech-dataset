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
* [References](#references)

---

## Tables of Datasets

### Datasets (2023-25)

| Index | Dataset      | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                     | Multilingual | Source                     | Version | Paper                                                                           | Interspeech | Description                                                                                                                                                                                                                                                                                                                  |
|-------|--------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|--------------------------------------------------------------|--------------|----------------------------|---------|---------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Common Voice | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [Common Voice](https://commonvoice.mozilla.org/en/datasets)  | True         | Mozilla Foundation         | 21      |                                                                                 |             | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed).                                                                                                                                                                                                                    |
| 2     | nEMO         | True                               |                     | True                |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [amu-cai/nEMO](https://huggingface.co/datasets/amu-cai/nEMO) |              | Adam Mickiewicz University |         | [nEMO: Dataset of Emotional Speech in Polish](https://arxiv.org/abs/2404.06292) |             | nEMO is a Creative Commons-licensed corpus of 4,481 Polish speech recordings by nine actors portraying six emotions (anger, fear, happiness, sadness, surprise, neutral), each with audio, orthographic and normalized transcriptions, and speaker metadata, designed for speech emotion recognition, ASR, and TTS research. |
| 3     |              |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                              |              |                            |         |                                                                                 |             |                                                                                                                                                                                                                                                                                                                              |
| 4     |              |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                              |              |                            |         |                                                                                 |             |                                                                                                                                                                                                                                                                                                                              |
| 5     |              |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                              |              |                            |         |                                                                                 |             |                                                                                                                                                                                                                                                                                                                              |
| 6     |              |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                              |              |                            |         |                                                                                 |             |                                                                                                                                                                                                                                                                                                                              |
| 7     |              |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                              |              |                            |         |                                                                                 |             |                                                                                                                                                                                                                                                                                                                              |

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
51. MSceneSpeech
52. StoryTTS
53. YODAS
54. Speak & Improve Corpus
55. Unsupervised People’s Speech
56. Helsinki Speech Challenge 2024 open audio dataset
57. Fair-speech Dataset
58. Casual Conversations
59. ShiftySpeech
60. SpeechCraft
61. ODSS
62. SSSD(Scalable Spontaneous Speech Dataset)
63. BBS-S2T
64. SIFT-50M
65. EmoHopeSpeech
66. CHSER

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

### Unlisted

Reasons for inclusion in the list:

* Insufficient information: Lack of accompanying research paper, missing downloading steps, absence of metadata or
  data dictionary, and unclear or unspecified annotation, dataset sources, or recording/collecting details.

* Extracted/Derived from another dataset:* Dataset has been derived or extracted from another pre-existing dataset.

* Not open source: Limited access due to insufficient publicly available information, many aspects being
  confidential, or availability restricted only to paid access.

* Out of date: Dataset is older than five years, indicating potential obsolescence.

* Specific tasks: Dataset is tailored for highly specialized subtasks or very specific applications.

1. AESDD

   AESDD (Acted Emotional Speech Dynamic Database) is a publicly available Greek‐language speech emotion recognition
   corpus introduced by Vryzas et al., designed to overcome limitations of existing acted SER datasets like SAVEE. It
   comprises around 500 high‐quality studio recordings by five professional actors (two male, three female, aged 25–30),
   each rendering 19 scripted theatrical utterances plus one improvised line across five basic emotions—happiness,
   sadness, anger, fear, and disgust—ensuring that every actor voices the same content in each emotional context; all
   clips are peak‐normalized to –3 dB and meticulously annotated for emotion. AESDD is conceived as an ever‐growing,
   project‐dependent resource, allowing collaborators to augment the database with new samples over time to support more
   robust, generalized emotion recognition models in theatrical and interactive applications, and it is freely
   accessible online for research purposes. [academia.edu][1], [m3c.web.auth.gr][2]

2. Audiocite

   Audiocite.net is a large-scale French speech corpus introduced by Felice et al. (2024) that comprises 6,682 hours of
   audiobook recordings read by 130 volunteer narrators, all harvested from the community‐driven audiocite.net platform;
   the paper details the corpus construction—from data acquisition and cleaning to metadata annotation—providing
   extensive statistics on speaker distribution, recording quality, and text coverage, and demonstrates how pre‐training
   on this dataset measurably boosts the performance of LeBenchmark’s 14k speech models across multiple downstream
   tasks. [aclanthology.org][3], [openslr.org][4]

3. AudioSet

   AudioSet, introduced by Gemmeke et al. in their ICASSP 2017 paper, presents a hierarchical ontology of 635 audio
   classes designed to comprehensively cover real-world sound events. The corresponding dataset comprises 2,084,320
   human-labeled 10-second clips from YouTube (totaling approximately 5.8 thousand hours) annotated across 527 of those
   classes, offering one of the largest multi-label corpora for audio event research. Segments for annotation were
   nominated through metadata, contextual cues (e.g., links), and content-based searches, then verified by human
   annotators to confirm the presence of target sounds. By providing this large-scale, realistic benchmark, AudioSet has
   become a foundational resource driving advances in automatic audio event detection and
   classification. [Google Research][5], [Google Research][6]

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
305. DAPS (Device and Produced Speech)
306. GigaSpeech
307. MS-SNSD (Microsoft Scalable Noisy Speech Dataset)
308. Multilingual TEDx
309. People's Speech
310. Spoken Wikipedia Corpora
311. TED-LIUM
312. VoxConverse
313. VoxPopuli
314. WHAM!
315. Clarin-PL EMU (Studio Corpus)
316. Turkish Speech Corpus
317. Multilingual Spoken Words Corpus
318. Turkish Neural Voice (turkishvoicedataset)
319. ...
320. ...
321. ...
322. ...
323. ...
324. ...
325. ...
326. ...
327. ...
328. ...
329. ...
330. ...
331. ...
332. ...
333. ...
334. ...
335. ...
336. ...
337. ...
338. ...
339. ...
340. ...
341. ...
342. ...
343. ...
344. ...
345. ...
346. ...
347. ...
348. ...
349. ...
350. ...
351. ...
352. ...
353. ...
354. ...
355. ...
356. ...
357. ...
358. ...
359. ...
360. ...
361. ...
362. ...
363. ...
364. ...
365. ...
366. ...
367. ...
368. ...
369. ...
370. ...
371. ...
372. ...
373. ...
374. ...
375. ...
376. ...
377. ...
378. ...
379. ...
380. ...
381. ...
382. ...

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

> **Note:** Please download the Markdown file to view the full list of references — GitHub’s web interface doesn’t
> render reference definitions.


[1]: https://www.academia.edu/37375381/Speech_Emotion_Recognition_for_Performance_Interaction "(PDF) Speech Emotion Recognition for Performance Interaction"

[2]: https://m3c.web.auth.gr/research/aesdd-speech-emotion-recognition/ "Acted Emotional Speech Dynamic Database - AESDD - M3C"

[3]: https://aclanthology.org/2024.lrec-main.159/ "Audiocite.net : A Large Spoken Read Dataset in French"

[4]: https://openslr.org/139/ "Audiocite.net - openslr.org"

[5]: https://research.google.com/pubs/pub45857.html "Audio Set: An ontology and human-labeled dataset for audio events"

[6]: https://research.google.com/audioset/ "AudioSet"
