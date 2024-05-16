Machine Learning 2 project - Wang Li Ting

The whole project can also be found in this link:
https://drive.google.com/drive/folders/1ooM_lMIo-IVaeWKjY8cxC7-Cau1vSLuF?usp=drive_link

1. Project goal/Motivation
I want to develop a computer vision-based classifier to accurately distinguish between different breeds of dogs and cats to solve the problem of tedious manual classification and accuracy issues that animal shelters face.
  Detailed explanantion in the following document:
  'Part1 Motivation'
https://docs.google.com/document/d/13I7xUudS8lUbTSI3s2fb8-uLoxlV0g2K/edit?usp=sharing&ouid=101071604631371999895&rtpof=true&sd=true

3. Data Collection and Generation
Used Oxford Pets dataset
  Detailed explanantion in the following document:
  'Part2 Data Collection and Generation'
https://docs.google.com/document/d/1htNsQUbzZnmArdVtOMQIlckGfQhBei8AfFIE72yq6qY/edit?usp=sharing

5. Modeling: Training/fine-tuning models
Code for all models can be found in ipynb files labelled 1_ to 11_

6a. Interpretation 
Out of the 11 models tried, model 7 had the best performance with a accuracy of 99.56%.
  More details regarding hyperparameter finetuning, accuracies and
  interpretation of all the models in the following document:
  'Part4 Interpretation'
https://docs.google.com/spreadsheets/d/17N36XGVNr86PGZYGTEOcGaar95--R9Gv/edit?usp=sharing&ouid=101071604631371999895&rtpof=true&sd=true

6b. Validation
User validation by setting up frontend
(useed randomly chosen pictures of different breeds online)
https://huggingface.co/spaces/wangliting/oxfordpets

Validation by comparing with 2 benchmarks: 
- 'TWIST (ResNet-50)' 2021
- 'OmniVec' 2023
  More details in the following document:
  'Part4 Validation'
https://docs.google.com/spreadsheets/d/1LGF5SZBCoyIvSouzVogzNV2Ikm3ICBPy/edit?usp=sharing&ouid=101071604631371999895&rtpof=true&sd=true
