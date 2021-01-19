# Sharvil_Portfolio
My portfolio for Machine Learning and Data Science.


# [Project 1: Fax Document Denoiser using Cycle GAN.](https://github.com/Sharvil97/Denoiser-AE)
* Modified CycleGANs to enchance the OCR on Electronic Health Records (EHRs).
* The data was utilized from [KEPRO](https://www.kepro.com/) where I was interning for the Summer of 2020, the data is not accessible for the general public due to HIPAA and other privacy protection laws for EHRs.
* The models where trained on Azure Machine Learning Services, the denoised documents were passed through [Tesseract](https://github.com/madmaze/pytesseract) which is an open sourced OCR software.
* The advantage of doing OCR on the EHRs is to create an unstructured dataset to do complicated NLP downstream tasks like such Summarization, NER and QnA using Bio Bert/ [Clinical Bert](https://github.com/EmilyAlsentzer/clinicalBERT).
