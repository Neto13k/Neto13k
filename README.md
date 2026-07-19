<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:58A6FF&height=120&section=header&text=José%20Neto&fontSize=42&fontColor=ffffff&fontAlignY=65&animation=fadeIn" width="100%"/>

### Fullstack Developer · Node.js · React · TypeScript · AI Agents

<p>
  <a href="https://www.linkedin.com/in/jose-hermes-dev/">
    <img src="https://img.shields.io/badge/LinkedIn-jose--hermes--dev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:jose.hermes.dev@gmail.com">
    <img src="https://img.shields.io/badge/Email-jose.hermes.dev%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Open%20to%20Work-Estágio%20%7C%20Júnior-22C55E?style=for-the-badge&logo=checkmarx&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Localização-Maceió%2C%20AL-58A6FF?style=flat&logo=googlemaps&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Modalidade-Remoto%20%7C%20Híbrido-58A6FF?style=flat"/>
</p>

</div>

---

## Sobre

Desenvolvedor Fullstack com portfólio de aplicações funcionais em produção e **7 anos de experiência em operações corporativas de alto volume** — fintech, e-commerce, telecom e seguros — o que me dá uma leitura prática de produto, SLA e impacto real de bugs em usuário final.

Construo aplicações com Node.js, React e TypeScript com foco em autenticação segura, integridade de dados e cobertura de testes. Atualmente expandindo para agentes de IA com Google ADK, com estudos em andamento em cloud (AWS).

```
Validação com Joi  ·  Autenticação JWT  ·  Testes de integração (Jest/Supertest)  ·  AI Agents  ·  REST APIs  ·  PostgreSQL  ·  Arquitetura MVC
```

---

## Projetos

### [Trello Process Bot](https://github.com/Neto13k/trello-process-bot) — Agente de IA para gestão de tarefas

> Agente conversacional que gerencia boards do Trello via linguagem natural. O modelo interpreta intenção, mapeia para ações da API do Trello e executa — incluindo correção de um bug nativo de datas (D-1) diretamente no agente.

- Criação, movimentação e priorização de cards por comandos em linguagem natural
- Gemini 2.5 Flash com tool use sobre Trello API, sem intermediários de n8n ou similares
- Correção de bug nativo D-1 da API do Trello implementada como lógica de normalização no agente

<img src="https://skillicons.dev/icons?i=python" height="28"/>
&nbsp;
<img src="https://img.shields.io/badge/Google%20ADK-4285F4?style=flat&logo=google&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Gemini%202.5%20Flash-8E24AA?style=flat&logo=google&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Trello%20API-0052CC?style=flat&logo=trello&logoColor=white"/>

---

### [BarberSync](https://github.com/Neto13k/barber-sync) — Sistema fullstack de agendamento para barbearias

