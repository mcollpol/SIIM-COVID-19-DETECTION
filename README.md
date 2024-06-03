# SIIM-COVID-19-DETECTION
Master thesis on covid-19 detection from x-ray images.

This thesis proposes a solution for the [SIIM-COVID19-DETECTION competition problem](https://www.kaggle.com/competitions/siim-covid19-detection/).


# Abstract

While the immediate urgency of the COVID-19 pandemic has evolved, the lessons we have learned during this period remain invaluable. We have seen that sometimes a timely and accurate diagnosis can be the difference between life and death.
Currently, there are two methods to diagnose COVID-19 with high fidelity, the first being the well-known PCR, which stands for polymerase chain reaction and requires a lab analysis, and the second is based on imaging techniques like chest X-rays or computed tomography
scans, that provide greater precision. However, PCR results can take several hours and, in some cases, more than a day, whereas radiographs can be obtained in a matter of minutes. For this reason, a tool that provides a visible bounding container around the area suspected
of being affected by COVID-19 could really help speed up an accurate diagnosis, especially for non-radiologist medical personnel.
This project, inspired by the Kaggle challenge ”SIIM-FISABIO-RSNA COVID-19 Detection”, focuses on the development of a machine learning model capable of identifying and localizing COVID-19 abnormalities in chest radiographs, more specifically, the model will categorize radiographs as negative for pneumonia or as having a typical, indeterminate or atypical appearance for pneumonia, the latter of which is associated with COVID-19, and provide a visual bounding box around the detected appearance. The main goal is to provide medical professionals with a quick and safe diagnostic tool, which could be expanded later to include the diagnosis of other lung conditions. In addition, doctors will be able to make better treatment decisions, as they will have a visual proof of the extent of the disease, which could prevent the worst possible outcomes.
