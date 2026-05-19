<div align="center">
  
# 🌿Eco'S (Ecoando Sustentabilidade)
**O Futuro da Sustentabilidade Gamificada**

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=3ECF8E)](https://supabase.com/)

Um ecossistema interativo que recompensa você por cuidar do planeta. Compartilhe o bem, engaje com a natureza e torne-se uma lenda viva da Terra. 🌎✨

[Explorar o Projeto](#-funcionalidades) · [Reportar Bug](https://github.com/seu-usuario/Ecos-Projeto-Integrador/issues) · [Solicitar Feature](https://github.com/seu-usuario/Ecos-Projeto-Integrador/issues)

</div>

---

## 📖 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Sistema de Gamificação](#-sistema-de-gamificação)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Começar (Instalação)](#-como-começar)
- [Como Contribuir](#-como-contribuir)
- [Licença](#-licença)

---

## 🌍 Sobre o Projeto

O **EcoNexus** (ou *Eco'S*) é mais do que um simples projeto: é uma plataforma social voltada inteiramente para o meio ambiente. Através de um design moderno (Dark Mode com tons de verde e azul neon) e uma experiência gamificada, nosso objetivo é engajar usuários em ações ecológicas. Seja lendo notícias sustentáveis, relatando incidentes que agridem o meio ambiente ou aprendendo através de mini-desafios, aqui você é recompensado por fazer a sua parte.

---

## 🚀 Funcionalidades

> Uma plataforma rica e desenhada para o máximo de interação e performance.

- 📊 **Dashboard Pessoal**: Seu centro de comando. Acompanhe sua carteira de `EcoS` (moeda virtual), nível atual, progresso para o próximo rank e missões ativas.
- 📰 **Eco'S FEED+**: Uma timeline interativa com notícias do mundo verde. Ganhe conhecimento e engaje (curta, ame ou envie ideias nos posts).
- 🚨 **Patrulha Ativa**: Encontrou lixo descartado irregularmente? Um foco de queimada? Tire uma foto e poste as evidências em tempo real com localização.
- 🤖 **Chatbot Inteligente**: Um assistente virtual ecológico (IA) para tirar todas as suas dúvidas sobre reciclagem e sustentabilidade diária.
- 🎮 **Arena de Desafios**: Um espaço com minigames e quizzes educacionais focados na vida na Terra.
- 🎯 **Eventos e Missões Sazonais**: Ganhe *Boosts* de XP ao concluir desafios práticos temporários.

---

## 🎮 Sistema de Gamificação

Para manter a comunidade ativa, implementamos recompensas diretas:

| Recompensa | Como Funciona |
| :--- | :--- |
| 🟢 **EcoS** | A moeda do sistema. Você a adquire engajando-se na plataforma e pode gastá-la para publicar suas próprias notícias (-50 EcoS). |
| ⚡ **XP (Experiência)** | Ganha ao completar missões. Serve para você subir de nível de forma vitalícia. |
| 🏆 **Sistema de Ranks** | Seu status reflete sua jornada. Comece como `Semente Curiosa 🌱` e evolua até se tornar uma `Lenda Viva da Terra 🌍✨`. |

---

## 🛠️ Tecnologias Utilizadas

A stack foi cuidadosamente escolhida para fornecer uma interface **Premium**, responsiva e veloz:

### Front-end
- **[React 18](https://react.dev/)** + **[TypeScript](https://www.typescriptlang.org/)**: Tipagem estática e componentização moderna.
- **[Vite](https://vitejs.dev/)**: Para um ambiente de desenvolvimento ultra rápido.
- **[Tailwind CSS](https://tailwindcss.com/)**: Construção de um design system complexo e responsivo via classes utilitárias.
- **[Framer Motion](https://www.framer.com/motion/)**: Micro-interações, efeitos de hover avançados e animações de transição de páginas.
- **[Shadcn/UI](https://ui.shadcn.com/)** & **Radix UI**: Componentes robustos e acessíveis de alta qualidade.
- **[Lucide React](https://lucide.dev/)**: Ícones minimalistas e elegantes.

### Back-end & Infraestrutura
- **[Supabase](https://supabase.com/)**: O coração dos dados e autenticação.
  - Banco de Dados (PostgreSQL) robusto e em tempo real.
  - Storage para hospedagem de fotos da Patrulha Ativa e imagens de Notícias.

---

## ⚙️ Como Começar

Siga os passos abaixo para rodar o projeto localmente em sua máquina.

### Pré-requisitos
* Node.js (v18.x ou superior)
* npm, yarn ou bun

### Instalação

1. Clone o repositório
   ```sh
   git clone https://github.com/seu-usuario/Ecos-Projeto-Integrador.git
   ```
2. Entre no diretório
   ```sh
   cd Ecos-Projeto-Integrador
   ```
3. Instale os pacotes necessários
   ```sh
   npm install
   ```
4. **Variáveis de Ambiente**: Crie um arquivo `.env` na raiz e preencha com as suas credenciais do Supabase:
   ```env
   VITE_SUPABASE_URL=https://sua-url-aqui.supabase.co
   VITE_SUPABASE_ANON_KEY=sua-anon-key-aqui
   ```
   *(Nota: O projeto exige as tabelas no Supabase: `profiles`, `games`, `newsfeed`, `reactions`, `newscomments`, `reports`)*

5. Rode a aplicação
   ```sh
   npm run dev
   ```

6. Abra [http://localhost:5173](http://localhost:5173) no seu navegador.

---

## 🤝 Como Contribuir

Toda e qualquer ajuda é fundamental para evoluirmos este ecossistema! 

1. Faça um **Fork** do projeto
2. Crie uma **Branch** para sua Feature (`git checkout -b feature/NovaFeatureIncrivel`)
3. Adicione suas mudanças (`git add .`)
4. Faça o **Commit** (`git commit -m 'feat: adicionando NovaFeatureIncrivel'`)
5. Faça o **Push** para a branch (`git push origin feature/NovaFeatureIncrivel`)
6. Abra um **Pull Request**

---

## 📝 Licença

Este projeto é desenvolvido para fins educacionais (Projeto Integrador). Licença MIT aplicável para contribuições open-source.

---
<div align="center">
  <br />
  <p>Feito com 💚 pela equipe do Projeto Integrador para um mundo mais sustentável.</p>
</div>
