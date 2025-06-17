# Desafio de projeto
Para este desafio, pratiquei os conhecimentos adquiridos no módulo de fundamentos, da trilha .NET da DIO.

## Contexto
Você foi contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Proposta
Você precisará construir uma classe chamada "Estacionamento", conforme o diagrama abaixo:
![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

# Sistema de Estacionamento (Desafio Concluído)

Este é um sistema simples de gerenciamento de estacionamento desenvolvido em C#. Ele permite cadastrar, remover e listar veículos, além de calcular o valor a ser pago com base em um preço inicial e um preço por hora.

## Funcionalidades

- ✅ Cadastrar veículos
- ✅ Remover veículos e calcular valor devido
- ✅ Listar veículos estacionados
- ✅ Menu interativo via terminal

## Como usar

1. Compile e execute o programa.
2. Ao iniciar, informe:
   - Preço inicial
   - Preço por hora
3. Use o menu para:
   - `1` Cadastrar um veículo (informe a placa)
   - `2` Remover veículo (informando a placa para cálculo de horas e valor)
   - `3` Listar todos os veículos cadastrados
   - `4` Encerrar o sistema