[![🔴 Live](https://img.shields.io/badge/🔴%20Live-barber--sync--nu.vercel.app-orange?style=flat)](https://barber-sync-nu.vercel.app/) &nbsp; ![Vercel](https://img.shields.io/badge/Frontend-Vercel-black?style=flat&logo=vercel&logoColor=white) &nbsp; ![Render](https://img.shields.io/badge/Backend-Render-46E3B7?style=flat&logo=render&logoColor=black) &nbsp; ![Neon](https://img.shields.io/badge/DB-Neon-00E599?style=flat&logo=postgresql&logoColor=black)

> Aplicação fullstack profissional com painéis separados para cliente e barbeiro, controle de acesso por perfil, validação robusta com Joi e arquitetura MVC escalável.

**Arquitetura & Qualidade de Código:**
- ✅ Arquitetura MVC com Controllers, Routes, Middlewares, Validators centralizados
- ✅ Validação de entrada com **Joi** (schemas para users e appointments)
- ✅ Middleware de validação customizado com tratamento de erros estruturado
- ✅ Tratamento global de erros centralizado (errorHandler middleware)
- ✅ AsyncHandler para eliminação de try/catch repetidos
- ✅ Clean Code com separação clara de responsabilidades

**Funcionalidades:**
- JWT com separação de permissões por perfil (cliente / barbeiro) em rotas protegidas
- Validação de conflito de horário no backend antes da inserção no banco
- Validação de data retroativa com mensagens de erro amigáveis
- Autenticação com bcrypt (10 rounds) para hash seguro de senhas
- Queries parametrizadas eliminando vetores de SQL Injection

**Testes & Documentação:**
- Suíte de testes de integração com Jest + Supertest (~30 casos de teste)
- Cobertura de fluxos críticos: autenticação, agendamento, autorização por role
- README profissional com API documentation, diagrama ER e instruções passo a passo
- Commits com padrão conventional commits

<img src="https://skillicons.dev/icons?i=react,ts,nodejs,express,postgres,jest" height="28"/>

`React 19` `TypeScript` `Node.js` `Express 5` `PostgreSQL` `JWT` `Bcrypt` `Joi` `Jest` `Supertest` `SCSS` `MVC`

---

### [News Hub System](https://github.com/Neto13k/news-hub-system) — Portal de notícias fullstack

[![🔴 Live](https://img.shields.io/badge/🔴%20Live-news--hub--system.vercel.app-orange?style=flat)](https://news-hub-system.vercel.app) &nbsp; ![Vercel](https://img.shields.io/badge/Frontend-Vercel-black?style=flat&logo=vercel&logoColor=white) &nbsp; ![Render](https://img.shields.io/badge/Backend-Render-46E3B7?style=flat&logo=render&logoColor=black) &nbsp; ![Neon](https://img.shields.io/badge/DB-Neon-00E599?style=flat&logo=postgresql&logoColor=black)

> Portal com autenticação, agregação de notícias em tempo real via GNews API e persistência de preferências entre sessões.

- Rotas protegidas com JWT no frontend + validação no backend em cada request
- Queries parametrizadas eliminando vetores de SQL Injection
- Integração com GNews API com filtro por categoria e paginação no lado do servidor

<img src="https://skillicons.dev/icons?i=react,ts,nodejs,express,postgres" height="28"/>

`React 19` `TypeScript` `Node.js` `Express 5` `PostgreSQL` `JWT` `React Hook Form` `SCSS`

---

## Stack

<table>
<tr>
<td valign="top" width="50%">

**Uso frequente**
<br/><br/>
<img src="https://skillicons.dev/icons?i=ts,react,nodejs,express,postgres,jest,html,css" height="28"/>
<br/><br/>
TypeScript · React · Node.js · Express · PostgreSQL · Jest · HTML · CSS/SCSS

</td>
<td valign="top" width="50%">

**Ferramentas e ecossistema**
<br/><br/>
<img src="https://skillicons.dev/icons?i=git,github,postman,vite,vercel" height="28"/>
&nbsp;
<img src="https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=black"/>
&nbsp;
<img src="https://img.shields.io/badge/Neon-00E599?style=flat&logo=postgresql&logoColor=black"/>
<br/><br/>
Git · GitHub · Postman · Vite · Vercel · Render · Neon

</td>
</tr>
<tr>
<td valign="top">

**Backend & Validação**
<br/><br/>
<img src="https://img.shields.io/badge/Joi-5A0A7E?style=flat&logo=npm&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Bcrypt-2C3E50?style=flat"/>

</td>
<td valign="top">

**IA & Agentes + Cloud (em estudo)**
<br/><br/>
<img src="https://skillicons.dev/icons?i=python,aws" height="28"/>
&nbsp;
<img src="https://img.shields.io/badge/Google%20ADK-4285F4?style=flat&logo=google&logoColor=white"/>

</td>
</tr>
</table>

---

## Experiência

**Representante de Atendimento — Operações Digitais · Almaviva Experience** *(Jul 2019 – Presente)*

7 anos em operações corporativas de alto volume com múltiplos clientes e stacks de CRM:

| Operação | Período | Contexto técnico |
|---|---|---|
| Brazino777 | Fev 2025 – presente | Microsoft Copilot integrado ao fluxo de atendimento em operação 24/7 |
| Sompo Seguros / HDI | Mar 2023 – Jan 2025 | Gestão de pipeline de tickets em CRM com foco em SLA e FCR |
| Shopee | Out 2021 – Fev 2023 | Operação simultânea em 3 canais com decisão baseada em dados de pedido |
| Vivo Telecom | Jul 2019 – Set 2021 | Diagnóstico técnico de conectividade e retenção dentro de meta mensal de churn |

---

## Formação

| Curso | Instituição | Status |
|---|---|---|
| Tecnólogo em ADS | UniFatecie | Jan 2026 – em andamento |
| Desenvolvimento Full Stack | StackX | 2025 – em conclusão |

**Certificações técnicas relevantes:**

| Certificação | Instituição | Ano |
|---|---|---|
| Do Prompt ao Agente (Google ADK) | DIO | 2026 |
| Fundamentos de Cloud com AWS | DIO | 2026 |
| Ferramentas de IA do Google | UniFatecie | 2026 |
| Fundamentos de Inteligência Artificial | UniFatecie | 2026 |

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats-fast.vercel.app/api?username=Neto13k&show_icons=true&theme=tokyonight&hide_border=true"/>
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Neto13k&layout=compact&theme=tokyonight&hide_border=true"/>

</div>

---

<div align="center">

**Aberto a estágio ou posição júnior em Fullstack ou Frontend.**

📩 [jose.hermes.dev@gmail.com](mailto:jose.hermes.dev@gmail.com) · [linkedin.com/in/jose-hermes-dev](https://www.linkedin.com/in/jose-hermes-dev/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,100:0D1117&height=80&section=footer" width="100%"/>

</div>
