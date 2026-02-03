📊 Python – Dashboard de Salários na Área de Dados

Este repositório contém o desenvolvimento de um **dashboard interativo** criado com Python durante os estudos de **Análise de Dados**, utilizando Streamlit, Pandas e Plotly.

O projeto trabalha com uma base de dados real sobre **salários, cargos e características de profissionais da área de dados**, permitindo a exploração das informações por meio de filtros e visualizações gráficas.

---

🎯 Objetivo do Projeto

- Praticar análise exploratória de dados (EDA)
- Aplicar filtros dinâmicos em um conjunto de dados real
- Criar métricas e visualizações interativas
- Aprender a construir dashboards com Streamlit
- Consolidar conceitos fundamentais de Pandas e Plotly
- Desenvolver um projeto para portfólio em Análise de Dados

---

📂 Estrutura do Repositório

data-salaries-dashboard/
│
├── app.py # Aplicação principal do dashboard (Streamlit)
├── requirements.txt # Dependências do projeto
├── README.md # Documentação do projeto
└── .venv/ # Ambiente virtual (uso local, não versionado)

---

🧠 Conteúdo do Projeto

📌 Dashboard Interativo (app.py)

- Leitura da base de dados a partir de um repositório público
- Criação de filtros interativos por:
  - Ano
  - Senioridade
  - Tipo de contrato
  - Tamanho da empresa
- Cálculo de métricas principais:
  - Salário médio anual (USD)
  - Salário máximo anual (USD)
  - Total de registros
  - Cargo mais frequente
- Criação de visualizações:
  - Gráfico de barras (Top 10 cargos por salário médio)
  - Histograma da distribuição salarial
  - Gráfico de pizza dos tipos de trabalho
  - Mapa coroplético do salário médio de Cientistas de Dados por país
- Exibição de tabela com os dados filtrados

---

🛠 Tecnologias Utilizadas

- Python 3
- Streamlit
- Pandas
- Plotly Express
- VS Code
- Git & GitHub

---

▶️ Como Executar o Projeto

Clone o repositório:
```bash
git clone https://github.com/mig-reis/data-salaries-dashboard.git
Acesse a pasta do projeto:

cd data-salaries-dashboard
Crie e ative o ambiente virtual:

python -m venv .venv
Windows:

.venv\Scripts\activate
Linux / macOS:

source .venv/bin/activate
Instale as dependências:

pip install -r requirements.txt
Execute a aplicação:

streamlit run app.py
📊 Fonte dos Dados

Os dados utilizados neste projeto são públicos e foram obtidos a partir do repositório:

Imersão Dados – Salários na Área de Dados

https://github.com/vqrca/dashboard_salarios_dados

📈 Evoluções Implementadas

✔ Criação de dashboard interativo com Streamlit
✔ Aplicação de múltiplos filtros dinâmicos
✔ Cálculo de métricas agregadas
✔ Uso de visualizações interativas com Plotly
✔ Organização do código e boas práticas

👨‍💻 Autor

Projeto desenvolvido por Miguel Reis
Estudante e entusiasta de Análise de Dados e Programação.

📌 GitHub: https://github.com/mig-reis


---
