# SEJA BEM VINDO
# Mobile Software Enginner
          
<div align="center">
  <a href="https://github.com/Lukazi19">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Lukazi19&show_icons=true&theme=transparent&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lukazi19&layout=compact&langs_count=7&theme=transparent"/>
</div>
  
 <div style="display: inline_block"><br>
    <img align="center" alt="Rafa-Js" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"/>
    <img align="center" alt="Rafa-Js" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg"/>
    <img align="center" alt="Rafa-Js" height="35" width="35" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg"/>
</div>
  
  ##
 
<div> 
<a href="https://www.instagram.com/luk4zi7/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href = "mailto:lucasflorencio876@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/lucas-florencio-91864b222" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
          
      
- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
