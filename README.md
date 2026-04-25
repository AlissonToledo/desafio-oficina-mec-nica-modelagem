# Projeto de Banco de Dados – Oficina Mecânica

Este projeto apresenta a modelagem conceitual de um banco de dados para um sistema de **controle e gerenciamento de ordens de serviço em uma oficina mecânica**. O objetivo do modelo é representar de forma estruturada as principais entidades e relacionamentos envolvidos no processo de manutenção e revisão de veículos.

No sistema, **clientes levam seus veículos à oficina** para realização de reparos ou revisões periódicas. Cada veículo pode gerar uma **ordem de serviço (OS)**, que registra informações como número da ordem, data de emissão, status, data prevista de conclusão e valor total dos serviços executados.

Os veículos são atendidos por **equipes de mecânicos**, responsáveis por avaliar os problemas apresentados e identificar os serviços necessários. Os serviços executados são baseados em uma **tabela de referência de mão-de-obra**, utilizada para calcular o valor de cada atividade realizada. Além disso, o valor das **peças utilizadas no reparo** também compõe o valor final da ordem de serviço.

O modelo inclui entidades como **Cliente, Veículo, Mecânico, Equipe, Ordem de Serviço, Serviço e Peça**, além de tabelas de relacionamento responsáveis por registrar os serviços executados e as peças utilizadas em cada ordem de serviço. Também é considerada a **autorização do cliente para execução dos serviços**, conforme descrito na narrativa do problema.

A modelagem foi desenvolvida utilizando conceitos de **bancos de dados relacionais**, incluindo entidades, atributos, chaves primárias, chaves estrangeiras e relacionamentos, com o objetivo de organizar as informações e garantir a integridade dos dados dentro do sistema.
