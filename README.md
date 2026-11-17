# Olá, eu sou o Lucas Paiva 👋

Desenvolvedor Full Stack com foco em backend e IA aplicada. Trabalho com Laravel e
PostgreSQL em produção, construo serviços em Go e aplicações com LLMs em Python:
RAG, extração estruturada, modelos locais, agentes e avaliação.

### O que eu uso

- **Backend:** PHP / Laravel, Go, Python (FastAPI), APIs REST, filas (RabbitMQ)
- **Banco de dados:** PostgreSQL (otimização de consultas, pg_trgm, pgvector, PL/pgSQL), Redis
- **IA aplicada:** RAG, LLMs locais com Ollama, saída estruturada em JSON, MCP, agentes, avaliação de modelos
- **Frontend:** Vue.js / Nuxt, React, TypeScript
- **Infra:** Docker, CI/CD, Prometheus, Linux

### Projetos em destaque

**[accounts-receivable](https://github.com/LucasMaPaiva/accounts-receivable)**: microsserviço
de contas a receber em Go, extraído de um monólito Laravel. API em net/http, PostgreSQL com
pagamento transacional, eventos pelo RabbitMQ com inbox idempotente e outbox, servidor MCP
só leitura e métricas Prometheus. Docker e CI com GitHub Actions.

**[rag-laravel-docs](https://github.com/LucasMaPaiva/rag-laravel-docs)**: RAG local sobre a
documentação do Laravel, com busca vetorial e híbrida no PostgreSQL (pgvector + pg_trgm).
Numa avaliação com 30 perguntas em português sobre a documentação em inglês, o modelo de
embeddings multilíngue levou o acerto conceitual de 21% para 84%, e a busca híbrida com
peso ajustado chegou a 90%.

**[agenda-bot](https://github.com/LucasMaPaiva/agenda-bot)**: bot do Telegram que transforma
mensagens como "dentista amanhã às 9h" em eventos no Google Agenda, com um LLM local
(Gemma 3 no Ollama). Uma avaliação com mensagens de resposta conhecida mostrou o modelo
sozinho acertando 0 de 15; com as datas e recorrências resolvidas em código, 14 de 15.
Python, pytest, CI com GitHub Actions.

### Outros projetos

- 🔗 [H7 Escalas](https://plataforma.h7-escalas.com.br): gestão de escalas, repertório e avisos
- 🔗 [Dois90 Pizzaria](https://dois90.com.br): site com cardápio digital, foco em performance e SEO local

<div>
  <img align="center" alt="PHP" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" />
  <img align="center" alt="Laravel" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/laravel/laravel-original.svg" />
  <img align="center" alt="Python" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
  <img align="center" alt="FastAPI" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" />
  <img align="center" alt="PostgreSQL" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" />
  <img align="center" alt="Vue" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vuejs/vuejs-original.svg" />
  <img align="center" alt="TypeScript" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" />
  <img align="center" alt="Docker" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" />
</div>

### Contato

<a href="https://www.linkedin.com/in/lucasmatheuspaiva/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:lucaspaivadev@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"></a>
