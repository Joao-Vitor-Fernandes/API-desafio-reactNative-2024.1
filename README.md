## Objetivos do repositorio

O objetivo do repositório é ter um projeto com uma API pré-configurada para os desenvolvedores realizarem o Desafio de Next da gestão 2023.2.

## Propositos do desafio

A proposta do desafio é criar um Site para um e-commerce/sistema de vendas, com tema de sua escolha. O site deve conter todos os requisitos funcionais que estão listados no Documento de Requesitos.

## Como executar o projeto inicial

Abra o Terminal na Pasta do Projeto
Instalar o NextJS no projeto: 'npx create-next-app@latest .' (O ponto . no final do comando serve para criar o projeto na pasta que está selecionado, em vez de criar uma adicional'
Instalar o json-server no projeto: 'npm install -g json-server'
Crie um arquivo db.json na raiz do projeto e adicione o conteúdo do arquivo db.json desse repositório
Inicie o json-server: 'json-server --watch db.json --port 3001' (Atenção, o comando --port deve ser inserido pois o json-server utiliza por padrão a porta 3000, assim como o NextJS, então para evitar bugs utilize --port 3001
Inicie o servidor: 'npm run dev'
Agora, se você ir para 'http://localhost:3001/membros', você verá toda a API sendo buscada.

Lembre-se de consultar a documentação sempre.

## Links Úteis

- [Documentação do JSON Server (Fake-API)]([https://nextjs.org/docs](https://github.com/typicode/json-server))
- [Documentação do Next.js](https://nextjs.org/learn)
