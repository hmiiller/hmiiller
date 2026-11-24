<!-- Header Banner -->
<div align="center">
  <img width="100%" src="./banner.png" alt="Humberto Müller — Full Stack Developer & DevOps" style="border-radius: 12px;" />
</div>

<!-- Typing Animation -->
<div align="center">
  <a href="https://github.com/hmiiller">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=3000&pause=1000&color=4070F4&center=true&vCenter=true&width=680&lines=Full+Stack+Software+Engineer+(Next.js+%26+Node.js);Analista+de+Infraestrutura+%26+SysAdmin+Linux%2FWindows;Especialista+em+GLPI%2C+ITIL+%26+Zabbix+7.0;Orquestra%C3%A7%C3%A3o+de+APIs+REST+%26+Sistemas+Corporativos" alt="Typing SVG" />
  </a>
</div>

<br/>

<!-- Social Badges & Views -->
<div align="center">
  <a href="https://www.linkedin.com/in/humbertomiiller/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/hmiiller" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://instagram.com/humberto.pxto" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=hmiiller&label=Visitas&color=4070F4&style=for-the-badge" alt="Profile Views" />
</div>

---

## ⚡ Sobre Mim

```ts
const humberto = {
  role: "Desenvolvedor Web Full Stack & Analista de Infraestrutura",
  organization: "SEDS-GO — Secretaria de Estado de Desenvolvimento Social",
  education: "Tecnólogo em Segurança da Informação",
  experience: "7+ anos em Tecnologia",
  focus: [
    "Aplicações Web de Alta Fidelidade (Next.js / React / Node.js)",
    "Automação ITSM & Integrações REST com GLPI",
    "Observabilidade & Telemetria (Zabbix 7.0, PaperCut, SNMP)",
    "Resiliência Linux, Docker, Nginx, PM2 & Windows Server (AD/GPO)"
  ],
  architecturePhilosophy: "Sistema Mestre: unificação de logs, métricas, SLAs e serviços em tempo real"
};
```

---

## 🛠️ Stack Tecnológica

<div align="center">

