# START PROJETO
- npm init -y na pasta backend, vai gerar o packjage.json
    o -y executando com tudo default respondendo yes das questões
- npm i json-server, cria um api baseada em json
- dentro do package.json add um script "start": "json-server --watch db.json --port 3001"

# TESTAR O SERVER
- npm start dentro da pasta backend

# CRIAR O FRONTEND
- npm i -g @angular/cli na pasta do projeto angular9, vai intalar o cli
- ng new frontend --minimal
- entrar na pasta frontend e rodar npm start, vai fazer toda a compilação e servir o porjeto na porta padrão 4200

# MUDANÇA NO frontend/angular.json
- mudar na linha 10 o inlineTemplate para false
- mudar na linha 10 o inlineStyle para false
    stratégia de arquilos de css e html separados

# ADD MATERIAL DESING
- ng add @angular/material dentro da pasta frontend
- themes: escolha o tema
- aplicar fonts globalmente: yes
- aplicar animação: yes

# GERAR COMPONENTES
- stop na aplicação
- ng g c caminho, na pasta frontend
- npm start para restart na aplicação

# ADD ROTAS
- no arquivo app-routing.module.ts importar as views e colocar na lista  routes:[]

