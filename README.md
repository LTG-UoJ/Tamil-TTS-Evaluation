# CMOS and WER Evaluation Dataset Repository

Welcome to the repository for CMOS and WER evaluation datasets and related files. This repository contains the necessary resources for evaluating audio datasets, including CMOS evaluation data, WER datasets, and transcriptions.

## Contents

1. **CMOS Evaluation Audio Dataset**
    - This dataset contains audio files used for CMOS (Comparative Mean Opinion Score) evaluation, which is commonly used to assess the quality of text-to-speech (TTS) systems.

2. **WER Evaluation Audio Dataset**
    - This dataset includes audio files intended for evaluating Word Error Rate (WER), an objective metric in speech recognition systems.

3. **WER Transcriptions for TTS**
    - Contains transcriptions of audio data used in WER evaluations, specifically for text-to-speech systems and ground truth for transcriptions. These transcriptions are important for aligning and calculating WER accurately.



## Usage

### CMOS Evaluation
1. Access the CMOS evaluation audio dataset from the `cmos_evaluation` folder.
2. Follow the standard CMOS scoring methodology to evaluate the TTS quality using this dataset.

### WER Evaluation
1. Locate the WER evaluation audio dataset in the `wer_evaluation` folder.
2. Use the  transcriptions provided in same folder.
3. Follow the standard WER calculation to evaluate the TTS using this dataset

## Repository Structure
```
├── cmos_evaluation
│   └── [Audio files for CMOS evaluation]
├── wer_evaluation
│   └── [Audio files for WER evaluation]
│   └── [Transcriptions for WER audio files]
├── README.md
```


## The evaluation using dataset and the collection of dataset is published in
@article{MAHAGANAPATHY2025100171,
title = {A survey and evaluation of text-to-speech systems for the Tamil language},
journal = {Natural Language Processing Journal},
volume = {12},
pages = {100171},
year = {2025},
issn = {2949-7191},
doi = {https://doi.org/10.1016/j.nlp.2025.100171},
url = {https://www.sciencedirect.com/science/article/pii/S2949719125000470},
author = {Ahrane Mahaganapathy and Kengatharaiyer Sarveswaran},
keywords = {TTS, Speech synthesis, Tamil, Benchmark, TTS evaluation},
abstract = {This survey provides a comprehensive review of existing Tamil Text-to-Speech (TTS) synthesis systems, synthesis approaches, evaluation approaches, and highlights state-of-the-art approaches and challenges in handling linguistic nuances. Voice-based interfaces are becoming part of life. Therefore, it is import to have an expensive TTS system which can make human experience better. Tamil, with its rich linguistic features and diagnostic nature, presents significant challenges to speech synthesis. In addition to the survey, importantly this work proposes a perceptual evaluation framework which consists of expressiveness, low listening fatigue, and overall quality, in addition to traditional intelligibility and naturalness, dimensions to evaluate better human experience. This study also uses the Comparative Mean Opinion Score (CMOS) for the subjective evaluation instead of the Mean Opinion Score. A dataset for the evaluation was also carefully prepared and six widely used Tamil TTS systems were evaluated using Word Error Rate and the subjective evaluation was done using the proposed evaluation framework with the support of 30 evaluators. The reliability of the subjective evaluation is also assessed using Krippendorff’s Alpha. The results indicate the existing systems have significant room for improvement in all perceptual dimensions. The study underscores the need for evaluation datasets and evaluation approaches that cater to subjective perceptual dimensions of speech synthesis for better human experience and lays a foundation for future research and development in Tamil and similar TTS systems.}
}

