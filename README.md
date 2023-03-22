# T3 stack: O template de um aplicativo "t3-app"

Crie aplicativos TypeScript de pilha completa usando uma coleção de bibliotecas populares conhecidas coletivamente como pilha T3.

O T3 Stack é uma coleção de ferramentas para implementar aplicativos TypeScript de pilha completa, consistindo em Next.js, tRPC, TailwindCSS, TypeScript e Prisma.

### TypeScript

O TypeScript é um superconjunto da linguagem de programação JavaScript que fornece digitação estática, verificações de erros em tempo de compilação e outros recursos mais avançados, como digitação estrutural .

### Next.js

Next.js é uma estrutura React que permite a renderização do lado do servidor em aplicativos React.

### tRPC

tRPC é uma biblioteca TypeScript para construir APIs em Node.js.

### Tailwind.css

TailwindCSS é uma estrutura para CSS que fornece muitas classes de utilitários que você pode usar para estilizar seu site facilmente.

### Prisma

Prisma é uma biblioteca de mapeamento relacional de objeto (ORM) para Node.js que fornece uma alternativa mais amigável ao desenvolvedor para consultas SQL feitas à mão.

## Criação do aplicativo

Pré-requisitos:
Para acompanhar este tutorial, você precisará instalar tanto o Node.js quanto o npm em seu ambiente de desenvolvimento local.
Você também precisará instalar o npx se ainda não o tiver instalado. Você pode usar o seguinte comando para instalar o npx:

npm install -g npx

### Comece executando o seguinte comando no terminal:

npx create-t3-app@latest

site: https://create.t3.gg/

Ok to proceed? (y) -> digite: y
Digite o nome do seu aplicativo no primeiro prompt.
What will your project be called? -> digite: app
Em seguida, você pode selecionar entre TypeScript e JavaScript.
Will you be using TypeScript or JavaScript? selecione: TYPESCRIPT
Em seguida, você receberá uma solicitação para selecionar os pacotes que deseja instalar.
Which packages would you like to enable? nextAuth, prisma, tailwind, trpc
Initialize a new git repository? Yes
Would you like us to run 'npm install'? Yes
What import alias would you like configured? ~/

### Comece executando o seguinte comando no terminal:

Quando o projeto estiver pronto, navegue até o novo diretório do projeto usando o seguinte comando:
cd <your-app-name>

A seguir, você precisará faça um protótipo do seu esquema com o comando abaixo:

npx prisma db push
Por fim, você pode usar o comando abaixo para iniciar seu servidor de desenvolvimento.

npm run dev
O servidor de aplicativos é executado na porta 3000 como um aplicativo React normal. Você pode acessar seu aplicativo em um navegador de http://localhost:3000/.

# Configurando uma instância do mongo db
