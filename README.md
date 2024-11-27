# Application of Generative Adversarial Network in Design and Art Generation

This project demonstrates the application of Generative Adversarial Networks (GANs) in creating synthetic art images, with a focus on portraits and handwriting. The project explores the capabilities of GANs in design and art generation by using multiple datasets, including the `MNIST` dataset, the `Art Portraits Image Dataset`, and a `Dog Images Dataset`.

---

## Table of Contents

- [Introduction](#introduction)
- [Datasets Used](#datasets-used)
- [Methodology](#methodology)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Results and Discussion](#results-and-discussion)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)

---

## Introduction

Generative Adversarial Networks (GANs) are powerful tools for generating realistic synthetic data. This project applies GANs to generate lifelike art images, focusing on portrait generation. By leveraging AI, this project showcases innovative possibilities for artistic expression and creative exploration.

---

## Datasets Used

1. **MNIST Dataset**:  
   A database of handwritten digits with 60,000 training images and 10,000 testing images.  
   Used for initial demonstration and GAN training.

2. **Art Portraits Image Dataset**:  
   A curated collection of diverse portrait images featuring various styles, subjects, and artistic interpretations.  
   Includes metadata such as:
   - `artist_name`
   - `year`
   - `genre`
   - `nationality`

3. **Dog Images Dataset**:  
   A dataset focusing on portraits of dogs, exploring GAN’s application in generating animal art.

---

## Methodology

The project follows these steps:

```plaintext
1. Data Collection:
   - Selection of datasets for training (`MNIST`, `Art Portraits Image Dataset`, `Dog Images Dataset`).

2. Setting up the Environment:
   - Install required libraries such as `TensorFlow`, `NumPy`, `Matplotlib`.

3. Building a Data Pipeline:
   - Preprocess data (resize, normalize, augment images).

4. Creating GAN Models:
   - `Generator`: Synthesizes new images.
   - `Discriminator`: Distinguishes real from synthetic images.

5. Training Loop:
   - Alternates training of the generator and discriminator using a custom training loop.

6. Image Generation:
   - Generates new synthetic images after training.

7. Performance Review:
   - Evaluate results qualitatively and quantitatively.
