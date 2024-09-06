# Projeto-Final-Formacao-Cientista-de-Dados

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Projeto Final da Formação de Cientista de Dados

## Project Organization

```
├── LICENÇA <- Licença de código aberto, se uma for escolhida
├── Makefile <- Makefile com comandos de conveniência como `make data` ou `make train`
├── README.md <- O README de nível superior para desenvolvedores que usam este projeto.
├── dados
│   ├── externo <- Dados de fontes de terceiros.
│   ├── interino <- Dados intermediários que foram transformados.
│   ├── processados ​​<- Os conjuntos de dados canônicos finais para modelagem.
│   └── brutos <- O despejo de dados original e imutável.
│
├── docs <- Um projeto mkdocs padrão; consulte www.mkdocs.org para obter detalhes
│
├── modelos <- Modelos treinados e serializados, previsões de modelos ou resumos de modelos
│
├── cadernos <- Cadernos Jupyter. A convenção de nomenclatura é um número (para ordenação),
│ as iniciais do criador e uma breve descrição delimitada por `-`, por exemplo
│ `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml <- Arquivo de configuração do projeto com metadados do pacote para
│ projeto_final_formacao_cientista_de_dados e configuração para ferramentas como black
│
├── referências <- Dicionários de dados, manuais e todos os outros materiais explicativos.
│
├── reports <- Gera análises como HTML, PDF, LaTeX, etc.
│   └── figures <- Gera gráficos e figuras para serem usados ​​em relatórios
│
├── sql <- Gera análises como HTML, PDF, LaTeX, etc.
│
├── requirements.txt <- O arquivo de requisitos para reproduzir o ambiente de análise, por exemplo
│ gerado com `pip freeze > requirements.txt`
│
├── setup.cfg <- Arquivo de configuração para flake8
│
└── projeto_final_formacao_cientista_de_dados <- Código fonte para uso neste projeto.
    │
    ├── __init__.py <- Torna projeto_final_formacao_cientista_de_dados um módulo Python
    │
    ├── config.py <- Armazena variáveis ​​úteis e configuração
    │
    ├── dataset.py <- Scripts para baixar ou gerar dados
    │
    ├── features.py <- Código para criar recursos para modelagem
    │
    ├── modelagem
    │   ├── __init__.py
    │   ├── predict.py <- Código para executar inferência de modelo com modelos treinados
    │   └── train.py <- Código para treinar modelos
    │
    └── plots.py <- Código para criar visualizações
```
--------
