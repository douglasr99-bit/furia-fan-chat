# 🦁 FURIA Fan Chat

Um chat em tempo real para torcedores da FURIA interagirem, reagirem a mensagens e acompanharem destaques com um bot de vídeos automático.

![preview](public/background.png)

---

## 🚀 Funcionalidades

- 💬 Salas temáticas: `Sala de Torcida` e `Highlights`
- 🎯 Reações nas mensagens: 👍 🖤 🔥
- 🟢 Contagem de usuários online por sala
- 🤖 Bot automático que envia vídeos na sala Highlights
- 🎨 Interface temática com identidade visual da FURIA

---

## 🧱 Tecnologias Utilizadas

| Frontend               | Backend                      |
|------------------------|------------------------------|
| React + TailwindCSS    | Node.js + Express + Socket.IO|
| Vite                   | Bot de vídeos via JS puro    |

---

## 📦 Instalação Local

### Clone o projeto
```bash
git clone https://github.com/seu-usuario/furia-fan-chat.git
cd furia-fan-chat
```

### Instale o frontend
```bash
cd client
npm install
npm run dev
```

### Em outro terminal, instale o backend
```bash
cd server
npm install
node server.js
```

---

## 🌐 Deploy

- Frontend hospedado via [Netlify](https://netlify.com)
- Backend pode ser hospedado via [Render](https://render.com) ou localmente
- Certifique-se de usar CORS no `server.js`:
```js
cors: {
  origin: 'https://seusite.netlify.app',
  methods: ['GET', 'POST']
}
```

---

## ✍️ Autor

Desenvolvido por [Seu Nome](https://github.com/seu-usuario) para o **Challenge FURIA**.