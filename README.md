# 📔 Folio - Productivity & Focus App

<p align="center">
  <img src="screenshots/logo-folio-terracota.svg" alt="Folio Logo" width="120"/>
</p>

<p align="center">
  <b>Um app de produtividade focado em simplicida### 💡 Idealizador & Web Developer

**Derik Martins**  
Criador original do conceito e desenvolvedor da versão Web.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/derik-s-martins/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/derik-martins)xecução.</b><br>
  Inspirado no Sunsama, construído para quem quer fazer mais com menos.
</p>

<p align="center">
  🌐 <b>Web</b> por <a href="https://github.com/derik-martins">Derik Martins</a> · 
  📱 <b>Mobile</b> por <a href="https://github.com/icaroaugustoh16">Ícaro Augusto</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-0.81-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React Native"/>
  <img src="https://img.shields.io/badge/Expo-SDK_54-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo"/>
  <img src="https://img.shields.io/badge/TypeScript-5.8-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/PostgreSQL-16-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/License-MIT-000000?style=flat-square&logo=opensourceinitiative&logoColor=white" alt="MIT License"/>
</p>

---

## 📱 Screenshots

<p align="center">
  <img src="screenshots/home.png" width="180"/>
  <img src="screenshots/focus.png" width="180"/>
  <img src="screenshots/planning.png" width="180"/>
  <img src="screenshots/tags.png" width="180"/>
</p>

<details>
<summary>📸 Ver mais screenshots</summary>
<p align="center">
  <img src="screenshots/login.png" width="180"/>
  <img src="screenshots/register.png" width="180"/>
  <img src="screenshots/create-task.png" width="180"/>
  <img src="screenshots/settings.png" width="180"/>
</p>
<p align="center">
  <img src="screenshots/onboarding-1.png" width="180"/>
  <img src="screenshots/onboarding-2.png" width="180"/>
  <img src="screenshots/onboarding-3.png" width="180"/>
  <img src="screenshots/completed-tasks.png" width="180"/>
</p>
</details>

---

## ✨ Funcionalidades

### 📥 Inbox Inteligente
Capture suas tarefas rapidamente sem interromper seu fluxo de trabalho.
- Criação rápida de tarefas em segundos
- Priorização visual (Alta, Média, Baixa)
- Estimativa de tempo por tarefa

### ⏱️ Modo Foco (Pomodoro)
Timer integrado para sessões de trabalho profundo.
- Sessões de 25 minutos de foco
- Pausas inteligentes (5 min curtas, 15 min longas)
- Vinculação de tarefas ao timer
- Contador de sessões e feedback tátil

### 📅 Planejamento Semanal
Visualize e organize sua semana de forma clara.
- Visão semanal completa
- Arrastar e soltar tarefas entre dias
- Navegação por semanas
- Adição rápida por dia

### 🏷️ Sistema de Tags
Organize suas tarefas por contexto.
- Cores personalizadas
- Múltiplas tags por tarefa
- Filtro visual por cor

### 📊 Estatísticas
Acompanhe seu progresso sem complexidade.
- Tarefas concluídas na semana
- Tempo total focado
- Média de tempo por tarefa

### 🔗 Integrações
| Serviço | Status |
|---------|--------|
| Google Calendar | ✅ Disponível |
| Todoist | 🔜 Em breve |
| Notion | 🔜 Em breve |

---

## 🛠️ Stack Tecnológica

### 📱 Mobile App
| Tecnologia | Versão | Descrição |
|------------|--------|-----------|
| **React Native** | 0.81 | Framework para apps nativos |
| **Expo** | SDK 54 | Plataforma de desenvolvimento |
| **TypeScript** | 5.8 | Tipagem estática |
| **React Query** | 5.x | Cache e data fetching |
| **React Navigation** | 7.x | Navegação entre telas |

### 💻 Web App
| Tecnologia | Descrição |
|------------|-----------|
| **React** | Biblioteca UI |
| **TypeScript** | Tipagem estática |
| **TailwindCSS** | Estilização utility-first |
| **Vite** | Build tool |

### 🔧 Backend API
| Tecnologia | Descrição |
|------------|-----------|
| **Node.js** | Runtime JavaScript |
| **Express** | Framework HTTP |
| **Prisma** | ORM type-safe |
| **PostgreSQL** | Banco relacional |
| **JWT + OAuth 2.0** | Autenticação |

---

## 🏗️ Arquitetura

```
┌─────────────────────────────────────────────────────────┐
│                      CLIENTES                           │
├─────────────────────┬───────────────────────────────────┤
│   📱 Mobile App     │         💻 Web App                │
│   React Native      │         React + Tailwind          │
│   Expo SDK 54       │         Vite                      │
└─────────┬───────────┴───────────────┬───────────────────┘
          │                           │
          └───────────┬───────────────┘
                      │
                      ▼
          ┌───────────────────────┐
          │      🔐 API REST      │
          │   Node.js + Express   │
          │      TypeScript       │
          └───────────┬───────────┘
                      │
                      ▼
          ┌───────────────────────┐
          │   🗄️ PostgreSQL       │
          │      + Prisma ORM     │
          └───────────────────────┘
```

---

## 🎨 Design System

| Aspecto | Detalhes |
|---------|----------|
| **Estética** | Cozy/Premium com tons quentes |
| **Cor Primária** | Terracota `#B8860B` |
| **Background** | Off-White `#FAF9F6` |
| **Tipografia** | Playfair Display (títulos) + Inter (corpo) |
| **Filosofia** | Minimalismo - menos é mais |

---

## 📱 Plataformas Suportadas

| Plataforma | Status | Requisitos |
|------------|--------|------------|
| **Android** | ✅ Suportado | API 21+ |
| **iOS** | ✅ Suportado | iOS 13+ |
| **Web** | ✅ Suportado | Navegadores modernos |

### 🏪 Distribuição (Em breve)

| Loja | Status |
|------|--------|
| **Google Play Store** | 🔜 Planejado |
| **Apple App Store** | 🔜 Planejado |

---

## 🚧 Status & Roadmap

### Status Atual
| Componente | Status |
|------------|--------|
| 📱 Mobile App | 🟢 Em desenvolvimento |
| 💻 Web App | 🟢 Em desenvolvimento |
| 🔧 Backend API | 🟢 Funcional |

### Roadmap
| Feature | Status |
|---------|--------|
| Modo offline | 🔜 Planejado |
| Widgets iOS/Android | 🔜 Planejado |
| Relatórios mensais | 🔜 Planejado |
| Temas personalizados | 🔜 Planejado |
| Modo escuro | 🔜 Planejado |
| Colaboração em equipe | 💭 Considerando |

---

## � Documentação

- [✨ Funcionalidades Detalhadas](docs/features.md)
- [🛠️ Stack Tecnológica](docs/tech-stack.md)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## � Equipe

### � Idealizador & Web Developer

**Derik Martins**  
Criador original do conceito e desenvolvedor da versão Web.

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/derik-martins)

### 📱 Mobile Developer

**Ícaro Augusto**  
Responsável pelo desenvolvimento mobile (iOS & Android) com React Native/Expo.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%C3%ADcaro-augusto-00b567227/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/icaroaugustoh16)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:icarodpvat@gmail.com)

---

<p align="center">
  <i>Este repositório é apenas uma vitrine. O código-fonte é privado.</i>
</p>

<p align="center">
  <i>Construído com ❤️ e muito ☕</i>
</p>
