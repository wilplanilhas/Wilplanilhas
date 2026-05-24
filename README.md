<div align="center">

<img src="https://i.pinimg.com/originals/7b/4c/4c/7b4c4c1c1d2a8c0c3f7f4f3f4d4b4b4.gif" width="100%" />

# 🦇 Willyan Gabriel 🦇

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&pause=1000&color=8B0000&center=true&vCenter=true&width=600&lines=Desenvolvedor+Iniciante;Dark+Code+Creator;Apaixonado+por+tecnologia;Welcome+to+the+dark+side..." />

</div>

---

# 🌑 Sobre Mim

```txt
💀 Desenvolvedor iniciante
🖤 Estilo gótico
⚡ Aprendendo programação
🎮 Gamer
🌙 Dark aesthetic

.github/workflows/snake.yml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"

  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: WillyanGabriel
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}