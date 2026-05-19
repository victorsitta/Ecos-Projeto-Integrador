# 🌿 EcoNexus (Eco'S) - Projeto Integrador

**EcoNexus** é uma plataforma interativa e gamificada focada em sustentabilidade e conscientização ambiental. O objetivo do projeto é engajar usuários através de um sistema de recompensas (EcoS e XP), permitindo que compartilhem notícias, reportem incidentes ambientais e aprendam sobre preservação de maneira divertida e colaborativa.

## 🚀 Funcionalidades

- 📊 **Dashboard Gamificado**: Perfil de usuário dinâmico com sistema de níveis, experiência (XP) e ranks (ex: *Semente Curiosa 🌱* até *Lenda Viva da Terra 🌍✨*).
- 📰 **Eco'S FEED+ (Feed de Notícias)**: Espaço para leitura e compartilhamento de notícias sobre o meio ambiente, energia limpa, clima e inovação. Os usuários podem reagir (curtir, amar, ideia) e comentar. Publicar uma nova notícia consome *EcoS* (moeda virtual do sistema).
- 🚨 **Patrulha Ativa (Denúncias)**: Sistema de monitoramento de incidentes em tempo real. Os usuários podem reportar problemas ambientais enviando fotos (evidências), descrição e localização.
- 🤖 **Chatbot Sustentável**: Assistente virtual integrado (IA) para ajudar e tirar dúvidas sobre práticas ecológicas no dia a dia.
- 🎮 **Arena de Desafios (Minigames)**: Seção de jogos educativos e desafios competitivos que recompensam o usuário com XP e EcoS.
- 🎯 **Missões Sazonais**: Desafios contínuos, como engajar com publicações do feed, que incentivam a participação ativa na plataforma em troca de recompensas.

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

## 🎮 Sistema de Gamificação

A plataforma foi projetada para incentivar boas ações através de um sistema de evolução do usuário:
- **EcoS**: Moeda virtual ganha ao realizar ações sustentáveis ou interagir na plataforma. Utilizada para ações premium, como publicar notícias (-50 EcoS).
- **XP e Níveis**: A participação na comunidade rende XP. Ao acumular XP, o usuário sobe de nível e alcança novos ranks, destacando seu nível de "Guardião da Natureza" no dashboard.

## ⚙️ Como executar o projeto localmente

### Pré-requisitos
- Node.js (versão 18 ou superior recomendada)
- npm ou yarn

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
# ou
yarn install
```

4. **Configuração de Variáveis de Ambiente**
Crie um arquivo `.env` na raiz do projeto contendo as chaves de conexão do **Supabase**:
```env
VITE_SUPABASE_URL=sua_url_do_supabase
VITE_SUPABASE_ANON_KEY=sua_anon_key_do_supabase
```
*(Nota: Certifique-se de configurar as tabelas no Supabase: `profiles`, `games`, `newsfeed`, `reactions`, `newscomments` e `reports`)*

5. **Inicie o servidor de desenvolvimento**
```sh
npm run dev
# ou
yarn dev
```

6. Acesse o sistema através do navegador na porta fornecida (geralmente `http://localhost:8080` ou `http://localhost:5173`).

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para melhorar o projeto, siga os passos:

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/IncrivelFeature`)
3. Faça o Commit de suas mudanças (`git commit -m 'feat: Add some IncrivelFeature'`)
4. Faça o Push para a Branch (`git push origin feature/IncrivelFeature`)
5. Abra um Pull Request

---
*Projeto Integrador - Desenvolvido com 💚 focando na sustentabilidade do nosso planeta.*
