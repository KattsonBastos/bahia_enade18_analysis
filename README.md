# Brazilian's Exame Nacional de Desempenho dos Estudantes* (ENADE): an analysis of the state of Bahia in 2018
*National Examination of the Student's Performance

![](https://github.com/KattsonBastos/bahia_enade18_analysis/blob/main/img/banner.png)

_Please, if something goes wrong when trying to open the notebook in github, try this link_: https://nbviewer.jupyter.org/github/KattsonBastos/bahia_enade18_analysis/blob/main/notebooks/v01_enade18.ipynb

Status: ⚠️ in progress ⚠️

Next steps: <br>
- Coment some code chunks to better explain the code;
- Perform some more statistics test in EDA;
- Finish Conclusions

## 💻 About the Project

This repository contains an analysis of the ENADE to the State of Bahia, Brazil. It aims to get an inital understanding of the relation between the students scores and some other variables, like parents education level, family income, and scholarship.

The notebook contents:
- Imports
    - Importing Packages
    - Helper Functions
    - Data Loading
- Dataset Analysis
    - Data Dimensions, Types, NANs, and some basic initial descriptive statistics
- Changing Attribute's type
- Exploratory Data Analysis
    - Educational Institution's Analysis
    - Students Analysis
    - Hypothesis Creation and Validation
- Conclusions

Data source: <a href="https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enade">Inep - Microdados do Exame Nacional de Desempenho dos Estudantes</a>

## About the brazilian's ENADE

ENADE evaluates both the students performance from undergraduate courses in relation to the syllabus contents in the curricular guidelines, the development of important skills to deepen the general learning and professional training, and how much the students are updated in relation to the brazilian and the worldwide realities. <br>

Enrollment is mandatory for incoming students and qualified graduates of bachelor's and technology superior courses linked to the edition's evaluation areas.<br>

ENADE has a 3 years of evaluation cycle and each year different areas are evaluated. Here it was used the year of 2018 and it corresponds to the following areas:

- Bachelor courses in the Applied Social Sciences and related;
- Humanities courses and related;
- Higher Technology Courses in Management and Business, School Support, Hospitality and Leisure, Cultural Production, and Design.

### How it works

It's divided in two parts: 
- General Components (common to all participants): 2 discursive and 8 with multiple choices (a total of 10 questions);
- Specific Components (specific to each course): 3 discursive and 27 with multiple choices (a total of 30 questions);

## How to contribute

1. Fork the project.
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save your changes and create a commit message telling you what you did: `git commit -m" feature: My new feature "`
4. Submit your changes: `git push origin my-feature`
> If you have any questions check this [guide on how to contribute](./CONTRIBUTING.md)

---

## Notebook Author

<img style="border-radius: 50%;" src="https://avatars2.githubusercontent.com/u/58278775?s=400&u=d8844a4668b5e377aaf6d021001dd3bd7338c205&v=4" width="100px;" alt="Kattson Bastos"/>
<br>

<sub><b>Kattson Bastos</b></sub></a>

<br>

[![Linkedin Badge](https://img.shields.io/badge/-Kattson-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/kattson-bastos-07b07a194/)](https://www.linkedin.com/in/kattson-bastos-07b07a194/) 
[![Gmail Badge](https://img.shields.io/badge/-kattsonbastos@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:kattsonbastos@gmail.com)](mailto:kattsonbastos@gmail.com)

---


## 📝 License

This project is under the license [MIT](./LICENSE).

---

## Acknowledgment
- I fisrt saw this ENADE dataset in <a href="https://comunidadeestatistica.landen.co/">Comunidade de Estatística do Prof. Thiago Marques</a>. There, we did all the analysis in R. So, I decided to do it in Python.
- I'm also very grateful for being taking the course <a href="https://comunidadeestatistica.landen.co/">Data Science em Produção</a>. There, the Data Science project's workflow (and many other things we're learning) helped to build this notebook structure. So, this project is a mix of these two courses above.
- I thank <a href="https://github.com/daianeklein/imersao-dados-Alura/blob/main/Analise-Educacao.ipynb">Daiane Klein and her project</a></br> on Enem 2019 data that served me as inspiration and I could better structure and analyse this notebook.

## Readme
This Readme is based on this one: https://github.com/tgmarinho/README-ecoleta/blob/master/README-en.md
