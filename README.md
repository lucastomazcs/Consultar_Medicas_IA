# 🩺 Sistema de Gestão de Consultas Médicas com IA

Este projeto é uma aplicação Full Stack para gerenciamento de consultas médicas, focada em clínicas e consultórios. Inclui funcionalidades administrativas, análise de dados e recursos de inteligência artificial para melhorar a gestão e prever faltas de pacientes.

---

## 📌 Funcionalidades

- Cadastro de pacientes, médicos e especialidades
- Agendamento de consultas com checagem de conflitos
- Histórico de atendimentos e diagnósticos
- Relatórios e dashboards (consultas por período, médicos mais ativos, taxa de faltas)
- Envio automático de lembretes por e-mail (integração com Celery)
- **[IA]** Predição de faltas de pacientes com base em histórico
- **[IA]** Chatbot médico para triagem inicial usando LLM

---

## ⚙️ Tecnologias Utilizadas

### 🖥️ Front-end
- React + TailwindCSS
- Axios para chamadas de API

### 🛠️ Back-end
- Python (FastAPI ou Django REST)
- PostgreSQL
- Redis + Celery para tarefas assíncronas
- JWT para autenticação

### 📊 Dados e IA
- Pandas e Scikit-learn para análise e modelo de predição
- Plotly/Dash ou Metabase para dashboards
- OpenAI API (ou similar) para chatbot de triagem

---

## 📁 Estrutura do Projeto (exemplo)
📦consultas-medicas
├── backend/
│ ├── app/
│ ├── models/
│ ├── routers/
│ └── main.py
├── frontend/
│ ├── src/
│ ├── components/
│ └── App.jsx
├── ai/
│ ├── predictor.py
│ └── chatbot.py
├── requirements.txt
└── README.md 


---

## ✅ Requisitos

### Ambiente

- Python 3.10+
- Node.js 18+
- PostgreSQL
- Redis (para Celery)

### Instalação Rápida

```bash
# Backend
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
cd frontend
npm install
npm run dev
📈 Melhorias Futuras
Sistema de pagamento e convênio

Notificações por WhatsApp

Exportação de relatórios em PDF

Painel médico com gráficos de desempenho

💡 Motivação
Esse projeto foi desenvolvido com o objetivo de unir habilidades de back-end, banco de dados e análise de dados com aplicação real. É ideal para clínicas que ainda usam sistemas manuais ou planilhas.

