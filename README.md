
# Python Insights - Análise de Cancelamento de Clientes

Projeto de análise de dados desenvolvido em Python para identificar os principais fatores relacionados ao cancelamento de clientes (churn) e propor ações para reduzir essa taxa.

## Objetivo

Analisar uma base com mais de 800 mil clientes e identificar quais características estão mais associadas ao cancelamento do serviço utilizando Python, Pandas e Plotly.

## Tecnologias utilizadas

- Python
- Pandas
- Plotly
- Jupyter Notebook
- VS Code

## Estrutura do Projeto

```text
PythonInsights/
│
├── inicial.ipynb        # Notebook com toda a análise de dados
├── cancelamentos.csv    # Base de dados utilizada
└── README.md            # Documentação do projeto
```

## Como executar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/PythonInsights.git
```

2. Instale as dependências:

```bash
pip install pandas plotly jupyter
```

3. Abra o notebook:

```bash
jupyter notebook inicial.ipynb
```

4. Execute todas as células em ordem para reproduzir a análise.

## Etapas da análise

- Importação da base de dados.
- Remoção de colunas irrelevantes.
- Tratamento de valores ausentes.
- Análise da taxa de cancelamento.
- Criação de gráficos exploratórios.
- Identificação dos principais fatores de churn.
- Simulação de ações para redução de cancelamentos.

## Principais insights encontrados

- Clientes com contrato **Monthly** apresentam maior taxa de cancelamento.
- Mais de 4 ligações ao call center estão fortemente associadas ao churn.
- Atrasos superiores a 20 dias aumentam significativamente a chance de cancelamento.

## Resultado da simulação

Após filtrar clientes com contrato mensal, excesso de ligações ao call center e atraso elevado, a taxa de cancelamento caiu consideravelmente em relação ao cenário inicial.

## Aprendizados

- Limpeza e tratamento de dados.
- Análise exploratória com Pandas.
- Visualização de dados com Plotly.
- Transformação de dados em decisões de negócio.
