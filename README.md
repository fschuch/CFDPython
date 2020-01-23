
# CFD Python

**CFD Python**, também conhecido como os **12 passos para Navier-Stokes**, é um módulo prático para o aprendizado dos fundamentos de Dinâmica dos Fluidos Computacional (CFD, do Inglês *Computational Fluid Dynamics*) por meio de códigos que resolvem as equações diferenciais parciais que descrevem a física dos escoamentos.
Esta é uma adaptação e tradução para português por [Felipe N. Schuch](https://fschuch.github.io/). Os textos e códigos originais foram parte do curso ministrado pela [Prof. Lorena Barba](http://lorenabarba.com) entre 2009 e 2013 no departamento de Engenharia Mecânica da Universidade de Boston (Prof. Barba então se mudou para Universidade George Washington), e estão publicado em:

> Barba, Lorena A., and Forsyth, Gilbert F. (2018). CFD Python: the 12 steps to Navier-Stokes equations. _Journal of Open Source Education_, **1**(9), 21, https://doi.org/10.21105/jose.00021

[![DOI](https://jose.theoj.org/papers/10.21105/jose.00021/status.svg)](https://doi.org/10.21105/jose.00021)

O módulo assume que o leitor tenha conhecimentos básicos sobre programação (qualquer linguagem) e alguma familiaridade com equações diferenciais e mecânica dos fluidos. Os "passos" foram inspirados pelas ideias do Dr. Rio Yokota, que era um pós-doc no laboratório da Prof. Barba até 2011, e as lições foram refinadas pela Prof. Barba e seus estudantes ao longo de vários semestres de ensino do curso de CFD.
O curso foi transcrito para o conjunto de Júpiter Notebooks em 2013 para ensinar em um curso intensivo de dois dias em Mendoza, Argentina.

Guiando estudantes através destes passos (sem falhar nenhum!), pode ensina-los lições valiosas. A constante evolução entre os exercícios proporciona um senso de recompensa ao final de cada atividade, e eles sentem que estão aprendendo com pouco esforço. Conforme avançam, eles naturalmente praticam como reutilizar trechos de código e progressivamente aprendem técnicas de programação e visualização. Enquanto eles analisam os resultados, aprendem sobre difusão, precisão e convergência.
Em cerca de quatro semanas em um curso de agenda regular, os alunos tornam-se programadores relativamente bem preparados e estão motivados para se engajar em questões de maior complexidade teórica.

## Como utilizar este módulo

Em uma disciplina universitária regular, os alunos podem completar as lições do **CFD com Python** em 4 a 5 semanas.
Como um curso intensivo, o módulo pode ser ministrado em 2 a 3 dias completos, à depender do conhecimento prévio da audiência.
As lições podem ser empregados por estudantes autodidatas.
Em todos os casos, o aluno é encorajado a seguir o trabalho de cada lição paralelamente ao reescrever em um Jupyter Notebook novo, mantendo anotações pessoais de seu progresso e de seus experimentos.

Lições
-------

> Execute uma seção interativa desta versão do CFD Python em seu navegador usando o serviço Binder:
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fschuch/CFDPython/master)

Passos 1 a 4 são em uma direção espacial. Passos 5 a 10 são em duas dimensões (2D). Passos 11 e 12 resolvem as equações da Navier-Stokes em 2D. Três Notebooks "bônus" cobrem a condição CFL de estabilidade, operações de arranjos multi-dimensionais com NumPy e definição de funções em Python.

* [Ligeira Introdução à Python](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/00_Ligeira_Intro_Python_.ipynb)
-- Para novatos em Python, essa lição introduz bibliotecas numéricas (NumPy e Matplotlib), variáveis em Python, endentação e manipulação de arranjos.
* [Passo 1](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/01_Passo_1.ipynb)
-- Convecção linear com avanço à partir da condição inicial (CI) e condições de contorno (CC) apropriadas.
* [Passo 2](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/02_Passo_2.ipynb)
-- Com as mesmas CI/BCs, convecção _não linear_.
* [Condição CFL](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/03_Condicao_CFL.ipynb)
-- Explorando a estabilidade numérica e a condição de Courant-Friedrichs-Lewy (CFL).
* [Passo 3](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/04_Passo_3.ipynb)
-- Com as mesmas CI/BCs, apenas _difusão_.
* [Passo 4](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/05_Passo_4.ipynb)
-- Equação de Burgers, com CI _dente de serra_ e CC periódica (e uma introdução ao SymPy).
* [Operações com arranjos em NumPy](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/06_Operacoes_de_arranjos_com_NumPy.ipynb)
* [Passo 5](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/07_Passo_5.ipynb)
-- Convecção linear 2D com CI função quadrada e CC apropriadas.
* [Passo 6](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/08_Passo_6.ipynb)
-- Com as mesmas CI/BCs, convecção _não linear_ 2D.
* [Passo 7](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/09_Passo_7.ipynb)
-- Com as mesmas CI/BCs, _difusão_ 2D.
* [Passo 8](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/10_Passo_8.ipynb)
-- Equação de Burgers 2D.
* [Definindo Funções em Python](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/11_Definindo_Funcoes_em_Python.ipynb)
* [Passo 9](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/12_Passo_9.ipynb)
-- Equação de Laplace 2D com CI zero e CC ambas Neumann e Dirichlet.
* [Passo 10](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/13_Passo_10.ipynb)
-- Equação de Poisson 2D.
* [Passo 11](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/14_Passo_11.ipynb)
-- Resolve o escoamento em Cavidade com Navier-Stokes 2D.
* [Passo 12](http://nbviewer.jupyter.org/github/fschuch/CFDPython-BR/blob/master/tarefas/15_Passo_12.ipynb)
-- Resolve o escoamento em Canal com Navier–Stokes 2D.

## Dependências

Para executar estas lições, você precisa de Python 3 e um conjunto das bibliotecas científicas padrões: NumPy, Matplotlib, SciPy e SymPy. E claro, você precisa de [Jupyter](http://jupyter.org), um ambiente multiplataforma e interativo, que roda no navegador web.

Este mini curso é construído em uma série de [Jupyter notebooks](https://jupyter-notebook.readthedocs.org/en/latest/notebook.html), que contem tanto o material descritivo quanto as soluções propostas programadas em Python. Para trabalhar com este material, recomenda-se que você comece cada lição com um novo notebook em branco e siga lado a lado, digitando cada linha de código (não copie e cole!), aproveite para explorar modificando parâmetros e vendo o que acontecerá.

#### Intalação via Anaconda

Nós recomendamos *fortemente* que você instale a [distribuição de Python Anaconda](http://docs.continuum.io/anaconda/install). Ela vai facilitar a sua vida. Você pode baixar e instalar em Windows, OSX e Linux.

Após a instalação, tenha certeza que todos os pacotes estão atualizados, execute os comandos a seguir em um terminal:

```Bash
conda update conda
conda update jupyter numpy sympy scipy matplotlib
```

Se você preferir Miniconda (uma versão reduzida de Anaconda que necessita menos espaço em disco), instale as bibliotecas necessárias para seguir o curso por meio dos seguintes comandos no terminal:

```Bash
conda update conda
conda install jupyter
conda install numpy scipy sympy matplotlib
```

#### Sem Anaconda

Se você já possui Python instalado na sua máquina, você pode instalar o Jupyter usando o pip:

```Bash
pip install jupyter
```

Tenha certeza que todas as bibliotecas necessárias estão instaladas por meio do comando:

```Bash
pip install numpy scipy sympy matplotlib
```

### Executando o servidor notebook

Uma vez que o Jupyter esteja instalado, abra um terminal e então execute:

```Bash
jupyter notebook
```

Isso vai iniciar uma seção Jupyter em seu navegador!

## Como contribuir com CFD com Python

Assim como sugerido na versão original, contribuições também serão bem-vindas na versão brasileira. Usuários são convidados a sugerir correções e pequenas melhorias via *pull request*. Você também pode abrir um *issue* se encontrar um bug ou tiver qualquer sugestão.

## Copyright and License

(c) Original por Lorena A. Barba, Gilbert F. Forsyth em 2017, traduzido por Felipe N. Schuch em 2020. All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE) (previously under MIT, and changed on March 8, 2018).

Ficamos felizes se você reutilizar o conteúdo de qualquer forma!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
