<div align="center">
  <img src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=1200&auto=format&fit=crop" alt="EcoNexus Banner" width="100%" style="border-radius: 15px; margin-bottom: 20px;" />

  # 🌿 EcoNexus (Eco'S)
  
  **A Plataforma Social Gamificada para um Planeta mais Verde**

  <p align="center">
    <a href="#-features">Funcionalidades</a> • 
    <a href="#-gamificação">Gamificação</a> • 
    <a href="#-tecnologias">Tech Stack</a> • 
    <a href="#-instalação">Instalação</a>
  </p>

  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-10b981?style=flat-square&logo=github" alt="Status" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square&logo=opensourceinitiative" alt="License" />
  <img src="https://img.shields.io/badge/Versão-1.0.0-f59e0b?style=flat-square" alt="Version" />
</div>

<br />

> **EcoNexus** transforma a sustentabilidade em uma jornada imersiva. Relate incidentes ambientais, consuma notícias focadas no clima, suba de nível e ajude a comunidade sendo recompensado na *Patrulha Ativa*.

---

<h2 id="-features">✨ Interface & Funcionalidades</h2>

<table width="100%" style="border-collapse: collapse; border: none;">
  <tr>
    <td width="50%" valign="top" style="border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 10px;">
      <h3>📊 Dashboard de Guardião</h3>
      Acompanhe sua carteira de <b>EcoS</b> (nossa moeda verde), veja sua barra de <b>XP</b> subir e conquiste Ranks. Um perfil dinâmico que recompensa suas ações reais e virtuais com micro-interações belíssimas.
    </td>
    <td width="50%" valign="top" style="border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 10px;">
      <h3>📰 Eco'S FEED+</h3>
      Um feed interativo (estilo rede social premium). Ao invés de apenas consumir, você <b>investe</b>. Gastando seus <i>EcoS</i>, você publica notícias sustentáveis, recebendo <i>Likes</i>, <i>Corações</i> e <i>Ideias</i>.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" style="border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 10px;">
      <h3>🚨 Patrulha Ativa</h3>
      Presenciou um crime ambiental ou um foco de queimada? Use nosso <b>monitoramento em tempo real</b>. Envie evidências fotográficas com geolocalização e ative a comunidade instantaneamente.
    </td>
    <td width="50%" valign="top" style="border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 10px;">
      <h3>🤖 Chatbot & Arena</h3>
      Dúvidas sobre reciclagem? Nossa <b>IA assistente</b> te responde. Quer competir? Entre na <b>Arena de Desafios</b> e acumule pontos em minigames educativos voltados para a preservação do planeta.
    </td>
  </tr>
</table>

---

<h2 id="-gamificação">🎮 O Motor Gamificado</h2>

Acreditamos que mudar o mundo pode (e deve) ser viciante e divertido. Nossa economia interna funciona assim:

<div align="center">
  
| Elemento | Ícone | Descrição Técnica & Utilidade |
| :---: | :---: | :--- |
| **EcoS** | 🟢 | A cripto-moeda virtual da plataforma. Taxa de transação para publicações globais custa `-50 EcoS`. |
| **Experiência** | ⚡ | **XP** adquirido ao cumprir *Missões Sazonais* (ex: "Engajar o feed rende +100XP"). |
| **Ranks** | 🏆 | Escalonamento de perfil. Vai do *Nível 1 (Semente Curiosa 🌱)* ao *Nível 50+ (Lenda Viva da Terra 🌍✨)*. |

</div>

#### Mockup de Progresso da Interface
```text
Semente Curiosa 🌱   [████████░░░░░░░░░░░░]   450 / 1000 XP
```

---

<h2 id="-tecnologias">💻 Tech Stack Premium</h2>

Toda a fundação foi construída para entregar uma interface impecável: **Dark Mode nativo**, **Glassmorphism**, animações fluidas e feedback em tempo real.

<div align="center">

| Core & Framework | UI & Estilização | Autenticação & Nuvem |
| :---: | :---: | :---: |
| <img src="https://skillicons.dev/icons?i=react,ts,vite" /><br><b>React 18 + TS + Vite</b> | <img src="https://skillicons.dev/icons?i=tailwind" /><br><b>Tailwind + Framer Motion</b> | <img src="https://skillicons.dev/icons?i=supabase,postgres" /><br><b>Supabase + PostgreSQL</b> |

*(Design System potenciado por **shadcn/ui** e ícones por **Lucide React**)*
</div>

---

<h2 id="-instalação">🚀 Inicialização Rápida</h2>

Quer testar a aplicação no seu ambiente e sentir a interface na prática?

<details>
<summary><b>🔥 Clique aqui para abrir as instruções detalhadas</b></summary>
<br>

**1. Clone o repositório**
```bash
git clone https://github.com/seu-usuario/Ecos-Projeto-Integrador.git
cd Ecos-Projeto-Integrador
```

**2. Instale as dependências via NPM**
```bash
npm install
```

**3. Configure o Banco de Dados (Supabase)**
Crie um arquivo `.env` na raiz do seu projeto com as suas credenciais:
```env
VITE_SUPABASE_URL="sua_url_aqui"
VITE_SUPABASE_ANON_KEY="sua_key_aqui"
```
> **⚠️ Importante:** O funcionamento depende das tabelas no backend: `profiles`, `games`, `newsfeed`, `reactions`, `newscomments` e `reports`.

**4. Dê o play no servidor de desenvolvimento**
```bash
npm run dev
```
Acesse: [http://localhost:5173](http://localhost:5173) no seu navegador.

</details>

---

<div align="center">
  
## 🤝 Junte-se à Revolução Verde

Sinta-se à vontade para realizar um **Fork**, criar a sua branch de **Feature** e abrir um **Pull Request**. O mundo precisa do seu código!

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=10b981&height=120&section=footer" width="100%"/>

*Projeto Integrador - 2026*
</div>
