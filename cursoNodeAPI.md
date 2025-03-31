# Curso criando API com Node, MongoDB e Express

  

Esse MarkDown foi criado para documentar códigos, bibliotecas e o que for interessante na criação de uma API.

  

## Sumário

- [node - Instalando o Node.js](#node.js)
- [npm](#npm)
- [yarn - Instalando o yarn](#yarn)
- [express - instalando o express](#express)
- [insomia - instalando o insomnia](#insomnia)
- [eslint - Padronizando código](#eslint)
- [criando uma api](#api)

  
  

  

## node.js

Acesse o site: https://nodejs.org/ e baixe a versão LTS, essa é versão mais estável do Node.js

  

```markdown
cmd

node -v
```

[Voltar ao topo](#sumário)

  

## npm

O **npm** (Node Package Manager) é o gerenciador de pacotes padrão para o ambiente de execução JavaScript **Node.js**. Ele é usado para gerenciar pacotes (bibliotecas ou ferramentas) que podem ser facilmente instalados e compartilhados dentro de projetos JavaScript. Para atualizar o npm, caso esteja em uma versão desatualizada, digite no `cmd` o seguinte código:

  

```markdown
cmd

npm install -g npm
```

  

[Voltar ao topo](#sumário)

  
  

## yarn

É um gerenciador de pacotes e sua instalação pode ser feita através de:

```markdown
cmd

npm install --global yarn
yarn -v
```

[Voltar ao topo](#sumário)

## express

O Express.js é um framework para Node.js que facilita a criação de aplicações web e APIs. Ele fornece um conjunto robusto de funcionalidades para desenvolver servidores web de maneira rápida e eficiente.
Dentro do diretório do projeto digite o seguinte código:

```markdown
cmd

yarn add express
```

  [Voltar ao topo](#sumário)
  
  ## insomania
  O  **Insomnia**  é uma  **ferramenta de desenvolvimento de API e cliente REST**  criada pela Kong. Ele foi projetado para simplificar o processo de construção e teste de APIs, tornando-o mais eficiente e produtivo para desenvolvedores. O Insomnia facilita o teste e a experimentação de APIs, sendo amigável o suficiente para qualquer pessoa começar a utilizá-lo.
 Poderá ser instalado pelo site:
  https://insomnia.rest/

## eslint

  

yarn add eslint -D - Biblioteca para fazer alterações no código

  

yarn eslint --init - Inicializa a biblioteca (Geralmente utiliza-se o padrão airbnb)

  

[Voltar ao topo](#sumário)

## api
Para criar uma API você abrirá o repositório pelo cmd e digitará o seguinte comando 

```markdown
cmd

yarn init -y
```
Dentro do VScode será criada uma pasta com um arquivo package.json que será onde todas as informações e dependências das bibliotecas serão utilizadas no projeto, no início não é necessário fazer nenhuma alteração nesse arquivo. 
Após isso volte ao cmd e digite o seguinte para instalar o express nas dependências do projeto: [express - instalando o express](#express)

```markdown
javascript

const express = required('express');
```

[Voltar ao topo](#sumário)