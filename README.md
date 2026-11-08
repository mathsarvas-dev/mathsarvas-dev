<div align="center">

<img src="avatar.jpg" width="160" style="border-radius:50%" alt="Matheus Mosconi Sarvas" />

# Matheus Mosconi Sarvas · Dev

**Desenvolvedor full stack · TypeScript, Bun e cloud**
Construo produtos do banco de dados à nuvem: API, web, mobile, CI/CD e infraestrutura própria.

[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mamosarvas@gmail.com)

</div>

---

## Sobre

Estudante e desenvolvedor que gosta de resolver problemas reais de ponta a ponta. Nos meus projetos eu decido a stack, modelo os dados, escrevo a API e a interface, automatizo o deploy e mantenho a infraestrutura rodando. Documento o **porquê** de cada decisão técnica, não só o como.

## Projetos em destaque

| Projeto | O que é | Stack |
|---|---|---|
| [**Mangr**](https://github.com/matheusmsarvas-creator/mangr) | App de finanças para casais (modo individual e casal), com lançamentos por IA a partir de comprovantes, texto e áudio | Expo/React Native, Bun, Hono, Postgres, Drizzle, Better Auth, pg-boss, Groq |
| [**Integra Teens**](https://github.com/matheusmsarvas-creator/integra-teens) | CRM de um ministério de adolescentes: funil do visitante até membro, líderes, organograma e eventos | Next.js 15, React 19, Prisma, Postgres 17, Better Auth, Docker, Caddy |
| [**Acampamento TeensIBP**](https://github.com/matheusmsarvas-creator/teensibp-backend) | Inscrição digital e painel administrativo do acampamento anual (pagamentos, autorizações, quartos, e-mails) | Hono, Drizzle, Postgres, React + Vite, nginx, Brevo, GHCR |

## Stack

**Linguagens** ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)

**Backend** ![Bun](https://img.shields.io/badge/Bun-000000?logo=bun&logoColor=white) ![Hono](https://img.shields.io/badge/Hono-E36002?logo=hono&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white) ![Better Auth](https://img.shields.io/badge/Better_Auth-000000)

**Frontend e mobile** ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white) ![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)

**Dados** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?logo=drizzle&logoColor=black) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)

**Cloud e DevOps** ![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?logo=oracle&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-1F88C0?logo=caddy&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

**IA** ![Groq](https://img.shields.io/badge/Groq-F55036) Extração de dados de comprovantes e áudio com revisão humana obrigatória.

## Cloud e infraestrutura

Eu mesmo publico e opero meus sistemas na **Oracle Cloud (Always Free, ARM Ampere A1)**. Detalhes no repositório [**cloud-foundation**](https://github.com/matheusmsarvas-creator/cloud-foundation):

- Provisionamento automatizado da VM (script OCI CLI que tenta até haver capacidade) e `cloud-init` com Docker, firewall, fuso e swap
- Imagens publicadas no **GitHub Container Registry** por GitHub Actions, multi-arquitetura (amd64 e arm64)
- **Caddy** como proxy reverso com HTTPS automático (Let's Encrypt) e cabeçalhos de segurança
- Postgres só na rede interna do Docker, com backup agendado e migração entre máquinas por dump
- DNS e túnel na **Cloudflare**, domínio no Registro.br

## Como eu decido

- **Simples primeiro.** Monólito modular antes de microsserviços, fila em cima do Postgres antes de Redis, Docker Compose antes de Kubernetes.
- **Portável.** A mesma imagem roda em desenvolvimento e produção, sem prender o projeto a um provedor.
- **Dinheiro é inteiro.** Valores em centavos, migrations versionadas e restrições de integridade no banco.
- **IA sugere, a pessoa confirma.**

---

<div align="center">
Aberto a oportunidades e conversas sobre produto e engenharia.
</div>
