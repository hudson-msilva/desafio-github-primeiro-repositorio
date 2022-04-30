
# Introdução ao Git e ao GitHub

As informações contidas neste arquivo foram baseadas no conteúdo ministrado no curso Introdução ao Git e ao GitHub na DIO (Digital Innovation One).

## Introdução

***O que é Git?***

Git é um *Sistema de Versionamento de Código* criado por **Linus Torvalds** para ser utilizado no desenvolvimento do *Kernel Linux*.

O Git teve o seu lançamento em 7 de Abril de 2005. Linus Torvalds tomou a iniciativa de criar o seu próprio sistema de versionamento, pois o que ele utilizava na época não estava sendo satisfatório.
Então, para solucionar o problema que estava tendo, decidiu criar o Git.

---

## Comandos Básicos

1. Comando que inicializa um Repositório;

    ``$ git init``

1. Comando utilizado para adicionar arquivos e/ou diretórios ao Repositório;

    ``$ git add``

1. Comando que gera um comentário relacionado ao arquivo ou diretório adicionado ou alteração feita em um arquivo existente;

    ``$ git commit -m <comentário>``

---

## Criando Repositórios

Para criar um novo *Repositório Local* via Terminal no Windows utilizando o **Git Bash** seguiremos os seguintes passos:

1. Criar um diretório

    ``$ mkdir <nome-do-diretório>``

2. Acessar o diretório criado

    ``$ cd <nome-do-diretório>``

3. Torná-lo um Repositório

    ``$ git init``

4. Realizar as configurações globais
    
    * Configuração global de e-mail  

    ``$ git config --global user.email "<user@email.com>"``

    * Configuração global de nome de usuário:
  
    ``$ git config --global user.name "<user-name>"``

    ---