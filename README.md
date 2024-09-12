# App de Metas

Este é um **App de Metas** interativo em Node.js que permite ao usuário cadastrar, listar, marcar como concluídas, visualizar e deletar metas pessoais. O aplicativo usa o terminal para interação e é perfeito para quem busca uma maneira simples e eficaz de gerenciar seus objetivos.

Desenvolvido durante a 17a NLW Pocket JavaScript da [Rocketseat](https://www.rocketseat.com.br/).

[Funcionalidades](#funcionalidade) •  [Linguagens e tecnologias utilizada](#linguagens-e-tecnologias-utilizada) •  [Requisitos](#requisitos) •  [Instalação](#instalacao) •  [Uso](#uso) •  [Exemplo de uso](#exemplo-de-uso) •  [Contato](#contato) 

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

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Instale as dependências:
   ```bash
    npm install
    ```

3. Inicie o aplicativo:
   ```bash
    node app.js
    ```

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
   