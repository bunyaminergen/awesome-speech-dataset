<div align="center">

# Awesome Speech Dataset

*Below is a markdown table summarizing the main sources for the Awesome Speech Dataset, including download links and a
brief explanation for each resource. These datasets provide diverse and high-quality speech data covering various
domains such as conversational, academic, political, and more. They are widely used for tasks like automatic speech
recognition (ASR), speaker identification, emotion analysis, and other speech processing applications.*

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

</div>

---

## Table of Contents

- [Topic](#topic)
    - [ASR](#asr)
    - [Speaker Recognition](#speaker-recognition)
    - [Emotion Recognition](#emotion-recognition)
    - [Multilingual Speech Corpora](#multilingual-speech-corpora)
    - [TTS](#tts)
    - [Speaker Diarization](#speaker-diarization)
    - [Source Separation](#source-separation)
    - [Health & Clinical Speech Datasets](#health--clinical-speech-datasets)
    - [Audio Events and Music](#audio-events-and-music)
- [Hub](#hub)
    - [TalkBank](#talkbank)

---

## Topic

---

### ASR

| Dataset                                                | Download                                                                                           | Description                                                                                                                                                                                |
|--------------------------------------------------------|----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **LibriSpeech**                                        | [OpenSLR SLR12](https://www.openslr.org/12)                                                        | ~1000 hours of 16 kHz English read speech derived from LibriVox audiobooks. Includes “clean” and “other” subsets, widely used for training and benchmarking ASR models.                    |
| **AISHELL-1 (Mandarin)**                               | [OpenSLR AISHELL-1](https://www.openslr.org/33/)                                                   | An open-source Mandarin Chinese speech corpus with ~178 hours of speech from 400 native speakers, recorded at 16 kHz with high-quality manual transcriptions; a benchmark for Chinese ASR. |
| **TED-LIUM (Release 3)**                               | [OpenSLR TED-LIUM 3](https://www.openslr.org/51/)                                                  | An English ASR dataset based on TED talks with 452 hours of audio from 2,351 talks, featuring diverse speakers and topics, ideal for lecture and presentation speech recognition.          |
| **CHiME Speech**                                       | [CHiME Challenge Datasets](http://chimechallenge.org)                                              | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far-field ASR research.                            |
| **GigaSpeech**                                         | [OpenSLR SLR85 / GitHub GigaSpeech](https://www.openslr.org/85)                                    | Extensive corpus with ~10,000 hours of transcribed speech and nearly 50,000 hours of audio from multiple sources, used for ASR training and evaluation.                                    |
| **Spotify Podcast Dataset**                            | [Podcast Dataset](https://podcastsdataset.github.io/)                                              | A dataset of over 100,000 podcast episodes with more than 100,000 hours of speech and extensive transcripts, used for various speech processing applications including ASR and LM.         |
| **SPGISpeech (Kensho)**                                | [Download Data](https://www.kensho.com/dataset)                                                    | A large-scale transcription dataset with 5,000 hours of professionally-transcribed financial audio from earnings calls; ideal for ASR research in the financial domain.                    |
| **ASR Datasets**                                       | [GitHub ASR_Audio_Data_Links](https://github.com/robmsmt/ASR_Audio_Data_Links)                     | A list of publicly available audio datasets for ASR or other speech activities.                                                                                                            |
| **AudioMNIST**                                         | [AudioMNIST](https://github.com/soerenab/AudioMNIST)                                               | 30,000 audio samples of spoken digits (0–9) from 60 different speakers.                                                                                                                    |
| **CMU Wilderness**                                     | [CMU Wilderness](http://festvox.org/cmu_wilderness/)                                               | A speech dataset with multiple accents reciting passages from the Bible.                                                                                                                   |
| **DAPS Dataset**                                       | [DAPS Dataset](https://archive.org/details/daps_dataset)                                           | 20 speakers reading 5 excerpts each from public domain books (~14 minutes of data per speaker).                                                                                            |
| **DIPCO**                                              | [DIPCO](https://arxiv.org/abs/1909.13447)                                                          | Dinner Party Corpus – recordings via a close-talk mic and five far-field arrays from 10 sessions (15–45 minutes each).                                                                     |
| **Free Spoken Digit Dataset**                          | [Free Spoken Digit Dataset](https://github.com/Jakobovski/free-spoken-digit-dataset)               | 2,000 recordings (50 per digit per speaker) of spoken digits from 4 speakers.                                                                                                              |
| **Flickr Audio Caption**                               | [Flickr Audio Caption](https://groups.csail.mit.edu/sls/downloads/flickraudio/)                    | 40,000 spoken captions for 8,000 natural images (approx. 4.2 GB).                                                                                                                          |
| **ISOLET Data Set**                                    | [ISOLET Data Set](https://data.world/uci/isolet)                                                   | A 38.7 GB dataset for predicting letter-names from spoken audio.                                                                                                                           |
| **Libriadapt**                                         | [Libriadapt](https://github.com/akhilmathurs/libriadapt)                                           | Designed to facilitate domain adaptation research for ASR models with three types of domain shifts.                                                                                        |
| **Libri-CSS**                                          | [Libri-CSS](https://github.com/chenzhuo1011/libri_css)                                             | Derived from LibriSpeech by concatenating utterances to simulate conversation with far-field replays.                                                                                      |
| **Microsoft Scalable Noisy Speech Dataset**            | [MS-SNSD](https://github.com/microsoft/MS-SNSD)                                                    | A noisy speech dataset that scales to arbitrary sizes with varying speakers, noise types, and SNR levels.                                                                                  |
| **MSP Podcast Corpus**                                 | [MSP Podcast Corpus](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Podcast.html)      | 100 hours of podcast speech from over 100 speakers, annotated with emotional labels and attribute-based descriptors.                                                                       |
| **OpenSLR**                                            | [OpenSLR](https://openslr.org)                                                                     | A repository hosting over 109 audio datasets for speech recognition purposes.                                                                                                              |
| **Persian Consonant Vowel Combination (PCVC) Dataset** | [PCVC](https://github.com/S-Malek/PCVC)                                                            | A Modern Persian speech corpus of consonant-vowel combinations (138 samples per speaker) useful for ASR and speaker recognition.                                                           |
| **sample_voice_data**                                  | [sample_voice_data](https://github.com/jim-schwoebel/sample_voice_data)                            | 52 audio files per class (male & female) for testing purposes.                                                                                                                             |
| **Speech Accent Archive**                              | [Speech Accent Archive](https://www.kaggle.com/rtatman/speech-accent-archive/version/1)            | A dataset for various accent detection tasks.                                                                                                                                              |
| **Speech Commands Dataset**                            | [Speech Commands Dataset](http://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html) | 65,000 one-second utterances of 30 short words contributed by members of the public.                                                                                                       |
| **Spoken Commands dataset**                            | [Spoken Commands dataset](https://github.com/JohannesBuchner/spoken-command-recognition)           | A large database of free audio samples for voice activity detection and syllable recognition.                                                                                              |
| **Spoken Wikipedia Corpora**                           | [Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/)                                            | A 38 GB dataset available in both audio and non-audio formats, based on Wikipedia articles.                                                                                                |
| **Tatoeba**                                            | [Tatoeba](https://tatoeba.org/eng/downloads)                                                       | A large database of sentences, translations, and spoken audio for language learning.                                                                                                       |
| **TIMIT dataset**                                      | [TIMIT dataset](https://catalog.ldc.upenn.edu/LDC93S1)                                             | Broadband recordings of 630 speakers reading phonetically rich sentences with time-aligned transcriptions.                                                                                 |
| **Zero Resource Speech Challenge**                     | [Zero Resource Speech Challenge](https://github.com/bootphon/zerospeech2017)                       | A challenge aimed at building an end-to-end spoken dialog system from scratch with zero linguistic expertise.                                                                              |

---

### Speaker Recognition

| Dataset                    | Download                                                                          | Description                                                                                                           |
|----------------------------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **VoxCeleb1**              | [VoxCeleb1](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)                       | 140k utterances from 1,251 speakers (≈352 hours) derived from celebrity interviews on YouTube.                        |
| **VoxCeleb2**              | [VoxCeleb2](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)              | Over 1 million utterances from 6,112 speakers (~2,442 hours), used for state-of-the-art speaker recognition research. |
| **CN-Celeb**               | [CN-Celeb (OpenSLR SLR82)](https://openslr.org/82/)                               | A large-scale Chinese speaker recognition dataset with over 130,000 utterances from 1,000 speakers across 11 genres.  |
| **Voice Gender Detection** | [Voice Gender Detection](https://github.com/jim-schwoebel/voice_gender_detection) | A GitHub repo for gender detection using the VoxCeleb dataset (7000+ speakers; roughly gender-balanced).              |

---

### Emotion Recognition

| Dataset                                    | Download                                                                                                              | Description                                                                                                                          |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| **IEMOCAP**                                | [USC IEMOCAP](https://sail.usc.edu/iemocap)                                                                           | ~12 hours of acted audiovisual dialogues by 10 actors with 9 emotion categories.                                                     |
| **RAVDESS**                                | [Zenodo RAVDESS](https://zenodo.org/record/1188976)                                                                   | 7,356 clips of emotional speech and song by 24 professional actors, covering 8 emotions.                                             |
| **CREMA-D**                                | [CREMA-D GitHub](https://github.com/CheyneyComputerScience/CREMA-D)                                                   | 7,442 audio-visual clips from 91 actors performing 12 sentences in 6 emotions with crowd-sourced ratings.                            |
| **AESDD**                                  | [AESDD](http://m3c.web.auth.gr/research/aesdd-speech-emotion-recognition/)                                            | ~500 utterances by diverse actors simulating various emotions.                                                                       |
| **ANAD**                                   | [ANAD](https://www.kaggle.com/suso172/arabic-natural-audio-dataset)                                                   | 1,384 recordings by multiple speakers with 3 emotions (angry, happy, surprised).                                                     |
| **BAVED**                                  | [BAVED](https://www.kaggle.com/a13x10/basic-arabic-vocal-emotions-dataset)                                            | 1,935 recordings by 61 speakers (45 male, 16 female) focusing on vocal emotion.                                                      |
| **CaFE**                                   | [CaFE](https://www.gel.usherbrooke.ca/audio/cafe.htm)                                                                 | 6 different sentences by 12 speakers (6 females, 6 males) for emotion recognition tasks.                                             |
| **CMU-MOSEI**                              | [CMU-MOSEI](https://www.amir-zadeh.com/datasets)                                                                      | 65 hours of annotated video and audio data from 1000+ speakers covering 6 emotions plus Likert scale ratings.                        |
| **CMU-MOSI**                               | [CMU-MOSI](https://www.amir-zadeh.com/datasets)                                                                       | 2,199 opinion utterances annotated with sentiment on a seven-point scale.                                                            |
| **DEMoS**                                  | [DEMoS](https://zenodo.org/record/2544829)                                                                            | 9,365 emotional and 332 neutral samples produced by 68 native speakers.                                                              |
| **DES**                                    | [DES](http://kom.aau.dk/~tb/speech/Emotions/)                                                                         | Recordings from 4 speakers expressing 5 emotions: neutral, surprise, happiness, sadness, and anger.                                  |
| **EEKK**                                   | [EEKK](https://metashare.ut.ee/repository/download/4d42d7a8463411e2a6e4005056b40024a19021a316b54b7fb707757d43d1a889/) | 26 passages read by 10 speakers in 4 emotions (joy, sadness, anger, neutral).                                                        |
| **Emo-DB**                                 | [Emo-DB](http://emodb.bilderbar.info/index-1280.html)                                                                 | 800 recordings from 10 actors (balanced gender) covering 7 emotions.                                                                 |
| **EmoFilm**                                | [EmoFilm](https://zenodo.org/record/1326428)                                                                          | 1,115 audio instances (sentences extracted from films) with emotional content.                                                       |
| **EmoSynth**                               | [EmoSynth](https://zenodo.org/record/3727593)                                                                         | 144 audio files labeled by 40 listeners in terms of valence and arousal.                                                             |
| **Emotional Voices Database**              | [Emotional Voices Database](https://github.com/numediart/EmoV-DB)                                                     | A dataset with various emotions recorded by 5 voice actors (amused, angry, disgusted, neutral, sleepy).                              |
| **Emotional Voice dataset - Nature**       | [Emotional Voice dataset - Nature](https://www.nature.com/articles/s41562-019-0533-6)                                 | 2,519 speech samples from 100 actors across 5 cultures, demonstrating at least 12 distinct emotions.                                 |
| **EmotionTTS**                             | [EmotionTTS](https://github.com/emotiontts/emotiontts_open_db)                                                        | Recordings with transcripts by diverse speakers in 4 emotions (general, joy, anger, sadness) – suited for TTS with emotional nuance. |
| **Emov-DB**                                | [Emov-DB](https://mega.nz/#F!KBp32apT!gLIgyWf9iQ-yqnWFUFuUHg!mYwUnI4K)                                                | Recordings from 4 speakers (2 male, 2 female) with emotions: neutral, sleepiness, anger, disgust, and amused.                        |
| **EMOVO**                                  | [EMOVO](http://voice.fub.it/activities/corpora/emovo/index.html)                                                      | 6 actors reading 14 sentences in 6 emotions: disgust, fear, anger, joy, surprise, and sadness.                                       |
| **eNTERFACE05**                            | [eNTERFACE05](http://www.enterface.net/enterface05/docs/results/databases/project2_database.zip)                      | Videos by 42 subjects from 14 nationalities in 6 emotions.                                                                           |
| **GEMEP corpus**                           | [GEMEP corpus](https://www.unige.ch/cisa/gemep)                                                                       | 10 actors portraying 10 states covering 12 primary and 5 additional emotions.                                                        |
| **JL corpus**                              | [JL corpus](https://www.kaggle.com/tli725/jl-corpus)                                                                  | 2,400 recordings of 240 sentences by 4 actors; includes 5 primary and 5 secondary emotions.                                          |
| **Keio-ESD**                               | [Keio-ESD](http://research.nii.ac.jp/src/en/Keio-ESD.html)                                                            | A Japanese male speaker dataset covering 47 different emotions.                                                                      |
| **LEGO Corpus**                            | [LEGO Corpus](https://www.ultes.eu/ressources/lego-spoken-dialogue-corpus/)                                           | 347 dialogs (9,083 exchanges) with emotions classified into garbage, non-angry, slightly angry, and very angry.                      |
| **MSP-IMPROV**                             | [MSP-IMPROV](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Improv.html)                                  | 20 sentences by 12 actors covering 4 emotions plus an “other” category.                                                              |
| **Multimodal EmotionLines Dataset (MELD)** | [MELD](https://github.com/SenticNet/MELD)                                                                             | Over 1,400 dialogues and 13,000 utterances from the TV series *Friends* labeled with 7 emotions.                                     |
| **MuSe-CAR**                               | [MuSe-CAR](https://zenodo.org/record/4134758)                                                                         | 40 hours and 25,000+ sentences from 70+ speakers for emotion recognition research.                                                   |
| **OGVC**                                   | [OGVC](https://sites.google.com/site/ogcorpus/home/en)                                                                | 9,114 spontaneous and 2,656 acted utterances by 4 professional actors covering 9 emotional states.                                   |
| **RECOLA**                                 | [RECOLA](https://diuf.unifr.ch/main/diva/recola/download.html)                                                        | 3.8 hours of recordings from 46 participants annotated with continuous valence and arousal values.                                   |
| **SAVEE Dataset**                          | [SAVEE Dataset](http://kahlan.eps.surrey.ac.uk/savee/)                                                                | 480 British English utterances from 4 male actors covering 7 different emotions.                                                     |
| **SEMAINE**                                | [SEMAINE](https://semaine-db.eu/)                                                                                     | 95 dyadic conversations from 21 subjects with 5 FeelTrace annotations (activation, valence, dominance, power, intensity).            |
| **SER Datasets**                           | [SER Datasets](https://github.com/SuperKogito/SER-datasets)                                                           | A collection of datasets aimed at emotion recognition/detection in speech.                                                           |
| **SEWA**                                   | [SEWA](https://db.sewaproject.eu/)                                                                                    | Over 2,000 minutes of audiovisual data from 398 people with continuous valence and arousal annotations.                              |
| **ShEMO**                                  | [ShEMO](https://github.com/mansourehk/ShEMO)                                                                          | 3,000 semi-natural utterances (~3 hours 25 minutes) from 87 native-Persian speakers in 6 emotion categories.                         |
| **TESS**                                   | [TESS](https://tspace.library.utoronto.ca/handle/1807/24487)                                                          | 2,800 recordings by 2 actresses covering 7 emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral).      |
| **URDU-Dataset**                           | [URDU-Dataset](https://github.com/siddiquelatif/urdu-dataset)                                                         | 400 utterances by 38 speakers (27 male, 11 female) in 4 emotions: angry, happy, neutral, and sad.                                    |
| **VIVAE**                                  | [VIVAE](https://zenodo.org/record/4066235)                                                                            | 1,085 non-speech audio files from ~12 speakers covering 6 emotions (achievement, anger, fear, pain, pleasure, surprise).             |

---

### Multilingual Speech Corpora

| Dataset                            | Download                                                                                 | Description                                                                                                                                                                                      |
|------------------------------------|------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Mozilla Common Voice**           | [Common Voice Datasets](https://commonvoice.mozilla.org/en/datasets)                     | A massively multilingual, crowd-sourced speech corpus with over 20,408 hours of validated speech across 124 languages; available under CC0 license.                                              |
| **Multilingual LibriSpeech (MLS)** | [Facebook AI MLS](https://dl.fbaipublicfiles.com/mls/index.html)                         | Derived from LibriVox audiobooks, spanning 8 languages with ~50,000 hours of speech; provides standardized splits for cross-lingual ASR research.                                                |
| **VoxPopuli**                      | [VoxPopuli GitHub](https://github.com/facebookresearch/voxpopuli)                        | European Parliament recordings (2009–2020) in 23 languages, offering 400,000 hours of unlabeled speech and 1,800 hours of transcribed data for multilingual ASR and speech translation research. |
| **MLCommons People's Speech**      | [Hugging Face People’s Speech](https://huggingface.co/datasets/MLCommons/peoples_speech) | Over 30,000 hours of transcribed English speech featuring diverse accents; widely used for ASR training and evaluation.                                                                          |

---

### TTS

| Dataset                      | Download                                                                         | Description                                                                                                                                                                                                                  |
|------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **LibriTTS**                 | [OpenSLR SLR60](https://www.openslr.org/60/)                                     | A TTS dataset derived from LibriVox audiobooks, containing ~585 hours of speech from 2,456 speakers; provides segmented audio with aligned text for multi-speaker TTS and voice cloning applications.                        |
| **LJSpeech-1.1**             | [LJSpeech Dataset](https://keithito.com/LJ-Speech-Dataset/)                      | A single-speaker English TTS dataset with 13,100 short audio clips (~24 hours) from a female speaker reading public-domain texts; widely used to train neural TTS models.                                                    |
| **VCTK (CSTR VCTK Corpus)**  | [VCTK Corpus](https://datashare.ed.ac.uk/handle/10283/3443)                      | A multi-speaker English speech corpus with 109 speakers from the UK, each reading about 400 sentences (~44 hours); provided at 48 kHz, used for accent-robust TTS, voice conversion, and ASR research.                       |
| **AISHELL-3 (Mandarin TTS)** | [OpenSLR AISHELL-3](https://openslr.org/93/)                                     | A multi-speaker Mandarin Chinese TTS corpus with ~85 hours of high-quality, emotion-neutral recordings from 218 native speakers with manual transcripts; supports multi-speaker and expressive TTS as well as voice cloning. |
| **Arabic Speech Corpus**     | [Arabic Speech Corpus](http://en.arabicspeechcorpus.com/)                        | A Modern Standard Arabic (MSA) speech corpus (1.5 GB) for speech synthesis with phonetic and orthographic transcriptions aligned at the phoneme level.                                                                       |
| **EmotionTTS**               | [EmotionTTS](https://github.com/emotiontts/emotiontts_open_db)                   | Recordings and associated transcriptions by a diverse set of speakers in 4 emotions (general, joy, anger, sadness) – suitable for developing emotionally expressive TTS models.                                              |
| **Thorsten dataset**         | [Thorsten dataset](https://github.com/thorstenMueller/deep-learning-german-tts/) | A German language TTS dataset with 22,668 recorded phrases (~23 hours), ideal for deep-learning based TTS research.                                                                                                          |

---

### Speaker Diarization

| Dataset                 | Download                                                                    | Description                                                                                    |
|-------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| **Awesome_Diarization** | [Awesome_Diarization](https://github.com/jim-schwoebel/awesome-diarization) | A curated list of papers, libraries, datasets, and resources for speaker diarization research. |

---

### Source Separation

| Dataset                     | Download                                                              | Description                                                                                                                  |
|-----------------------------|-----------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Deep Clustering Dataset** | [Deep Clustering Dataset](https://www.merl.com/demos/deep-clustering) | Dataset for training deep discriminative embeddings aimed at solving the cocktail party problem (source separation).         |
| **LibriMix**                | [LibriMix](https://github.com/JorisCos/LibriMix)                      | An open source dataset for source separation in noisy environments derived from LibriSpeech (clean) and WHAM noise.          |
| **SparseLibriMix**          | [SparseLibriMix](https://github.com/popcornell/SparseLibriMix)        | A test-set-only version for source separation with variable overlap-ratio.                                                   |
| **VCTK-2Mix**               | [VCTK-2Mix](https://github.com/JorisCos/VCTK-2Mix)                    | Derived from VCTK signals and WHAM noise; designed as a test set for source separation experiments.                          |
| **WHAM! and WHAMR!**        | [WHAM! and WHAMR!](http://wham.whisper.ai/)                           | The WHAM! dataset pairs two-speaker mixtures with real noise backgrounds; WHAMR! extends this with artificial reverberation. |

---

### Health & Clinical Speech Datasets

| Dataset                        | Download                                                                                                                                | Description                                                                                                                  |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Coswara**                    | [Coswara](https://github.com/iiscleap/Coswara-Data)                                                                                     | A database of respiratory sounds (cough, breath, and speech) from healthy and COVID-19 positive individuals.                 |
| **Parkinson's Speech Dataset** | [Parkinson's Speech Dataset](https://archive.ics.uci.edu/ml/datasets/Parkinson+Speech+Dataset+with++Multiple+Types+of+Sound+Recordings) | Recordings from 20 Parkinson’s Disease patients and 20 healthy subjects across 26 types of sound recordings (approx. 20 MB). |

---

### Audio Events and Music

| Dataset                            | Download                                                                                                   | Description                                                                                                                      |
|------------------------------------|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| **AudioSet**                       | [AudioSet](https://research.google.com/audioset/)                                                          | An expanding ontology of 632 audio event classes with over 2 million 10-second sound clips drawn from YouTube videos.            |
| **Bird Audio Detection Challenge** | [Bird Audio Detection Challenge](http://machine-listening.eecs.qmul.ac.uk/bird-audio-detection-challenge/) | Datasets collected from live bio-acoustics monitoring projects (approx. 5.4 GB).                                                 |
| **Environmental Audio Dataset**    | [Environmental Audio Dataset](http://www.cs.tut.fi/~heittolt/datasets)                                     | A collection of manually annotated environmental audio recordings for sound research.                                            |
| **Free Music Archive**             | [Free Music Archive](https://github.com/mdeff/fma)                                                         | A dataset for music analysis; approximately 1000 GB in size.                                                                     |
| **Freesound Dataset**              | [Freesound Dataset](https://www.kaggle.com/c/freesound-audio-tagging-2019/data)                            | 678,511 candidate annotations indicating the potential presence of sound sources in audio clips.                                 |
| **Karoldvl-ESC**                   | [Karoldvl-ESC](https://github.com/karoldvl/ESC-50)                                                         | A labeled collection of 2,000 environmental audio recordings suitable for benchmarking sound classification methods.             |
| **Million Song Dataset**           | [Million Song Dataset](https://labrosa.ee.columbia.edu/millionsong/)                                       | A freely available collection of audio features and metadata for one million contemporary popular music tracks (approx. 280 GB). |
| **MUSDB18**                        | [MUSDB18](https://sigsep.github.io/datasets/musdb.html)                                                    | A multi-track music dataset for source separation containing 150 tracks (~22 GB).                                                |
| **Public Domain Sounds**           | [Public Domain Sounds](http://pdsounds.tuxfamily.org/)                                                     | A collection of sounds (524 MB; 635 sounds) suitable for wake word detection and other audio tasks, all in the public domain.    |
| **RSC Sounds**                     | [RSC Sounds](https://github.com/2003scape/rsc-sounds)                                                      | Sounds from RuneScape Classic; 8-bit, u-law encoded, 8000 Hz PCM samples.                                                        |
| **Urban Sound Dataset**            | [Urban Sound Dataset](https://urbansounddataset.weebly.com/)                                               | Two datasets and a taxonomy for urban sound research.                                                                            |

---

## Hub

---

### TalkBank

The following table lists the TalkBank CABank corpora—naturalistic conversational recordings amenable to conversation
analysis—and includes additional TalkBank collections relevant to conversation analysis. You can also browse the CABank
database online from [TalkBank](https://ca.talkbank.org/access/).

| Corpus                    | Description                                                                                          | Contributor                               | Rating |
|---------------------------|------------------------------------------------------------------------------------------------------|-------------------------------------------|--------|
| **Bergmann**              | German emergency phone calls, recorded by Jörg Bergmann.                                             | Johannes Wagner                           | *****  |
| **Bradford**              | Narrative samples from African American adults from Washington, D.C.                                 | Angela Bradford Wainwright                | *      |
| **Business**              | Lingua Franca Business English phone calls.                                                          | Johannes Wagner                           | *****  |
| **CABNC**                 | Spoken language segment of the British National Corpus.                                              | Saul Albert                               | *****  |
| **CallFriend**            | Phone calls in Chinese, English, French, German, Japanese, and Spanish.                              | Linguistic Data Consortium                | **     |
| **CallHome**              | Phone calls in Arabic, Chinese, English, German, Japanese, and Spanish.                              | Linguistic Data Consortium                | **     |
| **CLAPI**                 | French conversations from the CLAPI Project.                                                         | Lorenza Mondada                           | *****  |
| **CORAAL**                | Corpus of Regional African American Language.                                                        | Tyler Kendall and Charlie Farrington      | ****   |
| **CMU**                   | Conversations collected by students at CMU (teaching use only).                                      | Brian MacWhinney                          | **     |
| **Croatian**              | Spontaneous informal conversations of adult speakers of different ages in various Croatian dialects. | Gordana Hrzica and Jelena Kuvac-Kraljevic | ***    |
| **Examples**              | Examples for testing the TalkBank browser.                                                           | Johannes Wagner and Brian MacWhinney      | ***    |
| **Garfinkel-Seminars**    | Lectures by Harold Garfinkel, contributed by Johannes Wagner.                                        | Johannes Wagner                           | *****  |
| **GCSAusE**               | Australian conversations.                                                                            | Michael Haugh                             | *****  |
| **Goodwin**               | Conversation analysis video.                                                                         | Charles Goodwin                           | *****  |
| **Grimshaw**              | An hour-long dissertation defense.                                                                   | Allen Grimshaw                            | *      |
| **GulfWar**               | Radio call-in show discussions during the first day of the first Gulf War.                           | Elizabeth Couper-Kuhlen                   | ***    |
| **Istriot**               | Conversations of 13 Istriot speakers.                                                                | Gordana Hrzica                            | *      |
| **ISL**                   | Conversations recorded for ASR testing in meetings.                                                  | Susie Burger                              | *      |
| **JOC**                   | Eight conversations from a special issue of the Journal of Communication.                            | Curtis LeBaron                            | *      |
| **Mambila**               | Conversations in Mambila.                                                                            | David Zeitlyn                             | **     |
| **Mesolex**               | Mesolex corpus.                                                                                      | Jonathan Amith                            | **     |
| **MICASE**                | Michigan Corpus of Academic Spoken English.                                                          | John Swales                               | ***    |
| **Mopan**                 | Mopan narratives.                                                                                    | Sotaro Kita                               | *      |
| **MOVIN**                 | Conversations in Danish, German, French, English, and Italian.                                       | Johannes Wagner                           | ***    |
| **Nahuatl**               | Nahuatl story of a shooting.                                                                         | Jane Hill                                 | ***    |
| **Sakura**                | Videotaped conversations of groups of 4 Japanese college students (not in CA format yet).            | Susanne Miyata                            | **     |
| **SBCSAE**                | The Santa Barbara Corpus of Spoken American English; various interactional types.                    | Jack DuBois                               | ****   |
| **SCoSE**                 | Saarbrücken Corpus of Spoken (American) English.                                                     | Dennis Norick                             | *      |
| **SPIRE**                 | HCI design discussions.                                                                              | Jakob Buur                                | *      |
| **Taiwan Hakka**          | Conversations and narratives in Taiwan Hakka.                                                        | Huei-ling Lai                             | ***    |
| **Taiwan Mandarin**       | Conversations in Taiwan Mandarin.                                                                    | Kawai Chui                                | ***    |
| **Yiddish**               | Hassidic Jews in New York speaking Yiddish.                                                          | Zelda Newman                              | **     |
| **Yucatec**               | Storytelling in Yucatec Mayan.                                                                       | John Haviland                             | **     |
| **Jefferson**             | *Group: Transcriptions by Gail Jefferson*                                                            |                                           |        |
| **Lingua Franca**         | Transcriptions by Gail Jefferson.                                                                    | Johannes Wagner                           | *****  |
| **Newport Beach**         | Transcriptions by Gail Jefferson.                                                                    | Johannes Wagner                           | *****  |
| **Poetics**               | Lecture in Boston in 1977 by Gail Jefferson.                                                         | Johannes Wagner                           | *****  |
| **Watergate**             | Phone call transcriptions from Watergate by Gail Jefferson.                                          | Johannes Wagner                           | *****  |
| **Aligned**               | A few NB and Watergate raw audio files processed through ASR.                                        | Brian MacWhinney                          | *      |
| **SCOTUS**                | *Group: US Supreme Court recordings*                                                                 |                                           |        |
| **SCOTUS-Blackmun**       | Interview with Justice Henry Blackmun.                                                               | Jerry Goldman                             | *      |
| **SCOTUS-Douglas**        | Interview with Justice William O. Douglas.                                                           | Jerry Goldman                             | *      |
| **SCOTUS_Oral_Arguments** | Oral arguments in the US Supreme Court (38 years, each in its own archive).                          | Jerry Goldman                             | *      |

