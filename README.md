# Sistema de Controle de Ordens de Serviço para Oficina Mecânica

Este repositório contém o modelo Entidade Relacionamento do banco de dados desenvolvido para gerenciar as ordens de serviço em uma oficina mecânica. O desafio foi proposto durante um bootcamp de Banco de Dados da DIO em parceria com a Heineken.

## Descrição do Projeto
O modelo foi desenvolvido a partir da proposta a seguir:

Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica:
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

## Tecnologia Utilizada

- **MySQL Workbench**: Ferramenta utilizada para modelagem do banco de dados.
