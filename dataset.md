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
Autor_Editor     | Texto        | string   |      32       | Autor-editor da mensagem
Intencionalidade | Booleano     | booleano |      4        | Intencionalidade da mensagem
Autenticidade    | Booleano     | booleano |      4        | Autenticidade da mensagem
Facticidade      | Booleano     | booleano |      4        | Facticidade da mensagem
Conteúdo         | Texto        | string   |   variável    | Texto, imagem ou vídeo da mensagem
Contexto         | Texto        | string   |   variável    | Contexto da mensagem (geral, política, educação, economia, saúde etc.)
Data             | Date         | date     |    8          | Data de criação ou edição da mensagem
Midia_Digital    | misto        | string, mp4, imagem  |  variável | Mensagem em texto, imagem e vídeo ou mistura deles.
Meio_divulgacao  | Texto        | string | variável | Divulgação em redes sociais ou outros

> **Observações sobre o dicionário de dados**
>> **Tamanho (bytes)** = variável: Ainda em etapa de análise e deve mudar de tamanho depois de fazer pré-processamento e limpeza das informações desses campos. O dicionário também pode mudar ao adicionar ou reduzir variáveis segundo seja o resultado da análise.

---
> Informações sobre **[dataset](dataset.md)** do projeto

> Informações sobre o **[Plano de Gestão de dados](pgd.md)** do projeto.

---
## Citar como:

> Jorge Zavaleta. (2021, April 5). zavaleta/Machine-Learning-and-Fake-News: Repository of Machine Learning and Fake News (Version rfn_v1.0). Zenodo. http://doi.org/10.5281/zenodo.4663365

---
#### <center>Plano de Gestão de dados,  Copyright &copy;  Jorge Zavaleta, 2021</center>