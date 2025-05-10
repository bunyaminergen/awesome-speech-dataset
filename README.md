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

- [Overview Table of Datasets](#overview-table-of-datasets)
    - [Verified](#verified)
    - [Unverified](#unverified)
    - [Unlisted](#unlisted)
- [Hub](#hub)
    - [TalkBank](#talkbank)
    - [OpenSLR](#openslr)
    - [Linguistic Data Consortium](#linguistic-data-consortium)

---

## Overview Table of Datasets

### Verified

|    | Dataset                                           | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Download                                                                                               | Multilingual | Source                                                                                     | Version | Paper                                                                                                                                                                                                                                                             | Interspeech | Description                                                                                                                                                                                                                                                                                                                        |
|----|---------------------------------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|--------------------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | Common Voice                                      | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [Common Voice](https://commonvoice.mozilla.org/en/datasets)                                            | True         | Mozilla Foundation                                                                         | 21      |                                                                                                                                                                                                                                                                   |             | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed).                                                                                                                                                                                                                          |
| 2  | Multilingual LibriSpeech (MLS)                    | True                               | True                |                     | True                   | True                 |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [facebook/multilingual_librispeech](https://huggingface.co/datasets/facebook/multilingual_librispeech) | True         | Facebook / Meta                                                                            | 1       |                                                                                                                                                                                                                                                                   |             | Multilingual LibriSpeech (MLS) is a large-scale multilingual corpus derived from LibriVox audiobooks, encompassing eight languages and designed to support research in speech processing tasks.                                                                                                                                    |
| 3  | People's Speech                                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech)                   |              | MLCommons                                                                                  | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344)                                                                                                                            |             | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA.                                                                                                                                  |
| 4  | VoxCeleb                                          | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                                   | True         | University of Oxford                                                                       | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                                                                                                                                                   |             | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                                                                                                                                    |
| 5  | VoxConverse                                       |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                                            |              | University of Oxford                                                                       |         | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                                                                                                                                                        |             | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                                                                                                                              |
| 6  | CHiME                                             | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [CHiME-6](https://openslr.org/150/)                                                                    |              | University of Sheffield                                                                    | 6       | [CHiME-6 Challenge:Tackling Multispeaker Speech Recognition for Unsegmented Recordings](https://arxiv.org/abs/2004.09249)                                                                                                                                         |             | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research.                                                                                                                                                                    |
| 7  | Speech-MASSIVE                                    | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   | True                                | True                    | True                          | True                 |            |                   |                          |                  | [FBK-MT/Speech-MASSIVE](https://huggingface.co/datasets/FBK-MT/Speech-MASSIVE)                         | True         | NAVER LABS                                                                                 |         | [Speech-MASSIVE: A Multilingual Speech Dataset for SLU and Beyond](https://arxiv.org/abs/2408.03900)                                                                                                                                                              | True        | Speech-MASSIVE is a publicly released multilingual speech dataset containing over 70 000 recordings in 12 typologically diverse languages, annotated for intent prediction and slot filling and designed to support SLU, ASR, language identification, and speech translation research.                                            |
| 8  | SPGISpeech                                        | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [kensho/spgispeech](https://huggingface.co/datasets/kensho/spgispeech)                                 |              | Kensho                                                                                     |         | [SPGISpeech: 5,000 hours of transcribed financial audio for fully formatted end-to-end speech recognition](https://arxiv.org/abs/2104.02014)                                                                                                                      | True        | SPGISpeech is a 5,000-hour, fully formatted, end-to-end English speech-to-text corpus of professionally transcribed financial earnings calls, released free for non-commercial use.                                                                                                                                                |
| 9  | DAPS (Device and Produced Speech)                 |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [DAPS (Device and Produced Speech) Dataset](https://zenodo.org/records/4660670)                        |              | Adobe Research / Center for Computer Research in Music and Acoustics (Stanford University) |         | [Can we Automatically Transform Speech Recorded on Common Consumer Devices in Real-World Environments into Professional Production Quality Speech? — A Dataset, Insights, and Challenges](https://ccrma.stanford.edu/~gautham/Site/daps_files/mysore-spl2015.pdf) |             | Thought for a couple of seconds The DAPS dataset is an aligned corpus of clean, professionally produced, and consumer-device recorded speech samples designed to train and evaluate algorithms that transform everyday recordings into studio-quality audio.                                                                       |
| 10 | DipCo (Dinner Party Corpus)                       | True                               |                     |                     | True                   |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            | True              |                          |                  | [DiPCo -- Dinner Party Corpus](https://zenodo.org/records/8122551)                                     |              | Amazon                                                                                     |         | [DiPCo -- Dinner Party Corpus](https://arxiv.org/abs/1909.13447)                                                                                                                                                                                                  | True        | The Dinner Party Corpus (DiPCo) is a multi-microphone dataset of natural English dinner-table conversations designed for benchmarking noise-robust and distant speech processing tasks.                                                                                                                                            |
| 11 | AMI Corpus                                        | True                               |                     | True                |                        |                      |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      | True       |                   | True                     |                  | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/index.shtml)                                       |              | University of Edinburgh                                                                    |         | [RECOGNITION AND UNDERSTANDING OF MEETINGS THE AMI AND AMIDA PROJECTS](https://www.cstr.ed.ac.uk/downloads/publications/2007/ami-asru2007.pdf)                                                                                                                    |             | The AMI Corpus is a publicly available 100-hour multimodal dataset of English four-person meetings recorded in instrumented rooms with synchronized audio, video, and pen/whiteboard streams, richly annotated for orthographic transcripts, dialogue acts, topic segmentation, summarization, named entities, gestures, and more. |
| 12 | nEMO                                              | True                               |                     | True                |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  | [amu-cai/nEMO](https://huggingface.co/datasets/amu-cai/nEMO)                                           |              | Adam Mickiewicz University                                                                 |         | [nEMO: Dataset of Emotional Speech in Polish](https://arxiv.org/abs/2404.06292)                                                                                                                                                                                   |             | nEMO is a Creative Commons-licensed corpus of 4,481 Polish speech recordings by nine actors portraying six emotions (anger, fear, happiness, sadness, surprise, neutral), each with audio, orthographic and normalized transcriptions, and speaker metadata, designed for speech emotion recognition, ASR, and TTS research.       |
| 13 | MS-SNSD (Microsoft Scalable Noisy Speech Dataset) |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  | [microsoft/MS-SNSD](https://github.com/microsoft/MS-SNSD)                                              |              | Microsoft                                                                                  |         | [A Scalable Noisy Speech Dataset and Online Subjective Test Framework](https://arxiv.org/abs/1909.08050)                                                                                                                                                          | True        | The Microsoft Scalable Noisy Speech Dataset (MS-SNSD) is an open-source collection of paired clean and noisy English speech clips—augmented with diverse noise types and configurable SNR levels—to facilitate scalable training and evaluation of deep learning–based speech enhancement models.                                  |
| 14 | Speech Commands Dataset                           |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | True             | [torchaudio.datasets.SPEECHCOMMANDS](https://docs.pytorch.org/audio/stable/datasets.html)              |              | Google                                                                                     | 2       | [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)                                                                                                                                                          |             | The Speech Commands dataset is a publicly available collection of one-second English audio clips of 35 distinct spoken words, designed to train and benchmark small-footprint, on-device keyword-spotting models.                                                                                                                  |
| 15 | Spoken Wikipedia Corpora                          | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  | [The Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                                            | True         | Hamburg University                                                                         | 2       | [Mining the Spoken Wikipedia for Speech Data and Beyond](https://aclanthology.org/L16-1735/)                                                                                                                                                                      |             | The Spoken Wikipedia Corpus is a freely licensed, multilingual dataset of time-aligned audio recordings and text transcripts of Wikipedia articles, produced via an automated scraping and alignment pipeline.                                                                                                                     |

### Unverified

* LibriSpeech
* LibriVox
* HowTo100M
* AudioSet
* CMU Wilderness Multilingual Speech Dataset
* CMU-MOSEI
* CMU-MOSI
* WHAM!
* WHAMR!
* VoxPopuli
* Million Song Dataset
* YouTube-8M

*
*
* DAPS Dataset
* DCASE 2014
* Deep Clustering Dataset
* DEMoS
* DES
* DIHARD Challenge datasets
* DIHARD Challenges
* EMOVO
* Emo-DB
* EmoFilm
* EmoSynth
* Emotional Voice dataset - Nature
* Emotional Voices Database
* EmotionTTS
* Emov-DB
* eNTERFACE05
* EPIC-KITCHENS-100
* EPIC-SOUNDS
* Environmental Audio Dataset
* ESC-50
* EPIC-SOUNDS
* EPIC-SOUNDS
* FSD50K
* FSDnoisy18k
* Free Music Archive
* Freesound Dataset
* GEMEP corpus
* ICBHI Respiratory Sound Database
* JL corpus
* Karoldvl-ESC
* Keio-ESD
* LEGO Corpus
* MIS
* MSP Podcast Corpus
* MSP-IMPROV
* MuSe-CAR
* Multimodal EmotionLines Dataset (MELD)
* OGVC
* Parkinson's Speech Dataset
* Persian Consonant Vowel Combination (PCVC) Dataset
* Public Domain Sounds
* RAVDESS
* RSC Sounds
* RECOLA
* SAVEE Dataset
* SEWA
* SER Datasets
* SEMAINE
* ShEMO
* SHD (Spiking Heidelberg Digits)
* SINGA\:PURA
* SSC (Spiking Speech Commands v0.2)
* Tatoeba
* TAU-NIGENS Spatial Sound Events 2021
* Thorsten dataset
* TESS
* URDU-Dataset
* VCTK (CSTR VCTK Corpus)
* VCTK-2Mix
* VIVAE
* VGG-Sound
* VGGSound-Sparse
* Voice Gender Detection
* Zero Resource Speech Challenge

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


- Speech Wikimedia
- AudioMNIST
- Free Spoken Digit Dataset
- MSR-86K
- MSNER
- IEMOCAP
- Spotify Podcast Datase
- Flickr Audio Caption Corpus
- ISOLET
- Libri-Adapt
- LibriCSS
- LibriMix
- SparseLibriMix
- Mini LibriSpeech
- LibriTTS
- Russian LibriSpeech
- Libri-Mixed-Speakers
- LibriTTS-R
- LJSpeech-1.1
- IBM Voicemail Corpus
- Infobip AMD
- Wavix Voicemail
- TIMIT
- NTIMIT
- CALLHOME American English Speech
- Fisher English Training Speech
- ICSI Corpus
- DEEP-VOICE
- Hume-VB
- aGender
- VocalSound
- InfantMarmosetsVox
- MeerKAT: Meerkat Kalahari Audio Transcripts
- Multimodal PISA (Multimodal Piano Skills Assessment)
- PC-GITA
- Respiratory and Drug Actuation Dataset
- ReefSet
- HumBug Zooniverse
- Mudestreda (Mudestreda Multimodal Device State Recognition Dataset)
- Speech Accent Archive
- MSP Podcast Corpus
- PCVC (Persian Consonant Vowel Combination)
- AESDD
- ANAD
- Arabic Speech Corpus
- BAVED
- Café
- Coswara
- CREMA-D
- Wikimedia Commons

### Unreviewed

-

---

## Hub

### TalkBank

- [TalkBank](https://ca.talkbank.org/)

### OpenSLR

- [OpenSLR.org](http://www.openslr.org)

### Linguistic Data Consortium

- [Linguistic Data Consortium](https://www.ldc.upenn.edu/)

---
