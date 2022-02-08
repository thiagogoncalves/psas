# PSAS - Peer Skills Assessment System

Sistema em desenvolvimento! Em breve!
Todos os commits serão publicados automaticamente nos endereços `http://tiagosantos.net/` e `https://psas.mybluemix.net`. Clique [aqui](https://psas.mybluemix.net) para acessar.

## Instalação

Para realizar a instalação do sistema, seguir os passos:
1. Instalar o node.js disponível em `https://nodejs.org/`;
2. Instalar o github e o VSCode (sugestão);
3. Baixar o código do repositório;
4. Abrir a pasta no VSCode e rodar o comando `npm install` no terminal;
5. Pronto!

## Servidor de desenvolvimento

Utilize o comando `ng serve` para utilizar o sistema localmente, navegando para o endereço `http://localhost:4200/` para visualizar a página.

## Criar componentes

Utilize o comando `ng generate component component-name [--module app]` para gerar um novo componente. Ou utilize `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Produção

Utilize o comando `ng build` para gerar a versão que estará no diretório `dist/`. A flag `--prod=true --aot=true --output-hashing=all` deve ser utilizada para configurar corretamente as variáveis.

## Rotinas de testes unitários

Utilize o comando `ng test` para executar testes unitários usando o [Karma](https://karma-runner.github.io).

## Rotinas de testes integrados

Utilize o comando `ng e2e` para executar testes integrados com o [Protractor](http://www.protractortest.org/).
