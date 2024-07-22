# Medical QA Instruction Sets
This is a Benchmark Medical Question Answer Dataset created with medical FAQ instruction set in format of questions and answers. The dataset contains 42 categories of common and critical diseases and their frequently asked questions. The dataset is created based on the source (https://www.medindia.net/patients/diseasefaq.asp) and this benchmark dataset is translated manually into Bengali. 

The dataset is stored here for future references in Large Language modeling tasks. The dataset is in json format, and it includes five columns: 
"Categories", "Instruction (Question)", "English_Instruction (Question)", "Output (Answer)", and "English_Output (Answer)". 

The dataset includes 300 rows of Medical Question-Answer data, both in Bengali and English. The statistics of the dataset are shown as follows:

| Column Name |           Contents        |
|-------------|----------------------------|
|Categories|42 Different Disease Names|
|Instruction (Question)|300 FAQs in Bengali|
|English_Instruction (Question)|300 FAQs in English|
|Output (Answer)|300 Answers in Bengali|
|English_Output (Answer)|300 Answers in English|

# Citation Information
If you find this benchmark dataset helpful, please consider giving a star and cite our paper from here: 

```
@article{sen2024healthcare,
  title={HEALTHCARE QUESTION ANSWERING SYSTEM IN BENGALI--A PROPOSED MODEL},
  author={SEN, ARGHYADEEP and DASH, DR SATYA RANJAN and PRADHAN, DR MANAS RANJAN and PARIDA, SHANTIPRIYA},
  journal={Journal of Theoretical and Applied Information Technology},
  volume={102},
  number={12},
  year={2024}
}
```
