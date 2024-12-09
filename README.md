# Assessing-Neurological-States-from-Physiological-Signals

### Introduction

Neurological health is a critical aspect of overall well-being, with conditions affecting the nervous system often having profound implications on quality of life. Traditionally, an EEG (electroencephalography) is used to measure the electrical activity in the brain, helping in diagnosing the brain condition [(Electroencephalogram), 2024)](https://www.mayoclinic.org/tests-procedures/eeg/about/pac-20393875). However, it’s resource intensive and requires specialized equipment. Thus, Non-EEG physiological signals examination has been introduced where it “evaluates brain and nervous system functioning” [(Cleveland Clinic Medical, 2022)](https://my.clevelandclinic.org/health/diagnostics/22664-neurological-exam). The exam is basically a physical examination to identify the signs of disorders affecting the brain [(Cleveland Clinic Medical, 2022)](https://my.clevelandclinic.org/health/diagnostics/22664-neurological-exam). This report is going to address the Non-EEG Dataset for the Assessment of Neurological Status, a database collected at the Quality of Life Laboratory at the University of Texas at Dallas, in various different ways with the potential to classify these collected physiological signals into  either one of the four neurological states:  physical stress, cognitive stress, emotional stress and relaxation. Thus, this is defined to be a classification problem with 4 classes.




### Dataset Description

Our dataset is retrieved from [Physionet](https://physionet.org/content/noneeg/1.0.0/#files-panel) and is collected at the Quality of Life Laboratory at University of Texas at Dallas.The data has been collected using non-invasive wrist worn biosensors, which measure 5 different attributes: electrodermal activity (EDA), temperature, acceleration, heart rate (HR), and arterial oxygen level (SpO2).  This was gathered for a total of 20 subjects, where each had to undergo a series of 7 stages of which include: 4 Relaxation periods spread in between all the states, physical stress, an emotional stress period, and a combination of a cognitive stress and a mini- emotional stress period. EDA, temperature, and acceleration were all recorded using 8 ticks per second- 4 for relaxation, 2 for emotional stress, 1 for physical stress and 1 for cognitive stress- over a 35 minute period. As for  HR, and SpO2 they were recorded using 1 tick per second over a 35 minute period as well. Thus, the data is compiled into 2 files for each of the subjects, 1 accounting for all three attributes EDA, temperature, and acceleration, and another for both HR, and SpO2. Finally, an excel file is collected containing info about each of its subjects with their age, height, weight, and gender. 
