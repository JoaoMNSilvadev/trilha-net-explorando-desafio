# dio-dotnet-explorando
www.dio.me

Projeto desenvolvido durante o Bootcamp Back-end .NET da DIO com foco em recursos intermediários do C# e da plataforma .NET.

## Sobre o projeto

Este projeto foi criado para explorar funcionalidades intermediárias da linguagem C#.

## Conceitos praticados

- Manipulação de dados
- Coleções
- Métodos
- Estruturas de controle
- Aplicação Console

## Tecnologias utilizadas

- C#
- .NET
- Git
- GitHub

## Autor

João Matheus do Nascimento Silva


## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de explorando a linguagem C#, da trilha .NET da DIO.

## Contexto
Você foi contratado para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Você precisará usar a classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos.

O seu programa deverá cálcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% para caso a reserva seja para um período maior que 10 dias.

## Regras e validações
1. Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. O método ObterQuantidadeHospedes da classe Reserva deverá retornar a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria deverá retornar o valor da diária (Dias reservados x valor da diária).
3. Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.


![Diagrama de classe estacionamento](diagrama_classe_hotel.png)

## Solução
O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.

🛠️ Implementação
O projeto foi implementado respeitando todas as regras descritas acima, utilizando apenas recursos nativos da linguagem C#.

Classe Reserva
Principais responsabilidades:
Validar capacidade da suíte
Cadastrar hóspedes
Calcular quantidade de hóspedes
Calcular valor total da reserva com desconto

🚀 Tecnologias Utilizadas
.NET
C#
Programação Orientada a Objetos (POO)

🎯 Objetivo do Desafio
Consolidar o entendimento sobre:
Classes e propriedades
Métodos e validações
Lançamento de exceções
Regras de negócio
Boas práticas iniciais em C#

👤 Autor
João Matheus
Estudante de Desenvolvimento de Sistemas | .NET

Projeto desenvolvido para fins educacionais na plataforma DIO.
