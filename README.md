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
    - [Datasets of the last 5 years(2020-25)](#datasets-of-the-last-5-years2020-25)
    - [Timeless](#timeless)
    - [Queue](#queue)
    - [Unlisted](#unlisted)
- [Hub / Database / Library](#hub--database--library)
    - [Open Source](#open-source)
    - [Closed Source](#closed-source)
    - [Contain Both Open and Closed Sources](#contain-both-open-and-closed-sources)

---

## Overview Table of Datasets

### Datasets of the last 5 years(2020-25)

| Index | Dataset                     | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                             | Multilingual | Source                     | Version | Paper                                                                                                                                  | Interspeech | Description                                                                                                                                                                                                                                                                                                                  |
|-------|-----------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|--------------------------------------------------------------------------------------|--------------|----------------------------|---------|----------------------------------------------------------------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Common Voice                | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [Common Voice](https://commonvoice.mozilla.org/en/datasets)                          | True         | Mozilla Foundation         | 21      |                                                                                                                                        |             | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed).                                                                                                                                                                                                                    |
| 2     | DipCo (Dinner Party Corpus) | True                               |                     |                     | True                   |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            | True              |                          |                  |                  | [DiPCo -- Dinner Party Corpus](https://zenodo.org/records/8122551)                   |              | Amazon                     |         | [DiPCo -- Dinner Party Corpus](https://arxiv.org/abs/1909.13447)                                                                       | True        | The Dinner Party Corpus (DiPCo) is a multi-microphone dataset of natural English dinner-table conversations designed for benchmarking noise-robust and distant speech processing tasks.                                                                                                                                      |
| 3     | nEMO                        | True                               |                     | True                |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [amu-cai/nEMO](https://huggingface.co/datasets/amu-cai/nEMO)                         |              | Adam Mickiewicz University |         | [nEMO: Dataset of Emotional Speech in Polish](https://arxiv.org/abs/2404.06292)                                                        |             | nEMO is a Creative Commons-licensed corpus of 4,481 Polish speech recordings by nine actors portraying six emotions (anger, fear, happiness, sadness, surprise, neutral), each with audio, orthographic and normalized transcriptions, and speaker metadata, designed for speech emotion recognition, ASR, and TTS research. |
| 4     | People's Speech             | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech) |              | MLCommons                  | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344) |             | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA.                                                                                                                            |
| 5     | VoxConverse                 |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                          |              | University of Oxford       | 0.3     | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                             | True        | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                                                                                                                        |

### Timeless

| Index | Dataset                                           | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                                  | Multilingual | Source                                                                                     | Version | Paper                                                                                                                                                                                                                                                             | Interspeech | Description                                                                                                                                                                                                                                                                                                                        |
|-------|---------------------------------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|-------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | AMI Corpus                                        | True                               |                     | True                |                        |                      |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      | True       |                   | True                     |                  |                  | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/index.shtml)                          |              | University of Edinburgh                                                                    |         | [RECOGNITION AND UNDERSTANDING OF MEETINGS THE AMI AND AMIDA PROJECTS](https://www.cstr.ed.ac.uk/downloads/publications/2007/ami-asru2007.pdf)                                                                                                                    |             | The AMI Corpus is a publicly available 100-hour multimodal dataset of English four-person meetings recorded in instrumented rooms with synchronized audio, video, and pen/whiteboard streams, richly annotated for orthographic transcripts, dialogue acts, topic segmentation, summarization, named entities, gestures, and more. |
| 2     | CHiME                                             | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [CHiME-6](https://openslr.org/150/)                                                       |              | University of Sheffield                                                                    | 6       | [CHiME-6 Challenge:Tackling Multispeaker Speech Recognition for Unsegmented Recordings](https://arxiv.org/abs/2004.09249)                                                                                                                                         | True        | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research.                                                                                                                                                                    |
| 3     | DAPS (Device and Produced Speech)                 |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [DAPS (Device and Produced Speech) Dataset](https://zenodo.org/records/4660670)           |              | Adobe Research / Center for Computer Research in Music and Acoustics (Stanford University) |         | [Can we Automatically Transform Speech Recorded on Common Consumer Devices in Real-World Environments into Professional Production Quality Speech? — A Dataset, Insights, and Challenges](https://ccrma.stanford.edu/~gautham/Site/daps_files/mysore-spl2015.pdf) |             | Thought for a couple of seconds The DAPS dataset is an aligned corpus of clean, professionally produced, and consumer-device recorded speech samples designed to train and evaluate algorithms that transform everyday recordings into studio-quality audio.                                                                       |
| 5     | LibriSpeech                                       |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  |                                                                                           |              |                                                                                            |         |                                                                                                                                                                                                                                                                   |             |                                                                                                                                                                                                                                                                                                                                    |
| 6     | MS-SNSD (Microsoft Scalable Noisy Speech Dataset) |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [microsoft/MS-SNSD](https://github.com/microsoft/MS-SNSD)                                 |              | Microsoft                                                                                  |         | [A Scalable Noisy Speech Dataset and Online Subjective Test Framework](https://arxiv.org/abs/1909.08050)                                                                                                                                                          | True        | The Microsoft Scalable Noisy Speech Dataset (MS-SNSD) is an open-source collection of paired clean and noisy English speech clips—augmented with diverse noise types and configurable SNR levels—to facilitate scalable training and evaluation of deep learning–based speech enhancement models.                                  |
| 7     | Speech Commands Dataset                           |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | True             |                  | [torchaudio.datasets.SPEECHCOMMANDS](https://docs.pytorch.org/audio/stable/datasets.html) |              | Google                                                                                     | 2       | [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)                                                                                                                                                          |             | The Speech Commands dataset is a publicly available collection of one-second English audio clips of 35 distinct spoken words, designed to train and benchmark small-footprint, on-device keyword-spotting models.                                                                                                                  |
| 8     | Spoken Wikipedia Corpora                          | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [The Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                               | True         | Hamburg University                                                                         | 2       | [Mining the Spoken Wikipedia for Speech Data and Beyond](https://aclanthology.org/L16-1735/)                                                                                                                                                                      |             | The Spoken Wikipedia Corpus is a freely licensed, multilingual dataset of time-aligned audio recordings and text transcripts of Wikipedia articles, produced via an automated scraping and alignment pipeline.                                                                                                                     |
| 9     | VoxCeleb                                          | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                      | True         | University of Oxford                                                                       | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                                                                                                                                                   | True        | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                                                                                                                                    |

### Queue

* LibriVox
* MASSIVE
* Million Song Dataset
* MuSe-CAR
* SINGA:PURA
* VoxPopuli
* WHAM!
* WHAMR!
* YouTube-8M

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
* AudioSet
* aGender
* ANAD
* Arabic Speech Corpus
* AudioMNIST
* AVSpeech
* BAVED
* CALLHOME American English Speech
* Café
* CMU-MOSEI
* Coswara
* CREMA-D
* DAPS
* DCASE 2014
* DEEP-VOICE
* DEMoS
* DIHARD Datasets
* EMOVO
* Emo-DB
* EmoSynth
* EmoV-DB
* EPIC-KITCHENS-100
* EPIC-SOUNDS
* EmoFilm
* eNTERFACE05
* ESC-50
* Fisher English Training Speech
* Flickr Audio Caption Corpus
* Free Spoken Digit Dataset
* FSD50K
* GEMEP corpus
* HowTo100M
* Hume-VB
* HumBug Zooniverse
* IBM Voicemail Corpus
* ICSI Corpus
* IEMOCAP
* InfantMarmosetsVox
* Infobip AMD
* ISOLET
* JL corpus
* Keio-ESD
* LEGO Spoken Dialogue Corpus
* Libri-Adapt
* Libri-Mixed-Speakers
* LibriCSS
* LibriMix
* LibriTTS
* LibriTTS-R
* LJSpeech-1.1
* MELD (Multimodal EmotionLines Dataset)
* MeerKAT: Meerkat Kalahari Audio Transcripts
* Mini LibriSpeech
* Multilingual LibriSpeech (MLS)
* MSP Podcast Corpus
* MSP-IMPROV
* MSNER
* MSR-86K
* Mudestreda (Mudestreda Multimodal Device State Recognition Dataset)
* Multimodal PISA (Multimodal Piano Skills Assessment)
* NTIMIT
* OGVC
* PC-GITA
* PCVC (Persian Consonant Vowel Combination)
* RAVDESS
* RECOLA
* ReefSet
* Respiratory and Drug Actuation Dataset
* Russian LibriSpeech
* SAVEE
* SEWA
* SEMAINE
* ShEMO
* SparseLibriMix
* Speech Accent Archive
* Speech Wikimedia
* Speech-MASSIVE
* SPGISpeechs
* Spotify Podcast Datase
* Spiking Heidelberg Digits (SHD)
* Spiking Speech Commands (SSC)
* TAU-NIGENS Spatial Sound
* Tatoeba
* TESS
* Thorsten-Voice
* TIMIT
* VCTK (CSTR VCTK Corpus)
* VCTK-2Mix
* VGG-Sound
* VGGSound-Sparse
* VIVAE
* VocalSound
* VoxBlink
* Wavix Voicemail
* Wikimedia Commons

---

## Hub / Database / Library

### Open Source

- [OpenSLR.org](http://www.openslr.org)
- [Sounddata](https://github.com/soundata/)
- [TorchAudio](https://github.com/pytorch/audio)

### Closed Source

- [Linguistic Data Consortium](https://www.ldc.upenn.edu/)

### Contain Both Open and Closed Sources

- [TalkBank](https://ca.talkbank.org/)
- [Zenodo](https://zenodo.org/)

---
