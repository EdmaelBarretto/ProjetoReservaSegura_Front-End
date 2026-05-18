# 🎨 Reserva Segura — Front-End

Interface web do aplicativo de educação financeira gamificado **Reserva Segura**, desenvolvido com React + Vite + TailwindCSS.

---

## 🚀 Deploy

| Ambiente | URL |
|---|---|
| **Produção** | https://projeto-reserva-segura-front-end.vercel.app |
| **Local** | http://localhost:5173 |

---

## 🏛️ Informações Acadêmicas

| Campo | Info |
|---|---|
| Instituição | Faculdade Senac Pernambuco |
| Programa | Residência Tecnológica — Porto Digital |
| Empresa Parceira | Bradesco |
| Turma | 2026.1 |
| Squad | 29 |

---

## 👥 Squad 29

| Nome | Papel |
|---|---|
| Agnes Letícia Soares Ribeiro | Front-End |
| Allan Harrison Lemos de Barros Falcão | Front-End |
| Ana Carolina da Silva Santos | Dados |
| Arthur Henrique Silveira de Paula | Design |
| Edmael Paulo Ribeiro Barreto | Back-End / QA |
| Gabriel Gleydson Lima dos Santos | Dados / Gestão |

---

## 📌 Sobre o Projeto

O **Reserva Segura** é uma aplicação web voltada para educação financeira e gestão de metas de poupança. O usuário pode:

- 🏦 Criar **caixinhas** (metas de reserva personalizadas)
- 💰 Realizar **depósitos e saques**
- 📊 Acompanhar seu **progresso**
- 🎯 Completar **missões diárias**
- 🏆 Participar de **ligas e rankings**
- 🛍️ Trocar pontos por **recompensas na loja**
- 📚 Aprender com **lições de educação financeira**

---

## 🛠️ Tecnologias

- React 18
- TypeScript
- Vite 6
- TailwindCSS v4
- Lucide React
- React Slick
- Recharts
- Vercel

---

## 🏗️ Arquitetura

```
[Usuário no navegador]
        ↓
[Front-End — React / Vite]
  localhost:5173 | projeto-reserva-segura-front-end.vercel.app
        ↓  HTTP REST + JWT
[Back-End — Spring Boot]
  localhost:8080 | projetoreservaseguraback-end-production.up.railway.app
        ↓  JPA / Hibernate
[Banco de Dados — PostgreSQL]
  Railway (nuvem)
```

---

## 📂 Estrutura do Projeto

```
src/
├── app/
│   ├── components/
│   │   ├── AuthScreen.tsx       # Telas de login e cadastro
│   │   ├── Boxes.tsx            # Gestão de caixinhas
│   │   ├── DesktopLayout.tsx    # Layout desktop
│   │   ├── Leagues.tsx          # Sistema de ligas
│   │   ├── Lessons.tsx          # Lições educacionais
│   │   ├── ProfileScreen.tsx    # Perfil do usuário
│   │   ├── Shop.tsx             # Loja de recompensas
│   │   └── icons/               # Ícones customizados
│   └── App.tsx                  # Componente principal
├── context/
│   └── AuthContext.tsx          # Contexto de autenticação
├── services/
│   └── api.ts                   # Chamadas à API do backend
├── imports/                     # Assets e imagens
└── styles/                      # Arquivos de estilo
```

---

## 🚀 Como rodar localmente

### Pré-requisitos
- Node.js 18+
- npm

### Passos

```bash
# Clone o repositório
git clone https://github.com/EdmaelBarretto/ProjetoReservaSegura_Front-End.git

# Acesse a pasta
cd ProjetoReservaSegura_Front-End

# Instale as dependências
npm install

# Rode o projeto
npm run dev
```

O front sobe em: `http://localhost:5173`

---

## ⚙️ Variáveis de Ambiente

Crie um arquivo `.env.production` na raiz do projeto:

```
VITE_API_URL=https://projetoreservaseguraback-end-production.up.railway.app
```

Para desenvolvimento local, o projeto usa `http://localhost:8080` por padrão.

> ⚠️ Nunca suba credenciais reais para o GitHub.

---

## 🎨 Tema de Cores

| Cor | Valor |
|---|---|
| Verde Principal | `#618c78` |
| Verde Claro | `#5bb49b` |
| Dourado (Moedas) | `#f59e0b` |
| Texto Escuro | `#101828` |
| Texto Secundário | `#6a7282` |

---

## 📱 Responsividade

- **Mobile**: Layout vertical com navegação inferior
- **Desktop**: Layout com header, sidebar e conteúdo central

---

## 🔗 Repositórios

| Camada | Repositório |
|---|---|
| 🎨 Front-End | https://github.com/EdmaelBarretto/ProjetoReservaSegura_Front-End |
| ⚙️ Back-End | https://github.com/EdmaelBarretto/ProjetoReservaSegura_Back-End |

---

## 📄 Licença

Projeto acadêmico desenvolvido para a Residência Tecnológica Porto Digital — Bradesco 2026.1.

Desenvolvido com pelo **Squad 29** — Residência Tecnológica Porto Digital × Bradesco
