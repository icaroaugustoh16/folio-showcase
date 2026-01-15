# 🛠️ Stack Tecnológica do Folio

> Uma visão geral das tecnologias utilizadas no desenvolvimento do Folio.

---

## 📱 Mobile App

O aplicativo mobile foi construído com foco em **performance** e **experiência nativa**.

### Core

| Tecnologia | Versão | Descrição |
|------------|--------|-----------|
| **React Native** | 0.81 | Framework para apps nativos |
| **Expo** | SDK 54 | Plataforma de desenvolvimento |
| **TypeScript** | 5.8 | Tipagem estática |

### Navegação

| Tecnologia | Uso |
|------------|-----|
| **React Navigation** | Navegação entre telas |
| **Material Top Tabs** | TabBar com swipe |
| **Native Stack** | Transições nativas |

### Estado & Data Fetching

| Tecnologia | Uso |
|------------|-----|
| **React Query (TanStack)** | Cache, sync e fetching |
| **Context API** | Estado global (Auth, Toast, Timer) |
| **AsyncStorage** | Persistência local |

### UI & Estilo

| Tecnologia | Uso |
|------------|-----|
| **StyleSheet** | Estilos nativos otimizados |
| **Expo Vector Icons** | Ícones (Feather, Ionicons) |
| **React Native SVG** | Logos e ilustrações |
| **Google Fonts** | Playfair Display + Inter |

### Gestos & Animações

| Tecnologia | Uso |
|------------|-----|
| **React Native Gesture Handler** | Swipe, pan, tap |
| **Animated API** | Animações fluidas |
| **PanResponder** | Gestos customizados |

---

## 💻 Web App

O frontend web compartilha a mesma filosofia de design.

| Tecnologia | Descrição |
|------------|-----------|
| **React** | Biblioteca UI |
| **TypeScript** | Tipagem estática |
| **TailwindCSS** | Estilização utility-first |
| **React Query** | Data fetching |

---

## 🔧 Backend API

API RESTful robusta e escalável.

### Core

| Tecnologia | Descrição |
|------------|-----------|
| **Node.js** | Runtime JavaScript |
| **Express** | Framework HTTP |
| **TypeScript** | Tipagem no servidor |

### Banco de Dados

| Tecnologia | Descrição |
|------------|-----------|
| **PostgreSQL** | Banco relacional principal |
| **Prisma** | ORM type-safe |

### Autenticação & Segurança

| Tecnologia | Descrição |
|------------|-----------|
| **JWT** | Tokens de acesso |
| **bcrypt** | Hash de senhas |
| **OAuth 2.0** | Login social (Google) |

### Integrações

| Serviço | Uso |
|---------|-----|
| **Google Calendar API** | Sincronização de eventos |
| **Todoist API** | Importação de tarefas (planejado) |
| **Notion API** | Conexão com databases (planejado) |

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

## 📦 Principais Dependências (Mobile)

```json
{
  "react-native": "0.81.5",
  "expo": "~54.0.0",
  "typescript": "^5.8.3",
  "@tanstack/react-query": "^5.90.16",
  "@react-navigation/native": "^7.1.27",
  "react-native-gesture-handler": "~2.28.0",
  "axios": "^1.13.2",
  "date-fns": "^4.1.0"
}
```

---

## 🎨 Design System

### Tipografia

| Fonte | Uso |
|-------|-----|
| **Playfair Display** | Títulos, números grandes |
| **Inter** | Corpo de texto, labels |

### Paleta de Cores

| Nome | Hex | Uso |
|------|-----|-----|
| **Terracota** | `#B8860B` | Cor primária/accent |
| **Off-White** | `#FAF9F6` | Background principal |
| **Charcoal** | `#2B2826` | Texto primário |
| **Sand** | `#E8E4DD` | Bordas, divisores |

### Princípios

- **Minimalismo** - Menos elementos, mais foco
- **Conforto visual** - Cores quentes, espaçamento generoso
- **Consistência** - Mesma linguagem visual em todas as telas

---

## 🧪 Testes

| Ferramenta | Uso |
|------------|-----|
| **Jest** | Testes unitários |
| **React Testing Library** | Testes de componentes |

---

## 📱 Plataformas Suportadas

| Plataforma | Status |
|------------|--------|
| **Android** | ✅ Suportado (API 21+) |
| **iOS** | ✅ Suportado (iOS 13+) |
| **Web** | ✅ Suportado |

---

## 🚀 DevOps & Deploy

| Serviço | Uso |
|---------|-----|
| **GitHub** | Versionamento de código |
| **EAS Build** | Build de apps mobile |
| **Expo Go** | Desenvolvimento local |

---

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"/>
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" alt="Prisma"/>
</p>

---

<p align="center">
  <i>Construído com ❤️ e muito ☕</i>
</p>
