# PhD Thesis: Variotional Autoencoder with Transfer Learning

This is the development code repo for the my doctoral thesis entitled:

## DEVELOPMENT OF DEEP TRANSFER LEARNING VIA ARTIFICIAL NEURAL NETWORKS IN MODELING THE INDEX OF SPEECH TRANSMISSION -

Thesis Proposal - Deep Convolutional Neural Network for Speech Transmission Index Prediction in Classroom Acoustics
This repository contains the code and resources for my thesis proposal on the topic of "Deep Convolutional Neural Network for Speech Transmission Index Prediction in Classroom Acoustics". The proposal is supervised by the following professors:

Prof. Dr.-Ing. Paulo Henrique Trombetta Zannin
Department of Mechanical Engineering, Federal University of Paraná (UFPR)

Prof. Dr. Nilson Barbieri
School of Engineering, Pontifical Catholic University of Paraná (PUCPR)

Prof. Ph.D. Arcanjo Lenzi
Department of Mechanical Engineering, Federal University of Santa Catarina (UFSC)

Prof. Ph.D. Eduardo Márcio de Oliveira Lopes
Department of Mechanical Engineering, Federal University of Paraná (UFPR)

## Abstract
The acoustic comfort in classrooms is a fundamental element that influences the teaching-learning dynamics. Therefore, classrooms with deficient acoustics can have socioeconomic implications for an entire society, as the pedagogical function loses its efficiency. The intelligibility of speech is typically measured using the Speech Transmission Index (STI), which quantifies the speech transmission quality. However, the measurement of STI is complex and requires expensive instrumentation.

Existing literature includes predictive models of STI that utilize the Reverberation Time (RT) as a regression variable. However, these models do not consider the spectral effects of the dual time-frequency localization of the room's impulse response signal, as well as the spectral content of background noise. Consequently, this research aims to model STI by applying a deep one-dimensional convolutional neural network.

The neural network model consists of two inputs: the simulated impulse response obtained through the Virtual Source Method with 10,000 samples, and the background noise with 564 samples. The training target is the predictive STI provided by the IEC 60268-16 standard. Due to the challenge of acquiring in-situ measurements, and to enhance the estimation robustness of the neural network, a novel method called Projective-Adaptive Variational Minimization Transfer Learning (MVPAnP) is proposed. MVPAnP optimizes the pretrained neural network models with simulated data and transfers the learned generalization to a dataset of in-situ measurements.

The model's validation was performed based on experimental acquisition of 60 classrooms with only RT measurements and 15 classrooms with both STI and RT measurements. The model's quality was evaluated using a calibration curve to experimentally validate its performance. The expected results include the development of a novel modeling approach for STI prediction compared to existing models, taking into account the cost and budgetary constraints associated with STI measurement instrumentation.

In conclusion, the proposed model can be used as a support tool for diagnostic evaluation of STI in classrooms, utilizing only the instrumentation typically employed for RT measurements.
