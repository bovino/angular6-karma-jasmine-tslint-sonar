# angular6-karma-jasmine-protractor-tslint-sonar
Projeto de exemplo demonstrando aplicação Angular 6.1 + testes (Karma, Jasmine, Protractor E2E) + TypeScript com regras TSLINT integrado ao SonarQube (exemplo testado apenas em SonarQube 7.2+).

Projeto gerado via Angular CLI com algumas modificações, sendo a mais relevante delas o incremento de versao do TypeScipt para 2.8. Porque? Veja aqui: [[https://github.com/DefinitelyTyped/DefinitelyTyped/issues/30310]]

# Para usar o exemplo:

- Tenha uma instalação do SonarQube disponivel (editar o arquivo sonar-project.properties)
- npm install na raiz
- ng build
- npm run test-full (roda os testes, gera o coverage e já rodar o sonar-scanner)
- Acessar o SonarQube e visualizar indicadores coletados
- Caso queira executar a aplicação -> ng serve
