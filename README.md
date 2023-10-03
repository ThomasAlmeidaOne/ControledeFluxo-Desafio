# Projeto Contador com Controle de Fluxo

Este projeto implementa um contador que recebe dois parâmetros via terminal e realiza a impressão de números incrementados. Além disso, ele lida com exceções personalizadas quando o primeiro parâmetro é maior que o segundo.

## Funcionalidades

- Recebe dois números inteiros via terminal.
- Realiza uma iteração (for) para imprimir números incrementados.
- Lança uma exceção personalizada (`ParametrosInvalidosException`) quando o primeiro parâmetro é maior que o segundo.
##
  Navegue até o diretório do projeto:
  cd DesafioControleFluxo

## Exceção Personalizada
Se o primeiro parâmetro for maior que o segundo, o programa lançará a exceção ParametrosInvalidosException com a mensagem "O segundo parâmetro deve ser maior que o primeiro."  

## Estrutura do Projeto
Contador.java: Contém a implementação principal do programa.
ParametrosInvalidosException.java: Classe de exceção personalizada para tratar o caso de parâmetros inválidos.

Licença
Este projeto está licenciado sob a Licença MIT.
