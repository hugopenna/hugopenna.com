---
layout: post
title: Quebrei o Homebrew
categories:

---

Originalmente esse post seria um pedido de ajuda no gist, mas como consegui descobrir o que tava rolando, resolvi documentar. 

Meu homebrew simplesmente parou de funcionar esses dias, foi durante a instalação do setup de um projeto que eu estava configurando na minha máquina para trabalhar nele, na verdade eu estava ajustando a configuração do ambiente virtual.
Eu estava usando `venv + pip install` e ia usar pela primeira vez pipenv

Não sei em qual momento isso aconteceu, mas o pyenv alterou meu .zshrc com uma alteração de path do homebrew, como eu fiz isso, não faço ideia.

Eu estava escrevendo esse texto para explicar toda a situação e pedir ajuda, até que tentei rodar o homebrew diretamente do diretório
/usr/local/homebrew/bin/brew e passei o comando doctor, que avalia sua instalação e retorna possiveis problemas.

Para a minha surpresa, ele acusava que a configuração estava fora do esperado que era /usr/local e que fiquei surpreso, pq eu tinha acabado de rodar o comando, 
foi ai que resolvi olhar o .zprofile e o .zshrc novamente e vi que a tag que eu tinha pulado, pq começava com `PYENV` alguma coisa, na verdade estava alterando o path do homebrew. 

Então fica o aprendizado, se vc fez a instalação do homebrew padrão no seu macos, então não é esperado que tenha nenhuma configuração do homebrew no seu .zshrc ou .bashrc
