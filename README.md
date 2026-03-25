# steelproof-steel-refinement-project
Projeto final de análise e solução de dados para otimização do processo de refinamento do aço na Steelproof, estruturado em planejamento, desenvolvimento da solução e relatório final.

## Visão Geral

Este projeto foi desenvolvido para a empresa fictícia **Steelproof** com o objetivo de apoiar a otimização do processo de refinamento do aço por meio da análise de dados. A proposta foi organizada em três etapas complementares: planejamento do projeto, desenvolvimento técnico da solução e elaboração do relatório final com os principais resultados e recomendações.

O trabalho combina entendimento do problema de negócio, exploração e preparação dos dados, modelagem analítica e comunicação final dos achados de forma estruturada e orientada à tomada de decisão.

## Problema de Negócio

A Steelproof busca melhorar a eficiência e a qualidade de seu processo de refinamento do aço com apoio de dados históricos do processo produtivo. O desafio consiste em desenvolver uma solução capaz de identificar padrões relevantes, modelar o comportamento da variável de interesse e apoiar decisões mais precisas no contexto operacional.

## Estrutura do Projeto

O projeto está dividido em três notebooks principais:

- `01_steelproof_project_planning.ipynb`  
  Contém o planejamento inicial do projeto, incluindo definição do problema, objetivos, proposta de abordagem e estrutura da solução.

- `02_steelproof_solution_development.ipynb`  
  Contém o desenvolvimento técnico da solução, incluindo carregamento dos dados, preparação, análise, modelagem e avaliação dos resultados.

- `03_steelproof_final_report.ipynb`  
  Contém o relatório final com a consolidação dos principais achados, conclusões e recomendações de negócio.

## Conjunto de Dados

Os arquivos utilizados no projeto estão organizados na pasta `CSV Archives/`:

- `data_arc_en.csv`
- `data_bulk_en.csv`
- `data_bulk_time_en.csv`
- `data_gas_en.csv`
- `data_temp_en.csv`
- `data_wire_en.csv`
- `data_wire_time_en.csv`

Esses arquivos representam diferentes aspectos do processo industrial e são combinados ao longo do desenvolvimento da solução para compor a base analítica do projeto.

## Objetivos do Projeto

Desenvolver uma solução analítica para apoiar a otimização do processo de refinamento do aço na Steelproof, estruturando o trabalho em três etapas: planejamento, desenvolvimento técnico da solução e relatório final.

Este projeto busca:

- compreender o problema de negócio da Steelproof
- estruturar uma abordagem analítica adequada
- preparar e integrar os dados do processo industrial
- desenvolver uma solução baseada em modelagem preditiva
- avaliar os resultados obtidos
- comunicar conclusões e recomendações de forma clara e executiva

## Etapas do Projeto

O fluxo geral do trabalho foi organizado em três fases:

1. planejamento do problema e da abordagem analítica
2. desenvolvimento técnico da solução e avaliação dos resultados
3. relatório final com consolidação dos achados e recomendações

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Estrutura do Repositório

```text
steelproof-steel-refinement-project/
├── .gitignore
├── README.md
├── requirements.txt
├── 01_steelproof_project_planning.ipynb
├── 02_steelproof_solution_development.ipynb
├── 03_steelproof_final_report.ipynb
└── CSV Archives/
    ├── data_arc_en.csv
    ├── data_bulk_en.csv
    ├── data_bulk_time_en.csv
    ├── data_gas_en.csv
    ├── data_temp_en.csv
    ├── data_wire_en.csv
    └── data_wire_time_en.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/steelproof-steel-refinement-project.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd steelproof-steel-refinement-project
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra os notebooks em ordem:

   * `01_steelproof_project_planning.ipynb`
   * `02_steelproof_solution_development.ipynb`
   * `03_steelproof_final_report.ipynb`

## Principais Entregáveis

O repositório reúne:

* planejamento estruturado do projeto
* preparação e integração de múltiplas fontes de dados do processo
* desenvolvimento técnico da solução analítica
* avaliação de desempenho da abordagem proposta
* relatório final com conclusões e recomendações para o negócio

## Resultados

Organização de um fluxo completo de solução de dados, desde a definição do problema até a entrega final orientada ao negócio. Integração de múltiplas bases do processo industrial e construção de uma solução técnica capaz de gerar análise útil para apoio a decisões operacionais e ampliação do entendimento do processo de refinamento do aço.

O projeto inclui:

* definição estruturada do problema
* exploração e preparação dos dados industriais
* construção da solução técnica
* avaliação dos resultados obtidos
* consolidação dos principais insights
* relatório final orientado à tomada de decisão

## Conclusão

Este projeto demonstra um fluxo completo de solução analítica aplicada a um problema industrial, cobrindo desde a definição estratégica do problema até a entrega final orientada a negócio. A estrutura em três etapas permite visualizar com clareza o raciocínio do projeto, o desenvolvimento da solução e a consolidação dos resultados para apoio à tomada de decisão na Steelproof.

## O que foi aprendido

Desenvolvimento e consolidação de habilidades em:
- estruturação de projetos analíticos em múltiplas etapas
- integração de diferentes fontes de dados industriais
- desenvolvimento e avaliação de modelos preditivos
- comunicação técnica e executiva de resultados
- conexão entre modelagem e aplicação em contexto industrial

## Melhorias Futuras

Possibilidades de evolução do projeto:
- ampliar o conjunto de atributos derivados do processo
- testar modelos adicionais e estratégias mais robustas de validação
- aprofundar a análise de interpretabilidade
- transformar a solução em pipeline mais automatizado para uso contínuo

## Autor

**Iago Zanquetta**
