<pre>
   ___   __  __  ___   __   __ ___   __   ___
  / __| / _|/ _|/ _ \  \ \ / /| __| / /  / _ \
 | (__ |  _|  _| (_) |  \ V / | _| / /__| (_) |
  \___||_| |_|  \___/    \_/  |___|____(_)___/
</pre>

<p align="center">
  <img src="https://raw.githubusercontent.com/sincevoid/sincevoid/main/assets/banner.gif" width="100%" alt="Banner Animado"/>
</p>

# 👋 Olá, Eu Sou João Vitor Silva Teixeira

* **17 anos** | Estudante de Programação
* **Chefe de Marketing** @ MRW Imobiliária (Sorocaba)
* Programador desde **2018**, impactando **22M+ usuários** em projetos de grande escala

---

## 🧑‍💻 Tecnologias

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Java-007396?logo=java&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Lua-2C2D72?logo=lua&logoColor=white" alt="Lua"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white" alt="PHP"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white" alt="Django"/>
  <img src="https://img.shields.io/badge/Discord.js-7289DA?logo=discord&logoColor=white" alt="discord.js"/>
  <img src="https://img.shields.io/badge/WhatsApp--web.js-25D366?logo=whatsapp&logoColor=white" alt="whatsapp-web.js"/>
  <img src="https://img.shields.io/badge/Lua_Frameworks-2F2F2F?logo=lua&logoColor=white" alt="Lua Frameworks"/>
</p>

---

## 📊 Estatísticas

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sincevoid&show_icons=true&theme=radical" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sincevoid&layout=compact&theme=radical" alt="Top Languages"/>
</p>

---

## 🚧 Progresso de Skills e Experiência

| Skill      | Nível       | Experiência                                 |
| ---------- | ----------- | ------------------------------------------- |
| Python     | Excelente ✅ | 6 anos desenvolvendo APIs, automações e IA  |
| JavaScript | Excelente ✅ | 5 anos em front-end, Node.js e bots Discord |
| TypeScript | Excelente ✅ | 4 anos criando aplicações escaláveis        |
| Java       | Excelente ✅ | 4 anos em sistemas corporativos             |
| Lua/Luau   | Excelente ✅ | 5 anos em desenvolvimento de jogos (Roblox) |
| HTML/CSS   | Excelente ✅ | 6 anos em layouts responsivos e Tailwind    |
| PHP        | Excelente ✅ | 4 anos em back-end e CMS personalizados     |

\------------ | --------- |
\| Python       | <progress value="80" max="100"/> |
\| JavaScript   | <progress value="75" max="100"/> |
\| TypeScript   | <progress value="70" max="100"/> |
\| Java         | <progress value="65" max="100"/> |
\| Lua/Luau     | <progress value="60" max="100"/> |
\| HTML/CSS     | <progress value="80" max="100"/> |
\| PHP          | <progress value="50" max="100"/> |

---

## 🎧 Agora Tocado

<p align="center">
  <img src="https://spotify-readme.now.sh/api/spotify" alt="Spotify Now Playing"/>
</p>

---

## 📜 Blog e Publicações

<p align="center">
  <img src="https://github-readme-rss.vercel.app/feed/?url=https://seublog.com/rss&layout=compact" alt="Últimas do Blog"/>
</p>

---

## 📅 Atividade Recente

<p align="center">
  <img src="https://activity-graph.herokuapp.com/graph?username=sincevoid&theme=react-dark" alt="Grafico de Atividade"/>
</p>

---

## 🖼️ Contador de Visitantes

<p align="center">
  <img src="https://visitor-badge.laobi.ren/badge?page_id=sincevoid.sincevoid" alt="Visitor Count"/>
</p>

---

## 💬 Citações Aleatórias

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&language=pt" alt="Random Quote"/>
</p>

---

## 📫 Contato

<p align="center">
  <a href="https://github.com/sincevoid"><img src="https://img.shields.io/badge/GitHub-sincevoid-181717?logo=github&logoColor=white"/></a>
  <a href="https://linkedin.com/in/joaovitor"><img src="https://img.shields.io/badge/LinkedIn-João_Vitor-0A66C2?logo=linkedin&logoColor=white"/></a>
</p>

---

<details>
<summary>⚙️ Configuração de Workflows</summary>

Para ativar os widgets acima, adicione estes workflows em `.github/workflows/`:

```yaml
# spotify.yml
name: Update Spotify Now Playing
on:
  schedule:
    - cron: '*/5 * * * *'
jobs:
  update_spotify:
    runs-on: ubuntu-latest
    steps:
      - uses: wbrito/spotify-readme-action@v2
        with:
          client-id: ${{ secrets.SPOTIFY_CLIENT_ID }}
          client-secret: ${{ secrets.SPOTIFY_CLIENT_SECRET }}
          refresh-token: ${{ secrets.SPOTIFY_REFRESH_TOKEN }}
```

```yaml
# blog.yml
name: Update RSS Feed
on:
  schedule:
    - cron: '0 * * * *'
jobs:
  update_rss:
    runs-on: ubuntu-latest
    steps:
      - uses: davesmes/github-readme-rss-action@v1
        with:
          feed-url: https://seublog.com/rss
          file: BLOG.md
```

```yaml
# quotes.yml
name: Update Random Quote
on:
  schedule:
    - cron: '*/30 * * * *'
jobs:
  update_quote:
    runs-on: ubuntu-latest
    steps:
      - name: Fetch Random Quote
        run: |
          curl -s https://api.quotable.io/random?lang=pt > quote.json
          echo "![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&language=pt)" > QUOTE.md
      - name: Commit Quote
        uses: stefanzweifel/git-auto-commit-action@v4
        with:
          commit_message: "✨ Atualizar citação"
```

```yaml
# contributions.yml
name: Update Contribution Graph
on:
  schedule:
    - cron: '0 * * * *'
jobs:
  update_activity:
    runs-on: ubuntu-latest
    steps:
      - uses: ashutosh00710/github-readme-activity-graph@main
        with:
          file: CONTRIBUTION.md
```

</details>
