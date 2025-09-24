# 📘 Projeto de Aprendizado de Máquina aplicado às Notas Escolares

Este repositório contém o código e os bancos de dados utilizados em meu **Trabalho de Conclusão de Curso (TCC)**.  
O objetivo é aplicar técnicas de **Aprendizado de Máquina** para prever a nota final (**G3**) dos estudantes a partir de variáveis socioeconômicas e escolares, com foco nas disciplinas de **Português** e **Matemática**.

---

## 📂 Estrutura do Repositório

- `codigo_TCC.Rmd` → Script principal em RMarkdown contendo toda a análise.  
- `Portuguese.csv` → Base de dados com notas e informações dos alunos em Português.  
- `maths.csv` → Base de dados com notas e informações dos alunos em Matemática.  
- `README.md` → Documento explicativo (este arquivo).  

---

## ⚙️ Requisitos

Antes de rodar o código, instale os seguintes pacotes no R:

```r
install.packages(c("readr", "tidymodels", "tidyverse", "DescTools", 
                   "skimr", "DataExplorer", "visdat", "corrplot", 
                   "GGally", "inspectdf", "nnet", "xgboost", "ranger", "kernlab"))
