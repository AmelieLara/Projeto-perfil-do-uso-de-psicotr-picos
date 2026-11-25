📊 Perfil de Uso de Medicamentos Psicotrópicos no SUS — Osório/RS
Análise exploratória, modelagem estatística/Machine Learning e dashboard interativo para monitoramento da dispensação de medicamentos psicotrópicos na Farmácia Municipal de Osório - RS.
________________________________________
🎯 Objetivo do Projeto
Investigar o padrão de consumo, o perfil sociodemográfico dos pacientes, a ocorrência de polimedicação e o impacto financeiro das dispensações de psicotrópicos na rede de Atenção Primária (Estratégias de Saúde da Família - ESF), fornecendo subsídios técnicos para a gestão da Assistência Farmacêutica e ações de farmacovigilância.
________________________________________
🔍 Principais Análises e Funcionalidades
1. Análise Exploratória & Farmacoepidemiologia (Jupyter Notebook)
•	Perfil Sociodemográfico e Territorial: Distribuição das dispensações por gênero, faixa etária e unidade de saúde (ESF).
•	Ranking de Consumo e Custo: Identificação dos medicamentos e classes terapêuticas mais dispensados (por volume de unidades e frequência de atendimento) e análise de impacto orçamentário (Val. Total. R$).
•	Indicadores de Polimedicação: Cálculo do percentual de pacientes em uso concomitante de múltiplos fármacos psicotrópicos e múltiplas classes terapêuticas.
•	Cruzamentos Clínicos: Relação entre faixa etária, gênero e classes terapêuticas prescritas (apoio à vigilância de medicamentos potencialmente inapropriados para idosos).
2. Modelagem Preditiva e Segmentação (Machine Learning)
•	Clusterização de Unidades de Saúde (K-Means): Segmentação das ESFs em perfis assistenciais distintos com base na idade média dos pacientes, volume de dispensações, custo total e custo médio por atendimento (com padronização StandardScaler).
3. Dashboard Interativo (app.py)
•	Desenvolvido em Python com Dash, Plotly e Dash Bootstrap Components.
•	Filtro Dinâmico por ESF: Permite isolar o perfil sociodemográfico e etário de cada unidade de saúde ou visualizar o consolidado municipal.
•	Panorama Geral: Painéis comparativos de medicamentos, classes terapêuticas, polimedicação e custos por gênero.
________________________________________
🛠️ Tecnologias Utilizadas
•	Linguagem: Python 3.x
•	Manipulação e Análise de Dados: pandas, numpy
•	Visualização e Dashboard: plotly, dash, dash-bootstrap-components, dash-bootstrap-templates, seaborn, matplotlib
•	Machine Learning: scikit-learn
________________________________________
📂 Estrutura do Repositório
├── analise_psicotropicos.ipynb   # Notebook com limpeza, EDA, estatísticas e K-Means
├── app.py                        # Código-fonte do dashboard interativo em Dash
├── requirements.txt              # Dependências do projeto
├── .gitignore                    # Arquivos ignorados (dados brutos protegidos)
└── README.md                     # Documentação do projeto

