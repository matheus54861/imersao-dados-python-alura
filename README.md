📊 Dashboard de Salários na Área de Dados

📌 Sobre o projeto

Este projeto é um Dashboard Interativo desenvolvido em Python, utilizando Streamlit para a interface web.
O objetivo é analisar salários da área de dados ao longo dos anos, permitindo aplicar filtros dinâmicos e explorar informações sobre cargos, senioridade, tipos de contrato e localização geográfica.

Com ele, você pode visualizar métricas principais (KPIs), gráficos interativos e tabelas detalhadas, tudo em uma interface simples e intuitiva.

_____________________________________________________________________________________________________________________________________________________________________________

🛠️ Tecnologias utilizadas

Python
Streamlit → Criação da aplicação web interativa
Pandas → Manipulação e tratamento dos dados
Plotly Express → Visualização de dados com gráficos interativos
_____________________________________________________________________________________________________________________________________________________________________________

⚙️ Funcionalidades

✅ Filtros interativos por Ano, Senioridade, Tipo de Contrato e Tamanho da Empresa
✅ KPIs principais: salário médio, salário máximo, total de registros e cargo mais frequente
✅ Gráficos interativos:

📊 Top 10 cargos por salário médio

📉 Distribuição de salários anuais

🥧 Proporção dos tipos de trabalho (remoto, híbrido, presencial)

🌍 Mapa coroplético: salário médio de Cientistas de Dados por país

✅ Exibição de tabela detalhada com os dados filtrados
_____________________________________________________________________________________________________________________________________________________________________________

📂 Estrutura do projeto

📦 projeto-dashboard-salarios
 ┣ 📜 app.py               Código principal do dashboard
 ┣ 📜 requirements.txt     Dependências do projeto
 ┣ 📜 dados-imersao-final.csv  Base de dados (ou link no GitHub)
 ┗ 📜 README.md            Documentação do projeto

🚀 Como executar o projeto localmente

1️⃣ Clonar o repositório
git clone https://github.com/seu-usuario/projeto-dashboard-salarios.git
cd projeto-dashboard-salarios

2️⃣ Criar e ativar o ambiente virtual
python -m venv .venv
.\.venv\Scripts\activate   # Windows (PowerShell)
source .venv/bin/activate  # Linux/Mac

3️⃣ Instalar as dependências
pip install -r requirements.txt

4️⃣ Rodar o projeto
streamlit run app.py

👉 Acesse no navegador: http://localhost:8501
_____________________________________________________________________________________________________________________________________________________________________________

📊 Demonstração

🔹 Métricas principais (KPIs)

Salário médio
Salário máximo
Total de registros
Cargo mais frequente
_____________________________________________________________________________________________________________________________________________________________________________

🔹 Gráficos interativos

Top 10 cargos por salário médio
Distribuição de salários
Proporção do trabalho remoto
Mapa coroplético por país
_____________________________________________________________________________________________________________________________________________________________________________

🔹 Tabela detalhada com os dados filtrados
_____________________________________________________________________________________________________________________________________________________________________________

📌 Melhorias futuras

Adicionar filtros por país e moeda
Permitir exportar gráficos e tabelas em PDF/Excel
Deploy online (Streamlit Cloud / Render / Hugging Face Spaces)
_____________________________________________________________________________________________________________________________________________________________________________

👨‍💻 Autor

Projeto desenvolvido durante a Imersão Dados com Python (Alura).
