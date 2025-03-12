<div align="center">

# Awesome Speech Dataset

*Below is a markdown table summarizing the main sources for the Awesome Speech Dataset, including download links and a
brief explanation for each resource. These datasets provide diverse and high-quality speech data covering various
domains such as conversational, academic, political, and more. They are widely used for tasks like automatic speech
recognition (ASR), speaker identification, emotion recognition, and other speech processing applications.*

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

</div>

---

## Table of Contents

- [Topic](#topic)
    - [Automatic Speech Recognition (ASR)](#automatic-speech-recognition-asr)
    - [Speaker Recognition & Identification & Verification](#speaker-recognition-identification-verification)
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

## Topic

---

### Automatic Speech Recognition (ASR)

| Dataset                                                | Download                                                                                           | Description                                                                                                                                                                        | OpenSource |
|--------------------------------------------------------|----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **CHiME Speech**                                       | [CHiME Challenge Datasets](http://chimechallenge.org)                                              | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far-field ASR research.                    |    True    |
| **Spotify Podcast Dataset**                            | [Podcast Dataset](https://podcastsdataset.github.io/)                                              | A dataset of over 100,000 podcast episodes with more than 100,000 hours of speech and extensive transcripts, used for various speech processing applications including ASR and LM. |    True    |
| **SPGISpeech (Kensho)**                                | [Download Data](https://www.kensho.com/dataset)                                                    | A large-scale transcription dataset with 5,000 hours of professionally-transcribed financial audio from earnings calls; ideal for ASR research in the financial domain.            |    True    |
| **ASR Datasets**                                       | [GitHub ASR_Audio_Data_Links](https://github.com/robmsmt/ASR_Audio_Data_Links)                     | A list of publicly available audio datasets for ASR or other speech activities.                                                                                                    |    True    |
| **AudioMNIST**                                         | [AudioMNIST](https://github.com/soerenab/AudioMNIST)                                               | 30,000 audio samples of spoken digits (0–9) from 60 different speakers.                                                                                                            |    True    |
| **CMU Wilderness**                                     | [CMU Wilderness](http://festvox.org/cmu_wilderness/)                                               | A speech dataset with multiple accents reciting passages from the Bible.                                                                                                           |    True    |
| **DAPS Dataset**                                       | [DAPS Dataset](https://archive.org/details/daps_dataset)                                           | 20 speakers reading 5 excerpts each from public domain books (~14 minutes of data per speaker).                                                                                    |    True    |
| **DIPCO**                                              | [DIPCO](https://arxiv.org/abs/1909.13447)                                                          | Dinner Party Corpus – recordings via a close-talk mic and five far-field arrays from 10 sessions (15–45 minutes each).                                                             |    True    |
| **Free Spoken Digit Dataset**                          | [Free Spoken Digit Dataset](https://github.com/Jakobovski/free-spoken-digit-dataset)               | 2,000 recordings (50 per digit per speaker) of spoken digits from 4 speakers.                                                                                                      |    True    |
| **Flickr Audio Caption**                               | [Flickr Audio Caption](https://groups.csail.mit.edu/sls/downloads/flickraudio/)                    | 40,000 spoken captions for 8,000 natural images (approx. 4.2 GB).                                                                                                                  |    True    |
| **ISOLET Data Set**                                    | [ISOLET Data Set](https://data.world/uci/isolet)                                                   | A 38.7 GB dataset for predicting letter-names from spoken audio.                                                                                                                   |    True    |
| **Libriadapt**                                         | [Libriadapt](https://github.com/akhilmathurs/libriadapt)                                           | Designed to facilitate domain adaptation research for ASR models with three types of domain shifts.                                                                                |    True    |
| **Libri-CSS**                                          | [Libri-CSS](https://github.com/chenzhuo1011/libri_css)                                             | Derived from LibriSpeech by concatenating utterances to simulate conversation with far-field replays.                                                                              |    True    |
| **Microsoft Scalable Noisy Speech Dataset**            | [MS-SNSD](https://github.com/microsoft/MS-SNSD)                                                    | A noisy speech dataset that scales to arbitrary sizes with varying speakers, noise types, and SNR levels.                                                                          |    True    |
| **MSP Podcast Corpus**                                 | [MSP Podcast Corpus](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Podcast.html)      | 100 hours of podcast speech from over 100 speakers, annotated with emotional labels and attribute-based descriptors.                                                               |    True    |
| **Persian Consonant Vowel Combination (PCVC) Dataset** | [PCVC](https://github.com/S-Malek/PCVC)                                                            | A Modern Persian speech corpus of consonant-vowel combinations (138 samples per speaker) useful for ASR and speaker recognition.                                                   |    True    |
| **sample_voice_data**                                  | [sample_voice_data](https://github.com/jim-schwoebel/sample_voice_data)                            | 52 audio files per class (male & female) for testing purposes.                                                                                                                     |    True    |
| **Speech Accent Archive**                              | [Speech Accent Archive](https://www.kaggle.com/rtatman/speech-accent-archive/version/1)            | A dataset for various accent detection tasks.                                                                                                                                      |    True    |
| **Speech Commands Dataset**                            | [Speech Commands Dataset](http://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html) | 65,000 one-second utterances of 30 short words contributed by members of the public.                                                                                               |    True    |
| **Spoken Commands dataset**                            | [Spoken Commands dataset](https://github.com/JohannesBuchner/spoken-command-recognition)           | A large database of free audio samples for voice activity detection and syllable recognition.                                                                                      |    True    |
| **Spoken Wikipedia Corpora**                           | [Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                                            | A 38 GB dataset available in both audio and non-audio formats, based on Wikipedia articles.                                                                                        |    True    |
| **Tatoeba**                                            | [Tatoeba](https://tatoeba.org/eng/downloads)                                                       | A large database of sentences, translations, and spoken audio for language learning.                                                                                               |    True    |
| **TIMIT dataset**                                      | [TIMIT dataset](https://catalog.ldc.upenn.edu/LDC93S1)                                             | Broadband recordings of 630 speakers reading phonetically rich sentences with time-aligned transcriptions.                                                                         |   False    |
| **Zero Resource Speech Challenge**                     | [Zero Resource Speech Challenge](https://github.com/bootphon/zerospeech2017)                       | A challenge aimed at building an end-to-end spoken dialog system from scratch with zero linguistic expertise.                                                                      |    True    |

---

### Speaker Recognition, Identification, Verification

| Dataset                    | Download                                                                          | Description                                                                                                           | OpenSource |
|----------------------------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|:----------:|
| **VoxCeleb1**              | [VoxCeleb1](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)                       | 140k utterances from 1,251 speakers (≈352 hours) derived from celebrity interviews on YouTube.                        |    True    |
| **VoxCeleb2**              | [VoxCeleb2](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)              | Over 1 million utterances from 6,112 speakers (~2,442 hours), used for state-of-the-art speaker recognition research. |    True    |
| **Voice Gender Detection** | [Voice Gender Detection](https://github.com/jim-schwoebel/voice_gender_detection) | A GitHub repo for gender detection using the VoxCeleb dataset (7000+ speakers; roughly gender-balanced).              |    True    |

---

### Speech Emotion Recognition (SER)

| Dataset                                    | Download                                                                                                              | Description                                                                                                                          | OpenSource |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **IEMOCAP**                                | [USC IEMOCAP](https://sail.usc.edu/iemocap)                                                                           | ~12 hours of acted audiovisual dialogues by 10 actors with 9 emotion categories.                                                     |   False    |
| **RAVDESS**                                | [Zenodo RAVDESS](https://zenodo.org/record/1188976)                                                                   | 7,356 clips of emotional speech and song by 24 professional actors, covering 8 emotions.                                             |    True    |
| **CREMA-D**                                | [CREMA-D GitHub](https://github.com/CheyneyComputerScience/CREMA-D)                                                   | 7,442 audio-visual clips from 91 actors performing 12 sentences in 6 emotions with crowd-sourced ratings.                            |    True    |
| **AESDD**                                  | [AESDD](http://m3c.web.auth.gr/research/aesdd-speech-emotion-recognition/)                                            | ~500 utterances by diverse actors simulating various emotions.                                                                       |    True    |
| **ANAD**                                   | [ANAD](https://www.kaggle.com/suso172/arabic-natural-audio-dataset)                                                   | 1,384 recordings by multiple speakers with 3 emotions (angry, happy, surprised).                                                     |    True    |
| **BAVED**                                  | [BAVED](https://www.kaggle.com/a13x10/basic-arabic-vocal-emotions-dataset)                                            | 1,935 recordings by 61 speakers (45 male, 16 female) focusing on vocal emotion.                                                      |    True    |
| **CaFE**                                   | [CaFE](https://www.gel.usherbrooke.ca/audio/cafe.htm)                                                                 | 6 different sentences by 12 speakers (6 females, 6 males) for emotion recognition tasks.                                             |    True    |
| **CMU-MOSEI**                              | [CMU-MOSEI](https://www.amir-zadeh.com/datasets)                                                                      | 65 hours of annotated video and audio data from 1000+ speakers covering 6 emotions plus Likert scale ratings.                        |    True    |
| **CMU-MOSI**                               | [CMU-MOSI](https://www.amir-zadeh.com/datasets)                                                                       | 2,199 opinion utterances annotated with sentiment on a seven-point scale.                                                            |    True    |
| **DEMoS**                                  | [DEMoS](https://zenodo.org/record/2544829)                                                                            | 9,365 emotional and 332 neutral samples produced by 68 native speakers.                                                              |    True    |
| **DES**                                    | [DES](http://kom.aau.dk/~tb/speech/Emotions/)                                                                         | Recordings from 4 speakers expressing 5 emotions: neutral, surprise, happiness, sadness, and anger.                                  |    True    |
| **EEKK**                                   | [EEKK](https://metashare.ut.ee/repository/download/4d42d7a8463411e2a6e4005056b40024a19021a316b54b7fb707757d43d1a889/) | 26 passages read by 10 speakers in 4 emotions (joy, sadness, anger, neutral).                                                        |    True    |
| **Emo-DB**                                 | [Emo-DB](http://emodb.bilderbar.info/index-1280.html)                                                                 | 800 recordings from 10 actors (balanced gender) covering 7 emotions.                                                                 |    True    |
| **EmoFilm**                                | [EmoFilm](https://zenodo.org/record/1326428)                                                                          | 1,115 audio instances (sentences extracted from films) with emotional content.                                                       |    True    |
| **EmoSynth**                               | [EmoSynth](https://zenodo.org/record/3727593)                                                                         | 144 audio files labeled by 40 listeners in terms of valence and arousal.                                                             |    True    |
| **Emotional Voices Database**              | [Emotional Voices Database](https://github.com/numediart/EmoV-DB)                                                     | A dataset with various emotions recorded by 5 voice actors (amused, angry, disgusted, neutral, sleepy).                              |    True    |
| **Emotional Voice dataset - Nature**       | [Emotional Voice dataset - Nature](https://www.nature.com/articles/s41562-019-0533-6)                                 | 2,519 speech samples from 100 actors across 5 cultures, demonstrating at least 12 distinct emotions.                                 |    True    |
| **EmotionTTS**                             | [EmotionTTS](https://github.com/emotiontts/emotiontts_open_db)                                                        | Recordings with transcripts by diverse speakers in 4 emotions (general, joy, anger, sadness) – suited for TTS with emotional nuance. |    True    |
| **Emov-DB**                                | [Emov-DB](https://mega.nz/#F!KBp32apT!gLIgyWf9iQ-yqnWFUFuUHg!mYwUnI4K)                                                | Recordings from 4 speakers (2 male, 2 female) with emotions: neutral, sleepiness, anger, disgust, and amused.                        |    True    |
| **EMOVO**                                  | [EMOVO](http://voice.fub.it/activities/corpora/emovo/index.html)                                                      | 6 actors reading 14 sentences in 6 emotions: disgust, fear, anger, joy, surprise, and sadness.                                       |    True    |
| **eNTERFACE05**                            | [eNTERFACE05](http://www.enterface.net/enterface05/docs/results/databases/project2_database.zip)                      | Videos by 42 subjects from 14 nationalities in 6 emotions.                                                                           |    True    |
| **GEMEP corpus**                           | [GEMEP corpus](https://www.unige.ch/cisa/gemep)                                                                       | 10 actors portraying 10 states covering 12 primary and 5 additional emotions.                                                        |    True    |
| **JL corpus**                              | [JL corpus](https://www.kaggle.com/tli725/jl-corpus)                                                                  | 2,400 recordings of 240 sentences by 4 actors; includes 5 primary and 5 secondary emotions.                                          |    True    |
| **Keio-ESD**                               | [Keio-ESD](http://research.nii.ac.jp/src/en/Keio-ESD.html)                                                            | A Japanese male speaker dataset covering 47 different emotions.                                                                      |    True    |
| **LEGO Corpus**                            | [LEGO Corpus](https://www.ultes.eu/ressources/lego-spoken-dialogue-corpus/)                                           | 347 dialogs (9,083 exchanges) with emotions classified into garbage, non-angry, slightly angry, and very angry.                      |    True    |
| **MSP-IMPROV**                             | [MSP-IMPROV](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Improv.html)                                  | 20 sentences by 12 actors covering 4 emotions plus an “other” category.                                                              |    True    |
| **Multimodal EmotionLines Dataset (MELD)** | [MELD](https://github.com/SenticNet/MELD)                                                                             | Over 1,400 dialogues and 13,000 utterances from the TV series *Friends* labeled with 7 emotions.                                     |    True    |
| **MuSe-CAR**                               | [MuSe-CAR](https://zenodo.org/record/4134758)                                                                         | 40 hours and 25,000+ sentences from 70+ speakers for emotion recognition research.                                                   |    True    |
| **OGVC**                                   | [OGVC](https://sites.google.com/site/ogcorpus/home/en)                                                                | 9,114 spontaneous and 2,656 acted utterances by 4 professional actors covering 9 emotional states.                                   |    True    |
| **RECOLA**                                 | [RECOLA](https://diuf.unifr.ch/main/diva/recola/download.html)                                                        | 3.8 hours of recordings from 46 participants annotated with continuous valence and arousal values.                                   |    True    |
| **SAVEE Dataset**                          | [SAVEE Dataset](http://kahlan.eps.surrey.ac.uk/savee/)                                                                | 480 British English utterances from 4 male actors covering 7 different emotions.                                                     |    True    |
| **SEMAINE**                                | [SEMAINE](https://semaine-db.eu/)                                                                                     | 95 dyadic conversations from 21 subjects with 5 FeelTrace annotations (activation, valence, dominance, power, intensity).            |    True    |
| **SER Datasets**                           | [SER Datasets](https://github.com/SuperKogito/SER-datasets)                                                           | A collection of datasets aimed at emotion recognition/detection in speech.                                                           |    True    |
| **SEWA**                                   | [SEWA](https://db.sewaproject.eu/)                                                                                    | Over 2,000 minutes of audiovisual data from 398 people with continuous valence and arousal annotations.                              |    True    |
| **ShEMO**                                  | [ShEMO](https://github.com/mansourehk/ShEMO)                                                                          | 3,000 semi-natural utterances (~3 hours 25 minutes) from 87 native-Persian speakers in 6 emotion categories.                         |    True    |
| **TESS**                                   | [TESS](https://tspace.library.utoronto.ca/handle/1807/24487)                                                          | 2,800 recordings by 2 actresses covering 7 emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral).      |    True    |
| **URDU-Dataset**                           | [URDU-Dataset](https://github.com/siddiquelatif/urdu-dataset)                                                         | 400 utterances by 38 speakers (27 male, 11 female) in 4 emotions: angry, happy, neutral, and sad.                                    |    True    |
| **VIVAE**                                  | [VIVAE](https://zenodo.org/record/4066235)                                                                            | 1,085 non-speech audio files from ~12 speakers covering 6 emotions (achievement, anger, fear, pain, pleasure, surprise).             |    True    |

---

### Multilingual Speech Corpora

| Dataset                            | Download                                                                                 | Description                                                                                                                                                                                      | OpenSource |
|------------------------------------|------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **Mozilla Common Voice**           | [Common Voice Datasets](https://commonvoice.mozilla.org/en/datasets)                     | A massively multilingual, crowd-sourced speech corpus with over 20,408 hours of validated speech across 124 languages; available under CC0 license.                                              |    True    |
| **Multilingual LibriSpeech (MLS)** | [Facebook AI MLS](https://dl.fbaipublicfiles.com/mls/index.html)                         | Derived from LibriVox audiobooks, spanning 8 languages with ~50,000 hours of speech; provides standardized splits for cross-lingual ASR research.                                                |    True    |
| **VoxPopuli**                      | [VoxPopuli GitHub](https://github.com/facebookresearch/voxpopuli)                        | European Parliament recordings (2009–2020) in 23 languages, offering 400,000 hours of unlabeled speech and 1,800 hours of transcribed data for multilingual ASR and speech translation research. |    True    |
| **MLCommons People's Speech**      | [Hugging Face People’s Speech](https://huggingface.co/datasets/MLCommons/peoples_speech) | Over 30,000 hours of transcribed English speech featuring diverse accents; widely used for ASR training and evaluation.                                                                          |    True    |

---

### Text to Speech (TTS)

| Dataset                     | Download                                                                         | Description                                                                                                                                                                                            | OpenSource |
|-----------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **LJSpeech-1.1**            | [LJSpeech Dataset](https://keithito.com/LJ-Speech-Dataset/)                      | A single-speaker English TTS dataset with 13,100 short audio clips (~24 hours) from a female speaker reading public-domain texts; widely used to train neural TTS models.                              |    True    |
| **VCTK (CSTR VCTK Corpus)** | [VCTK Corpus](https://datashare.ed.ac.uk/handle/10283/3443)                      | A multi-speaker English speech corpus with 109 speakers from the UK, each reading about 400 sentences (~44 hours); provided at 48 kHz, used for accent-robust TTS, voice conversion, and ASR research. |    True    |
| **Arabic Speech Corpus**    | [Arabic Speech Corpus](http://en.arabicspeechcorpus.com/)                        | A Modern Standard Arabic (MSA) speech corpus (1.5 GB) for speech synthesis with phonetic and orthographic transcriptions aligned at the phoneme level.                                                 |    True    |
| **EmotionTTS**              | [EmotionTTS](https://github.com/emotiontts/emotiontts_open_db)                   | Recordings and associated transcriptions by a diverse set of speakers in 4 emotions (general, joy, anger, sadness) – suitable for developing emotionally expressive TTS models.                        |    True    |
| **Thorsten dataset**        | [Thorsten dataset](https://github.com/thorstenMueller/deep-learning-german-tts/) | A German language TTS dataset with 22,668 recorded phrases (~23 hours), ideal for deep-learning based TTS research.                                                                                    |    True    |

---

### Diarization

| Dataset                            | Download                                                                                      | Description                                                                                                                                                                                    | OpenSource |
|------------------------------------|-----------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **Awesome_Diarization**            | [Awesome_Diarization](https://github.com/jim-schwoebel/awesome-diarization)                   | A curated list of papers, libraries, datasets, and resources for speaker diarization research.                                                                                                 |    True    |
| **AMI Corpus**                     | [AMI Corpus](http://groups.inf.ed.ac.uk/ami/corpus/)                                          | ~100 hours of multi-party meetings recorded with multiple microphones and video; widely used for benchmarking diarization, speaker identification, and ASR tasks.                              |   False    |
| **CallHome American English**      | [CallHome](https://catalog.ldc.upenn.edu/LDC97S42)                                            | Telephone conversations involving friends and family; ~120 calls (~120 hours), frequently used for speaker diarization research.                                                               |   False    |
| **DIHARD Challenge datasets**      | [DIHARD Challenges](https://dihardchallenge.github.io/data.html)                              | Rich collection of diverse, challenging audio datasets from different domains, widely adopted for diarization benchmarking.                                                                    |    True    |
| **Fisher English Training Speech** | [Fisher English](https://catalog.ldc.upenn.edu/LDC2004S13)                                    | ~2,000 hours of conversational telephone speech recorded between pairs of strangers, widely used for ASR, diarization, and speaker recognition.                                                |   False    |
| **AMI Headset Mix Dataset**        | [AMI Corpus](https://groups.inf.ed.ac.uk/ami/download/)                                       | Subset of the AMI corpus specifically designed for speaker diarization research, featuring close-talk microphones recordings from meetings.                                                    |   False    |
| **DIHARD Challenges**              | [DIHARD](https://dihardchallenge.github.io/)                                                  | Regularly updated challenges and datasets to evaluate diarization systems across diverse domains such as meetings, telephone conversations, broadcast interviews, etc.                         |    True    |
| **ICSI Meeting Corpus**            | [ICSI Corpus](https://catalog.ldc.upenn.edu/LDC2004S02)                                       | 75 recorded multi-party meetings (72 hours) from multiple microphone channels, providing annotated data useful for diarization and conversational analysis tasks.                              |   False    |
| **CHiME-6 Challenge**              | [CHiME-6](https://chimechallenge.github.io/chime6/)                                           | Multi-channel, multi-speaker, highly reverberant conversational speech recordings in realistic dinner-party scenarios, focusing on diarization, ASR, and source separation.                    |    True    |
| **AMI Meeting Corpus**             | [AMI](https://groups.inf.ed.ac.uk/ami/corpus/)                                                | ~100 hours of business meeting recordings with extensive annotations (speaker diarization labels, speaker roles, dialogue acts), widely used in speaker diarization, ASR, and speech analysis. |   False    |
| **LibriCSS**                       | [Libri-CSS](https://github.com/chenzhuo1011/libri_css)                                        | A dataset derived from LibriSpeech to simulate diarization scenarios by mixing utterances from different speakers with varying degrees of overlap, noise, and reverberation.                   |    True    |
| **VoxConverse**                    | [VoxConverse](https://www.robots.ox.ac.uk/~vgg/data/voxconverse/)                             | A speaker diarization dataset containing challenging conversational speech extracted from YouTube videos, featuring realistic multi-speaker scenarios with overlapping speech.                 |    True    |
| **CH-109 Dataset**                 | [CH109 Dataset](https://github.com/pyannote/pyannote-audio/tree/develop/tutorials/data/ch109) | A subset of the CALLHOME corpus frequently used for diarization benchmarking, containing telephone conversations recorded under real-life conditions.                                          |    True    |
| **VoxSRC Challenges (VoxCeleb)**   | [VoxSRC](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/competition.html)                     | A diarization challenge dataset based on VoxCeleb recordings, providing celebrity conversations with varying lengths, noise levels, and speaker overlap.                                       |    True    |

---

### Source Separation

| Dataset                     | Download                                                              | Description                                                                                                                  | OpenSource |
|-----------------------------|-----------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **Deep Clustering Dataset** | [Deep Clustering Dataset](https://www.merl.com/demos/deep-clustering) | Dataset for training deep discriminative embeddings aimed at solving the cocktail party problem (source separation).         |    True    |
| **LibriMix**                | [LibriMix](https://github.com/JorisCos/LibriMix)                      | An open source dataset for source separation in noisy environments derived from LibriSpeech (clean) and WHAM noise.          |    True    |
| **SparseLibriMix**          | [SparseLibriMix](https://github.com/popcornell/SparseLibriMix)        | A test-set-only version for source separation with variable overlap-ratio.                                                   |    True    |
| **VCTK-2Mix**               | [VCTK-2Mix](https://github.com/JorisCos/VCTK-2Mix)                    | Derived from VCTK signals and WHAM noise; designed as a test set for source separation experiments.                          |    True    |
| **WHAM! and WHAMR!**        | [WHAM! and WHAMR!](http://wham.whisper.ai/)                           | The WHAM! dataset pairs two-speaker mixtures with real noise backgrounds; WHAMR! extends this with artificial reverberation. |    True    |

---

### Health & Clinical Speech Datasets

| Dataset                        | Download                                                               | Description                                                                                                                  | OpenSource |
|--------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **Coswara**                    | [Coswara](https://github.com/iiscleap/Coswara-Data)                    | A database of respiratory sounds (cough, breath, and speech) from healthy and COVID-19 positive individuals.                 |    True    |
| **Parkinson's Speech Dataset** | [Parkinson's Speech Dataset](https://archive.org/details/daps_dataset) | Recordings from 20 Parkinson’s Disease patients and 20 healthy subjects across 26 types of sound recordings (approx. 20 MB). |    True    |

---

### Audio Events and Music

| Dataset                            | Download                                                                                                   | Description                                                                                                                      | OpenSource |
|------------------------------------|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **AudioSet**                       | [AudioSet](https://research.google.com/audioset/)                                                          | An expanding ontology of 632 audio event classes with over 2 million 10-second sound clips drawn from YouTube videos.            |    True    |
| **Bird Audio Detection Challenge** | [Bird Audio Detection Challenge](http://machine-listening.eecs.qmul.ac.uk/bird-audio-detection-challenge/) | Datasets collected from live bio-acoustics monitoring projects (approx. 5.4 GB).                                                 |    True    |
| **Environmental Audio Dataset**    | [Environmental Audio Dataset](http://www.cs.tut.fi/~heittolt/datasets)                                     | A collection of manually annotated environmental audio recordings for sound research.                                            |    True    |
| **Free Music Archive**             | [Free Music Archive](https://github.com/mdeff/fma)                                                         | A dataset for music analysis; approximately 1000 GB in size.                                                                     |    True    |
| **Freesound Dataset**              | [Freesound Dataset](https://www.kaggle.com/c/freesound-audio-tagging-2019/data)                            | 678,511 candidate annotations indicating the potential presence of sound sources in audio clips.                                 |    True    |
| **Karoldvl-ESC**                   | [Karoldvl-ESC](https://github.com/karoldvl/ESC-50)                                                         | A labeled collection of 2,000 environmental audio recordings suitable for benchmarking sound classification methods.             |    True    |
| **Million Song Dataset**           | [Million Song Dataset](https://labrosa.ee.columbia.edu/millionsong/)                                       | A freely available collection of audio features and metadata for one million contemporary popular music tracks (approx. 280 GB). |    True    |
| **MUSDB18**                        | [MUSDB18](https://sigsep.github.io/datasets/musdb.html)                                                    | A multi-track music dataset for source separation containing 150 tracks (~22 GB).                                                |    True    |
| **Public Domain Sounds**           | [Public Domain Sounds](http://pdsounds.tuxfamily.org/)                                                     | A collection of sounds (524 MB; 635 sounds) suitable for wake word detection and other audio tasks, all in the public domain.    |    True    |
| **RSC Sounds**                     | [RSC Sounds](https://github.com/2003scape/rsc-sounds)                                                      | Sounds from RuneScape Classic; 8-bit, u-law encoded, 8000 Hz PCM samples.                                                        |    True    |
| **Urban Sound Dataset**            | [Urban Sound Dataset](https://urbansounddataset.weebly.com/)                                               | Two datasets and a taxonomy for urban sound research.                                                                            |    True    |

---

### Answering Machine Detection (AMD)

| Dataset                  | Download                                                                                                                    | Description                                                                                                                                                                                                                                                                                                 | OpenSource |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------:|
| **IBM Voicemail Corpus** | [Voicemail Corpus Part I](https://catalog.ldc.upenn.edu/LDC98S77)                                                           | The IBM Voicemail Corpus, published by the Linguistic Data Consortium (LDC), is a comprehensive source of actual voicemail messages. The Voicemail Corpus Part I (1998) contains approximately 1,801 voicemail messages (average message duration 31 s, total ~15 hr)                                       |   False    |
| **Infobip AMD**          | [Infobip AMD](https://www.infobip.com/docs/voice-and-video/getting-started#answering-machine-detection-add-ons-and-options) | An internal dataset from Infobip, mentioned in an academic study in 2024, provided real call data for AMD models. This dataset consists of approximately 4,200 phone call audio files, and each recording is trimmed to around 4 seconds                                                                    |   False    |
| **Wavix Voicemail**      | [Wavix Voicemail](https://wavix.com/amd)                                                                                    | Cloud communications provider Wavix says it uses a vast database of proprietary data to back up its AI-based solution for AMD. The company’s AMD engine learns from a database of patterns based on billions of voice samples from voicemail machines, including regional accents and different languages.  |   False    |

## Hub

---

### TalkBank

The following table lists the TalkBank CABank corpora—naturalistic conversational recordings amenable to conversation
analysis—and includes additional TalkBank collections relevant to conversation analysis. You can also browse the CABank
database online from [TalkBank](https://ca.talkbank.org/access/).

| Dataset                   | Description                                                                                          | OpenSource |
|---------------------------|------------------------------------------------------------------------------------------------------|:----------:|
| **Bergmann**              | German emergency phone calls, recorded by Jörg Bergmann.                                             |    True    |
| **Bradford**              | Narrative samples from African American adults from Washington, D.C.                                 |    True    |
| **Business**              | Lingua Franca Business English phone calls.                                                          |    True    |
| **CABNC**                 | Spoken language segment of the British National Corpus.                                              |    True    |
| **CallFriend**            | Phone calls in Chinese, English, French, German, Japanese, and Spanish.                              |    True    |
| **CallHome**              | Phone calls in Arabic, Chinese, English, German, Japanese, and Spanish.                              |    True    |
| **CLAPI**                 | French conversations from the CLAPI Project.                                                         |    True    |
| **CORAAL**                | Corpus of Regional African American Language.                                                        |    True    |
| **CMU**                   | Conversations collected by students at CMU (teaching use only).                                      |    True    |
| **Croatian**              | Spontaneous informal conversations of adult speakers of different ages in various Croatian dialects. |    True    |
| **Examples**              | Examples for testing the TalkBank browser.                                                           |    True    |
| **Garfinkel-Seminars**    | Lectures by Harold Garfinkel, contributed by Johannes Wagner.                                        |    True    |
| **GCSAusE**               | Australian conversations.                                                                            |    True    |
| **Goodwin**               | Conversation analysis video.                                                                         |    True    |
| **Grimshaw**              | An hour-long dissertation defense.                                                                   |    True    |
| **GulfWar**               | Radio call-in show discussions during the first day of the first Gulf War.                           |    True    |
| **Istriot**               | Conversations of 13 Istriot speakers.                                                                |    True    |
| **ISL**                   | Conversations recorded for ASR testing in meetings.                                                  |    True    |
| **JOC**                   | Eight conversations from a special issue of the Journal of Communication.                            |    True    |
| **Mambila**               | Conversations in Mambila.                                                                            |    True    |
| **Mesolex**               | Mesolex corpus.                                                                                      |    True    |
| **MICASE**                | Michigan Corpus of Academic Spoken English.                                                          |    True    |
| **Mopan**                 | Mopan narratives.                                                                                    |    True    |
| **MOVIN**                 | Conversations in Danish, German, French, English, and Italian.                                       |    True    |
| **Nahuatl**               | Nahuatl story of a shooting.                                                                         |    True    |
| **Sakura**                | Videotaped conversations of groups of 4 Japanese college students (not in CA format yet).            |    True    |
| **SBCSAE**                | The Santa Barbara Corpus of Spoken American English; various interactional types.                    |    True    |
| **SCoSE**                 | Saarbrücken Corpus of Spoken (American) English.                                                     |    True    |
| **SPIRE**                 | HCI design discussions.                                                                              |    True    |
| **Taiwan Hakka**          | Conversations and narratives in Taiwan Hakka.                                                        |    True    |
| **Taiwan Mandarin**       | Conversations in Taiwan Mandarin.                                                                    |    True    |
| **Yiddish**               | Hassidic Jews in New York speaking Yiddish.                                                          |    True    |
| **Yucatec**               | Storytelling in Yucatec Mayan.                                                                       |    True    |
| **Jefferson**             | *Group: Transcriptions by Gail Jefferson*                                                            |    True    |
| **Lingua Franca**         | Transcriptions by Gail Jefferson.                                                                    |    True    |
| **Newport Beach**         | Transcriptions by Gail Jefferson.                                                                    |    True    |
| **Poetics**               | Lecture in Boston in 1977 by Gail Jefferson.                                                         |    True    |
| **Watergate**             | Phone call transcriptions from Watergate by Gail Jefferson.                                          |    True    |
| **Aligned**               | A few NB and Watergate raw audio files processed through ASR.                                        |    True    |
| **SCOTUS**                | *Group: US Supreme Court recordings*                                                                 |    True    |
| **SCOTUS-Blackmun**       | Interview with Justice Henry Blackmun.                                                               |    True    |
| **SCOTUS-Douglas**        | Interview with Justice William O. Douglas.                                                           |    True    |
| **SCOTUS_Oral_Arguments** | Oral arguments in the US Supreme Court (38 years, each in its own archive).                          |    True    |

---

### OpenSLR

**OpenSLR** is an initiative to host speech and language resources that need stable URLs for research and development in
speech recognition (ASR), speaker identification, text-to-speech (TTS), and related fields. You can find more details
and the official site here: [OpenSLR.org](http://www.openslr.org).

| Dataset                          | Description                                                                                                                | OpenSource |
|----------------------------------|----------------------------------------------------------------------------------------------------------------------------|:----------:|
| **SLR1: Yesno**                  | Speech – Sixty recordings of one individual saying yes or no in Hebrew; each recording is eight words long.                |    True    |
| **SLR2: OpenFST**                | Software – A mirror of the OpenFst toolkit.                                                                                |    True    |
| **SLR3: sph2pipe**               | Software – A mirror of the sph2pipe software.                                                                              |    True    |
| **SLR4: sctk**                   | Software – A mirror of the sctk scoring software.                                                                          |    True    |
| **SLR5: MSU Switchboard**        | Text – A mirror of the Mississippi State transcripts and lexicon for Switchboard.                                          |   False    |
| **SLR6: Vystadial**              | Speech – English and Czech data, mirrored from the Vystadial project.                                                      |    True    |
| **SLR7: TED-LIUM**               | Speech – English speech recognition training corpus from TED talks, created by LIUM (mirrored here).                       |    True    |
| **SLR8: Sprakbanken**            | Text – Danish pronunciation dictionary generated using eSpeak.                                                             |    True    |
| **SLR9: The AMI pack**           | Text – Some auxiliary non-speech data used to build AMI systems with Kaldi.                                                |    True    |
| **SLR10: SRE Data**              | Misc – Various files from SRE data that NIST used to host online.                                                          |   False    |
| **SLR11: LibriSpeech LMs**       | Text – Language modeling resources, vocabulary, and G2P models for LibriSpeech.                                            |    True    |
| **SLR12: LibriSpeech**           | Speech – Large-scale (1000 hours) corpus of read English speech.                                                           |    True    |
| **SLR13: RWCP**                  | Speech + Software – A database of real-world sounds, measured room impulse responses (mirrored from RWCP).                 |    True    |
| **SLR14: BEEP Dictionary**       | Text – Phonemic transcriptions of over 250,000 English words (British English pronunciations).                             |    True    |
| **SLR15: SRE Speaker List**      | Misc – A list linking speakers across NIST SRE corpora.                                                                    |    True    |
| **SLR16: The AMI Corpus**        | Speech – Acoustic speech data and meta-data from The AMI corpus.                                                           |   False    |
| **SLR17: MUSAN**                 | Audio – A corpus of music, speech, and noise.                                                                              |    True    |
| **SLR18: THCHS-30**              | Speech – A free Chinese speech corpus released by CSLT@Tsinghua University.                                                |    True    |
| **SLR19: TED-LIUMv2**            | Audio – Release 2 of the TED-LIUM corpus for English speech recognition, mirrored here.                                    |    True    |
| **SLR20: Aachen IR**             | Audio – Aachen Impulse Response database (AIR), a database of room impulse responses (mirrored).                           |    True    |
| **SLR21: Spanish Word List**     | Text – A list of Spanish words with frequencies derived from a large Spanish Gigaword corpus.                              |    True    |
| **SLR22: THUYG-20**              | Speech – A free Uyghur speech database by CSLT@Tsinghua University & Xinjiang University.                                  |    True    |
| **SLR23: NIST LRE 2007 Key**     | Misc – Metadata for utterances in the LRE 2007 evaluation.                                                                 |   False    |
| **SLR24: Iban**                  | Speech – Iban language text and speech corpora for ASR.                                                                    |    True    |
| **SLR25: ALFFA**                 | Speech – African Languages in the Field: includes Amharic, Swahili, and Wolof data.                                        |    True    |
| **SLR26: Simulated RIR**         | Audio – A database of simulated room impulse responses.                                                                    |    True    |
| **SLR27: Cantab-TEDLIUM**        | Text – Cantab Research Language Models for the TEDLIUM database.                                                           |    True    |
| **SLR28: Room IR & Noise**       | Audio – A database of simulated/real RIRs, isotropic/point-source noises (16kHz, 16-bit).                                  |    True    |
| **SLR29: Sprakbanken_Swe**       | Text – Swedish pronunciation dictionary.                                                                                   |    True    |
| **SLR30: Sinhala TTS**           | Speech – Sinhalese multi-speaker TTS corpora.                                                                              |    True    |
| **SLR31: Mini LibriSpeech**      | Speech – A regression-test subset of the LibriSpeech corpus.                                                               |    True    |
| **SLR32: Four South African**    | Speech – High-quality TTS data for four South African languages (Afrikaans, Sesotho, Setswana, isiXhosa).                  |    True    |
| **SLR33: Aishell**               | Speech – Mandarin data provided by Beijing Shell Shell Technology Co., Ltd.                                                |    True    |
| **SLR34: Santiago Spanish**      | Text – A pronouncing dictionary for the Spanish language.                                                                  |    True    |
| **SLR35: Large Javanese**        | Speech – Javanese ASR data (~185K utterances).                                                                             |    True    |
| **SLR36: Large Sundanese**       | Speech – Sundanese ASR data (~220K utterances).                                                                            |    True    |
| **SLR37: High-quality TTS (bn)** | Speech – Multi-speaker TTS data for Bangladesh Bengali (bn-BD) and Indian Bengali (bn-IN).                                 |    True    |
| **SLR38: Free ST Chinese**       | Speech – A free Chinese Mandarin corpus by Surfingtech, 855 speakers, 102600 utterances.                                   |    True    |
| **SLR39: Heroico**               | Speech – Spanish data, mirrored from the LDC.                                                                              |    True    |
| **SLR40: Zeroth-Korean**         | Speech – Korean ASR corpus from the Zeroth Project (https://github.com/goodatlas/zeroth).                                  |    True    |
| **SLR41: TTS for Javanese**      | Speech – Multi-speaker TTS data for Javanese (jv-ID).                                                                      |    True    |
| **SLR42: TTS for Khmer**         | Speech – Multi-speaker TTS data for Khmer (km-KH).                                                                         |    True    |
| **SLR43: TTS for Nepali**        | Speech – Multi-speaker TTS data for Nepali (ne-NP).                                                                        |    True    |
| **SLR44: TTS for Sundanese**     | Speech – Multi-speaker TTS data for Sundanese (su-ID).                                                                     |    True    |
| **SLR45: Free ST American**      | Speech – A free American English corpus by Surfingtech, 10 speakers, ~350 utterances each.                                 |    True    |
| **SLR46: Tunisian_MSA**          | Speech – Tunisian Modern Standard Arabic.                                                                                  |    True    |
| **SLR47: Primewords**            | Speech – 100 hours of Chinese Mandarin from Shanghai Primewords.                                                           |    True    |
| **SLR48: MADCAT Arabic splits**  | Other – Unofficial data splits (dev/train/test) for LDC’s MADCAT Arabic corpus.                                            |    True    |
| **SLR49: VoxCeleb Data**         | Misc – Various files for the VoxCeleb datasets.                                                                            |    True    |
| **SLR50: MADCAT Chinese splits** | Other – Unofficial data splits (dev/train/test) for LDC’s MADCAT Chinese corpus.                                           |    True    |
| **SLR51: TED-LIUM Release 3**    | Speech – Third release of the TED-LIUM corpus.                                                                             |    True    |
| **SLR52: Large Sinhala**         | Speech – Sinhala ASR data (~185K utterances).                                                                              |    True    |
| **SLR53: Large Bengali**         | Speech – Bengali ASR data (~196K utterances).                                                                              |    True    |
| **SLR54: Large Nepali**          | Speech – Nepali ASR data (~157K utterances).                                                                               |    True    |
| **SLR55: CLMAD**                 | Text – A Chinese Language Model Adaptation Dataset.                                                                        |    True    |
| **SLR56: IAM Aachen splits**     | Other – Aachen train/test/val splits for the IAM dataset.                                                                  |    True    |
| **SLR57: African Accented FR**   | Speech – Recordings of African-accented French speech.                                                                     |    True    |
| **SLR58: Pansori-TEDxKR**        | Speech – Korean speech from TEDx talks.                                                                                    |    True    |
| **SLR59: ParlamentParla**        | Speech – Catalan speech from Catalan Parliamentary sessions.                                                               |    True    |
| **SLR60: LibriTTS**              | Speech – Large-scale corpus of English speech derived from LibriSpeech for TTS (2,456 speakers, ~585 hours).               |    True    |
| **SLR61: Argentinian Spanish**   | Speech – Crowdsourced Argentinian Spanish data (~5739 recordings).                                                         |    True    |
| **SLR62: aidatatang_200zh**      | Speech – A 200-hour Chinese Mandarin speech corpus from Beijing DataTang.                                                  |    True    |
| **SLR63: Malayalam**             | Speech – Crowdsourced Malayalam multi-speaker speech dataset.                                                              |    True    |
| **SLR64: Marathi**               | Speech – Crowdsourced Marathi multi-speaker speech dataset.                                                                |    True    |
| **SLR65: Tamil**                 | Speech – Crowdsourced Tamil multi-speaker speech dataset.                                                                  |    True    |
| **SLR66: Telugu**                | Speech – Crowdsourced Telugu multi-speaker speech dataset.                                                                 |    True    |
| **SLR67: TEDx Spanish**          | Speech – Spanish data extracted from TEDx Talks.                                                                           |    True    |
| **SLR68: MAGICDATA**             | Speech – 755 hours of Mandarin from 1080 speakers by Magic Data Technology Co.                                             |    True    |
| **SLR69: Catalan**               | Speech – Crowdsourced high-quality Catalan speech dataset.                                                                 |    True    |
| **SLR70: Nigerian English**      | Speech – Crowdsourced high-quality Nigerian English speech dataset.                                                        |    True    |
| **SLR71: Chilean Spanish**       | Speech – Crowdsourced high-quality Chilean Spanish speech dataset.                                                         |    True    |
| **SLR72: Colombian Spanish**     | Speech – Crowdsourced high-quality Colombian Spanish speech dataset.                                                       |    True    |
| **SLR73: Peruvian Spanish**      | Speech – Crowdsourced high-quality Peruvian Spanish speech dataset.                                                        |    True    |
| **SLR74: Puerto Rico Spanish**   | Speech – Crowdsourced high-quality Puerto Rico Spanish speech dataset.                                                     |    True    |
| **SLR75: Venezuelan Spanish**    | Speech – Crowdsourced high-quality Venezuelan Spanish speech dataset.                                                      |    True    |
| **SLR76: Basque**                | Speech – Crowdsourced high-quality Basque speech dataset.                                                                  |    True    |
| **SLR77: Galician**              | Speech – Crowdsourced high-quality Galician speech dataset.                                                                |    True    |
| **SLR78: Gujarati**              | Speech – Crowdsourced high-quality Gujarati multi-speaker dataset.                                                         |    True    |
| **SLR79: Kannada**               | Speech – Crowdsourced high-quality Kannada multi-speaker dataset.                                                          |    True    |
| **SLR80: Burmese**               | Speech – Crowdsourced high-quality Burmese speech dataset.                                                                 |    True    |
| **SLR81: Small Audio Clips**     | Speech – 20 one-second audio clips from various sources, for testing.                                                      |    True    |
| **SLR82: CN-Celeb**              | Speech – Free Chinese Speaker Recognition corpus by CSLT@Tsinghua University (1,000 speakers).                             |    True    |
| **SLR83: UK/Irish English**      | Speech – Crowdsourced UK/Ireland dialect speech data, male and female.                                                     |    True    |
| **SLR84: ScribbleLens**          | Handwriting – Dutch cursive, 16-18th century pages/lines for AI research.                                                  |    True    |
| **SLR85: HI-MIA**                | Speech – Far-field text-dependent speaker verification (AISHELL Speaker Verification Challenge 2019).                      |    True    |
| **SLR86: Yoruba**                | Speech – Crowdsourced high-quality Yoruba speech dataset.                                                                  |    True    |
| **SLR87: MobvoiHotwords**        | Speech – Chinese hotword detection dataset from Mobvoi Co., Ltd.                                                           |    True    |
| **SLR88: Att-HACK**              | Speech – French expressive speech database (social attitudes).                                                             |    True    |
| **SLR89: Yoloxóchitl-Mixtec**    | Speech – Yolóxochitl Mixtec speech with transcription.                                                                     |    True    |
| **SLR92: Puebla-Nahuatl**        | Speech – Puebla Nahuatl speech with transcription.                                                                         |    True    |
| **SLR93: AISHELL-3**             | Speech – Mandarin TTS data by Beijing Shell Shell Technology (218 speakers, ~85 hours).                                    |    True    |
| **SLR94: MLS**                   | Speech – Multilingual LibriSpeech, a large dataset derived from LibriVox.                                                  |    True    |
| **SLR95: Thorsten Müller**       | Speech – Free single German speaker dataset (>23 hours) for TTS (by Thorsten Müller & Dominik Kreutz).                     |    True    |
| **SLR96: Russian LibriSpeech**   | Speech – Russian ASR dataset based on LibriVox audiobooks.                                                                 |    True    |
| **SLR97: Deeply Korean**         | Speech – Korean read-speech corpus with 3 text sentiments and 3 vocal sentiments, recorded in 3 places.                    |    True    |
| **SLR98: Deeply Parent-Child**   | Speech – Parent-child vocal interaction dataset (fairy tales, songs, etc.), in 3 places, at 3 distances, smartphone-based. |    True    |
| **SLR99: Deeply Nonverbal**      | Audio – Human nonverbal vocal sound dataset by Deeply Inc.                                                                 |    True    |
| **SLR100: Multilingual TEDx**    | Speech – Multilingual corpus of TEDx talks for speech recognition and translation.                                         |    True    |
| **SLR101: speechocean762**       | Speech – Pronunciation scoring dataset with each utterance labeled by five human experts.                                  |    True    |
| **SLR102: Kazakh Speech**        | Speech – A 330-hour crowdsourced Kazakh corpus by ISSAI.                                                                   |    True    |
| **SLR103: MUCS sub-task1**       | Speech – Multilingual/code-switching ASR Challenge datasets (low resource Indian languages).                               |    True    |
| **SLR104: MUCS sub-task2**       | Speech – Follow-up data for multilingual/code-switching ASR challenges.                                                    |    True    |
| **SLR105: nicolingua-0003**      | Speech – West African Radio Corpus.                                                                                        |    True    |
| **SLR106: nicolingua-0004**      | Speech – West African Virtual Assistant Speech Recognition Corpus.                                                         |    True    |
| **SLR107: Totonac**              | Speech – Totonac speech with transcription.                                                                                |    True    |
| **SLR108: MediaSpeech**          | Speech – French, Arabic, Turkish, Spanish media speech datasets.                                                           |    True    |
| **SLR109: Hi-Fi TTS**            | Speech – Multi-speaker English TTS dataset (Hi-Fi TTS).                                                                    |    True    |
| **SLR110: German Emotional**     | Speech – Free emotional single German speaker dataset by Thorsten Müller & Dominik Kreutz.                                 |    True    |
| **SLR111: AISHELL-4**            | Speech – Free Mandarin multi-channel meeting corpus (120 hours).                                                           |    True    |
| **SLR112: Samromur 21.05**       | Speech – Icelandic speech corpus, May 2021 release.                                                                        |    True    |
| **SLR113: SEOUL CORPUS**         | Speech – The Korean Corpus of Spontaneous Speech from an NRF-funded project.                                               |    True    |
| **SLR114: Golos**                | Speech – Russian ASR dataset (~1240 hours) with acoustic and language models.                                              |    True    |
| **SLR115: EmoV_DB**              | Speech – Emotional speech database for synthesis & generation (English, male/female).                                      |    True    |
| **SLR116: Samrómur Queries**     | Speech – Icelandic speech corpus focused on queries, Dec 2021 release.                                                     |    True    |
| **SLR117: Samrómur Children**    | Speech – Icelandic speech from children (ages 4-17), Sep 2021 release.                                                     |    True    |
| **SLR118: 1111 Hours Hindi**     | Speech – Data for 1111 Hours Hindi ASR Challenge (closed, self-supervised, open).                                          |    True    |
| **SLR119: AliMeeting**           | Speech – Free Mandarin multi-channel meeting corpus by Alibaba Group.                                                      |    True    |
| **SLR120: HI-MIA-CW**            | Speech – Free Mandarin supplemental corpus to HI-MIA (negative samples for “Hi, Mia” wake word).                           |    True    |
| **SLR121: WenetSpeech**          | Speech – 10,000+ hour multi-domain Mandarin corpus for speech recognition.                                                 |    True    |
| **SLR122: Kashmiri**             | Speech – Audio+text corpus for the Kashmiri language.                                                                      |    True    |
| **SLR123: MAGICDATA Convers**    | Speech – 180 hours of annotated spontaneous Mandarin speech from Magic Data.                                               |    True    |
| **SLR124: TIBMD@MUC**            | Speech – A Tibetan multi-dialect dataset (84.33 hours).                                                                    |    True    |
| **SLR125: Faroese BLARK**        | Speech – Faroese Basic Language Resource Kit 1.0.                                                                          |    True    |
| **SLR126: IISc-MILE Kannada**    | Speech – Kannada transcribed speech corpus for ASR.                                                                        |    True    |
| **SLR127: IISc-MILE Tamil**      | Speech – Tamil transcribed speech corpus for ASR.                                                                          |    True    |
| **SLR128: Samrómur Unverified**  | Speech – Icelandic speech (~2,200 hours) mostly unverified, July 2022 release.                                             |    True    |
| **SLR129: BibleTTS**             | Speech – A large African multilingual TTS corpus (high fidelity).                                                          |    True    |
| **SLR130: Samrómur L2**          | Speech – Icelandic speech (~150 hours) from L2 (non-native) speakers, Jul 2022.                                            |    True    |
| **SLR131: Samrómur Mimic**       | Speech – Icelandic speech (66.7 hours) where users mimic utterances, Sep 2022.                                             |    True    |
| **SLR132: Mohammed**             | Speech – Arabic speech-to-text Quran data.                                                                                 |    True    |
| **SLR133: XBMU-AMDO31**          | Speech – Tibetan Amdo dialect speech data from Northwest Minzu University.                                                 |    True    |
| **SLR134: SASPEECH**             | Speech – Hebrew (single speaker, 30 hours) with transcripts.                                                               |    True    |
| **SLR135: Libri-Mixed-Speakers** | Speech – English audio of simultaneous speakers derived from LibriTTS.                                                     |    True    |
| **SLR136: EMNS**                 | Speech, TTS, ASR – Emotive single-speaker dataset for narrative storytelling (with emotion, intensity labels).             |    True    |
| **SLR137: Silbo Gomero**         | Speech – 49 minutes of Silbo Gomero whistled language from 4 whistlers.                                                    |    True    |
| **SLR138: SHALCAS22A**           | Speech – Chinese Mandarin corpus by Shanghai Acoustics Laboratory & Wuxi Sandu.                                            |    True    |
| **SLR139: Audiocite.net**        | Speech – French audiobook recordings collected from audiocite.net (GETALP).                                                |    True    |
| **SLR140: Kazakh Speech (KSD)**  | Speech – 554-hour open-source Kazakh corpus from Al-Farabi Kazakh National University.                                     |    True    |
| **SLR141: LibriTTS-R**           | Speech – Sound-quality improved version of LibriTTS (large-scale English TTS).                                             |    True    |
| **SLR142: The MC Speech**        | Speech – Polish speech dataset with 24,018 short audio clips of a single speaker.                                          |    True    |
| **SLR143: Nepali TTS**           | Speech – Nepali text-to-speech data (male and female).                                                                     |    True    |
| **SLR144: SlideSpeech**          | Audio-Visual – Large-scale English multi-modal corpus, provided by Alibaba Group.                                          |    True    |
| **SLR145: LibriSpeech-PC**       | Text – LibriSpeech text with Punctuation and Capitalization.                                                               |    True    |
| **SLR146: CML-TTS**              | Speech – A multilingual dataset for TTS in low-resource languages.                                                         |    True    |
| **SLR147: Veracruz Orizaba**     | Speech – Orizaba (Veracruz) Nahuatl (ISO 639-3: nlv) speech corpus.                                                        |    True    |
| **SLR148: Tepetzintla**          | Speech – Zacatlán-Ahuacatlán-Tepetzintla (Puebla) Nahuatl (ISO 639-3: nhi) speech corpus.                                  |    True    |
| **SLR149: Tibetan Greetings**    | Speech – Selected Tibetan greetings data from various dialectal regions.                                                   |    True    |
| **SLR150: CHiME-6**              | Speech – English multi-channel far-field meeting data from CHiME-5, with synchronization fixes.                            |    True    |
| **SLR151: Kallaama**             | Speech – Wolof, Pulaar, and Sereer data.                                                                                   |    True    |
| **SLR152: Pragmatic Similarity** | Speech – Perceived similarity judgments between utterance pairs (English & Spanish).                                       |    True    |
| **SLR153: Yerevan City Mag**     | Text – A free Armenian news text corpus from Yerevan City Magazine (evnmag.com).                                           |    True    |
| **SLR154: ArmenianGrqaserAudio** | Speech – Audio-text pairs derived from Grqaser.org audiobooks (Armenian).                                                  |    True    |
| **SLR155: SBCSAE**               | Speech – The Santa Barbara Corpus of Spoken American English, mirrored from UCSB.                                          |    True    |
| **SLR156: SMIIP-TV**             | Speech – Short-term time-varying speaker verification dataset.                                                             |    True    |
| **SLR157: Sagalee**              | Speech – ASR dataset for Oromo (“Sagalee”).                                                                                |    True    |

