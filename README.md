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

- [Task](#task)
    - [Dataset Overview Table by Task](#dataset-overview-table-by-task)
    - [Automatic Speech Recognition (ASR)](#automatic-speech-recognition-asr)
    - [Speaker Recognition & Identification & Verification](#speaker-recognition--identification--verification)
    - [Speech Emotion Recognition (SER)](#speech-emotion-recognition-ser)
    - [Text to Speech (TTS)](#text-to-speech-tts)
    - [Multilingual Speech Corpora](#multilingual-speech-corpora)
    - [Diarization](#diarization)
    - [Source Separation](#source-separation)
    - [Health & Clinical Speech Datasets](#health--clinical-speech-datasets)
    - [Audio Events and Music](#audio-events-and-music)
    - [Answering Machine Detection (AMD)](#answering-machine-detection-amd)
    - [Audio Classification](#audio-classification)
- [Hub](#hub)
    - [TalkBank](#talkbank)
    - [OpenSLR](#openslr)

---

## Task

### Dataset Overview Table by Task

#### Verified

|   | Dataset                        | Automatic Speech Recognition (ASR) | Speaker Recognition | Emotion Recognition | Speaker Identification | Speaker Verification | Speech Separation | Speaker Diarisation (Diarization) | Voice Activity Detection (VAD) / Speech Activity Detection (SAD) / Speech Detection | Speech Enhancement | Download                                                                                               | Multilingual | Source               | Version | Paper                                                                                                                                  | Description                                                                                                                                                                                                              |
|--:|:-------------------------------|:-----------------------------------|---------------------|---------------------|:-----------------------|----------------------|-------------------|-----------------------------------|-------------------------------------------------------------------------------------|--------------------|--------------------------------------------------------------------------------------------------------|--------------|----------------------|---------|----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | Common Voice                   | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    | [Common Voice](https://commonvoice.mozilla.org/en/datasets)                                            | True         | Mozilla Foundation   | 21      |                                                                                                                                        | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed).                                                                                                                |
| 2 | Multilingual LibriSpeech (MLS) | True                               | True                |                     | True                   | True                 |                   |                                   |                                                                                     |                    | [facebook/multilingual_librispeech](https://huggingface.co/datasets/facebook/multilingual_librispeech) | True         | Facebook / Meta      | 1       |                                                                                                                                        | Multilingual LibriSpeech (MLS) is a large-scale multilingual corpus derived from LibriVox audiobooks, encompassing eight languages and designed to support research in speech processing tasks.                          |
| 3 | People's Speech                | True                               |                     |                     |                        |                      |                   |                                   |                                                                                     |                    | [MLCommons/peoples_speech](https://huggingface.co/datasets/MLCommons/peoples_speech)                   |              | MLCommons            | 1       | [The People's Speech: A Large-Scale Diverse English Speech Recognition Dataset for Commercial Usage](https://arxiv.org/abs/2111.09344) | The People's Speech dataset is a free-to-download, 30,000-hour (and growing) supervised conversational English speech recognition corpus licensed for academic and commercial use under CC-BY-SA (with a CC-BY subset).  |
| 4 | VoxCeleb                       | True                               | True                | True                | True                   | True                 | True              |                                   |                                                                                     |                    | [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)                                   | True         | University of Oxford | 2       | [VoxCeleb2: Deep Speaker Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf)                        | Over 1 million utterances from 6,112 speakers (~2,442 hours) for state-of-the-art speaker recognition research.                                                                                                          |
| 5 | VoxConverse                    |                                    | True                |                     | True                   | True                 |                   | True                              |                                                                                     |                    | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                                            |              | University of Oxford |         | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                             | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                    |
| 6 | CHiME                          | True                               |                     |                     |                        |                      |                   | True                              | True                                                                                | True               | [VoxConverse](https://mm.kaist.ac.kr/datasets/voxconverse/)                                            |              | University of Oxford |         | [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216)                                             | VoxConverse is an audio-visual speaker diarization dataset comprising over 50 hours of multispeaker clips of human speech, automatically extracted and time-aligned from “in the wild” YouTube videos                    |

#### Unverified

| Dataset                                            | ASR  | Speaker Recognition | Emotion Recognition | SLU (Intent/Slot) | Spoken NER | Speaker Identification |
|:---------------------------------------------------|:-----|:--------------------|:--------------------|:------------------|:-----------|:-----------------------|
| MSR-86K                                            | True |                     |                     |                   |            |                        |
| Speech-MASSIVE                                     | True |                     |                     | True              |            | True                   |
| MSNER                                              |      |                     |                     |                   | True       |                        |
| IEMOCAP                                            |      |                     | True                |                   |            |                        |
| CHiME Speech                                       | True |                     |                     |                   |            |                        |
| Spotify Podcast Dataset                            | True |                     |                     |                   |            |                        |
| SPGISpeech (Kensho)                                | True |                     |                     |                   |            |                        |
| AudioMNIST                                         | True |                     |                     |                   |            |                        |
| CMU Wilderness                                     | True |                     |                     |                   |            |                        |
| DAPS Dataset                                       | True |                     |                     |                   |            |                        |
| DIPCO                                              | True |                     |                     |                   |            |                        |
| Free Spoken Digit Dataset                          | True |                     |                     |                   |            |                        |
| Flickr Audio Caption                               | True |                     |                     |                   |            |                        |
| ISOLET Data Set                                    | True |                     |                     |                   |            |                        |
| Libriadapt                                         | True |                     |                     |                   |            |                        |
| Libri-CSS                                          | True |                     |                     |                   |            |                        |
| Microsoft Scalable Noisy Speech Dataset            | True |                     |                     |                   |            |                        |
| MSP Podcast Corpus                                 | True |                     |                     |                   |            |                        |
| Persian Consonant Vowel Combination (PCVC) Dataset | True |                     |                     |                   |            |                        |
| sample_voice_data                                  | True |                     |                     |                   |            |                        |
| Speech Accent Archive                              | True |                     |                     |                   |            |                        |
| Speech Commands Dataset                            | True |                     |                     |                   |            |                        |
| Spoken Commands dataset                            | True |                     |                     |                   |            |                        |
| Spoken Wikipedia Corpora                           | True |                     |                     |                   |            |                        |
| Tatoeba                                            | True |                     |                     |                   |            |                        |
| TIMIT dataset                                      | True |                     |                     |                   |            |                        |
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

---

### Automatic Speech Recognition (ASR)

#### Unverified

| Dataset                                                | Download                                                                                           | Description                                                                                                                                                     | Source |
|--------------------------------------------------------|----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|:------:|
| **CHiME Speech**                                       | [CHiME Datasets](https://www.chimechallenge.org/)                                                  | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far‐field ASR research. |  True  |
| **Spotify Podcast Dataset**                            | [Podcast Dataset](https://podcastsdataset.github.io/)                                              | Over 100,000 podcast episodes with 100,000+ hours of speech and extensive transcripts for various speech processing applications.                               |  True  |
| **SPGISpeech (Kensho)**                                | [SPGISpeech (Kensho) Data](https://www.kensho.com/dataset)                                         | 5,000 hours of professionally-transcribed financial audio from earnings calls; ideal for ASR research in the financial domain.                                  |  True  |
| **AudioMNIST**                                         | [AudioMNIST](https://github.com/soerenab/AudioMNIST)                                               | 30,000 audio samples of spoken digits (0–9) from 60 different speakers.                                                                                         |  True  |
| **CMU Wilderness**                                     | [CMU Wilderness](http://festvox.org/cmu_wilderness/)                                               | Speech dataset with multiple accents reciting passages from the Bible.                                                                                          |  True  |
| **DAPS Dataset**                                       | [DAPS Dataset](https://archive.org/details/daps_dataset)                                           | 20 speakers reading 5 excerpts each from public domain books (~14 minutes per speaker).                                                                         |  True  |
| **DIPCO**                                              | [DIPCO](https://zenodo.org/records/8122551)                                                        | Dinner Party Corpus – recordings via close‐talk and far‐field arrays from 10 sessions (15–45 minutes each).                                                     |  True  |
| **Free Spoken Digit Dataset**                          | [Free Spoken Digit Dataset](https://github.com/Jakobovski/free-spoken-digit-dataset)               | 2,000 recordings (50 per digit per speaker) of spoken digits from 4 speakers.                                                                                   |  True  |
| **Flickr Audio Caption**                               | [Flickr Audio Caption](https://groups.csail.mit.edu/sls/downloads/flickraudio/)                    | 40,000 spoken captions for 8,000 natural images (~4.2 GB).                                                                                                      |  True  |
| **ISOLET Data Set**                                    | [ISOLET Data Set](https://data.world/uci/isolet)                                                   | 38.7 GB dataset for predicting letter-names from spoken audio.                                                                                                  |  True  |
| **Libriadapt**                                         | [Libriadapt](https://github.com/akhilmathurs/libriadapt)                                           | Facilitates domain adaptation research for ASR models with three types of domain shifts.                                                                        |  True  |
| **Libri-CSS**                                          | [Libri-CSS](https://github.com/chenzhuo1011/libri_css)                                             | Derived from LibriSpeech by concatenating utterances to simulate conversational far‐field replays.                                                              |  True  |
| **Microsoft Scalable Noisy Speech Dataset**            | [MS-SNSD](https://github.com/microsoft/MS-SNSD)                                                    | Noisy speech dataset scalable to arbitrary sizes with varying speakers, noise types, and SNR levels.                                                            |  True  |
| **MSP Podcast Corpus**                                 | [MSP Podcast Corpus](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Podcast.html)      | 100 hours of podcast speech from 100+ speakers, annotated with emotional labels and attribute-based descriptors.                                                |  True  |
| **Persian Consonant Vowel Combination (PCVC) Dataset** | [PCVC](https://github.com/S-Malek/PCVC)                                                            | Modern Persian speech corpus of consonant-vowel combinations (138 samples per speaker) for ASR and speaker recognition.                                         |  True  |
| **sample_voice_data**                                  | [sample_voice_data](https://github.com/jim-schwoebel/sample_voice_data)                            | 52 audio files per class (male & female) for testing purposes.                                                                                                  |  True  |
| **Speech Accent Archive**                              | [Speech Accent Archive](https://www.kaggle.com/rtatman/speech-accent-archive/version/1)            | Dataset for various accent detection tasks.                                                                                                                     |  True  |
| **Speech Commands Dataset**                            | [Speech Commands Dataset](http://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html) | 65,000 one-second utterances of 30 short words for keyword spotting.                                                                                            |  True  |
| **Spoken Commands dataset**                            | [Spoken Commands dataset](https://github.com/JohannesBuchner/spoken-command-recognition)           | Large database of free audio samples for voice activity detection and syllable recognition.                                                                     |  True  |
| **Spoken Wikipedia Corpora**                           | [Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                                            | 38 GB dataset available in audio and non-audio formats based on Wikipedia articles.                                                                             |  True  |
| **Tatoeba**                                            | [Tatoeba](https://tatoeba.org/eng/downloads)                                                       | Large database of sentences, translations, and spoken audio for language learning.                                                                              |  True  |
| **TIMIT dataset**                                      | [TIMIT dataset](https://catalog.ldc.upenn.edu/LDC93S1)                                             | Broadband recordings of 630 speakers reading phonetically rich sentences with time-aligned transcriptions.                                                      | False  |
| **Zero Resource Speech Challenge**                     | [Zero Resource Speech Challenge](https://github.com/bootphon/zerospeech2017)                       | Challenge to build an end-to-end spoken dialogue system from scratch with zero linguistic expertise.                                                            |  True  |

---

### Speaker Recognition & Identification & Verification

#### Unverified

| Dataset                    | Download                                                                          | Description                                                                                                     | OpenSource |
|----------------------------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|:----------:|
| **Voice Gender Detection** | [Voice Gender Detection](https://github.com/jim-schwoebel/voice_gender_detection) | GitHub repo for gender detection using the VoxCeleb dataset (7000+ speakers).                                   |    True    |

---

### Speech Emotion Recognition (SER)

#### Unverified

| Dataset                                    | Download                                                                                                              | Description                                                                                                                 | OpenSource |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|:----------:|
| **IEMOCAP**                                | [USC IEMOCAP](https://sail.usc.edu/iemocap)                                                                           | ~12 hours of acted audiovisual dialogues by 10 actors with 9 emotion categories.                                            |   False    |
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

---

### Multilingual Speech Corpora

#### Unverified

| Dataset                            | Download                                                                    | Description                                                                                                                   | OpenSource |
|------------------------------------|-----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **Mozilla Common Voice**           | [Common Voice Datasets](https://commonvoice.mozilla.org/en/datasets)        | Massive multilingual, crowd-sourced speech corpus with 20,408+ hours across 124 languages (CC0 licensed).                     |    True    |
| **Multilingual LibriSpeech (MLS)** | [Facebook AI MLS](https://dl.fbaipublicfiles.com/mls/index.html)            | Derived from LibriVox audiobooks spanning 8 languages with ~50,000 hours of speech.                                           |    True    |
| **VoxPopuli**                      | [VoxPopuli GitHub](https://github.com/facebookresearch/voxpopuli)           | European Parliament recordings (2009–2020) in 23 languages; 400,000 hours of unlabeled and 1,800 hours of transcribed speech. |    True    |
| **MLCommons People's Speech**      | [People’s Speech](https://huggingface.co/datasets/MLCommons/peoples_speech) | Over 30,000 hours of transcribed English speech featuring diverse accents.                                                    |    True    |

---

### Text to Speech (TTS)

#### Unverified

| Dataset                     | Download                                                                         | Description                                                                                                                | OpenSource |
|-----------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|:----------:|
| **LJSpeech-1.1**            | [LJSpeech Dataset](https://keithito.com/LJ-Speech-Dataset/)                      | Single-speaker English TTS dataset with 13,100 short audio clips (~24h) from a female speaker reading public-domain texts. |    True    |
| **VCTK (CSTR VCTK Corpus)** | [VCTK Corpus](https://datashare.ed.ac.uk/handle/10283/3443)                      | Multi-speaker English speech corpus with 109 speakers (≈44h total); used for accent-robust TTS and voice conversion.       |    True    |
| **Arabic Speech Corpus**    | [Arabic Speech Corpus](http://en.arabicspeechcorpus.com/)                        | Modern Standard Arabic (MSA) TTS corpus (1.5GB) with phonetic and orthographic transcriptions.                             |    True    |
| **EmotionTTS**              | [EmotionTTS](https://github.com/emotiontts/emotiontts_open_db)                   | TTS dataset with recordings in 4 emotions (general, joy, anger, sadness) for emotionally expressive synthesis.             |    True    |
| **Thorsten dataset**        | [Thorsten dataset](https://github.com/thorstenMueller/deep-learning-german-tts/) | German TTS dataset with 22,668 recorded phrases (~23h); ideal for deep-learning based TTS.                                 |    True    |

---

### Diarization

#### Unverified

| Dataset                            | Download                                                                                      | Description                                                                                                               | OpenSource |
|------------------------------------|-----------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|:----------:|
| **Awesome_Diarization**            | [Awesome_Diarization](https://github.com/jim-schwoebel/awesome-diarization)                   | Curated list of papers, libraries, datasets, and resources for speaker diarization research.                              |    True    |
| **AMI Corpus**                     | [AMI Corpus](http://groups.inf.ed.ac.uk/ami/corpus/)                                          | ~100h multi-party meetings recorded with multiple microphones and video; used for benchmarking diarization and ASR tasks. |   False    |
| **CallHome American English**      | [CallHome](https://catalog.ldc.upenn.edu/LDC97S42)                                            | Telephone conversations (~120 calls/~120h) frequently used for speaker diarization research.                              |   False    |
| **DIHARD Challenge datasets**      | [DIHARD Challenges](https://dihardchallenge.github.io/data.html)                              | Diverse, challenging audio datasets from various domains for diarization benchmarking.                                    |    True    |
| **Fisher English Training Speech** | [Fisher English](https://catalog.ldc.upenn.edu/LDC2004S13)                                    | ~2,000h conversational telephone speech recorded between pairs of strangers for ASR and diarization.                      |   False    |
| **AMI Headset Mix Dataset**        | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/download/)                                       | Subset of AMI corpus designed for diarization research (close-talk recordings).                                           |   False    |
| **DIHARD Challenges**              | [DIHARD](https://dihardchallenge.github.io/)                                                  | Regularly updated challenges and datasets for evaluating diarization systems.                                             |    True    |
| **ICSI Meeting Corpus**            | [ICSI Corpus](https://catalog.ldc.upenn.edu/LDC2004S02)                                       | 75 multi-party meetings (72h) from multiple microphone channels with annotations for diarization.                         |   False    |
| **CHiME-6 Challenge**              | [CHiME-6](https://chimechallenge.github.io/chime6/)                                           | Multi-channel, multi-speaker, highly reverberant dinner-party recordings for diarization, ASR, and source separation.     |    True    |
| **AMI Meeting Corpus**             | [AMI](https://groups.inf.ed.ac.uk/ami/corpus/)                                                | ~100h business meeting recordings with extensive annotations (diarization labels, speaker roles, dialogue acts).          |   False    |
| **LibriCSS**                       | [Libri-CSS](https://github.com/chenzhuo1011/libri_css)                                        | Derived from LibriSpeech to simulate diarization scenarios with varying speaker overlap and noise.                        |    True    |
| **CH-109 Dataset**                 | [CH109 Dataset](https://github.com/pyannote/pyannote-audio/tree/develop/tutorials/data/ch109) | Subset of CALLHOME corpus for diarization benchmarking (telephone conversations).                                         |    True    |
| **VoxSRC Challenges (VoxCeleb)**   | [VoxSRC](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/competition.html)                     | Diarization challenge dataset based on VoxCeleb recordings with celebrity conversations.                                  |    True    |

---

### Source Separation

#### Unverified

| Dataset                     | Download                                                              | Description                                                                                               | OpenSource |
|-----------------------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|:----------:|
| **Deep Clustering Dataset** | [Deep Clustering Dataset](https://www.merl.com/demos/deep-clustering) | For training deep discriminative embeddings to solve the cocktail party problem.                          |    True    |
| **LibriMix**                | [LibriMix](https://github.com/JorisCos/LibriMix)                      | Open source dataset for source separation in noisy environments, derived from LibriSpeech and WHAM noise. |    True    |
| **SparseLibriMix**          | [SparseLibriMix](https://github.com/popcornell/SparseLibriMix)        | Test-set-only version for source separation with variable overlap-ratio.                                  |    True    |
| **VCTK-2Mix**               | [VCTK-2Mix](https://github.com/JorisCos/VCTK-2Mix)                    | Derived from VCTK and WHAM noise; designed as a test set for source separation experiments.               |    True    |
| **WHAM! and WHAMR!**        | [WHAM! and WHAMR!](http://wham.whisper.ai/)                           | Pairs two-speaker mixtures with real noise backgrounds; WHAMR! adds artificial reverberation.             |    True    |

---

### Health & Clinical Speech Datasets

#### Unverified

| Dataset                        | Download                                                               | Description                                                                                            | OpenSource |
|--------------------------------|------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|:----------:|
| **Coswara**                    | [Coswara](https://github.com/iiscleap/Coswara-Data)                    | Database of respiratory sounds (cough, breath, speech) from healthy and COVID-19 positive individuals. |    True    |
| **Parkinson's Speech Dataset** | [Parkinson's Speech Dataset](https://archive.org/details/daps_dataset) | Recordings from 20 Parkinson’s patients and 20 healthy subjects across 26 sound types (~20 MB).        |    True    |

---

### Audio Events and Music

#### Unverified

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

---

### Answering Machine Detection (AMD)

#### Unverified

| Dataset                  | Download                                                                                                                    | Description                                                                                                                          | OpenSource |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **IBM Voicemail Corpus** | [Voicemail Corpus Part I](https://catalog.ldc.upenn.edu/LDC98S77)                                                           | IBM Voicemail Corpus with 1,801 messages (avg. 31s each; total ~15h) of actual voicemail recordings.                                 |   False    |
| **Infobip AMD**          | [Infobip AMD](https://www.infobip.com/docs/voice-and-video/getting-started#answering-machine-detection-add-ons-and-options) | Internal Infobip dataset with ~4,200 phone call audio files (trimmed to ~4s) used in AMD research.                                   |   False    |
| **Wavix Voicemail**      | [Wavix Voicemail](https://wavix.com/amd)                                                                                    | Wavix’s proprietary dataset supporting its AI-based answering machine detection engine, incorporating diverse accents and languages. |   False    |

---

### Audio Classification

#### Unverified

| Dataset                                                                 | Download                                                                                           | Description                                                                                                                                     | OpenSource |
|-------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **AudioSet**                                                            | [AudioSet](https://research.google.com/audioset/)                                                  | Audio event dataset of 10-second clips from YouTube, annotated with a hierarchical ontology of 632 classes.                                     |    True    |
| **Common Voice**                                                        | [Common Voice](https://commonvoice.mozilla.org/en/datasets)                                        | Crowd-sourced speech corpus with 9,283 recorded hours (7,335 validated) across 60 languages, including demographic metadata.                    |    True    |
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
| **VocalSound**                                                          | N/A                                                                                                | Free dataset of 21,024 crowdsourced recordings of laughter, coughs, sighs, and other vocalizations with speaker metadata.                       |    True    |
| **ICBHI Respiratory Sound Database**                                    | [ICBHI](https://www.icbhi.org/respiratory-sound-database/)                                         | Respiratory sound dataset originally compiled for the ICBHI 2017 Challenge.                                                                     |    True    |
| **EPIC-SOUNDS**                                                         | [EPIC-SOUNDS](https://epic-kitchens.github.io/EPIC-SOUNDS/)                                        | Large-scale dataset of audio annotations capturing temporal extents and class labels within egocentric video streams.                           |    True    |
| **YouTube-100M**                                                        | [YouTube-100M](https://research.google.com/youtube-100m/)                                          | 100 million YouTube videos with topic labels; extensive audio content; note: labels are machine-generated and may be noisy.                     |   False    |
| **SSC (Spiking Speech Commands v0.2)**                                  | [SSC](https://github.com/neuromorphic-computing-group/SSC)                                         | Spiking version of the Speech Commands dataset generated using an artificial cochlea model.                                                     |    True    |
| **aGender**                                                             | N/A                                                                                                | Dataset containing audio recordings labeled by age and gender.                                                                                  |    True    |
| **SONYC-UST-V2**                                                        | [SONYC-UST-V2](https://zenodo.org/record/3960431)                                                  | Urban sound tagging dataset from the SONYC acoustic sensor network with spatiotemporal metadata.                                                |    True    |
| **TAU-NIGENS Spatial Sound Events 2021**                                | [TAU-NIGENS](https://zenodo.org/record/4643708)                                                    | Spatial sound-scene recordings with annotated sound events in both microphone array and Ambisonics formats.                                     |    True    |
| **DCASE 2014**                                                          | [DCASE 2014](http://dcase.community/challenge2014/)                                                | Benchmark dataset for audio classification challenges organized in 2014.                                                                        |    True    |
| **HUME-VB**                                                             | [HUME-VB](https://github.com/hume-research/HUME-VB)                                                | The Hume Vocal Burst Database with emotion ratings for vocal bursts.                                                                            |    True    |
| **VGGSound-Sparse**                                                     | [VGGSound-Sparse](https://github.com/karoldvl/VGGSound-Sparse)                                     | Subset of VGG-Sound containing temporally sparse audio-visual clips for classification.                                                         |    True    |
| **InfantMarmosetsVox**                                                  | N/A                                                                                                | Dataset for multi-class call-type and caller identification from infant marmosets.                                                              |    True    |
| **SINGA:PURA**                                                          | [SINGA:PURA](https://github.com/singaporepolytechnic/singa-pura)                                   | Strongly-labelled polyphonic urban sound dataset collected across Singapore for noise monitoring and classification.                            |    True    |
| **BGG dataset (PUBG Gun Sound Dataset)**                                | N/A                                                                                                | Gun sound recordings from the PUBG game environment, covering various gun types, directions, and distances.                                     |   False    |
| **DEEP-VOICE: DeepFake Voice Recognition**                              | [DEEP-VOICE](https://github.com/jordanbird/deep-voice)                                             | Dataset containing real human speech and AI-generated (DeepFake) versions for voice conversion detection.                                       |   False    |
| **MeerKAT: Meerkat Kalahari Audio Transcripts**                         | N/A                                                                                                | Large-scale audio recordings and transcripts from free-ranging meerkats in the Kalahari, South Africa.                                          |    True    |
| **Multimodal PISA (Multimodal Piano Skills Assessment)**                | N/A                                                                                                | Dataset for multimodal piano skill assessment including audio recordings and hand bounding box annotations.                                     |    True    |
| **PC-GITA**                                                             | N/A                                                                                                | Spanish speech corpus designed to analyze speech impairments in individuals with Parkinson's Disease.                                           |    True    |
| **RESPIRATORY AND DRUG ACTUATION DATASET**                              | N/A                                                                                                | Dataset of respiratory and drug actuation sounds for evaluating inhalation technique in asthma treatment.                                       |    True    |
| **ReefSet**                                                             | N/A                                                                                                | Strongly labeled audio clips from coral reef habitats for testing audio embedding models in bioacoustics.                                       |    True    |
| **Sound-based drone fault classification using multitask learning**     | [Link](https://arxiv.org/abs/2304.11708)                                                           | Dataset for classifying drone faults from audio signals using a multitask learning framework.                                                   |    True    |
| **Zooniverse (HumBug Zooniverse)**                                      | N/A                                                                                                | Dataset of mosquito audio recordings collected via the Zooniverse platform, with labels for mosquito events.                                    |    True    |
| **nEMO**                                                                | N/A                                                                                                | Simulated dataset of emotional speech in Polish, recorded from nine actors portraying six emotional states.                                     |    True    |
| **Mudestreda (Mudestreda Multimodal Device State Recognition Dataset)** | N/A                                                                                                | Multimodal dataset (audio, time series, images) from an industrial milling device for state recognition, anomaly detection, and RUL estimation. |    True    |

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
| **SLR11: LibriSpeech LMs**       | Language modeling resources, vocabulary, and G2P models for LibriSpeech.                                              |    True    |
| **SLR12: LibriSpeech**           | Large-scale (1000h) corpus of read English speech.                                                                    |    True    |
| **SLR13: RWCP**                  | Database of real-world sounds and room impulse responses (RWCP).                                                      |    True    |
| **SLR14: BEEP Dictionary**       | Phonemic transcriptions of 250,000+ English words (British pronunciations).                                           |    True    |
| **SLR15: SRE Speaker List**      | List linking speakers across NIST SRE corpora.                                                                        |    True    |
| **SLR16: The AMI Corpus**        | Acoustic speech data and metadata from the AMI corpus.                                                                |   False    |
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
| **SLR31: Mini LibriSpeech**      | Regression-test subset of the LibriSpeech corpus.                                                                     |    True    |
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
| **SLR60: LibriTTS**              | Large-scale English TTS corpus derived from LibriSpeech (2,456 speakers, ~585h).                                      |    True    |
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
| **SLR94: MLS**                   | Multilingual LibriSpeech dataset derived from LibriVox.                                                               |    True    |
| **SLR95: Thorsten Müller**       | Free single German speaker TTS dataset (>23h) by Thorsten Müller & Dominik Kreutz.                                    |    True    |
| **SLR96: Russian LibriSpeech**   | Russian ASR dataset based on LibriVox audiobooks.                                                                     |    True    |
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
| **SLR135: Libri-Mixed-Speakers** | English audio of simultaneous speakers derived from LibriTTS.                                                         |    True    |
| **SLR136: EMNS**                 | Emotive single-speaker dataset for narrative storytelling (with emotion labels).                                      |    True    |
| **SLR137: Silbo Gomero**         | 49 minutes of Silbo Gomero whistled language from 4 whistlers.                                                        |    True    |
| **SLR138: SHALCAS22A**           | Chinese Mandarin corpus by Shanghai Acoustics Laboratory & Wuxi Sandu.                                                |    True    |
| **SLR139: Audiocite.net**        | French audiobook recordings from audiocite.net.                                                                       |    True    |
| **SLR140: Kazakh Speech (KSD)**  | 554h open-source Kazakh corpus from Al-Farabi Kazakh National University.                                             |    True    |
| **SLR141: LibriTTS-R**           | Improved sound-quality version of LibriTTS (large-scale English TTS).                                                 |    True    |
| **SLR142: The MC Speech**        | Polish speech dataset with 24,018 short clips of a single speaker.                                                    |    True    |
| **SLR143: Nepali TTS**           | Nepali text-to-speech data (male and female).                                                                         |    True    |
| **SLR144: SlideSpeech**          | Large-scale English multi-modal corpus (audio-visual) provided by Alibaba Group.                                      |    True    |
| **SLR145: LibriSpeech-PC**       | LibriSpeech text with punctuation and capitalization.                                                                 |    True    |
| **SLR146: CML-TTS**              | Multilingual dataset for TTS in low-resource languages.                                                               |    True    |
| **SLR147: Veracruz Orizaba**     | Orizaba Nahuatl (ISO 639-3: nlv) speech corpus.                                                                       |    True    |
| **SLR148: Tepetzintla**          | Zacatlán-Ahuacatlán-Tepetzintla (Puebla) Nahuatl (ISO 639-3: nhi) speech corpus.                                      |    True    |
| **SLR149: Tibetan Greetings**    | Selected Tibetan greetings data from various dialectal regions.                                                       |    True    |
| **SLR150: CHiME-6**              | English multi-channel far-field meeting data from CHiME-5 with synchronization fixes.                                 |    True    |
| **SLR151: Kallaama**             | Wolof, Pulaar, and Sereer speech data.                                                                                |    True    |
| **SLR152: Pragmatic Similarity** | Perceived similarity judgments between utterance pairs (English & Spanish).                                           |    True    |
| **SLR153: Yerevan City Mag**     | Free Armenian news text corpus from Yerevan City Magazine.                                                            |    True    |
| **SLR154: ArmenianGrqaserAudio** | Audio-text pairs from Grqaser.org audiobooks (Armenian).                                                              |    True    |
| **SLR155: SBCSAE**               | Santa Barbara Corpus of Spoken American English, mirrored from UCSB.                                                  |    True    |
| **SLR156: SMIIP-TV**             | Short-term time-varying speaker verification dataset.                                                                 |    True    |
| **SLR157: Sagalee**              | ASR dataset for Oromo (“Sagalee”).                                                                                    |    True    |

