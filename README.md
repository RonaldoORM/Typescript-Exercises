# Typescript-exercicios-das-aulas-do-dia-21/08-e-28/08

Conteudo com resolução de exercícios, passo a passo da configuração do typescript.

Tópicos: 
- Interface e tipos de dados;
- Classes e heranças;
- Mudulos e namespaces;
- Generics;
- Decoretors;
- Manipulação de erros;
- Async, Await e Promises.


# Configuração para iniciar o typescript:

1)Instalação do TypeScript: 

    npm install -g typescript

2)Criar um Projeto TypeScript:

Crie uma pasta para o projeto e inicialize com npm :

    mkdir nome-do-projeto
    cd nome-do-projeto
    npm init -y

Instale o TypeScript como dependência de desenvolvimento:

    npm install typescript --save-dev

Crie um arquivo tsconfig.json com o comando:

    npx tsc --init

Estrutura básica do tsconfig.json :

    {
    "compilerOptions": {
    "target": "es6",
    "module": "commonjs",
    "strict": true,
    "esModuleInterop": true
    },
    "include": ["src/**/*"]
    }

2-classes-herancas
3-modulo-namespaces
4-generics
5-decorators
6-manipulacao-erros
7-async-await-promises
