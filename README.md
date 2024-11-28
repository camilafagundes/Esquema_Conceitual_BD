# Sistema de Controle de Oficina Mecânica

## Descrição do Projeto Conceitual

Este projeto tem como objetivo desenvolver um sistema para o controle e gerenciamento de ordens de serviço (OS) em uma oficina mecânica. O sistema permite que os clientes levem seus veículos para conserto ou revisão, com a possibilidade de controlar todos os processos relacionados à execução dos serviços.

### Funcionalidades Principais

- **Gerenciamento de clientes**: Acompanhamento de todos os clientes da oficina.
- **Gestão de veículos**: Cada cliente pode possuir múltiplos veículos, que são registrados no sistema.
- **Ordem de Serviço (OS)**: A criação de ordens de serviço para cada veículo, contendo detalhes dos serviços, peças e valor total.
- **Equipe de mecânicos**: Atribuição de equipes de mecânicos a cada ordem de serviço, levando em consideração a especialidade de cada mecânico.
- **Serviços e Peças**: Gerenciamento dos serviços executados e peças utilizadas, com cálculo do custo total da OS.
  
### Entidades

1. **Cliente**: Contém informações sobre os clientes da oficina.
2. **Veículo**: Informações sobre os veículos de cada cliente.
3. **Ordem de Serviço (OS)**: Registro das ordens de serviço, com detalhes dos serviços e peças.
4. **Mecânico**: Profissionais responsáveis pela execução dos serviços.
5. **Equipe**: Conjunto de mecânicos designados a executar as ordens de serviço.
6. **Serviço**: Descrição dos serviços prestados, com valores.
7. **Peça**: Peças utilizadas nos serviços, com valores.
8. **Tabela de Referência de Mão de Obra**: Tabela que define os valores de referência para os serviços.

### Tecnologias Utilizadas

- **Banco de Dados**: Relacional (SQL) - Para armazenar dados de clientes, veículos, ordens de serviço, etc.
- **Frameworks**: A ser definido conforme as necessidades do projeto.
