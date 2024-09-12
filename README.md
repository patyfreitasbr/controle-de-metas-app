# App de Metas

Este é um **App de Metas** interativo em Node.js que permite ao usuário cadastrar, listar, marcar como concluídas, visualizar e deletar metas pessoais. O aplicativo usa o terminal para interação e é perfeito para quem busca uma maneira simples e eficaz de gerenciar seus objetivos.

Desenvolvido durante a 17a NLW Pocket JavaScript da [Rocketseat](https://www.rocketseat.com.br/).

[Demonstração](#demonstracao)• [Funcionalidades](#funcionalidade) •  [Linguagens e tecnologias utilizada](#linguagens-e-tecnologias-utilizada) •  [Requisitos](#requisitos) </br>  [Instalação](#instalacao) •  [Uso](#uso) •  [Exemplo de uso](#exemplo-de-uso) •  [Contato](#contato) 

## Demonstração

![gif](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi_Yr7Ly1qvWA_Tnmskszc5FvK2QOKqf6G6-amDJITRurxb3Na4IR6tBnT8RglLm7MXZ7g2qG5T1E5oEnBa6oXsPYCSM3pccJixxN9IgpzpfkNrhWoc9bEwV0VDHOlkWc7CJ06qsBUoj9w3UsiUgAtq15iSgJOkQFRuMH7-lK2ftVXveZOGujQ1soFz-gfz/s16000/metas%20app.gif)

## Funcionalidades

- **Cadastrar Metas**: Adicione novas metas ao seu arquivo de metas.
- **Listar Metas**: Visualize todas as suas metas cadastradas.
- **Metas Realizadas**: Veja as metas que você marcou como concluídas.
- **Metas Abertas**: Veja as metas que ainda estão pendentes.
- **Deletar Metas**: Remova metas indesejadas do seu arquivo.
- **Persistência de Dados**: As metas são salvas em um arquivo `metas.json` para que possam ser acessadas e manipuladas em execuções futuras.

##  Linguagens e tecnologias utilizada

- **JavaScript (Node.js)**: A linguagem principal usada no projeto, com foco em criar um aplicativo de linha de comando que gerencia metas.
- **JSON**: Utilizado para salvar e carregar os dados das metas no arquivo metas.json.
- **Node.js Built-in Modules**: Especificamente o módulo fs (File System) para manipulação de arquivos.

## Requisitos
- [Node.js](https://nodejs.org/) v14 ou superior
- [@inquirer/prompts](https://www.npmjs.com/package/@inquirer/prompts)

## Instalação

⚠️ Necessário ter o [GIT](https://git-scm.com/downloads) instalado no computador

1. Abra o terminal Git Bash 
2. Digite ```pwd``` e aperte enter
3. Digite:  ```git clone https://github.com/patyfreitasbr/metas-app``` e aperte enter   
4. Digite: ```node index.js``` 
5. Digite: ```npm install```
6. Digite: ``ctrl l``` para limpar
7. Digite ```node index.js```


## Uso
O App de Metas interage via terminal. Quando você iniciar o app, verá um menu com as seguintes opções:

1. Cadastrar Meta: Adicione uma nova meta para alcançar.
2. Listar Metas: Veja todas as metas registradas e marque como concluídas.
3. Metas Realizadas: Exibe uma lista das metas já concluídas.
4. Metas Abertas: Exibe uma lista das metas ainda não concluídas.
5. Deletar Metas: Selecione metas que deseja remover permanentemente.
6. Sair: Fechar o aplicativo.   

## Exemplo de uso

   ```bash
    $ node app.js
Bem-vindo(a) ao App de Metas

Menu >
1. Cadastrar Meta
2. Listar Metas
3. Metas Realizadas
4. Metas Abertas
5. Deletar Metas
6. Sair
```
Navegue pelas opções usando as setas e siga as instruções exibidas no terminal para realizar suas ações.


## Contato

👩‍💻 Patrícia Freitas

📬 brpatyfreitas@gmail.com

 <div><a href="https://www.linkedin.com/in/patyfreitasbr"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></>
  <a href="https://www.instagram.com/patyfreitasbr"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></></div>

<br>

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/patyfreitasbr/Google-Search-Page-Clone/blob/main/LICENSE)
   