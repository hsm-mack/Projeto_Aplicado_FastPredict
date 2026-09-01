# FastPredict — Projeto Aplicado II

## Visão geral
O **FastPredict** é um projeto acadêmico de Ciência de Dados voltado à **previsão de vendas futuras de itens de cardápio** em uma empresa fictícia do setor de fast-food, a **FastPredict Foods Ltda.**

A proposta é utilizar dados históricos de vendas, técnicas de análise estatística e modelos de aprendizado de máquina para produzir previsões que possam apoiar decisões de estoque, compras, produção e planejamento operacional.

## Problema de pesquisa
**Como utilizar dados históricos de vendas para prever a quantidade futura de cada item do cardápio comercializado pela FastPredict Foods Ltda.?**

## Objetivo geral
Desenvolver uma solução de Ciência de Dados capaz de prever as vendas futuras dos itens do cardápio da FastPredict Foods Ltda., utilizando dados históricos, análise estatística e algoritmos de aprendizado de máquina.

## Dados
A referência inicial de dados é a base pública **Fast-Food Restaurant Chain**, disponibilizada no Kaggle. A base definitiva deverá ser validada e documentada no decorrer do projeto.

Variável-alvo prevista:
- `quantity` — quantidade vendida/comprada do item.

Variáveis desejáveis, quando disponíveis ou tecnicamente deriváveis:
- data;
- produto;
- preço;
- receita;
- loja;
- dia da semana;
- mês;
- promoção;
- feriado;
- categoria do produto.

## Etapas do projeto
- **Etapa 1 — Kick-off:** definição da organização, área de atuação, dados, objetivos, metas e cronograma.
- **Etapa 2:** aquisição, preparação e exploração dos dados.
- **Etapa 3:** modelagem e avaliação dos modelos.
- **Etapa 4:** consolidação da solução, resultados e apresentação final.

## Estrutura do repositório
```text
Projeto_Aplicado_II_FastPredict/
├── README.md
├── .gitignore
├── requirements.txt
├── data/
│   ├── raw/
│   └── processed/
├── docs/
│   ├── etapa_1_kickoff/
│   ├── etapa_2/
│   ├── etapa_3/
│   └── etapa_4/
├── notebooks/
├── src/
├── reports/
│   └── figures/
└── references/
```

## Organização dos diretórios
- `data/raw/`: dados originais, sem alterações.
- `data/processed/`: dados após limpeza, transformação e preparação.
- `docs/`: documentação e entregáveis de cada etapa.
- `notebooks/`: análises exploratórias, testes e modelagem.
- `src/`: código reutilizável do projeto.
- `reports/figures/`: gráficos e figuras gerados.
- `references/`: materiais de apoio e referências não protegidas/restritas.

## Tecnologias previstas
Python, Pandas, NumPy, Matplotlib/Plotly, Scikit-learn, Jupyter Notebook/Google Colab, Git/GitHub.

## Métricas previstas
Para modelos de regressão, serão consideradas principalmente:
- MAE;
- RMSE;
- R².

## Observação sobre manipulação de texto
O componente curricular exige que o projeto contemple manipulação de **texto ou imagem**. No FastPredict, está prevista a incorporação de dados textuais relacionados aos produtos — por exemplo, avaliações ou comentários de clientes — quando uma fonte adequada for selecionada e documentada.

## Status
🟡 **Em desenvolvimento — Etapa 1 / Kick-off**

## Autoria
Projeto acadêmico desenvolvido para a disciplina **Projeto Aplicado II**.
