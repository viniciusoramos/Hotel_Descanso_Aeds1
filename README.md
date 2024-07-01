Hotel Descanso Garantido
Este projeto é um sistema simples de gerenciamento de hotel em C. Ele permite cadastrar clientes, funcionários, e estadias, bem como pesquisar informações e gerenciar estadias.

Funcionalidades
Cadastrar Cliente: Adicionar novos clientes ao sistema.
Cadastrar Funcionario: Adicionar novos funcionários ao sistema.
Cadastrar Estadia: Registrar novas estadias para clientes, incluindo a data de entrada e saída, quantidade de hóspedes, e número do quarto.
Dar Baixa em Estadia: Finalizar uma estadia, calculando o valor total a ser pago e liberando o quarto.
Pesquisar Cliente: Buscar informações de clientes por código ou nome.
Pesquisar Funcionario: Buscar informações de funcionários por código ou nome.
Mostrar Estadias de um Cliente: Exibir todas as estadias de um cliente específico.
Estrutura de Dados
O sistema utiliza as seguintes estruturas de dados:

Cliente: Representa um cliente com código, nome, endereço e telefone.
Funcionario: Representa um funcionário com código, nome, telefone, cargo e salário.
Quarto: Representa um quarto com número, quantidade de hóspedes, valor da diária e status (ocupado ou desocupado).
Estadia: Representa uma estadia com código, data de entrada, data de saída, quantidade de diárias, código do cliente e número do quarto.
