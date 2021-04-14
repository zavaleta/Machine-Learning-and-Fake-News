[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zavaleta/Machine-Learning-and-Fake-News/main)
---
# Projeto de Pesquisa

---
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4663365.svg)](https://doi.org/10.5281/zenodo.4663365)

---
> ## Métodos de Machine Learning para Determinar Fake News em Saúde nas Mídias Sociais
> ### Autor: Jorge Juan Zavaleta Gavidia
> ### ORCID: 0000-0002-4747-8613
> ### Instituição: Programa de Pós-graduação em Informática - Universidade Federal do Rio de Janeiro (Brasil)
> ### Fonte de Financiamiento: CAPES Tecnodigital

---
## Experimentação de Planos de Gestão de Dados (PGD)

---
> - [DS-Wizard](dswizard.md)
> - [DMPOnline](dmponline.md)
> - [DMPTool](dmptool.md)
> - [Argos](argos.md)
> - [Fiocruz](fiocruz.md)

---
## Comparação dos templates

> **Critérios**:
> - Menu (visual): **B** - Bom; **R** - Regular; **F** - Fraco
> - Ajuda ao usuário: **B** - Bom; **R** - Regular; **F** - Fraco
> - Simplicidade para preencher: **B** - Bom; **R** - Regular; **F** - Fraco
> - Criação de Modelos: **SC** - Sem Configurar; **PC** - Precisa configurar
> - Compartilhamento: **S** - sim; **N** - Não
> - Acionável por máquina: **S** - sim; **N** - Não
> - Princípios FAIR: **S** - Sim; **N** - Não

Variável              | DS-Wizard  | DMPOnline  | DMPTool   | Argos   | Fiocruz |
----------------------|:----------:|:----------:|:---------:|:-------:|:-----:|
Menu                  |    B       |     B      |    R      |   F     |   R
Ajuda                 |    B       |     B      |    R      |   F     |   B
Simplicidade          |    B       |     B      |    R      |   F     |   R
Criação de Modelos    |   SC       |    PC      |    SC     |  SC     |   SC
Compartilhamento      |    S       |    S       |    S      |   S     |   S
Acionável por máquina |   S        |    N       |    N      |   N     |   N
Princípios FAIR       |   S        |    S       |    S      |   S     |   S

---
### Formatos de compartilhamento de dados

Formatos        | DS-Wizard  | DMPOnline  | DMPTool   | Argos   | Fiocruz |
----------------|:----------:|:----------:|:---------:|:-------:|:-----:|
HTML            |    x       |     x      |    x      |   -     |   -
TEXT            |    x       |     x      |    x      |   -     |   -
DOCX            |    x       |     x      |    x      |   x     |   -
PDF             |    x       |     x      |    x      |   x     |   x
MARKDOWN (MD)   |    x       |     x      |           |   -     |   -
LATEX           |    x       |     -      |    -      |   -     |   -
RDF             |    x       |     -      |    -      |   -     |   -
CSV             |    x       |     -      |    x      |   -     |   -
JSON            |    -       |     x      |    x      |   -     |   -
XML             |    -       |     -      |    -      |   x     |   -
RDA JSON        |    -       |     -      |    -      |   x     |   -

---

> Foi escolhido o **[DS-Wizard](dswizard.md)** pois está alinhado com as tendências atuais e emergentes em relação aos Princípios FAIR. Além de ser uma ferramenta abrangente, ela conecta-se com recursos externos (por exemplo, FAIRSharing, FAISsFAIR), avalia as respostas dos questionários em termos de métricas preditivas automatizadas para a prática FAIR e Open Science de forma gráfica, produzindo PGDs em diversos formatos como pode ser conferido na tabela acima.

> DS-Wizard também se diferencia das demais ferramentas pois é escalável e permite que os modelos de conhecimento (formulários) evoluam no tempo.

---
> **[Jupyter Notebook](Gera_dados.ipynb)** da geração dos dados do dataset do projeto.


---
> Informações sobre o **[dataset](dataset.md)** usado no projeto

---
## Citar como:

> Jorge Zavaleta. (2021, April 5). zavaleta/Machine-Learning-and-Fake-News: Repository of Machine Learning and Fake News (Version rfn_v1.0). Zenodo. http://doi.org/10.5281/zenodo.4663365

---
#### <center>Plano de Gestão de dados,  Copyright &copy;  Jorge Zavaleta, 2021</center>