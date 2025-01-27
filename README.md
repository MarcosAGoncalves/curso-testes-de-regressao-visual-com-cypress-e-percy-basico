## Configuração

1 - Será necessário realizar a instalar o Node.js caso não tenha, caso já tenha em sua maquina ignore esse passo. Você pode fazer o download no link: " https://nodejs.org/en/download ".

## Execução do projeto

1 - Será necessário clonar o repositório.

2 - Após clonar o repositório, baixe todas as dependências do projeto utilizando o comando: " npm install "

## Testar 

- Para realização dos testes, basta digitar no terminar o comando " npm test ". Foi criado um script no package.json com o seguinte comando: "test": "percy exec -- cypress run"

Os testes serão executados no modo serverless e, ao final, será gerada uma nova build no Percy.io, contendo os snapshots.

## Observações

- Existe um arquivo .env na raiz do projeto que contém a chave do Percy. Para um novo projeto, é necessário criar o projeto no Percy e atualizar essa chave.