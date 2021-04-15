[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zavaleta/Machine-Learning-and-Fake-News/main)
---
# Projeto de Pesquisa

---
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4663365.svg)](https://doi.org/10.5281/zenodo.4663365)

---
## Métodos de Machine Learning para Determinar Fake News em Saúde nas Mídias Sociais
> ### Autor: Jorge Zavaleta
> ### ORCID: 0000-0002-4747-8613
> ### Instituição: Programa de Pós-graduação em Informática - Universidade Federal do Rio de Janeiro (Brasil)
> ### Fonte de Financiamiento: CAPES Tecnodigital

---
## Dicionário de dados do Dataset
---

 Nome do campo   | Tipo de dado | Formato  |Tamanho (bytes)| Descrição                 |
:----------------|:------------:|:--------:|:-------------:|:--------------------------|
fonte            | Texto        | string   |      20       | Origem da mensagem
autor_Editor     | Texto        | string   |      32       | Autor-editor da mensagem
titulo_mensagem  | Texto        | string   |      32       | Título da mensagem
intencionalidade | Booleano     | booleano |      4        | Intencionalidade da mensagem
autenticidade    | Booleano     | booleano |      4        | Autenticidade da mensagem
facticidade      | Booleano     | booleano |      4        | Facticidade da mensagem
conteúdo         | Texto        | string   |   variável    | Texto, imagem ou vídeo da mensagem
contexto         | Texto        | string   |   variável    | Contexto da mensagem (geral, política, educação, economia, saúde etc.)
data             | Date         | date     |    8          | Data de criação ou edição da mensagem
tipo_fake        | Texto        | string   | 20       | Tipo de fake-news (sátira, parodia etc.) em alguns casos este campo pode aparecer como **categoria**
link             | texto        | string   | variável | url da mensagem
imagem           | imagem       | png, jpg | variável | imagem que acompanha a mensagem
video            | video        | mp4, mov | variável | mensagem em vídeo
meio_divulgacao  | Texto        | string   | variável | Divulgação em redes sociais ou outros


> **Observações sobre o dicionário de dados**
>> **Tamanho (bytes)** = variável: Ainda em etapa de análise e deve mudar de tamanho depois de fazer pré-processamento e limpeza das informações desses campos. O dicionário também pode mudar ao adicionar ou reduzir variáveis segundo seja o resultado da análise ou as necessidades no decorrer da pesquisa.

---
> Informações sobre **[Jupyter Notebook](Gera_dados.ipynb)** do dataset do projeto

> Informações sobre o **[Plano de Gestão de dados](pgd.md)** do projeto.

---
## Citar como:

> Jorge Zavaleta. (2021, April 5). zavaleta/Machine-Learning-and-Fake-News: Repository of Machine Learning and Fake News (Version rfn_v1.0). Zenodo. http://doi.org/10.5281/zenodo.4663365

---
#### <center>Plano de Gestão de dados,  Copyright &copy;  Jorge Zavaleta, 2021</center>