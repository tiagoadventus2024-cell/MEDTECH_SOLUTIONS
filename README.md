# Sistema de Atendimento MedTech Solutions
Sobre o projeto

Este projeto foi desenvolvido em Python com o objetivo de simular um sistema de atendimento para uma clínica ou empresa da área da saúde.

O sistema funciona pelo terminal e permite cadastrar clientes, organizar filas de atendimento, registrar atendimentos e gerar relatórios.

Durante o desenvolvimento foram utilizados conceitos de estruturas de dados e algoritmos estudados em sala de aula, como filas, pilhas, listas encadeadas, busca binária e Merge Sort.




Funcionalidades
Cadastro de clientes
Cadastro de atendentes
Inserção de clientes em filas
Fila comum e fila prioritária
Chamada do próximo cliente
Finalização de atendimento
Desfazer o último atendimento realizado (Undo)
Busca rápida de clientes por ID
Relatório de tempo médio de atendimento
Ordenação dos atendimentos por duração
Exportação dos dados para arquivo CSV
Remoção de clientes inativos




Estruturas de Dados Utilizadas
Vetor (Lista)

Foi utilizado para armazenar os clientes cadastrados e permitir a busca rápida por ID.

Fila (Queue)

Utilizada para controlar a ordem de atendimento dos clientes.

Existem duas filas:

Fila comum
Fila prioritária

Os clientes prioritários sempre têm preferência no atendimento.

Pilha (Stack)

Utilizada para implementar a funcionalidade de desfazer o último atendimento registrado.

Lista Encadeada (Linked List)

Utilizada para armazenar os clientes ativos e permitir a remoção de clientes inativos.


Algoritmos Utilizados
Busca Binária Recursiva

Utilizada para localizar clientes pelo ID de forma mais eficiente.

Merge Sort

Utilizado para ordenar os relatórios de atendimento com base no tempo de duração.

Estrutura do Projeto


Projeto
│

├── models

│├── client.py

│   ├── attendant.py

│   └── attendance.py

│

├── core

│   ├── structures.py

│   └── algorithms.py

│

├── services

│   └── manager.py

│

├── ui

│   └── terminal.py

│

├── data

│

└── main.py


Como Executar
1. Clone o repositório

   git clone LINK_DO_REPOSITORIO

2. Entre na pasta do projeto

python main.py


Exemplo de Uso
Cadastrar um cliente.
Inserir o cliente na fila.
Chamar o próximo cliente.
Finalizar o atendimento.
Consultar relatórios.
Exportar os dados para CSV.

Conceitos Aplicados

Neste projeto foram aplicados os seguintes conceitos:

Programação Orientada a Objetos (POO)
Classes e Objetos
Encapsulamento
Estruturas de Dados
Filas
Pilhas
Listas Encadeadas
Vetores
Busca Binária
Merge Sort
Manipulação de Arquivos CSV
Tratamento de Exceções
Modularização de Código
Considerações Finais

O projeto foi desenvolvido para praticar conceitos de Python e estruturas de dados vistos durante a disciplina. Além de reforçar o uso de algoritmos de busca e ordenação, também permitiu trabalhar com organização de código em módulos e desenvolvimento de aplicações em linha de comando.



Colaboradores:

 Kaua Barroso Silva 
 
 Tiago Soares da Cruz
 
 Erick Maycon da Silva Carneiro
 
 Argeu Viana Almeida






