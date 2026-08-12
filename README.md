

<p align="center">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0ea5e9,100:7c3aed&height=190&section=header&text=Jason%20Tralli&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=Full%20Stack%20Developer%20•%20Next.js%20•%20TypeScript%20•%20Supabase&descAlignY=55&descSize=17"
  />
</p>

<div align="center">

### Desenvolvendo aplicações com foco em arquitetura, backend e segurança.

`Next.js` · `TypeScript` · `Supabase` · `PostgreSQL` · `Java` · `Spring Boot`

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/jasontralliti/)
[![Email](https://img.shields.io/badge/Email-Contato-1f2937?style=for-the-badge\&logo=microsoftoutlook\&logoColor=white)](mailto:jtrallii@live.com)

</div>

---

## `> whoami`

```ts
const developer = {
  name: "Jason Tralli",

  role: "Full Stack Developer",

  mainStack: [
    "Next.js",
    "TypeScript",
    "Supabase",
    "PostgreSQL"
  ],

  backend: [
    "Java",
    "Spring Boot",
    "REST APIs"
  ],

  interests: [
    "Backend Architecture",
    "Application Security",
    "Authentication & Authorization",
    "Database Design",
    "SaaS"
  ]
};
```

Sou desenvolvedor Full Stack, formado em **Análise e Desenvolvimento de Sistemas** e pós-graduado em **Desenvolvimento de Sistemas em Java**.

Minha principal stack atualmente é **Next.js + TypeScript + Supabase + PostgreSQL**, trabalhando com aplicações que envolvem autenticação, autorização, banco de dados, APIs e regras de acesso.

Minha experiência com sistemas reais em produção aumentou meu interesse por entender o que acontece além da interface: **como os dados são protegidos, como permissões são aplicadas, como alterações no banco são versionadas e como evitar que mudanças aparentemente simples causem problemas em produção**.

Também desenvolvo e estudo soluções utilizando **Java e Spring Boot**, inclusive em projetos que combinam frontend Next.js com backend Java.

---

## `// core.stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=nextjs,ts,react,supabase,postgres&theme=dark" />

<br/><br/>

**Next.js · TypeScript · React · Supabase · PostgreSQL**

</div>

### Backend

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,nodejs&theme=dark" />

<br/><br/>

**Java · Spring Boot · Node.js · REST APIs**

</div>

### Desenvolvimento & Infra

<div align="center">

<img src="https://skillicons.dev/icons?i=git,github,docker,linux,vscode,idea&theme=dark" />

<br/><br/>

**Git · GitHub · Docker · Linux · VS Code · IntelliJ IDEA**

</div>

---

## `// engineering.focus`

Meu foco atual não está apenas em implementar funcionalidades, mas em compreender e estruturar os mecanismos que sustentam uma aplicação.

```text
Application
│
├── Authentication
│   ├── Sessions
│   └── Identity
│
├── Authorization
│   ├── Permissions
│   ├── RLS
│   └── Policies
│
├── Backend
│   ├── Server Actions
│   ├── REST APIs
│   └── Validation
│
├── Database
│   ├── PostgreSQL
│   ├── Migrations
│   └── Data Modeling
│
├── Security
│   ├── Rate Limiting
│   ├── Access Control
│   └── Secrets / Environment
│
└── Infrastructure
    ├── Development
    ├── Testing
    └── Production
```

---

# `// featured.projects`

## 🛡️ SaaS Base

> Base reutilizável para construção de aplicações SaaS com foco em segurança e padronização arquitetural.

<p>

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square\&logo=nextdotjs\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-181818?style=flat-square\&logo=supabase\&logoColor=3ECF8E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square\&logo=postgresql\&logoColor=white)

</p>

O projeto está sendo desenvolvido como uma estrutura reutilizável para futuros sistemas, concentrando práticas relacionadas a:

* autenticação e autorização;
* Supabase Auth;
* PostgreSQL;
* Row Level Security;
* policies;
* migrations;
* Server Actions;
* validação de dados;
* rate limiting;
* separação entre client e server;
* organização de variáveis de ambiente;
* controles de segurança para aplicações SaaS.

**Objetivo:** reduzir a necessidade de reconstruir e revisar toda a infraestrutura de segurança a cada novo projeto.

[**→ Ver projeto**](https://github.com/JTrallii/projeto-base)

---

## 💰 Fluxo Financeiro

> Aplicação Full Stack utilizando Next.js no frontend e Java/Spring Boot no backend.

### Arquitetura

```text
┌─────────────────────┐
│      Next.js        │
│     TypeScript      │
│      Frontend       │
└──────────┬──────────┘
           │
           │ API
           ▼
┌─────────────────────┐
│     Spring Boot     │
│   Spring Security   │
│   Spring Data JPA   │
│       Backend       │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│     PostgreSQL      │
│       Flyway        │
└─────────────────────┘
```

<p>

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square\&logo=nextdotjs\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square\&logo=postgresql\&logoColor=white)

</p>

Projeto utilizado também para aprofundar a integração entre aplicações **Next.js** e backends desenvolvidos com **Java/Spring Boot**.

[**→ Ver projeto**](https://github.com/JTrallii/fluxo-financeiro)

---

# `// security.mindset`

Parte importante da minha evolução como desenvolvedor veio da experiência com problemas reais em aplicações e ambientes de produção.

Isso direcionou meus estudos para assuntos como:

```yaml
security:
  authentication: true
  authorization: true
  row_level_security: true
  validation: true
  rate_limiting: true

database:
  engine: PostgreSQL
  migrations: true
  access_policies: true

architecture:
  client_server_separation: true
  environment_isolation: true
  production_safety: true
```

Tenho buscado entender não apenas **como implementar uma funcionalidade**, mas quais são as consequências dela para o restante da aplicação.

---

# `// knowledge.base`

<table>
<tr>
<td valign="top" width="50%">

### Frontend

* Next.js
* React
* TypeScript
* JavaScript
* HTML
* CSS

</td>

<td valign="top" width="50%">

### Backend

* Java
* Spring Boot
* Node.js
* REST APIs
* Server Actions
* Authentication

</td>
</tr>

<tr>
<td valign="top">

### Dados

* PostgreSQL
* Supabase
* SQL
* Database Migrations
* RLS
* Data Modeling

</td>

<td valign="top">

### Ferramentas

* Git
* GitHub
* Docker
* Linux
* VS Code
* IntelliJ IDEA

</td>
</tr>
</table>

---

# `// currently.building`

```bash
jason@dev:~$ current-focus

→ Arquitetura de aplicações SaaS
→ Segurança em aplicações web
→ Next.js e Server-Side Development
→ PostgreSQL e modelagem de dados
→ Autenticação e autorização
→ Java / Spring Boot
→ Docker e infraestrutura
```

---

# `// github.activity`

<div align="center">

<img
height="170"
src="https://github-readme-stats.vercel.app/api?username=JTrallii&show_icons=true&hide_border=true&theme=transparent&locale=pt-br"
/>

<img
height="170"
src="https://github-readme-stats.vercel.app/api/top-langs/?username=JTrallii&layout=compact&hide_border=true&theme=transparent&langs_count=6"
/>

</div>

---

<div align="center">

### `while (learning) { build(); understand(); improve(); }`

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jason_Tralli-0A66C2?style=flat-square\&logo=linkedin)](https://www.linkedin.com/in/jasontralliti/)
[![GitHub](https://img.shields.io/badge/GitHub-JTrallii-181717?style=flat-square\&logo=github)](https://github.com/JTrallii)
[![Email](https://img.shields.io/badge/Email-jtrallii%40live.com-333333?style=flat-square\&logo=microsoftoutlook)](mailto:jtrallii@live.com)

<br/><br/>

**Software não precisa apenas funcionar.
Precisa continuar funcionando quando o sistema evolui.**

</div>

<p align="center">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0ea5e9,100:7c3aed&height=100&section=footer"
  />
</p>
