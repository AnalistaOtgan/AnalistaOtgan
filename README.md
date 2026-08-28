# AnalistaOtgan

Engenheiro de software focado em sistemas operacionais para processos empresariais e automação operacional. Desenvolvo soluções práticas — backend confiável, integrações robustas e interfaces web leves — para transformar processos manuais em fluxos digitais eficientes e auditáveis.

---

## Resumo profissional

- Atuo em design e entrega de sistemas para RH, varejo (PDV), logística e operações internas.
- Metodologia pragmática: entregas incrementais, testes automatizados, observabilidade e redução de atrito operacional.
- Forte foco em integrações (webhooks, filas, adaptadores legados), conformidade (fiscal e de dados) e resiliência (retries, circuit breakers).

---

## Destaques recentes

- RHConecta — plataforma RH com pipeline de distribuição de contracheques, notificações em tempo real e RLS no PostgreSQL. (Último push: 2026-08-22)
- Agendaih — agendador de mensagens (WhatsApp) com Baileys, recorrência e processamento em background. (Último push: 2026-08-18)
- Axis — Sistema de Ponto de Venda (PDV) para Windows com emissão de NFC-e (Zeus.Net.NFe.NFCe), controle de estoque e recursos fiscais; documentação de integração NFC-e e roadmap de implantação. (Último push: 2026-08-28)
- ConectaRH — módulos para gestão de atestados e parametrização de limites por tipo (PR em revisão).
- AAOM (AI Agent Office Manager) — arquitetura e roadmap para orquestração de agentes LLM, visualização isométrica (Phaser.js) e motor de tarefas assíncronas (BullMQ). (Work in progress: mar/2026)
- PortalEscolar (ELO) — plataforma escolar B2B com assistente AI integrado (Gemini), gestão acadêmica e módulos de comunicação/financeiro.

---

## Projetos selecionados (descrição técnica resumida)

- Axis — PDV para Windows (C#)
  - Emissão de NFC-e integrada com Zeus.Net.NFe.NFCe; documentação de refatoração, exemplos práticos, migrações e checklist de produção.
  - Foco: desempenho no caixa, conformidade fiscal (SEFAZ/CSC), controle de estoque, promoções e backup automático.
  - Repositório: https://github.com/AnalistaOtgan/Axis
  - Demo/homepage: https://axis-tau-liard.vercel.app

- RHConecta — Plataforma RH (TypeScript / Supabase / PLpgSQL)
  - Distribuição automática de contracheques com parsing estruturado de PDFs, notificações in-app e push, RLS por instituição e funções RPC para operações críticas.
  - Arquitetura: React + Vite (web), Capacitor (Android), Supabase (Postgres 17, Edge Functions).
  - Repositório: https://github.com/AnalistaOtgan/RHConecta
  - Demo/homepage: https://rh-conecta-lilac.vercel.app

- Agendaih — Agendador de mensagens WhatsApp (TypeScript / Next.js / Supabase)
  - Integração via Baileys (multi-device), agendamento com recorrência, dashboard e processamento por background jobs/cron.
  - Repositório: https://github.com/AnalistaOtgan/Agendaih
  - Demo/homepage: https://agendaih-tau.vercel.app

- ConectaRH — Ferramenta complementar a RHConecta (PLpgSQL)
  - Módulos para controle de atestados, políticas e parametrizações por tipo; arquitetura orientada a banco e regras de negócio centralizadas.
  - Repositório: https://github.com/AnalistaOtgan/ConectaRH

- AAOM (AI Agent Office Manager) — Plataforma de orquestração de agentes LLM (TypeScript)
  - Roadmap e implementação de múltiplos épicos: LLM Engine, agentes, orquestração de tasks, visualização isométrica (Phaser.js), otimizações de memória (TurboQuant) e MCP Gateway.
  - Repositório: https://github.com/AnalistaOtgan/AAOM

- PortalEscolar (ELO) — Portal escolar B2B (TypeScript / Firebase)
  - MVP com módulos acadêmicos, comunicação, financeiro e assistente AI (Gemini/Inception). Roadmap de comercialização e estratégia SaaS.
  - Repositório: https://github.com/AnalistaOtgan/PortalEscolar
  - Demo/homepage: https://portal-escolar-alpha.vercel.app

- ConsultaNFe — Aplicação de consulta de notas fiscais (ASP.NET)
  - Ferramenta utilitária para consulta e conferência de notas fiscais eletrônicas.
  - Repositório: https://github.com/AnalistaOtgan/ConsultaNFe

- ControleValidade — Utilitário de controle de validade (JavaScript)
  - Aplicações para prevenção de perdas por controle de prazo e inventário básico.
  - Repositório: https://github.com/AnalistaOtgan/ControleValidade

- RegistroDePerda — Registro de perdas hortifrutícolas (TypeScript)
  - Fluxos para registrar, auditar e analisar perdas operacionais.
  - Repositório: https://github.com/AnalistaOtgan/RegistroDePerda

- Fluxo — Gerenciador financeiro pessoal (TypeScript)
  - Ferramenta pragmática para controle de orçamento e despesas pessoais.
  - Repositório: https://github.com/AnalistaOtgan/Fluxo

---

## Stack técnico (síntese)

- Linguagens: Python, TypeScript, C#, JavaScript, PLpgSQL, ASP.NET
- Infra & DB: Supabase (Postgres), Firebase, Redis, SQLite (prototipagem)
- Mensageria/Jobs: BullMQ, Cron jobs, processadores background
- Integrações: Webhooks, Baileys (WhatsApp), Zeus.Net.NFe.NFCe (NFC-e), APIs REST, Socket.io
- Front-end: React (Vite / Next.js), Capacitor (Android), Phaser.js (visualizações isométricas)
- Ferramentas: Docker, CI/CD, observabilidade (Prometheus / logs estruturados), testes automatizados

---

## Como colaborar

- Abra uma issue no repositório alvo descrevendo o objetivo, passos para reproduzir e resultados esperados.
- Para PRs: fork, branch por feature, testes automatizados quando aplicável e descrição técnica clara.
- Para parcerias: abrir issue com label `discuss` ou enviar proposta técnica com escopo e prazos.

---

## Contato

- Perfil GitHub: https://github.com/AnalistaOtgan
- Preferência: discussões técnicas por issues e PRs (inclua logs, passos e objetivo esperado).

---

Missão: reduzir complexidade operacional e transformar dados em decisões acionáveis.
