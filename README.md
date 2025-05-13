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

### Timeless

|    | Dataset                                           | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Keyword Spotting | Audio-Visual(AV) | Download                                                                                               | Multilingual | Source                                                                                     | Version | Paper                                                                                                                                                                                                                                                             | Interspeech | Description                                                                                                                                                                                                                                                                                                                        |
|----|---------------------------------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|------------------|------------------|--------------------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | Common Voice                                      | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [Common Voice](https://commonvoice.mozilla.org/en/datasets)                                            | True         | Mozilla Foundation                                                                         | 21      |                                                                                                                                                                                                                                                                   |             | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed).                                                                                                                                                                                                                          |
| 2  | Multilingual LibriSpeech (MLS)                    | True                               | True                |                     | True                   | True                 |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [facebook/multilingual_librispeech](https://huggingface.co/datasets/facebook/multilingual_librispeech) | True         | Facebook / Meta                                                                            | 1       |                                                                                                                                                                                                                                                                   |             | Multilingual LibriSpeech (MLS) is a large-scale multilingual corpus derived from LibriVox audiobooks, encompassing eight languages and designed to support research in speech processing tasks.                                                                                                                                    |
| 3  | People's Speech                                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech)                   |              | MLCommons                                                                                  | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344)                                                                                                                            |             | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA.                                                                                                                                  |
| 4  | VoxCeleb                                          | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                                   | True         | University of Oxford                                                                       | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                                                                                                                                                   |             | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                                                                                                                                    |
| 5  | VoxConverse                                       |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  | True             | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                                            |              | University of Oxford                                                                       |         | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                                                                                                                                                        |             | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                                                                                                                              |
| 6  | CHiME                                             | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [CHiME-6](https://openslr.org/150/)                                                                    |              | University of Sheffield                                                                    | 6       | [CHiME-6 Challenge:Tackling Multispeaker Speech Recognition for Unsegmented Recordings](https://arxiv.org/abs/2004.09249)                                                                                                                                         |             | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research.                                                                                                                                                                    |
| 7  | Speech-MASSIVE                                    | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   | True                                | True                    | True                          | True                 |            |                   |                          |                  |                  | [FBK-MT/Speech-MASSIVE](https://huggingface.co/datasets/FBK-MT/Speech-MASSIVE)                         | True         | NAVER LABS                                                                                 |         | [Speech-MASSIVE: A Multilingual Speech Dataset for SLU and Beyond](https://arxiv.org/abs/2408.03900)                                                                                                                                                              | True        | Speech-MASSIVE is a publicly released multilingual speech dataset containing over 70 000 recordings in 12 typologically diverse languages, annotated for intent prediction and slot filling and designed to support SLU, ASR, language identification, and speech translation research.                                            |
| 8  | SPGISpeech                                        | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [kensho/spgispeech](https://huggingface.co/datasets/kensho/spgispeech)                                 |              | Kensho                                                                                     |         | [SPGISpeech: 5,000 hours of transcribed financial audio for fully formatted end-to-end speech recognition](https://arxiv.org/abs/2104.02014)                                                                                                                      | True        | SPGISpeech is a 5,000-hour, fully formatted, end-to-end English speech-to-text corpus of professionally transcribed financial earnings calls, released free for non-commercial use.                                                                                                                                                |
| 9  | DAPS (Device and Produced Speech)                 |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [DAPS (Device and Produced Speech) Dataset](https://zenodo.org/records/4660670)                        |              | Adobe Research / Center for Computer Research in Music and Acoustics (Stanford University) |         | [Can we Automatically Transform Speech Recorded on Common Consumer Devices in Real-World Environments into Professional Production Quality Speech? — A Dataset, Insights, and Challenges](https://ccrma.stanford.edu/~gautham/Site/daps_files/mysore-spl2015.pdf) |             | Thought for a couple of seconds The DAPS dataset is an aligned corpus of clean, professionally produced, and consumer-device recorded speech samples designed to train and evaluate algorithms that transform everyday recordings into studio-quality audio.                                                                       |
| 10 | DipCo (Dinner Party Corpus)                       | True                               |                     |                     | True                   |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            | True              |                          |                  |                  | [DiPCo -- Dinner Party Corpus](https://zenodo.org/records/8122551)                                     |              | Amazon                                                                                     |         | [DiPCo -- Dinner Party Corpus](https://arxiv.org/abs/1909.13447)                                                                                                                                                                                                  | True        | The Dinner Party Corpus (DiPCo) is a multi-microphone dataset of natural English dinner-table conversations designed for benchmarking noise-robust and distant speech processing tasks.                                                                                                                                            |
| 11 | AMI Corpus                                        | True                               |                     | True                |                        |                      |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      | True       |                   | True                     |                  |                  | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/index.shtml)                                       |              | University of Edinburgh                                                                    |         | [RECOGNITION AND UNDERSTANDING OF MEETINGS THE AMI AND AMIDA PROJECTS](https://www.cstr.ed.ac.uk/downloads/publications/2007/ami-asru2007.pdf)                                                                                                                    |             | The AMI Corpus is a publicly available 100-hour multimodal dataset of English four-person meetings recorded in instrumented rooms with synchronized audio, video, and pen/whiteboard streams, richly annotated for orthographic transcripts, dialogue acts, topic segmentation, summarization, named entities, gestures, and more. |
| 12 | nEMO                                              | True                               |                     | True                |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [amu-cai/nEMO](https://huggingface.co/datasets/amu-cai/nEMO)                                           |              | Adam Mickiewicz University                                                                 |         | [nEMO: Dataset of Emotional Speech in Polish](https://arxiv.org/abs/2404.06292)                                                                                                                                                                                   |             | nEMO is a Creative Commons-licensed corpus of 4,481 Polish speech recordings by nine actors portraying six emotions (anger, fear, happiness, sadness, surprise, neutral), each with audio, orthographic and normalized transcriptions, and speaker metadata, designed for speech emotion recognition, ASR, and TTS research.       |
| 13 | MS-SNSD (Microsoft Scalable Noisy Speech Dataset) |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          |                  |                  | [microsoft/MS-SNSD](https://github.com/microsoft/MS-SNSD)                                              |              | Microsoft                                                                                  |         | [A Scalable Noisy Speech Dataset and Online Subjective Test Framework](https://arxiv.org/abs/1909.08050)                                                                                                                                                          | True        | The Microsoft Scalable Noisy Speech Dataset (MS-SNSD) is an open-source collection of paired clean and noisy English speech clips—augmented with diverse noise types and configurable SNR levels—to facilitate scalable training and evaluation of deep learning–based speech enhancement models.                                  |
| 14 | Speech Commands Dataset                           |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | True             |                  | [torchaudio.datasets.SPEECHCOMMANDS](https://docs.pytorch.org/audio/stable/datasets.html)              |              | Google                                                                                     | 2       | [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)                                                                                                                                                          |             | The Speech Commands dataset is a publicly available collection of one-second English audio clips of 35 distinct spoken words, designed to train and benchmark small-footprint, on-device keyword-spotting models.                                                                                                                  |
| 15 | Spoken Wikipedia Corpora                          | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          |                  |                  | [The Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                                            | True         | Hamburg University                                                                         | 2       | [Mining the Spoken Wikipedia for Speech Data and Beyond](https://aclanthology.org/L16-1735/)                                                                                                                                                                      |             | The Spoken Wikipedia Corpus is a freely licensed, multilingual dataset of time-aligned audio recordings and text transcripts of Wikipedia articles, produced via an automated scraping and alignment pipeline.                                                                                                                     |

### Queue

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
* EmoFilm
* MuSe-CAR
* SINGA:PURA
* AVSpeech

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

| Index | Dataset                                                             | Description |
|-------|---------------------------------------------------------------------|-------------|
| 1     | AESDD                                                               |             |
| 2     | ANAD                                                                |             |
| 3     | Arabic Speech Corpus                                                |             |
| 4     | AudioMNIST                                                          |             |
| 5     | BAVED                                                               |             |
| 6     | CALLHOME American English Speech                                    |             |
| 7     | Café                                                                |             |
| 8     | Coswara                                                             |             |
| 9     | CREMA-D                                                             |             |
| 10    | DAPS                                                                |             |
| 11    | DCASE 2014                                                          |             |
| 12    | DEEP-VOICE                                                          |             |
| 13    | DEMoS                                                               |             |
| 14    | DIHARD Datasets                                                     |             |
| 15    | EMOVO                                                               |             |
| 16    | Emo-DB                                                              |             |
| 17    | EmoSynth                                                            |             |
| 18    | EmoV-DB                                                             |             |
| 19    | EPIC-KITCHENS-100                                                   |             |
| 20    | EPIC-SOUNDS                                                         |             |
| 21    | eNTERFACE05                                                         |             |
| 22    | ESC-50                                                              |             |
| 23    | Fisher English Training Speech                                      |             |
| 24    | Flickr Audio Caption Corpus                                         |             |
| 25    | Free Spoken Digit Dataset                                           |             |
| 26    | FSD50K                                                              |             |
| 27    | GEMEP corpus                                                        |             |
| 28    | Hume-VB                                                             |             |
| 29    | HumBug Zooniverse                                                   |             |
| 30    | IBM Voicemail Corpus                                                |             |
| 31    | ICSI Corpus                                                         |             |
| 32    | IEMOCAP                                                             |             |
| 33    | InfantMarmosetsVox                                                  |             |
| 34    | Infobip AMD                                                         |             |
| 35    | ISOLET                                                              |             |
| 36    | JL corpus                                                           |             |
| 37    | Keio-ESD                                                            |             |
| 38    | LEGO Spoken Dialogue Corpus                                         |             |
| 39    | Libri-Adapt                                                         |             |
| 40    | Libri-Mixed-Speakers                                                |             |
| 41    | LibriCSS                                                            |             |
| 42    | LibriMix                                                            |             |
| 43    | LibriTTS                                                            |             |
| 44    | LibriTTS-R                                                          |             |
| 45    | LJSpeech-1.1                                                        |             |
| 46    | MELD (Multimodal EmotionLines Dataset)                              |             |
| 47    | MeerKAT: Meerkat Kalahari Audio Transcripts                         |             |
| 48    | Mini LibriSpeech                                                    |             |
| 49    | MSP Podcast Corpus                                                  |             |
| 50    | MSP-IMPROV                                                          |             |
| 51    | MSNER                                                               |             |
| 52    | MSR-86K                                                             |             |
| 53    | Mudestreda (Mudestreda Multimodal Device State Recognition Dataset) |             |
| 54    | Multimodal PISA (Multimodal Piano Skills Assessment)                |             |
| 55    | NTIMIT                                                              |             |
| 56    | OGVC                                                                |             |
| 57    | PC-GITA                                                             |             |
| 58    | PCVC (Persian Consonant Vowel Combination)                          |             |
| 59    | RAVDESS                                                             |             |
| 60    | RECOLA                                                              |             |
| 61    | ReefSet                                                             |             |
| 62    | Respiratory and Drug Actuation Dataset                              |             |
| 63    | Russian LibriSpeech                                                 |             |
| 64    | SAVEE                                                               |             |
| 65    | SEWA                                                                |             |
| 66    | SEMAINE                                                             |             |
| 67    | ShEMO                                                               |             |
| 68    | SparseLibriMix                                                      |             |
| 69    | Speech Accent Archive                                               |             |
| 70    | Speech Wikimedia                                                    |             |
| 71    | Spotify Podcast Datase                                              |             |
| 72    | Spiking Heidelberg Digits (SHD)                                     |             |
| 73    | Spiking Speech Commands (SSC)                                       |             |
| 74    | TAU-NIGENS Spatial Sound                                            |             |
| 75    | Tatoeba                                                             |             |
| 76    | TESS                                                                |             |
| 77    | Thorsten-Voice                                                      |             |
| 78    | TIMIT                                                               |             |
| 79    | VCTK (CSTR VCTK Corpus)                                             |             |
| 80    | VCTK-2Mix                                                           |             |
| 81    | VGG-Sound                                                           |             |
| 82    | VGGSound-Sparse                                                     |             |
| 83    | VIVAE                                                               |             |
| 84    | VocalSound                                                          |             |
| 85    | VoxBlink                                                            |             |
| 86    | Wavix Voicemail                                                     |             |
| 87    | Wikimedia Commons                                                   |             |
| 88    | aGender                                                             |             |

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
