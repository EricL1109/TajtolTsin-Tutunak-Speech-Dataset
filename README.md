# Tutunakú-Speech-Dataset

This repository presents a speech database and digital lexical resource for the Tutunakú language developed for research in Automatic Speech Recognition (ASR), Natural Language Processing (NLP), phonetic analysis, and low-resource indigenous language technologies.

## Tutunakú Speech Database Generation

The Tutunakú speech database was specifically developed for speech processing, computational analysis, and linguistic preservation of a low-resource indigenous language spoken in Tlayehualancingo, Puebla, Mexico. Due to the limited availability of structured digital resources for this linguistic variant, a complete methodology for lexical collection, controlled audio recording, preprocessing, phonetic annotation, and corpus organization was designed.

The construction of the corpus involved collaboration with native speakers, teachers, and students from the local community to ensure phonetic diversity and linguistic representativeness. As part of the initial phase of the project, a lexical thesaurus composed of 127 representative Tutunakú words was generated, covering semantic categories related to animals, food, colors, greetings, objects, and body parts.

Audio recordings were performed using professional DJI Mic 2 wireless microphones in controlled acoustic environments to improve speech quality and reduce environmental noise. Multiple repetitions per speaker were collected to capture pronunciation variability and strengthen the acoustic representation within the dataset.

Subsequently, the audio files underwent preprocessing stages including manual segmentation, acoustic cleaning, noise reduction, normalization, and phonetic labeling using tools such as Audacity. The orthographic transcription process was carried out with the support of bilingual native speakers following standardized Tutunakú writing conventions proposed by the Instituto Nacional de Lenguas Indígenas (INALI).

The final structure of the dataset integrates segmented audio recordings, orthographic transcriptions, simplified phonetic representations, Spanish translations, and metadata associated with each audio instance. The corpus was hierarchically organized by participant, school grade, and recording session, facilitating reproducibility and future computational experimentation.

The complete database contains more than 20,000 segmented audio fragments generated from recordings of 54 native Tutunakú-speaking children. This resource provides a representative speech corpus suitable for Automatic Speech Recognition (ASR), phonetic analysis, grapheme-to-phoneme modeling, and digital preservation of low-resource indigenous languages.

---

## Authors

- Johanna Keira Badillo-Zavala (UPIIT--IPN) 
- Anahi Sánchez-Flores (UPIIT--IPN) 
- Eric Ramos-Aguilar (UPIIT--IPN)   
- J. Arturo Olvera-López (BUAP)
- Ricardo Ramos-Aguilar (UPIIT--IPN) 

---

## Dataset Contents

- Segmented Tutunakú speech audio corpus: **20,574 instances**
- Public audio sample available in this repository: **1,890 audio files**
- Acoustic embeddings generated from the complete corpus
- Orthographic writing in Tutunakú
- Tutunakú–Spanish translations
- Simplified phonetic representations
- Grapheme-to-phoneme correspondence
- Metadata associated with each audio instance

These resources enable acoustic and phonetic analysis, as well as experimentation in speech recognition, phonetic classification, grapheme-to-phoneme modeling, and low-resource indigenous language preservation tasks.

---

## Dataset Structure

The dataset is organized using a hierarchical folder structure:

```text
Dataset/
│
├── Audios/
│   ├── child_1/
│   ├── child_2/
│   └── ...
│
├── Embeddings/
│
├── Metadata/
│
├── Transcriptions/
│
└── Phonemes/
```

Each instance contains:

- Segmented audio in `.mp3` format
- Tutunakú orthographic transcription
- Spanish translation
- Simplified phonetic representation
- Speaker identifier
- Associated metadata

---

## Applications

This resource can be used for:

- Automatic Speech Recognition (ASR)
- Grapheme-to-phoneme modeling
- Phonetic classification
- Acoustic analysis
- Natural Language Processing (NLP)
- Linguistic documentation
- Digital preservation of indigenous languages
- Research on low-resource languages

---

## Citation

If you use this dataset in academic research, please cite:

```bibtex
@article{badillo2025tutunaku,
  title={Desarrollo de Base de Datos para el Procesamiento Automático del Tutunakú: una Aproximación desde Lenguas de Bajos Recursos},
  author={Badillo Zavala, Johanna Keira and Sánchez Flores, Anahi and Ramos-Aguilar, Eric and Olvera-López, J Arturo},
  journal={Computación y Sistemas},
  year={2025}
}
```

---
## License

© 2025 Johanna Keira Badillo Zavala et al.

This dataset is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** License.

You are free to:
- Share — copy and redistribute the material  
- Adapt — remix, transform, and build upon the material  

Under the following terms:
- Attribution — You must give appropriate credit to the original authors  
- NonCommercial — You may not use the material for commercial purposes  

This dataset is intended for research and educational use, particularly in the study of low-resource languages.

For more details: https://creativecommons.org/licenses/by-nc/4.0/

For commercial use or special permissions, please contact the authors:  

Johanna Keira Badillo Zavala ([jbadillozz2100@alumno.ipn.mx](mailto:jbadillozz2100@alumno.ipn.mx))  
Anahi Sánchez Flores ([asanchezf2101@alumno.ipn.mx](mailto:asanchezf2101@alumno.ipn.mx))  
Eric Ramos Aguilar ([eramosa@ipn.mx](mailto:eramosa@ipn.mx))


This dataset is intended for research and educational purposes, particularly for the study of low-resource indigenous languages.

For more details:  
https://creativecommons.org/licenses/by-nc/4.0/
