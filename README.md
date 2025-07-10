# 🧠 NLW Agents - App com IA Autônoma

Este projeto foi desenvolvido durante o **NLW Agents** da [Rocketseat](https://rocketseat.com.br), sob a mentoria de Diego Fernandes. O objetivo é criar uma aplicação que utiliza **agentes de IA generativa** para atuar de forma autônoma, integrando com tecnologias modernas como **Next.js, React, TailwindCSS e IA via OpenAI API**.

---

## 🚀 Tecnologias Utilizadas

- [React.js](https://reactjs.org)
- [Next.js](https://nextjs.org)
- [Tailwind CSS](https://tailwindcss.com)
- [LangChain](https://js.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [TypeScript](https://www.typescriptlang.org/)

---

## 🧩 Funcionalidades

- 🔍 Criação de **Agentes de IA** capazes de pensar, planejar e agir.
- 🤖 Chat com **inteligência artificial** treinada em tarefas específicas.
- 🔄 Comunicação entre múltiplos agentes.
- 📦 Backend via Server Actions do Next.js (sem API REST).
- 🌐 UI moderna com Tailwind e componentes reativos.

---

## 📁 Estrutura do Projeto

```bash
├── app
│   └── page.tsx        # Página principal
├── components
│   └── AgentCard.tsx   # Cartão de cada agente
├── lib
│   └── agents.ts       # Funções de IA com LangChain
├── actions
│   └── chat.ts         # Server action para IA
├── public
├── styles
│   └── globals.css
└── ...
