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

---

## Overview Table of Datasets

### Verified

|    | Dataset                           | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Answering Machine Detection (AMD) | Spoken Language Understanding (SLU) | Speech Translation (ST) | Language Identification (LID) | Text to Speech (TTS) | Spoken NER | Source separation | Dialogue Act Recognition | Download                                                                                               | Multilingual | Source                                                                                     | Version | Paper                                                                                                                                                                                                                                                             | Interspeech | Description                                                                                                                                                                                                                                                                                                                        |
|----|-----------------------------------|------------------------------------|---------------------|---------------------|------------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|-----------------------------------|-------------------------------------|-------------------------|-------------------------------|----------------------|------------|-------------------|--------------------------|--------------------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | Common Voice                      | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | [Common Voice](https://commonvoice.mozilla.org/en/datasets)                                            | True         | Mozilla Foundation                                                                         | 21      |                                                                                                                                                                                                                                                                   |             | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed).                                                                                                                                                                                                                          |
| 2  | Multilingual LibriSpeech (MLS)    | True                               | True                |                     | True                   | True                 |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | [facebook/multilingual_librispeech](https://huggingface.co/datasets/facebook/multilingual_librispeech) | True         | Facebook / Meta                                                                            | 1       |                                                                                                                                                                                                                                                                   |             | Multilingual LibriSpeech (MLS) is a large-scale multilingual corpus derived from LibriVox audiobooks, encompassing eight languages and designed to support research in speech processing tasks.                                                                                                                                    |
| 3  | People's Speech                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech)                   |              | MLCommons                                                                                  | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344)                                                                                                                            |             | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA.                                                                                                                                  |
| 4  | VoxCeleb                          | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                                   | True         | University of Oxford                                                                       | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                                                                                                                                                   |             | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                                                                                                                                    |
| 5  | VoxConverse                       |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                                            |              | University of Oxford                                                                       |         | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                                                                                                                                                        |             | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                                                                                                                              |
| 6  | CHiME                             | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               |                                   |                                     |                         |                               |                      |            |                   |                          | [CHiME-6](https://openslr.org/150/)                                                                    |              | University of Sheffield                                                                    | 6       | [CHiME-6 Challenge:Tackling Multispeaker Speech Recognition for Unsegmented Recordings](https://arxiv.org/abs/2004.09249)                                                                                                                                         |             | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research.                                                                                                                                                                    |
| 7  | Speech-MASSIVE                    | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   | True                                | True                    | True                          | True                 |            |                   |                          | [FBK-MT/Speech-MASSIVE](https://huggingface.co/datasets/FBK-MT/Speech-MASSIVE)                         | True         | NAVER LABS                                                                                 |         | [Speech-MASSIVE: A Multilingual Speech Dataset for SLU and Beyond](https://arxiv.org/abs/2408.03900)                                                                                                                                                              | True        | Speech-MASSIVE is a publicly released multilingual speech dataset containing over 70 000 recordings in 12 typologically diverse languages, annotated for intent prediction and slot filling and designed to support SLU, ASR, language identification, and speech translation research.                                            |
| 8  | SPGISpeech                        | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            |                   |                          | [kensho/spgispeech](https://huggingface.co/datasets/kensho/spgispeech)                                 |              | Kensho                                                                                     |         | [SPGISpeech: 5,000 hours of transcribed financial audio for fully formatted end-to-end speech recognition](https://arxiv.org/abs/2104.02014)                                                                                                                      | True        | SPGISpeech is a 5,000-hour, fully formatted, end-to-end English speech-to-text corpus of professionally transcribed financial earnings calls, released free for non-commercial use.                                                                                                                                                |
| 9  | DAPS (Device and Produced Speech) |                                    |                     |                     |                        |                      |                   |                                   |                                                                                     | True               |                                   |                                     |                         |                               |                      |            |                   |                          | [DAPS (Device and Produced Speech) Dataset](https://zenodo.org/records/4660670)                        |              | Adobe Research / Center for Computer Research in Music and Acoustics (Stanford University) |         | [Can we Automatically Transform Speech Recorded on Common Consumer Devices in Real-World Environments into Professional Production Quality Speech? — A Dataset, Insights, and Challenges](https://ccrma.stanford.edu/~gautham/Site/daps_files/mysore-spl2015.pdf) |             | Thought for a couple of seconds The DAPS dataset is an aligned corpus of clean, professionally produced, and consumer-device recorded speech samples designed to train and evaluate algorithms that transform everyday recordings into studio-quality audio.                                                                       |
| 10 | DipCo (Dinner Party Corpus)       | True                               |                     |                     | True                   |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               |                      |            | True              |                          | [DiPCo -- Dinner Party Corpus](https://zenodo.org/records/8122551)                                     |              | Amazon                                                                                     |         | [DiPCo -- Dinner Party Corpus](https://arxiv.org/abs/1909.13447)                                                                                                                                                                                                  | True        | The Dinner Party Corpus (DiPCo) is a multi-microphone dataset of natural English dinner-table conversations designed for benchmarking noise-robust and distant speech processing tasks.                                                                                                                                            |
| 11 | AMI Corpus                        | True                               |                     | True                |                        |                      |                   | True                              |                                                                                     |                    |                                   |                                     |                         |                               |                      | True       |                   | True                     | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/index.shtml)                                       |              | University of Edinburgh                                                                    |         | [RECOGNITION AND UNDERSTANDING OF MEETINGS THE AMI AND AMIDA PROJECTS](https://www.cstr.ed.ac.uk/downloads/publications/2007/ami-asru2007.pdf)                                                                                                                    |             | The AMI Corpus is a publicly available 100-hour multimodal dataset of English four-person meetings recorded in instrumented rooms with synchronized audio, video, and pen/whiteboard streams, richly annotated for orthographic transcripts, dialogue acts, topic segmentation, summarization, named entities, gestures, and more. |
| 12 | nEMO                              | True                               |                     | True                |                        |                      |                   |                                   |                                                                                     |                    |                                   |                                     |                         |                               | True                 |            |                   |                          | [amu-cai/nEMO](https://huggingface.co/datasets/amu-cai/nEMO)                                           |              | Adam Mickiewicz University                                                                 |         | [nEMO: Dataset of Emotional Speech in Polish](https://arxiv.org/abs/2404.06292)                                                                                                                                                                                   |             | nEMO is a Creative Commons-licensed corpus of 4,481 Polish speech recordings by nine actors portraying six emotions (anger, fear, happiness, sadness, surprise, neutral), each with audio, orthographic and normalized transcriptions, and speaker metadata, designed for speech emotion recognition, ASR, and TTS research.       |

LibriSpeech
LibriVox
HowTo100M ?

### Unverified

| Dataset                                            | ASR  | Speaker Recognition | Emotion Recognition | SLU (Intent/Slot) | Spoken NER | Speaker Identification |
|:---------------------------------------------------|:-----|:--------------------|:--------------------|:------------------|:-----------|:-----------------------|
| Microsoft Scalable Noisy Speech Dataset            | True |                     |                     |                   |            |                        |
| MSP Podcast Corpus                                 | True |                     |                     |                   |            |                        |
| Persian Consonant Vowel Combination (PCVC) Dataset | True |                     |                     |                   |            |                        |
| Speech Commands Dataset                            | True |                     |                     |                   |            |                        |
| Spoken Commands dataset                            | True |                     |                     |                   |            |                        |
| Spoken Wikipedia Corpora                           | True |                     |                     |                   |            |                        |
| Tatoeba                                            | True |                     |                     |                   |            |                        |
| Zero Resource Speech Challenge                     | True |                     |                     |                   |            |                        |
| Voice Gender Detection                             |      | True                |                     |                   |            |                        |
| RAVDESS                                            |      |                     | True                |                   |            |                        |
| CREMA-D                                            |      |                     | True                |                   |            |                        |
| AESDD                                              |      |                     | True                |                   |            |                        |
| ANAD                                               |      |                     | True                |                   |            |                        |
| BAVED                                              |      |                     | True                |                   |            |                        |
| CaFE                                               |      |                     | True                |                   |            |                        |
| CMU-MOSEI                                          |      |                     | True                |                   |            |                        |
| CMU-MOSI                                           |      |                     | True                |                   |            |                        |
| DEMoS                                              |      |                     | True                |                   |            |                        |
| DES                                                |      |                     | True                |                   |            |                        |
| EEKK                                               |      |                     | True                |                   |            |                        |
| Emo-DB                                             |      |                     | True                |                   |            |                        |
| EmoFilm                                            |      |                     | True                |                   |            |                        |
| EmoSynth                                           |      |                     | True                |                   |            |                        |
| Emotional Voices Database                          |      |                     | True                |                   |            |                        |
| Emotional Voice dataset - Nature                   |      |                     | True                |                   |            |                        |
| EmotionTTS                                         |      |                     | True                |                   |            |                        |
| Emov-DB                                            |      |                     | True                |                   |            |                        |
| EMOVO                                              |      |                     | True                |                   |            |                        |
| eNTERFACE05                                        |      |                     | True                |                   |            |                        |
| GEMEP corpus                                       |      |                     | True                |                   |            |                        |
| JL corpus                                          |      |                     | True                |                   |            |                        |
| Keio-ESD                                           |      |                     | True                |                   |            |                        |
| LEGO Corpus                                        |      |                     | True                |                   |            |                        |
| MSP-IMPROV                                         |      |                     | True                |                   |            |                        |
| Multimodal EmotionLines Dataset (MELD)             |      |                     | True                |                   |            |                        |
| MuSe-CAR                                           |      |                     | True                |                   |            |                        |
| OGVC                                               |      |                     | True                |                   |            |                        |
| RECOLA                                             |      |                     | True                |                   |            |                        |
| SAVEE Dataset                                      |      |                     | True                |                   |            |                        |
| SEMAINE                                            |      |                     | True                |                   |            |                        |
| SER Datasets                                       |      |                     | True                |                   |            |                        |
| SEWA                                               |      |                     | True                |                   |            |                        |
| ShEMO                                              |      |                     | True                |                   |            |                        |
| TESS                                               |      |                     | True                |                   |            |                        |
| URDU-Dataset                                       |      |                     | True                |                   |            |                        |
| VIVAE                                              |      |                     | True                |                   |            |                        |
| VoxPopuli                                          | True |                     |                     |                   |            | True                   |

| Dataset                                                | Download                                                                                           | Description                                                                                                             | Source |
|--------------------------------------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|:------:|
| **CMU Wilderness**                                     | [CMU Wilderness](http://festvox.org/cmu_wilderness/)                                               | Speech dataset with multiple accents reciting passages from the Bible.                                                  |  True  |
| **DAPS Dataset**                                       | [DAPS Dataset](https://archive.org/details/daps_dataset)                                           | 20 speakers reading 5 excerpts each from public domain books (~14 minutes per speaker).                                 |  True  |
| **Microsoft Scalable Noisy Speech Dataset**            | [MS-SNSD](https://github.com/microsoft/MS-SNSD)                                                    | Noisy speech dataset scalable to arbitrary sizes with varying speakers, noise types, and SNR levels.                    |  True  |
| **MSP Podcast Corpus**                                 | [MSP Podcast Corpus](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Podcast.html)      | 100 hours of podcast speech from 100+ speakers, annotated with emotional labels and attribute-based descriptors.        |  True  |
| **Persian Consonant Vowel Combination (PCVC) Dataset** | [PCVC](https://github.com/S-Malek/PCVC)                                                            | Modern Persian speech corpus of consonant-vowel combinations (138 samples per speaker) for ASR and speaker recognition. |  True  |
| **sample_voice_data**                                  | [sample_voice_data](https://github.com/jim-schwoebel/sample_voice_data)                            | 52 audio files per class (male & female) for testing purposes.                                                          |  True  |
| **Speech Commands Dataset**                            | [Speech Commands Dataset](http://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html) | 65,000 one-second utterances of 30 short words for keyword spotting.                                                    |  True  |
| **Spoken Commands dataset**                            | [Spoken Commands dataset](https://github.com/JohannesBuchner/spoken-command-recognition)           | Large database of free audio samples for voice activity detection and syllable recognition.                             |  True  |
| **Spoken Wikipedia Corpora**                           | [Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                                            | 38 GB dataset available in audio and non-audio formats based on Wikipedia articles.                                     |  True  |
| **Tatoeba**                                            | [Tatoeba](https://tatoeba.org/eng/downloads)                                                       | Large database of sentences, translations, and spoken audio for language learning.                                      |  True  |
| **Zero Resource Speech Challenge**                     | [Zero Resource Speech Challenge](https://github.com/bootphon/zerospeech2017)                       | Challenge to build an end-to-end spoken dialogue system from scratch with zero linguistic expertise.                    |  True  |

| Dataset                    | Download                                                                          | Description                                                                   | OpenSource |
|----------------------------|-----------------------------------------------------------------------------------|-------------------------------------------------------------------------------|:----------:|
| **Voice Gender Detection** | [Voice Gender Detection](https://github.com/jim-schwoebel/voice_gender_detection) | GitHub repo for gender detection using the VoxCeleb dataset (7000+ speakers). |    True    |

| Dataset                                    | Download                                                                                                              | Description                                                                                                                 | OpenSource |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|:----------:|
| **RAVDESS**                                | [Zenodo RAVDESS](https://zenodo.org/record/1188976)                                                                   | 7,356 clips of emotional speech and song by 24 professional actors covering 8 emotions.                                     |    True    |
| **CREMA-D**                                | [CREMA-D GitHub](https://github.com/CheyneyComputerScience/CREMA-D)                                                   | 7,442 audio-visual clips from 91 actors performing 12 sentences in 6 emotions with crowd-sourced ratings.                   |    True    |
| **AESDD**                                  | [AESDD](http://m3c.web.auth.gr/research/aesdd-speech-emotion-recognition/)                                            | ~500 utterances by diverse actors simulating various emotions.                                                              |    True    |
| **ANAD**                                   | [ANAD](https://www.kaggle.com/suso172/arabic-natural-audio-dataset)                                                   | 1,384 recordings by multiple speakers with 3 emotions (angry, happy, surprised).                                            |    True    |
| **BAVED**                                  | [BAVED](https://www.kaggle.com/a13x10/basic-arabic-vocal-emotions-dataset)                                            | 1,935 recordings by 61 speakers (45 male, 16 female) focusing on vocal emotion.                                             |    True    |
| **CaFE**                                   | [CaFE](https://www.gel.usherbrooke.ca/audio/cafe.htm)                                                                 | 6 different sentences by 12 speakers (6 females, 6 males) for emotion recognition tasks.                                    |    True    |
| **CMU-MOSEI**                              | [CMU-MOSEI](https://www.amir-zadeh.com/datasets)                                                                      | 65 hours of annotated video and audio data from 1000+ speakers covering 6 emotions plus Likert scale ratings.               |    True    |
| **CMU-MOSI**                               | [CMU-MOSI](https://www.amir-zadeh.com/datasets)                                                                       | 2,199 opinion utterances annotated with sentiment on a seven-point scale.                                                   |    True    |
| **DEMoS**                                  | [DEMoS](https://zenodo.org/record/2544829)                                                                            | 9,365 emotional and 332 neutral samples produced by 68 native speakers.                                                     |    True    |
| **DES**                                    | [DES](http://kom.aau.dk/~tb/speech/Emotions/)                                                                         | Recordings from 4 speakers expressing 5 emotions: neutral, surprise, happiness, sadness, and anger.                         |    True    |
| **EEKK**                                   | [EEKK](https://metashare.ut.ee/repository/download/4d42d7a8463411e2a6e4005056b40024a19021a316b54b7fb707757d43d1a889/) | 26 passages read by 10 speakers in 4 emotions (joy, sadness, anger, neutral).                                               |    True    |
| **Emo-DB**                                 | [Emo-DB](http://emodb.bilderbar.info/index-1280.html)                                                                 | 800 recordings from 10 actors (balanced gender) covering 7 emotions.                                                        |    True    |
| **EmoFilm**                                | [EmoFilm](https://zenodo.org/record/1326428)                                                                          | 1,115 audio instances (sentences extracted from films) with emotional content.                                              |    True    |
| **EmoSynth**                               | [EmoSynth](https://zenodo.org/record/3727593)                                                                         | 144 audio files labeled by 40 listeners in terms of valence and arousal.                                                    |    True    |
| **Emotional Voices Database**              | [Emotional Voices Database](https://github.com/numediart/EmoV-DB)                                                     | Various emotions recorded by 5 voice actors (amused, angry, disgusted, neutral, sleepy).                                    |    True    |
| **Emotional Voice dataset - Nature**       | [Emotional Voice dataset - Nature](https://www.nature.com/articles/s41562-019-0533-6)                                 | 2,519 speech samples from 100 actors across 5 cultures, demonstrating at least 12 distinct emotions.                        |    True    |
| **EmotionTTS**                             | [EmotionTTS](https://github.com/emotiontts/emotiontts_open_db)                                                        | Recordings with transcripts by diverse speakers in 4 emotions (general, joy, anger, sadness) for TTS with emotional nuance. |    True    |
| **Emov-DB**                                | [Emov-DB](https://mega.nz/#F!KBp32apT!gLIgyWf9iQ-yqnWFUFuUHg!mYwUnI4K)                                                | 4-speaker recordings with emotions: neutral, sleepiness, anger, disgust, and amused.                                        |    True    |
| **EMOVO**                                  | [EMOVO](http://voice.fub.it/activities/corpora/emovo/index.html)                                                      | 6 actors reading 14 sentences in 6 emotions: disgust, fear, anger, joy, surprise, and sadness.                              |    True    |
| **eNTERFACE05**                            | [eNTERFACE05](http://www.enterface.net/enterface05/docs/results/databases/project2_database.zip)                      | Videos by 42 subjects from 14 nationalities in 6 emotions.                                                                  |    True    |
| **GEMEP corpus**                           | [GEMEP corpus](https://www.unige.ch/cisa/gemep)                                                                       | 10 actors portraying 10 states covering 12 primary and 5 additional emotions.                                               |    True    |
| **JL corpus**                              | [JL corpus](https://www.kaggle.com/tli725/jl-corpus)                                                                  | 2,400 recordings of 240 sentences by 4 actors; includes 5 primary and 5 secondary emotions.                                 |    True    |
| **Keio-ESD**                               | [Keio-ESD](http://research.nii.ac.jp/src/en/Keio-ESD.html)                                                            | Japanese male speaker dataset covering 47 different emotions.                                                               |    True    |
| **LEGO Corpus**                            | [LEGO Corpus](https://www.ultes.eu/ressources/lego-spoken-dialogue-corpus/)                                           | 347 dialogs (9,083 exchanges) with emotions classified into garbage, non-angry, slightly angry, and very angry.             |    True    |
| **MSP-IMPROV**                             | [MSP-IMPROV](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Improv.html)                                  | 20 sentences by 12 actors covering 4 emotions plus an “other” category.                                                     |    True    |
| **Multimodal EmotionLines Dataset (MELD)** | [MELD](https://github.com/SenticNet/MELD)                                                                             | Over 1,400 dialogues and 13,000 utterances from the TV series *Friends* labeled with 7 emotions.                            |    True    |
| **MuSe-CAR**                               | [MuSe-CAR](https://zenodo.org/record/4134758)                                                                         | 40 hours and 25,000+ sentences from 70+ speakers for emotion recognition research.                                          |    True    |
| **OGVC**                                   | [OGVC](https://sites.google.com/site/ogcorpus/home/en)                                                                | 9,114 spontaneous and 2,656 acted utterances by 4 professional actors covering 9 emotional states.                          |    True    |
| **RECOLA**                                 | [RECOLA](https://diuf.unifr.ch/main/diva/recola/download.html)                                                        | 3.8 hours of recordings from 46 participants with continuous valence and arousal annotations.                               |    True    |
| **SAVEE Dataset**                          | [SAVEE Dataset](http://kahlan.eps.surrey.ac.uk/savee/)                                                                | 480 British English utterances from 4 male actors covering 7 different emotions.                                            |    True    |
| **SEMAINE**                                | [SEMAINE](https://semaine-db.eu/)                                                                                     | 95 dyadic conversations from 21 subjects with 5 FeelTrace annotations.                                                      |    True    |
| **SER Datasets**                           | [SER Datasets](https://github.com/SuperKogito/SER-datasets)                                                           | A collection of datasets aimed at emotion recognition in speech.                                                            |    True    |
| **SEWA**                                   | [SEWA](https://db.sewaproject.eu/)                                                                                    | Over 2,000 minutes of audiovisual data from 398 people with continuous valence and arousal annotations.                     |    True    |
| **ShEMO**                                  | [ShEMO](https://github.com/mansourehk/ShEMO)                                                                          | 3,000 semi-natural utterances (~3h25m) from 87 native-Persian speakers in 6 emotion categories.                             |    True    |
| **TESS**                                   | [TESS](https://tspace.library.utoronto.ca/handle/1807/24487)                                                          | 2,800 recordings by 2 actresses covering 7 emotions.                                                                        |    True    |
| **URDU-Dataset**                           | [URDU-Dataset](https://github.com/siddiquelatif/urdu-dataset)                                                         | 400 utterances by 38 speakers in 4 emotions (angry, happy, neutral, sad).                                                   |    True    |
| **VIVAE**                                  | [VIVAE](https://zenodo.org/record/4066235)                                                                            | 1,085 non-speech audio files from ~12 speakers covering 6 emotions.                                                         |    True    |

| Dataset       | Download                                                          | Description                                                                                                                   | OpenSource |
|---------------|-------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **VoxPopuli** | [VoxPopuli GitHub](https://github.com/facebookresearch/voxpopuli) | European Parliament recordings (2009–2020) in 23 languages; 400,000 hours of unlabeled and 1,800 hours of transcribed speech. |    True    |

| Dataset                     | Download                                                                         | Description                                                                                                          | OpenSource |
|-----------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|:----------:|
| **VCTK (CSTR VCTK Corpus)** | [VCTK Corpus](https://datashare.ed.ac.uk/handle/10283/3443)                      | Multi-speaker English speech corpus with 109 speakers (≈44h total); used for accent-robust TTS and voice conversion. |    True    |
| **Arabic Speech Corpus**    | [Arabic Speech Corpus](http://en.arabicspeechcorpus.com/)                        | Modern Standard Arabic (MSA) TTS corpus (1.5GB) with phonetic and orthographic transcriptions.                       |    True    |
| **EmotionTTS**              | [EmotionTTS](https://github.com/emotiontts/emotiontts_open_db)                   | TTS dataset with recordings in 4 emotions (general, joy, anger, sadness) for emotionally expressive synthesis.       |    True    |
| **Thorsten dataset**        | [Thorsten dataset](https://github.com/thorstenMueller/deep-learning-german-tts/) | German TTS dataset with 22,668 recorded phrases (~23h); ideal for deep-learning based TTS.                           |    True    |

| Dataset                          | Download                                                                    | Description                                                                                                               | OpenSource |
|----------------------------------|-----------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|:----------:|
| **DIHARD Challenge datasets**    | [DIHARD Challenges](https://dihardchallenge.github.io/data.html)            | Diverse, challenging audio datasets from various domains for diarization benchmarking.                                    |    True    |
| **DIHARD Challenges**            | [DIHARD](https://dihardchallenge.github.io/)                                | Regularly updated challenges and datasets for evaluating diarization systems.                                             |    True    |
| **VoxSRC Challenges (VoxCeleb)** | [VoxSRC](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/competition.html)   | Diarization challenge dataset based on VoxCeleb recordings with celebrity conversations.                                  |    True    |

| Dataset                     | Download                                                              | Description                                                                                   | OpenSource |
|-----------------------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|:----------:|
| **Deep Clustering Dataset** | [Deep Clustering Dataset](https://www.merl.com/demos/deep-clustering) | For training deep discriminative embeddings to solve the cocktail party problem.              |    True    |
| **VCTK-2Mix**               | [VCTK-2Mix](https://github.com/JorisCos/VCTK-2Mix)                    | Derived from VCTK and WHAM noise; designed as a test set for source separation experiments.   |    True    |
| **WHAM! and WHAMR!**        | [WHAM! and WHAMR!](http://wham.whisper.ai/)                           | Pairs two-speaker mixtures with real noise backgrounds; WHAMR! adds artificial reverberation. |    True    |

| Dataset                        | Download                                                               | Description                                                                                            | OpenSource |
|--------------------------------|------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|:----------:|
| **Coswara**                    | [Coswara](https://github.com/iiscleap/Coswara-Data)                    | Database of respiratory sounds (cough, breath, speech) from healthy and COVID-19 positive individuals. |    True    |
| **Parkinson's Speech Dataset** | [Parkinson's Speech Dataset](https://archive.org/details/daps_dataset) | Recordings from 20 Parkinson’s patients and 20 healthy subjects across 26 sound types (~20 MB).        |    True    |

| Dataset                            | Download                                                                                                   | Description                                                                                            | OpenSource |
|------------------------------------|------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|:----------:|
| **AudioSet**                       | [AudioSet](https://research.google.com/audioset/)                                                          | Over 2M human-annotated 10-second video clips with a hierarchical ontology of 632 audio event classes. |    True    |
| **Bird Audio Detection Challenge** | [Bird Audio Detection Challenge](http://machine-listening.eecs.qmul.ac.uk/bird-audio-detection-challenge/) | Sound event dataset from live bio-acoustics monitoring projects (~5.4 GB).                             |    True    |
| **Environmental Audio Dataset**    | [Environmental Audio Dataset](http://www.cs.tut.fi/~heittolt/datasets)                                     | Manually annotated environmental audio recordings for sound research.                                  |    True    |
| **Free Music Archive**             | [Free Music Archive](https://github.com/mdeff/fma)                                                         | Approximately 1000 GB dataset for music analysis.                                                      |    True    |
| **Freesound Dataset**              | [Freesound Dataset](https://www.kaggle.com/c/freesound-audio-tagging-2019/data)                            | 678,511 candidate annotations for sound sources in audio clips from Freesound.                         |    True    |
| **Karoldvl-ESC**                   | [ESC-50](https://github.com/karoldvl/ESC-50)                                                               | 2,000 5-second environmental audio clips across 50 classes.                                            |    True    |
| **Million Song Dataset**           | [Million Song Dataset](https://labrosa.ee.columbia.edu/millionsong/)                                       | Audio features and metadata for one million popular music tracks (~280 GB).                            |    True    |
| **MUSDB18**                        | [MUSDB18](https://sigsep.github.io/datasets/musdb.html)                                                    | Multi-track music dataset for source separation (150 tracks, ~22 GB).                                  |    True    |
| **Public Domain Sounds**           | [Public Domain Sounds](http://pdsounds.tuxfamily.org/)                                                     | 524 MB collection of public domain sounds (635 sounds) for tasks like wake word detection.             |    True    |
| **RSC Sounds**                     | [RSC Sounds](https://github.com/2003scape/rsc-sounds)                                                      | 8-bit, u-law encoded, 8000 Hz PCM samples from RuneScape Classic.                                      |    True    |
| **Urban Sound Dataset**            | [Urban Sound Dataset](https://urbansounddataset.weebly.com/)                                               | 8,732 labeled urban sound excerpts (≤4s) from 10 classes.                                              |    True    |

| Dataset                                                                 | Download                                                                                           | Description                                                                                                                                     | OpenSource |
|-------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **AudioSet**                                                            | [AudioSet](https://research.google.com/audioset/)                                                  | Audio event dataset of 10-second clips from YouTube, annotated with a hierarchical ontology of 632 classes.                                     |    True    |
| **Speech Commands**                                                     | [Speech Commands Dataset](http://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html) | Spoken words dataset designed for keyword spotting.                                                                                             |    True    |
| **ESC-50**                                                              | [ESC-50](https://github.com/karoldvl/ESC-50)                                                       | Labeled collection of 2,000 5-second environmental audio recordings across 50 classes.                                                          |    True    |
| **VGG-Sound**                                                           | [VGG-Sound](https://www.robots.ox.ac.uk/~vgg/data/vggsound/)                                       | Over 210k videos covering 310 audio classes, collected from YouTube.                                                                            |    True    |
| **EPIC-KITCHENS-100**                                                   | [EPIC-KITCHENS-100](https://epic-kitchens.github.io/EPIC-Kitchens-100/)                            | 100-hour, 20M-frame, 90K-action egocentric video dataset capturing long-term unscripted activities in 45 environments.                          |    True    |
| **FSD50K**                                                              | [FSD50K](https://zenodo.org/record/4060432)                                                        | Open dataset of 51,197 Freesound clips labeled with 200 classes (AudioSet ontology).                                                            |    True    |
| **UrbanSound8K**                                                        | [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html)                             | 8,732 labeled urban sound excerpts (≤4s) from 10 classes.                                                                                       |    True    |
| **UCR Time Series Classification Archive**                              | [UCR Archive](https://www.cs.ucr.edu/~eamonn/time_series_data/)                                    | Archive of 128 time series datasets widely used for classification research.                                                                    |    True    |
| **DiCOVA**                                                              | [DiCOVA Challenge](https://dcase.community/challenge/2020/task-diCOVA/)                            | Dataset derived from Coswara for detecting COVID-19 from respiratory sounds.                                                                    |    True    |
| **FSDnoisy18k**                                                         | [FSDnoisy18k](https://zenodo.org/record/4060432) *(placeholder)*                                   | Open dataset with 42.5 hours of noisy audio clips across 20 sound event classes.                                                                |    True    |
| **SHD (Spiking Heidelberg Digits)**                                     | [SHD](https://github.com/Neuromorphic-Computing-Group/SHD-dataset)                                 | Spiking version of the Heidelberg Digits dataset, with audio converted into spike trains.                                                       |    True    |
| **ICBHI Respiratory Sound Database**                                    | [ICBHI](https://www.icbhi.org/respiratory-sound-database/)                                         | Respiratory sound dataset originally compiled for the ICBHI 2017 Challenge.                                                                     |    True    |
| **EPIC-SOUNDS**                                                         | [EPIC-SOUNDS](https://epic-kitchens.github.io/EPIC-SOUNDS/)                                        | Large-scale dataset of audio annotations capturing temporal extents and class labels within egocentric video streams.                           |    True    |
| **YouTube-8M**                                                          | [YouTube-100M](https://research.google.com/youtube-100m/)                                          | 100 million YouTube videos with topic labels; extensive audio content; note: labels are machine-generated and may be noisy.                     |    True    |
| **SSC (Spiking Speech Commands v0.2)**                                  | [SSC](https://github.com/neuromorphic-computing-group/SSC)                                         | Spiking version of the Speech Commands dataset generated using an artificial cochlea model.                                                     |    True    |
| **SONYC-UST-V2**                                                        | [SONYC-UST-V2](https://zenodo.org/record/3960431)                                                  | Urban sound tagging dataset from the SONYC acoustic sensor network with spatiotemporal metadata.                                                |    True    |
| **TAU-NIGENS Spatial Sound Events 2021**                                | [TAU-NIGENS](https://zenodo.org/record/4643708)                                                    | Spatial sound-scene recordings with annotated sound events in both microphone array and Ambisonics formats.                                     |    True    |
| **DCASE 2014**                                                          | [DCASE 2014](http://dcase.community/challenge2014/)                                                | Benchmark dataset for audio classification challenges organized in 2014.                                                                        |    True    |
| **VGGSound-Sparse**                                                     | [VGGSound-Sparse](https://github.com/karoldvl/VGGSound-Sparse)                                     | Subset of VGG-Sound containing temporally sparse audio-visual clips for classification.                                                         |    True    |
| **SINGA:PURA**                                                          | [SINGA:PURA](https://github.com/singaporepolytechnic/singa-pura)                                   | Strongly-labelled polyphonic urban sound dataset collected across Singapore for noise monitoring and classification.                            |    True    |
| **Sound-based drone fault classification using multitask learning**     | [Link](https://arxiv.org/abs/2304.11708)                                                           | Dataset for classifying drone faults from audio signals using a multitask learning framework.                                                   |    True    |

### Unlisted

Reasons: Insufficient information, extracted/derived from another dataset, not open source, specific tasks, etc.

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

---

## Hub

### TalkBank

The following table lists the TalkBank CABank corpora—naturalistic conversational recordings amenable to conversation
analysis—and additional related collections. Browse the full CABank online
at [TalkBank](https://ca.talkbank.org/access/).

| Dataset                   | Description                                                                 | OpenSource |
|---------------------------|-----------------------------------------------------------------------------|:----------:|
| **Bergmann**              | German emergency phone calls recorded by Jörg Bergmann.                     |    True    |
| **Bradford**              | Narrative samples from African American adults in Washington, D.C.          |    True    |
| **Business**              | Lingua Franca Business English phone calls.                                 |    True    |
| **CABNC**                 | Spoken language segment of the British National Corpus.                     |    True    |
| **CallFriend**            | Phone calls in Chinese, English, French, German, Japanese, and Spanish.     |    True    |
| **CallHome**              | Phone calls in Arabic, Chinese, English, German, Japanese, and Spanish.     |    True    |
| **CLAPI**                 | French conversations from the CLAPI Project.                                |    True    |
| **CORAAL**                | Corpus of Regional African American Language.                               |    True    |
| **CMU**                   | Conversations collected by CMU students (teaching use only).                |    True    |
| **Croatian**              | Informal conversations of adult speakers in various Croatian dialects.      |    True    |
| **Examples**              | Examples for testing the TalkBank browser.                                  |    True    |
| **Garfinkel-Seminars**    | Lectures by Harold Garfinkel, contributed by Johannes Wagner.               |    True    |
| **GCSAusE**               | Australian conversational recordings.                                       |    True    |
| **Goodwin**               | Conversation analysis video.                                                |    True    |
| **Grimshaw**              | An hour-long dissertation defense.                                          |    True    |
| **GulfWar**               | Radio call-in show discussions during the first Gulf War.                   |    True    |
| **Istriot**               | Conversations of 13 Istriot speakers.                                       |    True    |
| **ISL**                   | Conversations recorded for ASR testing in meetings.                         |    True    |
| **JOC**                   | Eight conversations from a special issue of the Journal of Communication.   |    True    |
| **Mambila**               | Conversations in Mambila.                                                   |    True    |
| **Mesolex**               | Mesolex corpus.                                                             |    True    |
| **MICASE**                | Michigan Corpus of Academic Spoken English.                                 |    True    |
| **Mopan**                 | Mopan narratives.                                                           |    True    |
| **MOVIN**                 | Conversations in Danish, German, French, English, and Italian.              |    True    |
| **Nahuatl**               | Nahuatl story of a shooting.                                                |    True    |
| **Sakura**                | Videotaped conversations of Japanese college students.                      |    True    |
| **SBCSAE**                | Santa Barbara Corpus of Spoken American English.                            |    True    |
| **SCoSE**                 | Saarbrücken Corpus of Spoken (American) English.                            |    True    |
| **SPIRE**                 | HCI design discussions.                                                     |    True    |
| **Taiwan Hakka**          | Conversations and narratives in Taiwan Hakka.                               |    True    |
| **Taiwan Mandarin**       | Conversations in Taiwan Mandarin.                                           |    True    |
| **Yiddish**               | Recordings of Hassidic Jews speaking Yiddish in New York.                   |    True    |
| **Yucatec**               | Storytelling in Yucatec Mayan.                                              |    True    |
| **Jefferson**             | Group transcriptions by Gail Jefferson.                                     |    True    |
| **Lingua Franca**         | Transcriptions by Gail Jefferson.                                           |    True    |
| **Newport Beach**         | Transcriptions by Gail Jefferson.                                           |    True    |
| **Poetics**               | Lecture in Boston (1977) by Gail Jefferson.                                 |    True    |
| **Watergate**             | Transcriptions from Watergate phone calls by Gail Jefferson.                |    True    |
| **Aligned**               | NB and Watergate raw audio files processed through ASR.                     |    True    |
| **SCOTUS**                | US Supreme Court recordings.                                                |    True    |
| **SCOTUS-Blackmun**       | Interview with Justice Henry Blackmun.                                      |    True    |
| **SCOTUS-Douglas**        | Interview with Justice William O. Douglas.                                  |    True    |
| **SCOTUS_Oral_Arguments** | Oral arguments in the US Supreme Court (38 years, each in its own archive). |    True    |

---

### OpenSLR

**OpenSLR** is an initiative to host speech and language resources with stable URLs for research in ASR, speaker
identification, TTS, and related fields. Learn more at [OpenSLR.org](http://www.openslr.org).

| Dataset                          | Description                                                                                                           | OpenSource |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------|:----------:|
| **SLR1: Yesno**                  | 60 recordings of one individual saying yes or no in Hebrew (each 8 words long).                                       |    True    |
| **SLR2: OpenFST**                | Mirror of the OpenFst toolkit.                                                                                        |    True    |
| **SLR3: sph2pipe**               | Mirror of the sph2pipe software.                                                                                      |    True    |
| **SLR4: sctk**                   | Mirror of the sctk scoring software.                                                                                  |    True    |
| **SLR5: MSU Switchboard**        | Transcripts and lexicon for the Switchboard corpus (Mississippi State).                                               |   False    |
| **SLR6: Vystadial**              | English and Czech speech data mirrored from the Vystadial project.                                                    |    True    |
| **SLR7: TED-LIUM**               | English speech corpus from TED talks (created by LIUM).                                                               |    True    |
| **SLR8: Sprakbanken**            | Danish pronunciation dictionary generated using eSpeak.                                                               |    True    |
| **SLR9: The AMI pack**           | Auxiliary non-speech data for building AMI systems with Kaldi.                                                        |    True    |
| **SLR10: SRE Data**              | Various files from SRE data used by NIST.                                                                             |   False    |
| **SLR12: LibriSpeech**           | Large-scale (1000h) corpus of read English speech.                                                                    |    True    |
| **SLR13: RWCP**                  | Database of real-world sounds and room impulse responses (RWCP).                                                      |    True    |
| **SLR14: BEEP Dictionary**       | Phonemic transcriptions of 250,000+ English words (British pronunciations).                                           |    True    |
| **SLR15: SRE Speaker List**      | List linking speakers across NIST SRE corpora.                                                                        |    True    |
| **SLR17: MUSAN**                 | Corpus of music, speech, and noise.                                                                                   |    True    |
| **SLR18: THCHS-30**              | Free Chinese speech corpus released by CSLT@Tsinghua University.                                                      |    True    |
| **SLR19: TED-LIUMv2**            | Second release of the TED-LIUM English speech corpus.                                                                 |    True    |
| **SLR20: Aachen IR**             | Aachen Impulse Response database (AIR).                                                                               |    True    |
| **SLR21: Spanish Word List**     | Spanish word list with frequencies from a large Spanish Gigaword corpus.                                              |    True    |
| **SLR22: THUYG-20**              | Free Uyghur speech database by CSLT@Tsinghua & Xinjiang University.                                                   |    True    |
| **SLR23: NIST LRE 2007 Key**     | Metadata for utterances in the LRE 2007 evaluation.                                                                   |   False    |
| **SLR24: Iban**                  | Iban language text and speech corpora for ASR.                                                                        |    True    |
| **SLR25: ALFFA**                 | African Languages in the Field: includes Amharic, Swahili, Wolof data.                                                |    True    |
| **SLR26: Simulated RIR**         | Database of simulated room impulse responses.                                                                         |    True    |
| **SLR27: Cantab-TEDLIUM**        | Cantab Research Language Models for the TED-LIUM database.                                                            |    True    |
| **SLR28: Room IR & Noise**       | Database of simulated/real room impulse responses and noises (16kHz, 16-bit).                                         |    True    |
| **SLR29: Sprakbanken_Swe**       | Swedish pronunciation dictionary.                                                                                     |    True    |
| **SLR30: Sinhala TTS**           | Sinhalese multi-speaker TTS corpora.                                                                                  |    True    |
| **SLR32: Four South African**    | High-quality TTS data for four South African languages.                                                               |    True    |
| **SLR33: Aishell**               | Mandarin data provided by Beijing Shell Shell Technology Co., Ltd.                                                    |    True    |
| **SLR34: Santiago Spanish**      | Pronouncing dictionary for the Spanish language.                                                                      |    True    |
| **SLR35: Large Javanese**        | Javanese ASR data (~185K utterances).                                                                                 |    True    |
| **SLR36: Large Sundanese**       | Sundanese ASR data (~220K utterances).                                                                                |    True    |
| **SLR37: High-quality TTS (bn)** | Multi-speaker TTS data for Bangladesh and Indian Bengali.                                                             |    True    |
| **SLR38: Free ST Chinese**       | Free Chinese Mandarin corpus by Surfingtech (855 speakers, 102600 utterances).                                        |    True    |
| **SLR39: Heroico**               | Spanish data mirrored from the LDC.                                                                                   |    True    |
| **SLR40: Zeroth-Korean**         | Korean ASR corpus from the Zeroth Project.                                                                            |    True    |
| **SLR41: TTS for Javanese**      | Multi-speaker TTS data for Javanese.                                                                                  |    True    |
| **SLR42: TTS for Khmer**         | Multi-speaker TTS data for Khmer.                                                                                     |    True    |
| **SLR43: TTS for Nepali**        | Multi-speaker TTS data for Nepali.                                                                                    |    True    |
| **SLR44: TTS for Sundanese**     | Multi-speaker TTS data for Sundanese.                                                                                 |    True    |
| **SLR45: Free ST American**      | Free American English corpus by Surfingtech (10 speakers, ~350 utterances each).                                      |    True    |
| **SLR46: Tunisian_MSA**          | Tunisian Modern Standard Arabic speech data.                                                                          |    True    |
| **SLR47: Primewords**            | 100h Chinese Mandarin data from Shanghai Primewords.                                                                  |    True    |
| **SLR48: MADCAT Arabic splits**  | Unofficial data splits for LDC’s MADCAT Arabic corpus.                                                                |    True    |
| **SLR49: VoxCeleb Data**         | Various files for the VoxCeleb datasets.                                                                              |    True    |
| **SLR50: MADCAT Chinese splits** | Unofficial data splits for LDC’s MADCAT Chinese corpus.                                                               |    True    |
| **SLR51: TED-LIUM Release 3**    | Third release of the TED-LIUM corpus.                                                                                 |    True    |
| **SLR52: Large Sinhala**         | Sinhala ASR data (~185K utterances).                                                                                  |    True    |
| **SLR53: Large Bengali**         | Bengali ASR data (~196K utterances).                                                                                  |    True    |
| **SLR54: Large Nepali**          | Nepali ASR data (~157K utterances).                                                                                   |    True    |
| **SLR55: CLMAD**                 | Chinese Language Model Adaptation Dataset.                                                                            |    True    |
| **SLR56: IAM Aachen splits**     | Aachen train/test/val splits for the IAM dataset.                                                                     |    True    |
| **SLR57: African Accented FR**   | Recordings of African-accented French speech.                                                                         |    True    |
| **SLR58: Pansori-TEDxKR**        | Korean speech from TEDx talks.                                                                                        |    True    |
| **SLR59: ParlamentParla**        | Catalan speech from Catalan Parliamentary sessions.                                                                   |    True    |
| **SLR61: Argentinian Spanish**   | Crowdsourced Argentinian Spanish data (~5739 recordings).                                                             |    True    |
| **SLR62: aidatatang_200zh**      | 200h Chinese Mandarin speech corpus from Beijing DataTang.                                                            |    True    |
| **SLR63: Malayalam**             | Crowdsourced Malayalam multi-speaker speech dataset.                                                                  |    True    |
| **SLR64: Marathi**               | Crowdsourced Marathi multi-speaker speech dataset.                                                                    |    True    |
| **SLR65: Tamil**                 | Crowdsourced Tamil multi-speaker speech dataset.                                                                      |    True    |
| **SLR66: Telugu**                | Crowdsourced Telugu multi-speaker speech dataset.                                                                     |    True    |
| **SLR67: TEDx Spanish**          | Spanish data extracted from TEDx Talks.                                                                               |    True    |
| **SLR68: MAGICDATA**             | 755h Mandarin speech from 1080 speakers by Magic Data Technology Co.                                                  |    True    |
| **SLR69: Catalan**               | Crowdsourced high-quality Catalan speech dataset.                                                                     |    True    |
| **SLR70: Nigerian English**      | Crowdsourced high-quality Nigerian English speech dataset.                                                            |    True    |
| **SLR71: Chilean Spanish**       | Crowdsourced high-quality Chilean Spanish speech dataset.                                                             |    True    |
| **SLR72: Colombian Spanish**     | Crowdsourced high-quality Colombian Spanish speech dataset.                                                           |    True    |
| **SLR73: Peruvian Spanish**      | Crowdsourced high-quality Peruvian Spanish speech dataset.                                                            |    True    |
| **SLR74: Puerto Rico Spanish**   | Crowdsourced high-quality Puerto Rico Spanish speech dataset.                                                         |    True    |
| **SLR75: Venezuelan Spanish**    | Crowdsourced high-quality Venezuelan Spanish speech dataset.                                                          |    True    |
| **SLR76: Basque**                | Crowdsourced high-quality Basque speech dataset.                                                                      |    True    |
| **SLR77: Galician**              | Crowdsourced high-quality Galician speech dataset.                                                                    |    True    |
| **SLR78: Gujarati**              | Crowdsourced high-quality Gujarati multi-speaker dataset.                                                             |    True    |
| **SLR79: Kannada**               | Crowdsourced high-quality Kannada multi-speaker dataset.                                                              |    True    |
| **SLR80: Burmese**               | Crowdsourced high-quality Burmese speech dataset.                                                                     |    True    |
| **SLR81: Small Audio Clips**     | 20 one-second audio clips from various sources (for testing).                                                         |    True    |
| **SLR82: CN-Celeb**              | Free Chinese Speaker Recognition corpus by CSLT@Tsinghua University (1,000 speakers).                                 |    True    |
| **SLR83: UK/Irish English**      | Crowdsourced UK/Ireland dialect speech data (male & female).                                                          |    True    |
| **SLR84: ScribbleLens**          | Dutch cursive handwriting (16-18th century pages/lines) for AI research.                                              |    True    |
| **SLR85: HI-MIA**                | Far-field text-dependent speaker verification dataset (AISHELL Speaker Verification Challenge 2019).                  |    True    |
| **SLR86: Yoruba**                | Crowdsourced high-quality Yoruba speech dataset.                                                                      |    True    |
| **SLR87: MobvoiHotwords**        | Chinese hotword detection dataset from Mobvoi Co., Ltd.                                                               |    True    |
| **SLR88: Att-HACK**              | French expressive speech database (social attitudes).                                                                 |    True    |
| **SLR89: Yoloxóchitl-Mixtec**    | Yolóxochitl Mixtec speech with transcription.                                                                         |    True    |
| **SLR92: Puebla-Nahuatl**        | Puebla Nahuatl speech with transcription.                                                                             |    True    |
| **SLR93: AISHELL-3**             | Mandarin TTS data by Beijing Shell Shell Technology (218 speakers, ~85h).                                             |    True    |
| **SLR95: Thorsten Müller**       | Free single German speaker TTS dataset (>23h) by Thorsten Müller & Dominik Kreutz.                                    |    True    |
| **SLR97: Deeply Korean**         | Korean read-speech corpus with 3 text sentiments and 3 vocal sentiments (recorded in 3 places).                       |    True    |
| **SLR98: Deeply Parent-Child**   | Parent-child vocal interaction dataset (fairy tales, songs, etc.) recorded in 3 places at 3 distances via smartphone. |    True    |
| **SLR99: Deeply Nonverbal**      | Human nonverbal vocal sound dataset by Deeply Inc.                                                                    |    True    |
| **SLR100: Multilingual TEDx**    | Multilingual TEDx talks corpus for speech recognition and translation.                                                |    True    |
| **SLR101: speechocean762**       | Pronunciation scoring dataset with each utterance labeled by five human experts.                                      |    True    |
| **SLR102: Kazakh Speech**        | 330h crowdsourced Kazakh corpus by ISSAI.                                                                             |    True    |
| **SLR103: MUCS sub-task1**       | Multilingual/code-switching ASR Challenge datasets for low-resource Indian languages.                                 |    True    |
| **SLR104: MUCS sub-task2**       | Follow-up data for multilingual/code-switching ASR challenges.                                                        |    True    |
| **SLR105: nicolingua-0003**      | West African Radio Corpus.                                                                                            |    True    |
| **SLR106: nicolingua-0004**      | West African Virtual Assistant Speech Recognition Corpus.                                                             |    True    |
| **SLR107: Totonac**              | Totonac speech with transcription.                                                                                    |    True    |
| **SLR108: MediaSpeech**          | French, Arabic, Turkish, and Spanish media speech datasets.                                                           |    True    |
| **SLR109: Hi-Fi TTS**            | Multi-speaker English TTS dataset (Hi-Fi TTS).                                                                        |    True    |
| **SLR110: German Emotional**     | Free emotional single German speaker dataset by Thorsten Müller & Dominik Kreutz.                                     |    True    |
| **SLR111: AISHELL-4**            | Free Mandarin multi-channel meeting corpus (120h).                                                                    |    True    |
| **SLR112: Samromur 21.05**       | Icelandic speech corpus (May 2021 release).                                                                           |    True    |
| **SLR113: SEOUL CORPUS**         | Korean Corpus of Spontaneous Speech from an NRF-funded project.                                                       |    True    |
| **SLR114: Golos**                | Russian ASR dataset (~1240h) with acoustic and language models.                                                       |    True    |
| **SLR115: EmoV_DB**              | Emotional speech database for synthesis/generation (English).                                                         |    True    |
| **SLR116: Samrómur Queries**     | Icelandic speech corpus focused on queries (Dec 2021 release).                                                        |    True    |
| **SLR117: Samrómur Children**    | Icelandic speech from children (ages 4–17, Sep 2021 release).                                                         |    True    |
| **SLR118: 1111 Hours Hindi**     | Data for 1111 Hours Hindi ASR Challenge (closed, self-supervised, open).                                              |    True    |
| **SLR119: AliMeeting**           | Free Mandarin multi-channel meeting corpus by Alibaba Group.                                                          |    True    |
| **SLR120: HI-MIA-CW**            | Free Mandarin supplemental corpus to HI-MIA (negative samples for “Hi, Mia” wake word).                               |    True    |
| **SLR121: WenetSpeech**          | 10,000+ hour multi-domain Mandarin corpus for speech recognition.                                                     |    True    |
| **SLR122: Kashmiri**             | Audio+text corpus for the Kashmiri language.                                                                          |    True    |
| **SLR123: MAGICDATA Convers**    | 180h annotated spontaneous Mandarin speech from Magic Data.                                                           |    True    |
| **SLR124: TIBMD@MUC**            | Tibetan multi-dialect dataset (84.33h).                                                                               |    True    |
| **SLR125: Faroese BLARK**        | Faroese Basic Language Resource Kit 1.0.                                                                              |    True    |
| **SLR126: IISc-MILE Kannada**    | Kannada transcribed speech corpus for ASR.                                                                            |    True    |
| **SLR127: IISc-MILE Tamil**      | Tamil transcribed speech corpus for ASR.                                                                              |    True    |
| **SLR128: Samrómur Unverified**  | Icelandic speech (~2,200h) mostly unverified (July 2022 release).                                                     |    True    |
| **SLR129: BibleTTS**             | Large African multilingual TTS corpus (high fidelity).                                                                |    True    |
| **SLR130: Samrómur L2**          | Icelandic speech (~150h) from L2 (non-native speakers, Jul 2022).                                                     |    True    |
| **SLR131: Samrómur Mimic**       | Icelandic speech (66.7h) where users mimic utterances (Sep 2022).                                                     |    True    |
| **SLR132: Mohammed**             | Arabic speech-to-text Quran data.                                                                                     |    True    |
| **SLR133: XBMU-AMDO31**          | Tibetan Amdo dialect speech data from Northwest Minzu University.                                                     |    True    |
| **SLR134: SASPEECH**             | Hebrew (single speaker, 30h) with transcripts.                                                                        |    True    |
| **SLR136: EMNS**                 | Emotive single-speaker dataset for narrative storytelling (with emotion labels).                                      |    True    |
| **SLR137: Silbo Gomero**         | 49 minutes of Silbo Gomero whistled language from 4 whistlers.                                                        |    True    |
| **SLR138: SHALCAS22A**           | Chinese Mandarin corpus by Shanghai Acoustics Laboratory & Wuxi Sandu.                                                |    True    |
| **SLR139: Audiocite.net**        | French audiobook recordings from audiocite.net.                                                                       |    True    |
| **SLR140: Kazakh Speech (KSD)**  | 554h open-source Kazakh corpus from Al-Farabi Kazakh National University.                                             |    True    |
| **SLR142: The MC Speech**        | Polish speech dataset with 24,018 short clips of a single speaker.                                                    |    True    |
| **SLR143: Nepali TTS**           | Nepali text-to-speech data (male and female).                                                                         |    True    |
| **SLR144: SlideSpeech**          | Large-scale English multi-modal corpus (audio-visual) provided by Alibaba Group.                                      |    True    |
| **SLR146: CML-TTS**              | Multilingual dataset for TTS in low-resource languages.                                                               |    True    |
| **SLR147: Veracruz Orizaba**     | Orizaba Nahuatl (ISO 639-3: nlv) speech corpus.                                                                       |    True    |
| **SLR148: Tepetzintla**          | Zacatlán-Ahuacatlán-Tepetzintla (Puebla) Nahuatl (ISO 639-3: nhi) speech corpus.                                      |    True    |
| **SLR149: Tibetan Greetings**    | Selected Tibetan greetings data from various dialectal regions.                                                       |    True    |
| **SLR151: Kallaama**             | Wolof, Pulaar, and Sereer speech data.                                                                                |    True    |
| **SLR152: Pragmatic Similarity** | Perceived similarity judgments between utterance pairs (English & Spanish).                                           |    True    |
| **SLR153: Yerevan City Mag**     | Free Armenian news text corpus from Yerevan City Magazine.                                                            |    True    |
| **SLR154: ArmenianGrqaserAudio** | Audio-text pairs from Grqaser.org audiobooks (Armenian).                                                              |    True    |
| **SLR155: SBCSAE**               | Santa Barbara Corpus of Spoken American English, mirrored from UCSB.                                                  |    True    |
| **SLR156: SMIIP-TV**             | Short-term time-varying speaker verification dataset.                                                                 |    True    |
| **SLR157: Sagalee**              | ASR dataset for Oromo (“Sagalee”).                                                                                    |    True    |

---

## Linguistic Data Consortium
