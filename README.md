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
        * [1995-2000](#1995-2000)
        * [2000-2005](#2000-2005)
        * [2005-2010](#2005-2010)
        * [2010-2015](#2010-2015)
        * [2015-2020](#2015-2020)
        * [2020-2025](#2020-2025)

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

#### 1995-2000

#### 2000-2005

#### 2005-2010

#### 2010-2015

| Index | Dataset | Main Task | Sub-Task(s) | Multilingual | Source                           | Year | Derived |
|-------|---------|-----------|-------------|--------------|----------------------------------|------|---------|
|       | aGender |           |             |              | Deutsche Telekom AG Laboratories | 2010 |         |

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

#### 2015-2020

| Index | Dataset              | Main Task                        | Sub-Task(s) | Multilingual | Source                               | Year | Derived |
|-------|----------------------|----------------------------------|-------------|--------------|--------------------------------------|------|---------|
|       | Arabic Speech Corpus | Speech Synthesis                 |             |              | University of Southampton            | 2016 |         |
|       | AudioSet             |                                  |             |              | Google Inc.                          | 2017 |         |
|       | AESDD                | Speech Emotion Recognition (SER) |             |              | Aristotle University of Thessaloniki | 2018 |         |

1. Arabic Speech Corpus

   The Arabic Speech Corpus (≈ 1.5 GB) is an original Modern Standard Arabic dataset created at the University of
   Southampton by PhD researcher Nawar Halabi for high-quality text-to-speech synthesis. Comprising over 3.7 hours of
   professionally recorded Damascene-accent speech, it supplies time-aligned phoneme-level labels and explicit
   word-stress annotations, allowing researchers not only to build natural-sounding Arabic TTS voices (as already
   demonstrated) but also to explore auxiliary tasks such as phoneme segmentation, stress and prosody modelling, and
   other Arabic speech studies. The recordings are newly produced in-house, so the corpus is not derived from any prior
   dataset, and it is monolingual Arabic. [Modern Standard Arabic Phonetics for Speech Synthesis][2]

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
   systems. [Audio Set: An ontology and human-labeled dataset for audio events][3]

3. AESDD

   Published in 2018 in the Journal of the Audio Engineering Society, the study from Aristotle University of
   Thessaloniki presents the Acted Emotional Speech Dynamic Database (AESDD)—an acted-speech corpus recorded for
   core speech-emotion recognition (SER) research and benchmarked against the English-language SAVEE set. AESDD was
   initially built in Greek, but the authors stress that the “dynamic” repository is already being enriched with
   new recordings in both Greek and English, enabling broader cross-lingual experiments while remaining
   predominantly Greek at this stage. Beyond supplying training data, the paper demonstrates live SER that can drive
   emotion-aware stage lighting, interactive actor training and audience-engagement tools, as well as automated
   archiving and retrieval of theatrical performances, illustrating the dataset’s dual technical and creative
   value. [Speech Emotion Recognition for Performance Interaction][4]

#### 2020-2025

| Index | Dataset    | Main Task                          | Sub-Task(s)                                                                                        | Multilingual | Source                                                                               | Year | Derived       |
|-------|------------|------------------------------------|----------------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------|------|---------------|
|       | Att-HACK   | Speech Synthesis                   | Speech Emotion Recognition (SER)                                                                   |              | STMS-Lab – IRCAM / CNRS / Sorbonne Université                                        | 2020 |               |
|       | AliMeeting | Automatic Speech Recognition (ASR) | Speaker Verification, Speech Enhancement, Speech Separation, Speech Segmentation, Overlap Handling |              | Alibaba Group Speech Lab (China & Singapore), Beijing Shell Tech, AISHELL Foundation | 2022 |               |
|       | Audiocite  |                                    | Automatic Speech Recognition (ASR), Speaker Verification                                           |              | Univ. Grenoble Alpes, CNRS, Grenoble INP, LIG                                        | 2024 | audiocite.net |

1. Att-HACK

   Att-HACK is a freely available French database released in 2020 by the STMS-Lab (IRCAM / CNRS / Sorbonne Université)
   to push research on expressive speech and social attitudes beyond the usual “basic-emotion” corpora. It contains
   roughly 30 hours of studio-quality speech in which 25 actors each read 100 short French sentences while deliberately
   portraying four interpersonal attitudes – friendly, seductive, dominant, and distant – with 3-5 prosodically varied
   repetitions per sentence, yielding more than 22 000 utterances so far. Besides waveform audio, the release includes
   orthographic text, forced phonetic alignments and raw F0 tracks. While primarily intended for modelling and
   synthesising prosody in socially-expressive TTS systems, the rich, repeated renditions also suit side tasks such as
   social-attitude or emotion recognition, prosody analysis, and neutral-to-expressive voice conversion. The corpus is
   entirely original (not derived from earlier data) and is monolingual French, distributed for academic use under a
   Creative-Commons licence. [Att-HACK: An Expressive Speech Database with Social Attitudes][5]


1. AliMeeting

   The M2MeT Challenge, introduced at ICASSP 2022, provides the first large-scale public benchmark for multi-channel,
   multi-speaker Mandarin meeting transcription. Developed jointly by Alibaba Group’s Speech Labs, Beijing Shell Tech,
   and the AISHELL Foundation, the release centres on AliMeeting, a 120-hour corpus of real meetings recorded with an
   8-microphone circular array plus parallel headset tracks, covering 2-4 participants, diverse rooms and a high (≈42 %)
   overlap ratio. The challenge defines two core tasks—speaker diarization and multi-speaker automatic speech
   recognition (ASR)—with sub-tracks that either restrict or allow external data (notably AISHELL-4 and CN-Celeb). By
   supplying time-aligned transcriptions, per-speaker head-set audio and far-field array recordings, the dataset also
   supports front-end enhancement and separation research. Although multilingual corpora exist for English, M2MeT fills
   a critical gap for Mandarin, enabling reproducible research on real-world meeting processing and advancing
   “who-spoke-what-when” technology in
   Chinese. [M2MeT: The ICASSP 2022 Multi-Channel Multi-Party Meeting Transcription Challenge][6]

2. Audiocite

   Published in 2024, Audiocite.net: A Large Spoken Read Dataset in French introduces a 6,682-hour corpus of
   volunteer-read audiobooks harvested from the Audiocité platform by researchers at Université Grenoble Alpes / CNRS /
   Grenoble INP / LIG. Created to fuel self-supervised pre-training for French speech models, the monolingual French
   dataset also supports downstream tasks such as ASR and speaker verification, and—despite lacking transcriptions—is
   suitable for topic modelling, signal reconstruction and speech synthesis research. Entirely sourced from
   Creative-Commons licensed audiobooks, Audiocite.net fills the size gap between English and French resources and has
   already been used to boost the 14 k-hour LeBenchmark models, demonstrating its practical impact on French speech
   technology. [Audiocite.net: A Large Spoken Read Dataset in French][7]

---

* AudioMNIST
* BAVED
* BibleTTS
* CALLHOME American English Speech
* Café
* ClovaCall
* CML-TTS
* CMU-MOSEI
* CN-CELEB
* Common Phone
* Coswara
* CoVoST
* CoVoST2
* CVSS
* DAPS
* DCASE 2014
* DEEP-VOICE
* DEMoS
* Earnings-21
* EasyCom
* Europarl-ST
* EMOVO
* Emo-DB
* EmoSynth
* EmoV-DB
* EPIC-KITCHENS-100
* EPIC-SOUNDS
* EMNS
* EmoFilm
* eNTERFACE05
* Fisher English Training Speech
* Flickr Audio Caption Corpus
* FMFCC-A
* Free Spoken Digit Dataset
* FSD50K
* GEMEP corpus
* GigaST
* Golos
* Hi-Fi TTS (Hi-Fi Multi-Speaker English TTS Dataset)
* HowTo100M
* Hume-VB
* HumBug Zooniverse
* IBM Voicemail Corpus
* ICSI Corpus
* IISc-MILE Kannada ASR Corpus
* IISc-MILE Tamil ASR Corpus
* InfantMarmosetsVox
* Infobip AMD
* Interview
* ISOLET
* JL corpus
* KazakhTTS
* KSC (Kazakh Speech Corpus)
* Keio-ESD
* Kosp2e
* LEGO Spoken Dialogue Corpus
* Libri-Adapt
* Libri-Mixed-Speakers
* LibriCSS
* LibriMix
* LibriTTS
* LibriTTS-R
* LJSpeech
* LJSpeech-1.1
* MaSS
* MeerKAT: Meerkat Kalahari Audio Transcripts
* Mini LibriSpeech
* MobvoiHotwords
* Mohammed
* MOSI
* MRDA (ICSI Meeting Recorder Dialog Act Corpus)
* MSP Podcast Corpus
* MSNER
* Mudestreda (Mudestreda Multimodal Device State Recognition Dataset)
* Multimodal PISA (Multimodal Piano Skills Assessment)
* MuSe-CAR
* Nepali Text-to-Speech Data (Male and Female)
* NTIMIT
* OGVC
* ParlamentParla
* PartialSpoof
* PC-GITA
* PCVC (Persian Consonant Vowel Combination)
* PodcastFillers
* PromptSpeech
* PromptTTS
* Puebla-Nahuatl
* RECOLA
* ReefSet
* Respiratory and Drug Actuation Dataset
* ReVerb
* RuLS (Russian LibriSpeech)
* Samrómur Mimic 22.09
* SASPEECH
* SAVEE
* SEWA
* SEMAINE
* SEOUL CORPUS
* SHALCAS22A
* ShEMO
* Silbo Gomero Speech Corpus
* SINGA:PURA (SINGApore: Polyphonic URban Audio)
* SingFake
* SLUE
* SparseLibriMix
* SpeechMatrix
* Speech Accent Archive
* Speech Wikimedia
* SPEECH-COCO
* Speech-MASSIVE
* Spiking Heidelberg Digits (SHD)
* Spiking Speech Commands (SSC)
* SPGISpeech
* Spotify Podcast Datase
* Spoken-SQuAD
* TAU Urban Acoustic Scenes 2019
* TAU-NIGENS Spatial Sound
* Tatoeba
* TESS
* THCHS-30
* Thorsten-Voice
* MC Speech Dataset
* TIMIT
* TUDA
* UGIF
* VCTK-2Mix
* VGG-Sound
* VGGSound-Sparse
* VIVAE
* VocalSound
* VOICES
* Yoloxóchitl-Mixtec
* YouTube-8M
* Wavix Voicemail
* WHAMR!
* Wikimedia Commons
* XBMU-AMDO31
* Zeroth-Korean
* DeToxy
* EasyCall
* REAL-M
* RTASC
* ReMASC
* Talking With Hands 16.2M
* Timers and Such
* ASR-GLUE
* EMOVIE
* LibriVoxDeEn
* NusaCrowd
* RESD
* SpokenSTS
* TaL Corpus (The Tongue and Lips Corpus)
* AV Digits Database
* BD-4SK-ASR
* CI-AVSR
* JVS-MuSiC
* LaboroTVSpeech
* MASRI-HEADSET
* MAVS
* NPSC
* MultiSV
* NeuroVoz
* RyanSpeech
* SDN (Situated Dialogue Navigation)
* AVA-Speech
* AVASpeech-SMAD
* Arabic Speech Commands Dataset
* DR-VCTK
* EVI
* EmoSpeech
* FT Speech
* Greek Parliament Proceedings
* JSS Dataset (Jejueo Single Speaker Speech)
* THVD (Talking Head Video Dataset)
* Kinect-WSJ
* LibriS2S
* MediBeng
* Persian Preschool Cognition Speech
* Quechua-SER
* RUSLAN
* VedantaNY-10M
* MCCSD (Mandarin Chinese Cued Speech Dataset)
* TurkicASR
* UrbanSound8K
* CMUARCTIC
* QUESST 2014
* SNIPS
* YESNO
* AccentDB
* Free Spoken Digit Dataset (FSDD)
* Libri-Light
* LRS3-TED
* CAS-VSR-W1k (LRW-1000)
* GLips
* DIRHA
* BERSt
* CANDOR
* MSP-Podcast
* EmoDB
* LSSED
* Doc2Dial
* Switchboard-1
* CPED (Chinese Personalized and Emotional Dialogue)
* LRW (Lip Reading in the Wild)
* CSS10
* iKala
* FKD (Football Keywords Dataset)
* mDRT
* BABEL Speech Corpus
* WiLI-2018
* Common Language
* NLI-PT
* FUSS (Free Universal Sound Separation)
* Auto-KWS
* AVMIT (Audiovisual Moments in Time)
* Lingala Read Speech Corpus
* Congolese Speech Radio Corpus
* Zambezi Voice
* Friends-MMC
* Laboro-ASV (LaboroTVSpeech-ASV)
* CAVES (Cantonese Audio-Visual Emotional Speech)
* BANSpEmo
* MDER
* EMOVOME
* Spanish MEACorpus 2023
* LibriheavyMix
* Echo2Mix
* RATS Low Speech Density
* BhasaAnuvaad
* AVMuST-TED
* RoDia
* NLSpeech
* Balinese TTS
* Rasa
* IndicVoices-R
* RASwDA (Re-Aligned Switchboard Dialog Act Corpus)
* MOCKS
* WenetPhrase
* MDSC
* LIP-RTVE
* SlideAVSR
* OLKAVS
* AVA Datasets
* DipCo (Dinner Party Corpus)
* Samanantar
* SEP-28k (Stuttering Events in Podcasts)
* GUM
* speechocean762
* MagicData-RAMC
* SwissDials
* Europarl-ASR
* Vāksañcayaḥ (Sanskrit Speech Corpus by IIT Bombay)
* ADIMA
* Samrómur L2 22.09
* MediaSpeech
* Totonac Resources
* ASCEND
* NISP
* NISQA Speech Quality Corpus
* Silent Speech EMG
* VESUS
* DDS (Device-Degraded Speech)
* WSJ0-2mix
* VoxForge
* VOCASET
* JVS corpus
* GRID
* CMU Wilderness Multilingual Speech Dataset
* MuST-C
* LRS2 (Lip Reading Sentences 2)
* MELD (Multimodal EmotionLines Dataset)
* MSP-IMPROV
* CREMA-D
* RAVDESS
* AVA (Atomic Visual Actions)
* Fluent Speech Commands
* MIR Corpora
* NIST SRE (SRE Data)
* SITW
* DIHARD
* Voicebank DEMAND
* SLURP
* Tatoeba
* CMUDict
* Switchboard Dialog Act Corpus (SwDA)
* SGD (Schema-Guided Dialogue)
* AVSpeech
* MIT (Moments in Time Dataset)
* Multilingual LibriSpeech (MLS)
* AISHELL (4)
* ESD (Emotional Speech Database)
* WenetSpeech
* BEAT (Body-Expression-Audio-Text)
* BSTC (Baidu Speech Translation Corpus)
* SOMOS
* DAPS (Device and Produced Speech)
* GigaSpeech
* MS-SNSD (Microsoft Scalable Noisy Speech Dataset)
* Multilingual TEDx
* People's Speech
* Spoken Wikipedia Corpora
* TED-LIUM
* VoxConverse
* VoxPopuli
* WHAM!
* Clarin-PL EMU (Studio Corpus)
* Turkish Speech Corpus
* Multilingual Spoken Words Corpus
* Turkish Neural Voice (turkishvoicedataset)
* VOTE400
* M-AILABS Speech Dataset
* FLEURS
* Czech Parliament Plenary
* SIWIS French Speech Synthesis Database
* MELD-ST
* ETHOS
* Skit-S2I
* DailyTalk
* RedPen
* ASED (Amharic Speech Emotion Dataset)
* GreThE
* HERDPhobia
* ASMDD (Arabic Speech Mispronunciation Detection Dataset)
* TEET
* PodcastMix
* NHSS
* HateXplain
* KeSpeech
* BembaSpeech
* Crowd-Sourced Speech Corpora
* EVBCorpus
* Modality Corpus
* SDS-200
* Lahjoita Puhetta
* MDCC (Multi-Domain Cantonese Corpus)
* 3MASSIV
* MGB
* QASR
* LRS2-BBC
* LRS3-Lang
* JSpeech
* L2-ARCTIC
* MyST Children's Conversational Speech
* National Speech Corpus
* DiDiSpeech
* RVTE database
* KsponSpeech
* Fearless Steps
* Bundestag
* UserLibri
* ReazonSpeech
* Chinese Mandarin Lip Reading (CMLR)
* ParlaSpeech-HR
* VoxLingua107
* JTubeSpeech
* Primewords
* ST-CMDS
* NST Danish ASR Database
* NST Swedish ASR Database
* NST Norwegian ASR Database
* NorGovPCC (The Norwegian Government Press Conference Speech Corpus)
* ARU Speech Corpus
* Althingi Parliamentary Speech Corpus
* Pansori
* ALFFA (African Languages in the Field: speech Fundamentals and Automation)
* Hey Snips
* ACAV100M
* Mead
* PACS
* MAD
* Speech2Gesture
* VideoCC
* DeepMine
* BookTubeSpeech
* CSSD
* Carnatic Varnam Dataset
* Clotho
* CFAD: A Chinese Dataset for Fake Audio Detection
* FestCat
* USPDATRO
* FPT Open Speech Dataset (FOSD) - Vietnamese
* FOSD Female Speech Dataset
* How2
* KdConv
* Libriheavy
* MuAViC
* RealMAN
* WaveFake
* DECRO
* Chichewa
* Middle East Technical University Turkish Microphone Speech
* Turkish Broadcast News Speech and Transcripts
* Apollo Corpus
* Half-Truth
* LaFresCat
* Sagalee
* SMIIP-TV dataset
* Pragmatic Similarity Judgments
* Kallaama
* VietMed
* Neural Audio Fingerprint Dataset
* Jam-ALT
* CAS-VSR-S101
* CUCO Database
* Emozionalmente
* DreamVoice
* AnglistikVoices
* MSNER
* SpeechBrown
* United-MedSyn
* Watch Your Mouth: Point Clouds based Speech Recognition Dataset
* InaGVAD
* SONICS
* FakeMusicCaps
* Granary
* OpenLID
* GlotLID
* MSR-86K
* KazEmoTTS
* KBES
* Dusha
* M5SER
* Divide and Remaster v3 (DnR v3)
* ITALIC
* FalAI
* TextrolSpeech
* MMCSG
* Lombard-GRID-2mix
* MCAS
* TextrolMix
* Hi, KIA
* KAN-AV
* Facestar
* RVTALL
* AVE-Speech
* MSceneSpeech
* StoryTTS
* Speak & Improve Corpus
* Unsupervised People’s Speech
* Helsinki Speech Challenge 2024 open audio dataset
* nEMO
* ODSS
* TIMIT-TTS
* BBS-S2T
* SIFT-50M
* MIVIA Speech Command
* TunSwitch
* DiffSSD
* OOD-Speech
* AS-70
* DisfluencySpeech
* Boli
* SPIRE-SIES
* NaturalVoices
* ArmanTTS
* KSoF (Kassel State of Fluency)
* RIRs (Room Impulse Responses)
* STAIR Captions
* EmoSeC
* RescueSpeech
* ClArTTS
* CORAAL
* Audio-FLAN
* VocalMind
* GTSinger
* Fair-speech Dataset
* 3D-Speaker
* EARS
* EdAcc (Edinburgh International Accents of English Corpus)
* ShiftySpeech
* SlideSpeech
* SpeechCraft
* COVYT
* CitySpeechMix

-2

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

[2]: https://en.arabicspeechcorpus.com/Nawar%20Halabi%20PhD%20Thesis%20Revised.pdf "Modern Standard Arabic Phonetics for Speech Synthesis"

[3]: https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45857.pdf "Audio Set: An ontology and human-labeled dataset for audio events"

[4]: https://www.academia.edu/37375381/Speech_Emotion_Recognition_for_Performance_Interaction "Speech Emotion Recognition for Performance Interaction"

[5]: https://arxiv.org/abs/2004.04410 "Att-HACK: An Expressive Speech Database with Social Attitudes"

[6]: https://arxiv.org/abs/2110.07393 "M2MeT: The ICASSP 2022 Multi-Channel Multi-Party Meeting Transcription Challenge"

[7]: https://aclanthology.org/2024.lrec-main.159 "Audiocite.net: A Large Spoken Read Dataset in French"

