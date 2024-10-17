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

+ `npm install -D eslint-plugin-simple-import-sort`: Plugin que ordena as importações do projeto.
+ `"react/self-closing-comp": "off"`: Adicionar regra no `.eslintrc.json`.

### Aula "React Router DOM"

+ `npm install react-router-dom localforage match-sorter sort-by`: Instalação do React Router DOM para esse projeto no browser.
  > **_OBS:_** Aqui você pode encontrar a documentação do [React Router](https://reactrouter.com/en/main/start/tutorial)


### Aula "React Helmet (SEO)"

+ `npm i react-helmet-async`: Instalação do React Helmet Async.
  > **_OBS:_** Aqui você pode encontrar a documentação do [React Helmet Async](https://github.com/staylor/react-helmet-async/blob/main/LICENSE)

### Aula "Usando React Hook Form"

+ `npm i react-hook-form zod @hookform/resolvers`: Instalando o React Hook Form e o zod.

### Aula "Notificações toast (sonner)"

+ `npm i sonner`: Biblioteca para notificações toast.

### Aula "Gráfico de receita no período"

+ `npm i recharts`: Biblioteca para gráficos.
  > **_OBS:_** Aqui você pode encontrar a documentação do [Recharts](https://recharts.org/en-US/examples)

### Aula "Rodando API localmente"

+ `sudo apt install unzip`: Package necessário para instalar o bun.
+ `curl -fsSL https://bun.sh/install | bash`: Comando para instalação do Bun. Semelhante ao Node, mas baseado no motor de busca do Safari ao invés do Chrome.
  > **_OBS1:_** Aqui você pode encontrar a documentação do [Bun](https://bun.sh/docs/installation)
  > **_OBS2:_** Aqui você pode encontrar no GitHub da RocketSeat o [Projeto da API Pizzashop](https://github.com/rocketseat-education/pizzashop-api)

+ `sudo systemctl start docker`: Starta o docker na máquina.
+ `docker compose up -d`: Se tiver um arquivo `docker-compose.yml` no projeto, ele inicia o container docker. 
+ `bun i`: Instala o bun no projeto.
+ `bun migrate`: Roda as migrates criando o banco de dados.
+ `bun seed`: Preenche o banco de dados com informações.
+ `bun dev`: Abre o projeto.

### Aula "Configurando API client"

+ `npm i axios`: Instala o axios para fazer requisições
+ `npm i @tanstack/react-query`: Instala o react-query para lidar com as requisições.

### Aula "Atualizando HTTP state"

+ `Local state`: Estados que colocamos dentro de componentes (usando useState, por exemplo).
+ `Global state`: Quando utilizamos bibliotecas como Zustand, Redux ou Jotai para criar estados globais que são acessados por vários componentes dentro da aplicação. 
+ `HTTP state`: Estado dos dados que são retornados pelas requisições HTTP.


### Aula "Listagem de pedidos"

+ `npm i date-fns`: Biblioteca para lidar com datas e horários.

## Autoria e Créditos:

+ Documentação criada com carinho e dedicação por [Júlio César Freitas](https://github.com/juliofreitasbm) a serviço do [CREA-GO](https://www.creago.org.br/).
