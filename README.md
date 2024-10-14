# Módulo 4 de ReactJS Rocket-Seat

Esse módulo é um projeto Pizza Shop em ReactJS. Ele é focado na Integração entre frontend e backend.
___
### Palavras chave:
>ReactJS

## Conteúdo Programático do Módulo 4

<details style="font-size: 16px">
<summary><strong style="font-size: 18px">1. Setup do Projeto</strong></summary>

  ---

  + Especificação e apresentação do projeto
  + Criando App React com Vite
  ---
</details>

## Atalhos do VSCode:

>Clique para visualizar os [Atalhos do VSCode](https://silicon-chips-f58.notion.site/VsCode-Shortcuts-Atalhos-4ced0388660c4f1c93b410765c0a44cd) no Notion.

## Principais comandos:

### Aula "Criando App React com Vite"

+ `npm create vite@latest`: Cria o projeto Vite.
  > **_OBS:_** Aqui você pode encontrar a documentação do [Vite](https://vitejs.dev/guide/)
+ `npm i`: Instala as dependências para rodar o projeto.
+ `npm run dev`: Roda o projeto na porta configurada no arquivo vite.config.js. Nesse projeto está na localhost:3001.
+ `npm i styled-componentes`: Biblioteca que permite trabalhar com estilos usando componentes.
+ `npm i @types/styled-components -D`: Tipagem da biblioteca styled-components.

### Aula "Instalando shadcn/ui"

+ [Shadcn/ui](https://ui.shadcn.com/): Biblioteca de componentes pré estilizados baseada em tailwind css.
+ `npm install -D tailwindcss postcss autoprefixer`: Instalação do tailwind autoprefixer.
+ `npx tailwindcss init -p`: Executa o tailwind.
+ `npm i -D @types/node`: Atualiza o vite para suportar as importações.
+ `npx shadcn@latest init`: Inicializar o shadcn.
+ `npx shadcn@latest add button`: Instalação do Button (Instalação dos demais componentes estão na documentação).

### **Passo a Passo para Configuração do ESLint do Crea-GO:**

1. Excluir a pasta `node_modules`.
2. Dentro do arquivo `package.json`, excluir todas as `devDependencies` que tenham "eslint" no nome.
3. Rodar `npm i`
4. Rodar o comando: `npm install eslint@8.22.0 @typescript-eslint/eslint-plugin@5.45.0 @typescript-eslint/parser@5.45.0 eslint-plugin-prettier@4.2.1 prettier@2.7.1 --save-dev`
5. Rodar o comando: `npm i -D eslint-config-creago`
6. Exclua o arquivo `.eslint.config.js` e, se não existir, crie o arquivo ´.eslintrc.json´ e coloque no seu conteúdo:
    >
    ```
    {
      "extends": "eslint-config-creago/react"
    }
    ```
7. Alterar as configurações de usuário no `settings.json`, acrescentando:
    >
    ```
    {
      "editor.codeActionsOnSave": {
          "source.fixAll": "explicit",
          "source.fixAll.eslint": "explicit"
      },
      "eslint.format.enable": true,
      "editor.formatOnSave": true
    }
    ```
8. Instalar a extensão ESLint da Microsoft no VSCode
9. Rodar `npm run lint` para mostrar os erros.
10. Testar se `Ctrl + S` num arquivo .ts ou .tsx aplica formatação do ESLint

### Aula "Configurando ESLint e Prettier"

+ `npm install -D prettier-plugin-tailwindcss`: Plugin que ajuda a escrever o css com Tailwind ordenando as classes no classname.
+ `npm install -D eslint-plugin-simple-import-sort`: Plugin que ordena as importações do projeto.

### Aula "React Router DOM"

+ `npm install react-router-dom localforage match-sorter sort-by`: Instalação do React Router DOM para esse projeto no browser.
  > **_OBS:_** Aqui você pode encontrar a documentação do [React Router](https://reactrouter.com/en/main/start/tutorial)


### Aula "React Helmet (SEO)"

+ `npm i react-helmet-async`: Instalação do React Helmet Async.
  > **_OBS:_** Aqui você pode encontrar a documentação do [React Helmet Async](https://github.com/staylor/react-helmet-async/blob/main/LICENSE)

## Autoria e Créditos:

+ Documentação criada com carinho e dedicação por [Júlio César Freitas](https://github.com/juliofreitasbm) a serviço do [CREA-GO](https://www.creago.org.br/).
