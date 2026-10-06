# Análise de Cancelamento de Clientes

Projeto de análise de dados com Python para identificar padrões associados ao cancelamento de clientes.

## Tecnologias

- Python
- Pandas
- Plotly
- Jupyter Notebook

## Objetivo

Analisar uma base de clientes e identificar fatores relacionados ao cancelamento.

A taxa geral de cancelamento encontrada foi de aproximadamente **56,8%**.

## Principais resultados

Na base analisada:

- Clientes com contrato mensal: **100% de cancelamento**
- Clientes com mais de 4 ligações ao call center: **99% de cancelamento**
- Clientes com mais de 20 dias de atraso: **100% de cancelamento**

Esses resultados indicam uma forte associação entre esses fatores e o cancelamento.

## Etapas da análise

- Importação da base de dados
- Limpeza e tratamento dos dados
- Análise da taxa de cancelamento
- Criação de gráficos com Plotly
- Identificação dos principais padrões
- Análise dos grupos com maior taxa de cancelamento

## Como executar

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
```

Instale as dependências:

```bash
pip install pandas plotly ipykernel
```

Abra o arquivo:

```text
analise_cancelamento_clientes.ipynb
```

Selecione um Kernel Python no VS Code e execute as células de cima para baixo.

## Estrutura

```text
analise-cancelamento-clientes/
│
├── .gitignore
├── README.md
├── analise_cancelamento_clientes.ipynb
└── cancelamentos_sample.csv
```

## Autor

**Kennedy Martins**