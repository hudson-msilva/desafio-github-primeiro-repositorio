## Desafio de Projeto da DIO sobre Git/GitHub

---

### Descrição do Projeto

Consiste em criar o primeiro *repositório* no **GitHub** para versionar o projeto. Abaixo estão relacionadas as ações realizadas para concluir o desafio de projeto da DIO.

### Ações Realizadas

1. Configurar usuário e e-mail (obrigatório serem os mesmos utilizados na conta do GitHub)

   ```PowerShell
    $ git config --global user.email "<e-mail>"
    $ git config --global user.name "<userName>"
   ```
2. Criar um repositório no GitHub e depois clona-lo para um diretório de Projetos (utilizando o Windows)

  ```PowerShell
    $ cd C:\Users\<userName>\Projetos
    $ git clone https://github.com/<userName>/<repositorio>
  ```
3. Criar um arquivo README.md

  ```PowerShell
    $ cd <repositorio>
    $ New-Item README.md
  ```

4. Realizar edição do arquivo existente (utilizando o Visual Studio Code)

  ```PowerShell
    $ code .
  ```
5. Adicionar as alterações ao repositório local

  ```PowerShell
    $ git add README.md
  ```
6. Fazer o Commit das alterações

  ```PowerShell
    $ git commit -m "<commit>"
  ```
7. Subir as alterações para o repositório no GitHub

  ```PowerShell
    $ git push origin main
  ```

> Após as ações serem realizadas o *desafio de projeto* estará finalizado.

---

### Links Úteis
[Guia Básico de Markdown](https://www.markdownguide.org/)

[Git - Documentação](https://git-scm.com/doc)

---