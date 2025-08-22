📊 Dashboard de Salários na Área de Dados

Projeto desenvolvido durante a Imersão Dados com Python (Alura), com foco em análise, tratamento e visualização de dados e na construção de um dashboard interativo utilizando Streamlit.

🚀 Sobre o projeto

O dashboard permite explorar informações sobre salários da área de dados, aplicando filtros dinâmicos e analisando métricas principais (KPIs), gráficos interativos e tabelas detalhadas.

Além de rodar localmente, o projeto foi publicado na nuvem utilizando o Streamlit Cloud, permitindo acesso direto pelo navegador.

👉 Acesse aqui a versão online: https://imersao-dados-python-alura-2026.streamlit.app/

_____________________________________________________________________________________________________________________________________________________________________________

🛠️ Tecnologias utilizadas

Python → linguagem base do projeto

Pandas → manipulação e tratamento de dados

Matplotlib → utilizado no aprendizado inicial no Colab

Plotly Express → visualização interativa dos dados

Streamlit → criação da aplicação web interativa e deploy na nuvem
_____________________________________________________________________________________________________________________________________________________________________________

⚙️ Funcionalidades

✅ Filtros dinâmicos (Ano, Senioridade, Tipo de Contrato, Empresa)

✅ KPIs principais: salário médio, máximo, total de registros, cargo mais frequente

✅ Gráficos interativos:

Top 10 cargos por salário médio

Distribuição de salários anuais

Proporção de trabalho remoto/híbrido/presencial

Mapa coroplético de Cientistas de Dados por país

✅ Exibição de tabela detalhada com os dados filtrados

✅ Deploy online acessível pelo navegador
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
