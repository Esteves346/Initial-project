#passos para replicar o projeto

##1 criar pasta e mudar para a mesma
    mkdir ...
    cd ...

##2 criar o package.json file (descreve o projeto)
    npm init -y

##3 intall typescript
    npm install typescript --save-dev

##4 Command to add support for using Node.js
    npm install @types/node --save-dev

##5 configure Typescript
    npx tsc --init --rootDir src --outDir build --esModuleInterop
    --resolveJsonModule --lib es6 --module commonjs --allowJs true
    --noImplicitAny true

##6 Criar pasta src
    mkdir src
    criar ficheiro .ts

##7 VSCode
##8 Compilar typescript source files
    npx tsc
##9 Execute files
    node build/nome do ficheiro