# BK Control FrontEnd

> Interface web do sistema **Informatizando Processos BK** — front-end da Bread King Londrina (ACK Comércio de Alimentos Ltda).

---

## 📋 Sobre o Projeto

O **BK Control FrontEnd** é a interface de usuário do sistema operacional da Bread King Londrina. Desenvolvido em React, funciona em **computadores e smartphones** com navegação simples e intuitiva, substituindo listas impressas e pranchetas por uma solução digital acessível pelo navegador.

---

## 🚀 Funcionalidades

- **Login e Autenticação** — Acesso seguro via JWT.
- **Check-list de Tarefas** — Visualização, marcação e acompanhamento de tarefas diárias por colaborador.
- **Listas de Reposição** — Criação e compartilhamento de listas, com destaque visual para produtos em falta.
- **Contagem de Estoque** — Registro de contagem para loja e câmara fria, com quantidade e validade por produto.
- **Alertas de Validade** — Destaque visual para produtos com vencimento em **15 dias** e **30 dias**.
- **Painel da Gerente** — Visão consolidada de tarefas, estoque, reposição e desempenho dos colaboradores.

---

## 🛠️ Tecnologias

| Camada | Tecnologia |
|---|---|
| Framework | React |
| Comunicação com API | Axios / Fetch (HTTPS) |
| Autenticação | JWT |

---

## ⚙️ Pré-requisitos

- Node.js 18+
- npm ou yarn
- BK Control API rodando e acessível

---

## 🔧 Instalação e Configuração

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/bk-control-frontend.git
cd bk-control-frontend

# Instale as dependências
npm install

# Configure a URL da API
cp .env.example .env
# Edite o .env:
# VITE_API_URL=https://sua-api-url.com

# Inicie o servidor de desenvolvimento
npm run dev
```

---

## 🏗️ Estrutura de Pastas

```
bk-control-frontend/
└── src/
    ├── components/     # Componentes reutilizáveis
    ├── pages/          # Telas da aplicação
    │   ├── Login/
    │   ├── Tasks/
    │   ├── Restock/
    │   ├── Inventory/
    │   └── Dashboard/
    ├── services/       # Chamadas à API
    ├── context/        # Contexto de autenticação
    └── utils/          # Funções auxiliares
```

---

## 📱 Compatibilidade

| Dispositivo | Suporte |
|---|---|
| Smartphone | ✅ |
| Tablet | ✅ |
| Computador / Notebook | ✅ |

Navegadores suportados: Chrome, Firefox, Edge e Safari (versões modernas).

---

## 👥 Telas por Perfil

| Perfil | Telas |
|---|---|
| **Colaborador** | Login, Tarefas, Reposição, Contagem de Estoque |
| **Gerente** | Login, Tarefas, Reposição, Contagem, Alertas de Validade, Painel, Gestão de Usuários |

---

## 🔗 Repositório da API

[bk-control-api](https://github.com/seu-usuario/bk-control-api)

---

## 📄 Licença

Confidencial © Bread King Londrina (ACK Comércio de Alimentos Ltda) 2026. Todos os direitos reservados.
