## Oi, aqui é a T-1000... ops...Tay! 👋

<div align="center"> 
<img src="https://static.doomworld.com/monthly_2020_06/tumblr_07903323f018c59fca84196da40bc717_3f29893c_500.gif.145407ece02c03995b2bfcf62695c588.gif" width="500px" />
</div>

## Escritora, Criadora de Conteúdo e DEV Iniciante! 😎​🤓​
Comecei minha jornada para o Lado Nerd da Força desde a infância ao descobrir os jogos da Nintendo. Hoje sou formada em letras-Inglês pela UFPI e atualmente estou a aprender programação.

name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  

<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Rafa-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="Rafa-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  
</div> 

## Meu Status no GitHub
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=tayprogrammer&show_icons=true&theme=onedark)
## Minhas Redes Sociais
<div> 
  <a href="https://www.youtube.com/@aprofessoraoficial" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>
  <a href="https://www.instagram.com/aprofessoratutoriais/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 	<a href="https://www.facebook.com/taynara.pereirabr/" target="_blank"><img src="https://img.shields.io/badge/Facebook-Connect-brightgreen?style=for-the-badge&labelColor=black&logo=facebook" target="_blank"></a>
 <a href="https://www.tiktok.com/@aprofessoraoficial" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/Tiktok-logo?style=for-the-badge&labelColor=blank&color=black"
></a> 
</div>
