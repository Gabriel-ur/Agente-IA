# 🤖 Agente de IA — Organizador de Tarefas

**Agente de IA** é um projeto simples em Python que transforma listas de tarefas em um cronograma diário organizado e (opcionalmente) envia os eventos para o Google Calendar via **API**.
Apesar da integração com o Google Calendar, como o programa não é um serviço registrado e verificado pelo Google, apenas eu, o autor do projeto, posso conectar à minha conta do calendário.
O objetivo do projeto foi desenvolver competências práticas em integração de modelos generativos, engenharia de automação, APIs Google, e construção de um pequeno serviço web com Flask.

Link de deploy: https://agente-de-ia-6yr5.onrender.com/

# 🎯 Objetivo

Automatizar a transformação de uma lista de tarefas em um cronograma executável (CSV) aplicando regras de produtividade (timeboxing, sequência lógica), e permitir envio desses eventos para o Google Calendar via OAuth.

# 🧩 Funcionalidades

- Recebe entrada de tarefas (via endpoint HTTP ou linha de comando).
- API do Google Gemini analisa as tarefas informadas
- Gera cronograma em formato JSON
- Integração opcional com Google Calendar:
  - OAuth2 via google-auth-oauthlib.

# ⚙️ Tecnologias e Ferramentas

- Python 3.11
- Flask
- Pandas
- Crewai
- Google Generative AI
- Integração com Google Calendar (OAuth)

# 📌 Limitações

- Projeto orientado a backend / protótipo — sem frontend rico; interface web mínima via Flask.
- Conexão com Google Calendar viável apenas para a conta geradora da API
