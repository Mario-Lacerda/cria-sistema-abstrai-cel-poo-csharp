# Criando um Sistema e Abstraindo um Celular com POO em C#

O objetivo deste projeto é criar um sistema abrangente e abstrato que modele um celular usando Programação Orientada a Objetos (POO) em C#. O sistema deve ser bem estruturado, documentado, testável e integrável.

## **Requisitos**

## **Estruturando o Projeto**

- O projeto deve ser estruturado em camadas, com uma camada de apresentação, uma camada de lógica de negócios e uma camada de acesso a dados.

- As camadas devem ser desacopladas, permitindo que sejam facilmente substituídas ou modificadas.

- O projeto deve usar padrões de design apropriados, como MVC ou MVVM.

  

## **Documentando (Documentação)**

- O projeto deve ser bem documentado, usando comentários XML e documentação Markdown.

- A documentação deve explicar claramente o propósito de cada classe, método e propriedade.

- A documentação deve fornecer exemplos de código para mostrar como usar o sistema.

  

## **Definindo Modelos**

- O sistema deve definir modelos de dados que representem as diferentes entidades do mundo real, como produtos, clientes e pedidos.

- Os modelos devem ser persistentes e devem ser capazes de armazenar e recuperar dados de um banco de dados.

- Os modelos devem ter métodos de validação para garantir que os dados sejam válidos antes de serem persistidos.

  

## **Definindo Serviços**

- O sistema deve definir serviços que encapsulam a lógica de negócios do sistema.

- Os serviços devem ser responsáveis por executar operações como criar, ler, atualizar e excluir dados.

- Os serviços devem ser testáveis e devem usar técnicas de injeção de dependência.

  

## **Definindo Lógica de Negócios**

- O sistema deve definir a lógica de negócios que controla o comportamento do sistema.

- A lógica de negócios deve ser modular e reutilizável.

- A lógica de negócios deve ser testável e deve usar técnicas de programação funcional.

  

## **Integrando e Testando**

- O sistema deve ser integrado usando um mecanismo de injeção de dependência.
- O sistema deve ser testado usando uma estrutura de teste unitário.
- Os testes devem cobrir todos os aspectos do sistema, incluindo a camada de apresentação, a camada de lógica de negócios e a camada de acesso a dados.



## Contexto
Você é responsável por modelar um sistema que trabalha com celulares. Para isso, foi solicitado que você faça uma abstração de um celular e disponibilize maneiras de diferentes marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.



## Proposta
Você precisa criar um sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. 
Você deve criar as suas classes de acordo com o diagrama abaixo:

![Diagrama classes](Imagens/diagrama.png)

## Regras e Validações
1. A classe **Smartphone** deve ser abstrata, não permitindo instanciar e servindo apenas como modelo.

2. A classe **Nokia** e **Iphone** devem ser classes filhas de Smartphone.

3. O método **InstalarAplicativo** deve ser sobrescrito na classe Nokia e iPhone, pois ambos possuem diferentes maneiras de instalar um aplicativo.

   

## Solução
O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.



## **Conclusão com Aprendizado**

- O projeto fornecerá uma compreensão profunda dos conceitos de POO em C#.

- O projeto ensinará como projetar e implementar sistemas abrangentes e abstratos.

- O projeto fornecerá experiência prática com padrões de design, técnicas de teste e integração.

  

## **Aplicabilidade Prática**

- O sistema pode ser usado como base para desenvolver aplicativos móveis reais.
- O sistema pode ser usado para ensinar conceitos de POO em C#.
- O sistema pode ser usado como um modelo para projetar e implementar outros sistemas abstratos.
