<h1 align="center">Rafael Veneroso Morici</h1>

<p align="center">
  <b>Senior Software Engineer · C# / .NET · Applied AI</b><br>
  Belo Horizonte, Brazil · remote
</p>

<p align="center">
  <a href="https://rvmtech.com.br"><img alt="Resume" src="https://img.shields.io/badge/resume-rvmtech.com.br-68217A?style=flat-square"></a>
  <a href="https://rvmit.com.br"><img alt="RVMIT" src="https://img.shields.io/badge/company-rvmit.com.br-007ACC?style=flat-square"></a>
  <a href="https://www.linkedin.com/in/rafael-veneroso-morici/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-rafael--veneroso--morici-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:rvenerosomorici@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-rvenerosomorici%40gmail.com-555?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

---

15+ years building business systems in C# and .NET end to end, from the domain model to production:
ERP, banking, HR, carbon-emissions calculation and, today, healthcare. Lately my focus is making AI
agents do real engineering work: skills, orchestration, tool use, MCP and the guardrails around them.

## What I'm building

Most of this lives in private repositories. Happy to walk through it in a call.

| Project | What it is |
|---|---|
| **RVM.Harness** | The "handbook" my AI agents work by: layered instructions per role, Claude Skills for the whole delivery process, shell hooks, persistent memory, a JSON schema for every agent result, and a weekly self-audit that opens a PR. |
| **RVM.Maestro** | An orchestration hub for AI agents. It routes a prompt to the right project and chains six roles (PMO, Developer, Reviewer, QA, DevOps, Architect), each on the model that fits the job. The Reviewer runs on a different vendor on purpose. Humans only see the approval queue. Spec to production in 8 days. |
| **Safra em Dia** | ERP for small farmers, operated over WhatsApp in natural language: Whisper speech-to-text, LLM tool use (Gemini with OpenAI fallback) and an MCP layer over the ERP operations. |
| **Obra em Dia** | Machinery and workforce management for construction companies. Nothing gets allocated unless it is cleared, and every cost lands in the right cost center. |
| **Binder** | Collection and value tracker for Pokémon, Magic and Yu-Gi-Oh cards: 166k+ cards, search by photo (OCR), collection value in BRL, USD and EUR from TCGplayer and Cardmarket prices. Live at [binder.rvmtech.com.br](https://binder.rvmtech.com.br) · [case study](https://rvmtech.com.br/en/portfolio/binder/). |
| **RVM.UI** | The Blazor component library behind all of the above (v3, 150+ `Rvm*` components). Its design tokens come from an extractor that reads the Figma `.fig` file directly. Private because the design kit it reimplements is licensed per seat. |

## Open source

| Repository | |
|---|---|
| [**RVM.TcgDex**](https://github.com/Elfarrar/RVM.TcgDex) [![NuGet](https://img.shields.io/nuget/v/RVM.TcgDex?style=flat-square)](https://www.nuget.org/packages/RVM.TcgDex) | C# SDK for the [TCGdex](https://tcgdex.dev) API (Pokémon TCG): cards, sets, prices and images in 18 languages. `net8.0`/`net10.0`, source-generated JSON, built-in cache. |
| [**RVM.UI.Tutor**](https://github.com/Elfarrar/RVM.UI.Tutor) | Guided tours for Blazor (Server and WebAssembly) with zero runtime dependencies: highlight, step-by-step, keyboard and ARIA, optional narrated presenter. |
| [**RVM.DesignSystem**](https://github.com/Elfarrar/RVM.DesignSystem) | Blazor component library packaged for NuGet, with a [documentation site](https://design.dev.rvmtech.com.br) built with the library itself. Visual derived from the NEATLAB kit by hello.uiworld (CC BY 4.0). |
| [**RVM.Curriculo**](https://github.com/Elfarrar/RVM.Curriculo) | My resume as code: Markdown → DOCX/PDF and a bilingual Astro site, deployed by GitHub Actions. |

Contribution: [adding RVM.TcgDex to the TCGdex community SDKs](https://github.com/tcgdex/documentation/pull/236).

## Stack

| | |
|---|---|
| **Backend** | C#, .NET 10, ASP.NET Core, EF Core, REST, Vertical Slice Architecture, DDD |
| **Frontend** | Blazor (Server and WebAssembly), TypeScript, Next.js, Angular, Astro |
| **Data** | PostgreSQL, SQL Server, SQLite, MySQL |
| **AI** | Claude Code, Codex, Claude Skills, MCP, LLM tool use (Anthropic, OpenAI, Gemini), Whisper |
| **Cloud & DevOps** | AWS, Azure, GCP, Docker, GitHub Actions, Gitea, Linux, Caddy/Nginx, Playwright |

## Experience

- **Marlabs** · Senior Software Engineer · Jun 2026 – present: US clients in healthcare and carbon-emissions software
- **Questrade** · Senior Software Developer · Jun 2020 – Jan 2026: banking web systems, technical owner of affiliate and partner systems
- **Mereo** · Senior Software Developer / Team Lead · Jul 2018 – Jun 2020: HR SaaS, led a team of 3 developers and 1 QA
- **EMC** · Mid-level Software Developer · Jan 2017 – Jul 2018: ERP built from scratch with DDD

Postgraduate program in Software Engineering for Applied AI (UNIPDS, Sep 2026 – expected 2027).

<details>
<summary><b>🇧🇷 Em português</b></summary>

<br>

Mais de 15 anos construindo sistemas corporativos em C# e .NET de ponta a ponta, do modelo de domínio
à produção: ERP, banco, gestão de pessoas, cálculo de emissão de carbono e, hoje, saúde. Meu foco
recente é fazer agentes de IA trabalharem de verdade: skills, orquestração, tool use, MCP e as travas
em volta deles.

### O que estou construindo

A maior parte está em repositórios privados. Posso mostrar numa conversa.

| Projeto | O que é |
|---|---|
| **RVM.Harness** | O "manual" com que meus agentes de IA trabalham: instruções em camadas por papel, Claude Skills para o processo de entrega inteiro, hooks em shell, memória persistente, um JSON schema para o resultado de todo agente e uma auditoria semanal que abre PR. |
| **RVM.Maestro** | Central de orquestração dos agentes. Roteia o pedido para o projeto certo e encadeia seis papéis (PMO, Developer, Reviewer, QA, DevOps e Arquiteto), cada um com o modelo adequado à função. O revisor roda em outro fornecedor, de propósito. Para mim sobra só a fila de aprovação. Da especificação à produção em 8 dias. |
| **Safra em Dia** | ERP para o pequeno produtor rural, operado pelo WhatsApp em linguagem natural: Whisper para transcrever áudio, tool use com LLM (Gemini, com OpenAI de fallback) e uma camada MCP sobre as operações do ERP. |
| **Obra em Dia** | Gestão de máquinas e pessoas em construtoras. Nada é alocado sem estar apto, e todo custo cai no centro de custo certo. |
| **Binder** | Coleção e valor de cartas de Pokémon, Magic e Yu-Gi-Oh: mais de 166 mil cartas, busca pela foto (OCR) e valor da coleção em R$, US$ e € pelos preços do TCGplayer e do Cardmarket. No ar em [binder.rvmtech.com.br](https://binder.rvmtech.com.br) · [estudo de caso](https://rvmtech.com.br/portfolio/binder/). |
| **RVM.UI** | A biblioteca de componentes Blazor por trás de tudo isso (v3, mais de 150 componentes `Rvm*`). Os tokens de design vêm de um extrator que lê o arquivo `.fig` do Figma direto. É privada porque o kit de design que ela reimplementa tem licença por usuário. |

### Open source

| Repositório | |
|---|---|
| [**RVM.TcgDex**](https://github.com/Elfarrar/RVM.TcgDex) | SDK C# da API [TCGdex](https://tcgdex.dev) (Pokémon TCG): cartas, coleções, preços e imagens em 18 idiomas. `net8.0`/`net10.0`, JSON por source generator, cache embutido. Publicado no nuget.org. |
| [**RVM.UI.Tutor**](https://github.com/Elfarrar/RVM.UI.Tutor) | Tour guiado para Blazor (Server e WebAssembly), sem dependência em tempo de execução: destaque, passo a passo, teclado e ARIA, apresentador com narração opcional. |
| [**RVM.DesignSystem**](https://github.com/Elfarrar/RVM.DesignSystem) | Biblioteca de componentes Blazor empacotada para NuGet, com [site de documentação](https://design.dev.rvmtech.com.br) feito com a própria biblioteca. Visual derivado do kit NEATLAB, de hello.uiworld (CC BY 4.0). |
| [**RVM.Curriculo**](https://github.com/Elfarrar/RVM.Curriculo) | Meu currículo como código: Markdown → DOCX/PDF e um site Astro bilíngue, publicado pelo GitHub Actions. |

Contribuição: [inclusão do RVM.TcgDex entre os SDKs da comunidade TCGdex](https://github.com/tcgdex/documentation/pull/236).

### Stack

| | |
|---|---|
| **Backend** | C#, .NET 10, ASP.NET Core, EF Core, REST, Vertical Slice Architecture, DDD |
| **Frontend** | Blazor (Server e WebAssembly), TypeScript, Next.js, Angular, Astro |
| **Dados** | PostgreSQL, SQL Server, SQLite, MySQL |
| **IA** | Claude Code, Codex, Claude Skills, MCP, tool use com LLM (Anthropic, OpenAI, Gemini), Whisper |
| **Cloud e DevOps** | AWS, Azure, GCP, Docker, GitHub Actions, Gitea, Linux, Caddy/Nginx, Playwright |

### Experiência

- **Marlabs** · Engenheiro de Software Sênior · jun/2026 – atual: clientes americanos de software de saúde e de cálculo de emissão de carbono
- **Questrade** · Programador Sênior · jun/2020 – jan/2026: sistemas web do banco, responsável técnico pelos sistemas de afiliados e parceiros
- **Mereo** · Programador Sênior / Líder Técnico · jul/2018 – jun/2020: SaaS de RH, liderança de 3 desenvolvedores e 1 QA
- **EMC** · Programador Pleno · jan/2017 – jul/2018: ERP construído do zero com DDD

Pós-graduação em Engenharia de Software em IA Aplicada (UNIPDS, set/2026 – previsão 2027).
Currículo completo em [rvmtech.com.br](https://rvmtech.com.br).

</details>
