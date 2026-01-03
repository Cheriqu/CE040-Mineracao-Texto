# Mineração de Texto (Text Mining) - UFPR

Este repositório apresenta um projeto prático de Mineração de Texto desenvolvido durante a graduação em Estatística na UFPR. O objetivo é aplicar técnicas de Processamento de Linguagem Natural (NLP) para extrair padrões e insights de bases de dados não estruturadas (textos).

## 🛠️ Objetivos Técnicos

O projeto abrange as etapas fundamentais de um fluxo de mineração de texto:
1. **Limpeza de Dados (Pre-processing):** Remoção de *stopwords*, pontuação, números e conversão para minúsculas.
2. **Tokenização:** Decomposição do texto em unidades individuais (palavras ou n-grams).
3. **Análise de Frequência:** Identificação das palavras mais recorrentes no corpo do texto.
4. **Visualização de Dados:** Criação de nuvens de palavras (WordClouds) e gráficos de barras para representação de termos dominantes.

## 🚀 Tecnologias e Pacotes

* **Linguagem:** R
* **Pacotes Utilizados:**
  - `tm` ou `tidytext` (Processamento de texto)
  - `wordcloud` (Visualização)
  - `ggplot2` (Gráficos estatísticos)
  - `dplyr` (Manipulação de dados)

## 📈 Insights Demonstrados

* **Identificação de Temas Centrais:** Através da frequência de termos, foi possível mapear os tópicos mais relevantes da base de dados analisada.
* **Refino Estatístico:** Aplicação de filtros para garantir que termos comuns da língua (artigos, preposições) não enviesassem a análise de conteúdo.

## 📂 Estrutura de Arquivos

* [MineraçãoTexto01.Rmd](./MineraçãoTexto01.Rmd): Código-fonte documentado contendo todo o script de tratamento e análise.
* [MineraçãoTexto01.html](./MineraçãoTexto01.html): Relatório final renderizado com as visualizações e resultados.

---
**Autor:** Luiz Henrique Barretta Francisco  
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