| Camada | Tecnologias |
| :--- | :--- |
| **Frontend & UI** | ![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) |
| **Backend & Real-Time** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white) ![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black) |
| **Dados & Cache** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis_7-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black) |
| **Infra, DevOps & ITSM** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white) ![Zabbix](https://img.shields.io/badge/Zabbix_7.0-D40000?style=for-the-badge&logo=zabbix&logoColor=white) |

</div>

---

## 🚀 Sistemas Concluídos em Produção

> **🔒 Aviso Institucional & Confidencialidade:**  
> Os sistemas abaixo foram arquitetados e desenvolvidos para atender demandas e especificações internas da **Secretaria de Estado de Desenvolvimento Social de Goiás (SEDS-GO)**.  
> Por razões de **segurança da informação, proteção de infraestrutura e governança institucional**, o código-fonte dessas aplicações é mantido exclusivamente em **ambiente/repositório privado**, não sendo publicado em repositórios públicos. As informações aqui apresentadas têm caráter estritamente demonstrativo de arquitetura e stack tecnológica, sem exposição de dados, credenciais ou endpoints internos.

| Status | Sistema | Propósito & Impacto | Stack | Acesso |
| :---: | :--- | :--- | :--- | :---: |
| ![Prod](https://img.shields.io/badge/Produção-10B981?style=flat-square) | **ADMGOV** | Painel de telemetria e resiliência de servidores com integração **Zabbix 7.0** (JSON-RPC Bearer), alertas sonoros/visuais, terminal de logs PM2 filtrado e rotina automática de backups SQLite (retenção 7 dias). | `Next.js 15` `Prisma` `Zabbix 7.0` `PM2` | 🔒 Privado (SEDS-GO) |
| ![Prod](https://img.shields.io/badge/Produção-10B981?style=flat-square) | **SGC SEDS Mobile** | Aplicativo Web Progressivo (**PWA**) mobile-first integrado à API REST do GLPI: abertura guiada de chamados, upload em chunks via Redis, biometria/PIN, triagem por IA, carrossel de comunicados e painel de SLA. | `Next.js 15` `React 19` `Redis 7` `Docker` | 🔒 Privado (SEDS-GO) |
| ![Prod](https://img.shields.io/badge/Produção-10B981?style=flat-square) | **Monitor de SLAs GLPI** | Dashboard estilo **NOC** em tempo real para acompanhamento de SLAs de atendimento (TTO) e solução (TTR), com proxy seguro (Helmet/CSP), contadores ao vivo e matriz RBAC por perfil/entidade. | `Node.js` `Express` `Vanilla JS` `GLPI API` | 🔒 Privado (SEDS-GO) |
| ![Prod](https://img.shields.io/badge/Produção-10B981?style=flat-square) | **Auditor SLA Painel** | Plataforma full-stack em contêiner **Docker** para fiscalização de contratos de TI, auditoria de SLAs e cálculo de glosas no HUB TI com autenticação GLPI. | `React (Vite)` `Express` `PostgreSQL` `Docker` | 🔒 Privado (SEDS-GO) |
| ![Prod](https://img.shields.io/badge/Produção-10B981?style=flat-square) | **SEDS Hub TI - Reservas** | Gestão e agendamento de equipamentos tecnológicos com validação de choque de horário, controle de devoluções e autenticação centralizada via LDAP/GLPI. | `React 19` `TypeScript` `Prisma` `PostgreSQL` | 🔒 Privado (SEDS-GO) |
| ![Prod](https://img.shields.io/badge/Produção-10B981?style=flat-square) | **Monitoramento de Impressão** | Painel de telemetria em tempo real para servidores de impressão e níveis de toner via **PaperCut** e protocolo **SNMP**, com abertura automática de chamados no SGC/GLPI. | `React 19` `Tailwind v4` `Node.js` `SNMP` | 🔒 Privado (SEDS-GO) |
| ![Prod](https://img.shields.io/badge/Produção-10B981?style=flat-square) | **Atendimento WhatsApp Bot** | Plataforma multiusuário via WhatsApp (**Baileys**) com chatbot de IA, fila de atendimento em tempo real via WebSocket, notificações push, RBAC e histórico completo. | `Next.js 14` `Socket.io` `Baileys` `Drizzle` | 🔒 Privado (SEDS-GO) |

<details>
<summary>🔍 <b>Ver detalhes de arquitetura e segurança aplicados nos sistemas</b></summary>

- **BFF & Proxy Seguro:** Tokens corporativos (`App-Token`, `Session-Token`, `ZABBIX_API_TOKEN`) isolados estritamente no servidor via cookies `httpOnly` e cabeçalhos `Authorization: Bearer`.
- **Controle de Acesso (RBAC):** Validação ID-First integrada aos perfis e entidades do GLPI, garantindo isolamento de filas e painéis gerenciais.
- **Alta Disponibilidade:** Deploy containerizado com Docker Compose + Healthchecks ou daemonizado com PM2 + Logrotate e proxy reverso Nginx.
- **Resiliência Offline & Performance:** Upload fragmentado em chunks com reconstrução em Redis, modo offline outbox e tipagem estrita TypeScript.

</details>

---

## 📊 Métricas no GitHub

<div align="center">
  <img height="175em" src="https://github-readme-stats.vercel.app/api?username=hmiiller&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=4070F4&icon_color=4070F4&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hmiiller&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=4070F4" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=hmiiller&theme=tokyonight&hide_border=true&background=0D1117&ring=4070F4&fire=4070F4&currStreakLabel=4070F4" alt="GitHub Streak" />
</div>

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=hmiiller&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=4070F4&line=4070F4&point=FFFFFF&area=true" alt="Activity Graph" />
</div>

---

<!-- Footer Wave Banner -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0E2431,50:1d3f58,100:4070F4&height=100&section=footer" alt="Footer Banner" />
</div>
