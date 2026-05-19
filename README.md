<div align="center">
  <img src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=1200&auto=format&fit=crop" alt="EcoNexus Banner" width="100%" style="border-radius: 15px; margin-bottom: 20px;" />

  # 🌿 EcoNexus (Eco'S)
  **Projeto Integrador - O Futuro da Sustentabilidade Gamificada**

  <p align="center">
    <a href="#-funcionalidades">Funcionalidades</a> • 
    <a href="#-sistema-de-gamificação">Gamificação</a> • 
    <a href="#️-tecnologias-utilizadas">Tech Stack</a> • 
    <a href="#️-como-executar-o-projeto-localmente">Instalação</a>
  </p>

  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://vitejs.dev/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=3ECF8E)](https://supabase.com/)

</div>

<br />

> **EcoNexus** é uma plataforma interativa e gamificada focada em sustentabilidade e conscientização ambiental. O objetivo do projeto é engajar usuários através de um sistema de recompensas (EcoS e XP), permitindo que compartilhem notícias, reportem incidentes ambientais e aprendam sobre preservação de maneira divertida e colaborativa.

---

## 🚀 Funcionalidades

- 📊 **Dashboard Gamificado**: Perfil de usuário dinâmico com sistema de níveis, experiência (XP) e ranks (ex: *Semente Curiosa 🌱* até *Lenda Viva da Terra 🌍✨*).
- 📰 **Eco'S FEED+ (Feed de Notícias)**: Espaço para leitura e compartilhamento de notícias sobre o meio ambiente, energia limpa, clima e inovação. Os usuários podem reagir (curtir, amar, ideia) e comentar. Publicar uma nova notícia consome *EcoS* (moeda virtual do sistema).
- 🚨 **Patrulha Ativa (Denúncias)**: Sistema de monitoramento de incidentes em tempo real. Os usuários podem reportar problemas ambientais enviando fotos (evidências), descrição e localização.
- 🤖 **Chatbot Sustentável**: Assistente virtual integrado (IA) para ajudar e tirar dúvidas sobre práticas ecológicas no dia a dia.
- 🎮 **Arena de Desafios (Minigames)**: Seção de jogos educativos e desafios competitivos que recompensam o usuário com XP e EcoS.
- 🎯 **Missões Sazonais**: Desafios contínuos, como engajar com publicações do feed, que incentivam a participação ativa na plataforma em troca de recompensas.

---

## 🎮 Sistema de Gamificação

A plataforma foi projetada para incentivar boas ações através de um sistema de evolução do usuário:

| Recompensa | Como Funciona |
| :--- | :--- |
| 🟢 **EcoS** | Moeda virtual ganha ao realizar ações sustentáveis ou interagir na plataforma. Utilizada para ações premium, como publicar notícias (-50 EcoS). |
| ⚡ **XP e Níveis** | A participação na comunidade rende XP. Ao acumular XP, o usuário sobe de nível e alcança novos ranks, destacando seu nível de "Guardião da Natureza". |

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído com foco em performance e interface premium, utilizando o seguinte ecossistema:

- **React 18**
- **TypeScript** (Tipagem estática e segurança)
- **Vite** (Ferramenta de build super rápida)
- **Tailwind CSS** (Estilização de alta performance e design responsivo)
- **Framer Motion** (Animações fluidas, dinâmicas e micro-interações)
- **Shadcn/UI & Radix UI** (Componentes de interface acessíveis e customizáveis)
- **Supabase** (Backend as a Service - Autenticação, Banco de Dados PostgreSQL e Storage)
- **React Router Dom** (Roteamento da aplicação)
- **React Query** (Gerenciamento de cache e estado de requisições)
- **Lucide React** (Biblioteca de ícones)

---

## ⚙️ Como executar o projeto localmente

### Pré-requisitos
- Node.js (versão 18 ou superior recomendada)
- npm, yarn ou bun

### Passo a passo

1. **Clone o repositório**
```sh
git clone https://github.com/seu-usuario/Ecos-Projeto-Integrador.git
```

2. **Acesse o diretório do projeto**
```sh
cd Ecos-Projeto-Integrador
```

3. **Instale as dependências**
```sh
npm install
```

4. **Configuração de Variáveis de Ambiente**
Crie um arquivo `.env` na raiz do projeto contendo as chaves de conexão do **Supabase**:
```env
VITE_SUPABASE_URL=sua_url_do_supabase
VITE_SUPABASE_ANON_KEY=sua_anon_key_do_supabase
```
> *(Nota: Certifique-se de configurar as tabelas no Supabase: `profiles`, `games`, `newsfeed`, `reactions`, `newscomments` e `reports`)*

5. **Inicie o servidor de desenvolvimento**
```sh
npm run dev
```

6. Acesse o sistema através do navegador na porta fornecida (geralmente `http://localhost:5173`).

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para melhorar o projeto, siga os passos:

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/IncrivelFeature`)
3. Faça o Commit de suas mudanças (`git commit -m 'feat: Add some IncrivelFeature'`)
4. Faça o Push para a Branch (`git push origin feature/IncrivelFeature`)
5. Abra um Pull Request

---
<div align="center">
  <br />
  <p>Feito com 💚 pela equipe do Projeto Integrador focando na sustentabilidade do nosso planeta.</p>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=10b981&height=120&section=footer" width="100%"/>
</div>
