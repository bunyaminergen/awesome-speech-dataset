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

### Datasets between 2020-23

| Index | Dataset                     | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                             | Multilingual | Source               | Version | Paper                                                                                                                                                                      | Interspeech | Description                                                                                                                                                                                                                                                                                                                               |
|-------|-----------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|--------------------------------------------------------------------------------------|--------------|----------------------|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | DipCo (Dinner Party Corpus) | True                               |                     |                     | True                   |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            | True              |                          |                  |                  | [DiPCo -- Dinner Party Corpus](https://zenodo.org/records/8122551)                   |              | Amazon               |         | [DiPCo -- Dinner Party Corpus](https://arxiv.org/abs/1909.13447)                                                                                                           | True        | The Dinner Party Corpus (DiPCo) is a multi-microphone dataset of natural English dinner-table conversations designed for benchmarking noise-robust and distant speech processing tasks.                                                                                                                                                   |
| 4     | People's Speech             | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech) |              | MLCommons            | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344)                                     |             | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA.                                                                                                                                         |
| 5     | VoxConverse                 |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                          |              | University of Oxford | 0.3     | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                                                                 | True        | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                                                                                                                                     |
| 6     | VoxPopuli                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [facebook/voxpopuli](https://huggingface.co/datasets/facebook/voxpopuli)             | True         | Facebook / Meta      |         | [VoxPopuli: A Large-Scale Multilingual Speech Corpus for Representation Learning, Semi-Supervised Learning and Interpretation](https://aclanthology.org/2021.acl-long.80/) |             | VoxPopuli is a large-scale multilingual speech corpus comprising 400 000 hours of unlabeled audio in 23 European languages, 1 800 hours of transcribed speech in 15 languages, and 17 300 hours of aligned oral interpretations, designed for unsupervised representation learning, semi-supervised ASR, and speech translation research. |

* GigaSpeech
* Multilingual LibriSpeech (MLS)
* AISHELL (4)
* ESD (Emotional Speech Database)
* WenetSpeech
* BEAT (Body-Expression-Audio-Text)
* Samanantar
* SEP-28k (Stuttering Events in Podcasts)
* GUM
* speechocean762
* BSTC (Baidu Speech Translation Corpus)
* MagicData-RAMC
* SOMOS
* EARS
* SwissDial
* Europarl-ASR
* ADIMA
* Samrómur L2 22.09
* MediaSpeech
* Totonac Resources
* Multilingual TEDx
* ASCEND
* NISP

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

* MUSAN
* WSJ0-2mix
* TED-LIUM
* VoxForge
* VOCASET
* JVS corpus
* GRID

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

* AESDD
* Audiocite
* AudioSet
* aGender
* AliMeeting
* ANAD
* Arabic Speech Corpus
* Att-HACK
* AudioMNIST
* AVSpeech
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
* CoVoST2
* CREMA-D
* CVSS
* DAPS
* DCASE 2014
* DEEP-VOICE
* DEMoS
* DIHARD Datasets
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
* ESC-50
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
* IEMOCAP
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
* LJSpeech-1.1
* MaSS
* MELD (Multimodal EmotionLines Dataset)
* MeerKAT: Meerkat Kalahari Audio Transcripts
* Mini LibriSpeech
* MobvoiHotwords
* Mohammed
* MOSI
* MRDA
* MSP Podcast Corpus
* MSP-IMPROV
* MSNER
* MSR-86K
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
* PromptTTS
* Puebla-Nahuatl
* RAVDESS
* RECOLA
* ReefSet
* Respiratory and Drug Actuation Dataset
* ReVerb
* Russian LibriSpeech
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
* TAU-NIGENS Spatial Sound
* Tatoeba
* TESS
* THCHS-30
* Thorsten-Voice
* The MC Speech Dataset
* TIMIT
* TUDA
* UGIF
* VCTK (CSTR VCTK Corpus)
* VCTK-2Mix
* VGG-Sound
* VGGSound-Sparse
* VIVAE
* VocalSound
* VOICES
* VoxBlink
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
* Arabic Speech Commands Dataset.
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

---

## Hub / Database / Library

### Open Source

* [OpenSLR.org](http://www.openslr.org)
* [Sounddata](https://github.com/soundata/)
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
