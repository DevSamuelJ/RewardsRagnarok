
# 🎮 CB Games - Personalização de Personagens

Sistema de personalização de personagens com autenticação (login e senha), desenvolvido para a empresa **CB Games**. Este projeto permite aos usuários criar e personalizar seus próprios personagens, salvando suas escolhas de forma segura e acessível.

---

## 🚀 Funcionalidades

- ✅ Cadastro e login de usuários
- ✅ Autenticação segura com senha criptografada
- ✅ Personalização de atributos:
  - Força
  - Inteligência
  - Cor de pele
  - Cabelo
  - E outros
- ✅ Armazenamento dos personagens personalizados
- ✅ Interface intuitiva e responsiva
- ✅ Empacotamento da aplicação como um executável (.exe, .dmg, .AppImage)

---

## 🛠️ Tecnologias Utilizadas e Motivações

| Tecnologia   | Função no Projeto  | Motivação                                           |
|---------------|---------------------|-----------------------------------------------------|
| **Node.js**   | Backend             | Ambiente rápido e escalável para APIs em JavaScript. Permite executar JS no servidor. |
| **Express.js**| Framework Backend   | Facilita criação de rotas, middleware e estruturação da API de forma simples e produtiva. |
| **MySQL**     | Banco de Dados      | Banco relacional robusto, ideal para armazenar usuários, senhas e dados dos personagens. |
| **React.js**  | Frontend            | Criação de interfaces reativas, rápidas e modernas. Facilita o desenvolvimento de UIs dinâmicas. |
| **Tailwind CSS** | Estilização UI   | Framework utilitário que acelera a construção de layouts responsivos e modernos, com classes direto no JSX. |
| **Electron.js**| Empacotamento Desktop | Transforma a aplicação web em um programa executável (.exe, .dmg, .AppImage), como solicitado no briefing. |

---

## 📁 Estrutura do Projeto

```
cbgames-app/
├── backend/         # API com Node.js + Express + MySQL
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
│
├── frontend/        # Interface com React + Tailwind
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.js
│   │   └── index.js
│
├── desktop/         # Electron para empacotamento
│   └── main.js
│
└── README.md        # Este arquivo
```

---

## 🔐 Segurança

- Senhas protegidas com hash usando `bcrypt`.
- Tokens JWT para autenticação segura nas rotas protegidas.
- Proteção contra SQL Injection com prepared statements ou ORM.

---

## 📦 Como Executar o Projeto

### Pré-requisitos:
- Node.js instalado
- MySQL instalado

### Passos:

1. Clone este repositório:
   ```
   git clone https://github.com/DevSamuelJ/RewardsRagnarok.git
   ```

2. Instale as dependências do backend:
   ```
   cd backend
   npm install
   ```

3. Instale as dependências do frontend:
   ```
   cd ../frontend
   npm install
   ```

4. Rode o backend:
   ```
   cd ../backend
   node server.js
   ```

5. Rode o frontend:
   ```
   cd ../frontend
   npm run dev
   ```

6. Empacote com Electron (opcional para gerar executável):
   ```
   cd ../desktop
   npm install
   npm start
   ```

---

## 🧠 Considerações Finais

Este projeto foi desenvolvido com foco em atender às necessidades descritas no briefing da **CB Games**, garantindo:

- Segurança de dados
- Interface moderna e fácil de usar
- Portabilidade como programa de computador (executável)

---

## ✨ Autor

**Samuel J**
