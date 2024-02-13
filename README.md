Desafio Cientista de Dados - Indicium
==============================
<p align="center">
<img src="https://github.com/diovani-dupont/Desafio-Cientista-de-Dados-Indicium/assets/109030838/4249fab9-1e09-45c5-852e-bd0c457181f2" alt="indicium" width="900">
</p>

Este projeto foi desenvolvido como parte de um desafio técnico proposto pela Indicium, visando demonstrar habilidades em resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos no contexto do mercado de aluguéis temporários. Utilizando um conjunto de dados do maior concorrente no mercado de Nova York, o objetivo foi realizar uma análise exploratória de dados (EDA) abrangente, seguida pelo desenvolvimento e validação de um modelo preditivo para a precificação de imóveis listados na plataforma.


# Análise de Preços de Aluguéis Temporários em Nova York

## Objetivo do Projeto

Este projeto foi desenvolvido como parte de um desafio de Cientista de Dados proposto pela Indicium, com o intuito de avaliar habilidades em análise de dados, resolução de problemas de negócios e aplicação de modelos preditivos. O foco está em analisar dados de aluguéis temporários na cidade de Nova York, fornecendo insights sobre estratégias de precificação e desenvolvendo um modelo preditivo de preços para ajudar na tomada de decisões estratégicas de investimento em propriedades para aluguel na plataforma.

## Conteúdo do Notebook

O notebook aborda as seguintes etapas:

### 1. Análise Exploratória de Dados (EDA)
- Carregamento e análise inicial do dataset para entender a estrutura e as características dos dados.
- Geração de estatísticas descritivas, identificação de valores faltantes e análise de distribuições de variáveis chave como preço, número mínimo de noites, e disponibilidade ao longo do ano.

### 2. Análise para Investimento em Apartamento
- Avaliação do preço médio por bairro e análise de correlação entre variáveis para identificar potenciais áreas de investimento.
- Investigação sobre o impacto do número mínimo de noites e a disponibilidade ao longo do ano no preço dos aluguéis.

### 3. Previsão do Preço de Aluguel
- Preparação dos dados, incluindo tratamento de valores faltantes e codificação de variáveis categóricas.
- Desenvolvimento de um modelo de regressão usando o algoritmo Random Forest para prever os preços dos aluguéis.
- Avaliação do modelo através de métricas como RMSE (Root Mean Square Error) e R².

### 4. Salvamento do Modelo
- Exportação do modelo treinado no formato `.pkl` para utilização futura.

## Como Executar o Projeto

### Pré-requisitos
- Python 3
- Bibliotecas: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, joblib
- Jupyter Notebook ou ambiente compatível para executar um arquivo `.ipynb`

### Instalação
1. **Clone o repositório** ou baixe o arquivo do projeto.
2. **Instale as dependências** usando o arquivo `requirements.txt` incluído no projeto:

```bash
pip install -r requirements.txt


Organização do projeto
------------

    ├── LICENSE
    ├── Makefile           <- Makefile com comandos como `make data` ou `make train`
    ├── README.md          <- O README de nível superior para desenvolvedores que usam este projeto.
    ├── data
    │   ├── external       <- Dados de fontes de terceiros.
    │   ├── interim        <- Dados intermediários que foram transformados.
    │   ├── processed      <- Os conjuntos de dados canônicos finais para modelagem.
    │   └── raw            <- O despejo de dados original e imutável.
    │
    ├── docs               <- Um projeto Sphinx padrão; veja sphinx-doc.org para detalhes
    │
    ├── models             <- Modelos treinados e serializados, previsões de modelos ou resumos de modelos
    │
    ├── notebooks          <- Cadernos Jupyter. A convenção de nomenclatura é um número (para ordenação),
    │ as iniciais do criador e uma breve descrição delimitada por `-`, por ex. `1.0-jqp-exploração de dados iniciais`.
    │ 
    │
    ├── references         <- Dicionários de dados, manuais e todos os outros materiais explicativos.
    │
    ├── reports            <- Análise gerada como HTML, PDF, LaTeX, etc.
    │   └── figures        <- Gráficos e números gerados para serem usados em relatórios
    │
    ├── requirements.txt   <- O arquivo de requisitos para reproduzir o ambiente de análise, por exemplo.
    │                         gerado com `pip freeze> requisitos.txt`
    │
    ├── setup.py           <- torna o projeto pip instalável (pip install -e .) para que o src possa ser importado
    ├── src                <- Código fonte para uso neste projeto.
    │   ├── __init__.py    <- Torna src um módulo Python
    │   │
    │   ├── data           <- Scripts para baixar ou gerar dados
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts para transformar dados brutos em recursos para modelagem
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts para treinar modelos e depois usar modelos treinados para fazer previsões
    │   │   │                 
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts para criar visualizações exploratórias e orientadas a resultados
    │       └── visualize.py
    │
    └── tox.ini            <- arquivo tox com configurações para executar o tox; veja tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
