# CS598CourseProject

Step11 is the final notebook. Notebooks 1-8 are data processing and will take a long time. The data is too large to host and requires credentials to be able to download. Hosting that data without consent would vioilate the terms of physionet.

## Reproduced Paper

Tahmina Zebin and Thierry J. Chaussalet. 2019. De-
sign and implementation of a deep recurrent model
for prediction of readmission in urgent care using
electronic health records. In 2019 IEEE Conference
on Computational Intelligence in Bioinformatics and
Computational Biology (CIBCB), pages 1–5.

[Paper Link](https://ieeexplore.ieee.org/document/8791466)

## Dependencies

Please install the python requirements from the `requirements.txt` file.

```python
python -m pip install -r requirements.txt
```

## Data Download Instructions

This one is a bit tricky if you do not have access to the MIMIC-III database. While this is publicy available, you need to have athorization. Please follow the instructions from the [mimic.mit.edu](https://mimic.mit.edu/docs/gettingstarted/) website or the [physionet](https://physionet.org/content/mimic3-carevue/1.4/) website to get started.

## Preprocessing

In order to proprocess the data, you will need to run through the notebooks labeled Step1 - Step8. THIS WILL TAKE A LONG TIME. Preprocessing the data was the most difficult part of this project. 

## Training and Running

Place the decompressed MIMIC-III csv files in a folder in the main repository called `mimic-iii`.
