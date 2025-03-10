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

- [ASR](#asr)
- [Speaker Recognition](#speaker-recognition)
- [Emotion Recognition](#emotion-recognition)
- [Multilingual Speech Corpora](#multilingual-speech-corpora)
- [TTS](#tts)

---

### ASR

| Dataset                 | Download                                                        | Description                                                                                                                                                                                       |
|-------------------------|-----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| LibriSpeech             | [OpenSLR SLR12](https://www.openslr.org/12)                     | ~1000 hours of 16 kHz English read speech derived from LibriVox audiobooks. Includes “clean” and “other” subsets, widely used for training and benchmarking ASR models.                           |
| AISHELL-1 (Mandarin)    | [OpenSLR AISHELL-1](https://www.openslr.org/33/)                | An open-source Mandarin Chinese speech corpus with ~178 hours of speech from 400 native speakers, recorded at 16 kHz with high-quality manual transcriptions; a benchmark for Chinese ASR.        |
| TED-LIUM (Release 3)    | [OpenSLR TED-LIUM 3](https://www.openslr.org/51/)               | An English ASR dataset based on TED talks with 452 hours of audio from 2,351 talks, featuring diverse speakers and topics, ideal for lecture and presentation speech recognition.                 |
| CHiME Speech            | [CHiME Challenge Datasets](http://chimechallenge.org)           | A series of datasets focusing on speech in noisy environments (streets, cafés, homes). Includes CHiME-4 and CHiME-5/6, used for robust, far-field ASR research.                                   |
| GigaSpeech              | [OpenSLR SLR85 / GitHub GigaSpeech](https://www.openslr.org/85) | Extensive corpus with ~10,000 hours of transcribed speech and nearly 50,000 hours of audio from multiple sources, used for ASR training and evaluation.                                           |
| Spotify Podcast Dataset | [Podcast Dataset](https://podcastsdataset.github.io/)           | A dataset of over 100,000 podcast episodes with more than 100,000 hours of speech and extensive transcripts, used for various speech processing applications including ASR and language modeling. |

---

### Speaker Recognition

| Dataset   | Download                                                             | Description                                                                                                                                                                          |
|-----------|----------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| VoxCeleb1 | [VoxCeleb1](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)          | A speaker recognition dataset with 140k utterances from 1,251 speakers (≈352 hours) derived from celebrity interviews on YouTube.                                                    |
| VoxCeleb2 | [VoxCeleb2](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html) | An expanded speaker recognition dataset with over 1 million utterances from 6,112 speakers (~2,442 hours), used for state-of-the-art speaker recognition research.                   |
| CN-Celeb  | [CN-Celeb (OpenSLR SLR82)](https://openslr.org/82/)                  | A large-scale Chinese speaker recognition dataset with over 130,000 utterances from 1,000 speakers across 11 genres, providing challenging real-world conditions for identification. |

---

### Emotion Recognition

| Dataset | Download Link                                                       | Description                                                                                                                                                                                         |
|---------|---------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| IEMOCAP | [USC IEMOCAP](https://sail.usc.edu/iemocap)                         | A multimodal dataset with ~12 hours of acted dialogues from 10 trained actors in 5 dyadic sessions, annotated with 9 emotion categories; includes audio, video, and motion capture data.            |
| RAVDESS | [Zenodo RAVDESS](https://zenodo.org/record/1188976)                 | An emotional speech and song dataset recorded by 24 professional actors in North American English, comprising 7,356 clips covering 8 emotions and intensity levels.                                 |
| CREMA-D | [CREMA-D GitHub](https://github.com/CheyneyComputerScience/CREMA-D) | Contains 7,442 audio-visual clips from 91 actors performing 12 sentences in 6 emotions at varying intensities with crowd-sourced ratings; used for building multimodal emotion recognition systems. |

---

### Multilingual Speech Corpora

| Dataset                        | Download                                                                                 | Description                                                                                                                                                                                                                          |
|--------------------------------|------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Mozilla Common Voice           | [Common Voice Datasets](https://commonvoice.mozilla.org/en/datasets)                     | A massively multilingual, crowd-sourced speech corpus with over 20,408 hours of validated speech across 124 languages, featuring metadata such as age, sex, and accent; available under CC0 license for academic and commercial use. |
| Multilingual LibriSpeech (MLS) | [Facebook AI MLS](https://dl.fbaipublicfiles.com/mls/index.html)                         | Derived from LibriVox audiobooks, this corpus spans 8 languages with a total of ~50,000 hours of speech, providing standardized splits for training and evaluation, ideal for cross-lingual and multilingual ASR research.           |
| VoxPopuli                      | [VoxPopuli GitHub](https://github.com/facebookresearch/voxpopuli)                        | European Parliament recordings (2009–2020) in 23 languages, offering 400,000 hours of unlabeled speech and 1,800 hours of transcribed speech, used for self-supervised learning, multilingual ASR, and speech translation research.  |
| MLCommons People's Speech      | [Hugging Face People’s Speech](https://huggingface.co/datasets/MLCommons/peoples_speech) | Over 30,000 hours of transcribed English speech featuring various accents; used extensively for ASR training and evaluation.                                                                                                         |

---

### TTS

| Dataset                  | Download                                                    | Description                                                                                                                                                                                                                           |
|--------------------------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| LibriTTS                 | [OpenSLR SLR60](https://www.openslr.org/60/)                | A TTS dataset derived from LibriVox audiobooks, containing ~585 hours of speech from 2,456 speakers; provides high-quality segmented audio with aligned text for multi-speaker TTS models and voice cloning applications.             |
| LJSpeech-1.1             | [LJSpeech Dataset](https://keithito.com/LJ-Speech-Dataset/) | A single-speaker English TTS dataset with 13,100 short audio clips (~24 hours) from a female speaker reading public-domain texts; widely used to train neural TTS models such as Tacotron and WaveGlow.                               |
| VCTK (CSTR VCTK Corpus)  | [VCTK Corpus](https://datashare.ed.ac.uk/handle/10283/3443) | A multi-speaker English speech corpus with 109 speakers from the UK, each recording about 400 sentences (~44 hours); provided at 48 kHz and used for accent-robust TTS, voice conversion, and ASR research.                           |
| AISHELL-3 (Mandarin TTS) | [OpenSLR AISHELL-3](https://openslr.org/93/)                | A multi-speaker Mandarin Chinese TTS corpus with ~85 hours of high-quality, emotion-neutral recordings from 218 native speakers with manual transcripts; supports multi-speaker and expressive TTS as well as voice cloning research. |




