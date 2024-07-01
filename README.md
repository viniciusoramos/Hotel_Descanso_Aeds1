Hotel Descanso Garantido
Descanso Garantido é um hotel que tem como objetivo atender bem seus clientes, além disso,
procura fideliza lós. Está localizado no centro de Itacaré – BA e possui alguns funcionários com
seguintes cargos (recepcionista, auxiliar de limpeza, garçom, gerente). Acontece que até hoje o
Hotel Descanso Garantido fazia seus controles de estadias, clientes e funcionários em planilhas do
excel e cadernos, o que tem gerado diversos problemas para a organização. Sem falar que muitas
vezes um mesmo quarto é reservado para mais de um cliente. Diante dos problemas vividos pela
Descanso Garantido, o hotel resolveu contratar uma empresa desenvolvedora de sistemas (vocês).
Sendo assim, é necessário compreender a real necessidade do hotel e desenvolver um software
específico. A seguir foi descrito como deverá ser o sistema, bem como suas restrições.
O sistema
Deseja-se cadastrar os clientes, os funcionários e as estadias do hotel. As informações que devem
ser cadastradas são:
• CLIENTE = código, nome, endereço, telefone
• FUNCIONARIO = código, nome, telefone, cargo, salario
• ESTADIA = código da estadia, data de entrada, data de saída, quantidade de diárias, código do
cliente, número do quarto
• QUARTO = número do quarto, quantidade de hospedes, valor diária, status
Pontifícia Universidade Católica de Minas Gerais
Considere as seguintes restrições: para cadastrar uma estadia, primeiro é necessário que o cliente
e o quarto estejam cadastrados. As estadias devem ser cadastradas apenas para quartos com status
desocupado, sendo que os possíveis status para o quarto são: ocupado e desocupado. Além disso,
não devem ser feitas mais de uma estadia para um mesmo quarto em um mesmo período (data de
entrada, data de saída). As diárias têm início às 14h00 horas e findam as 12h00 horas do dia
seguinte.
1. Implemente uma função para cadastrar um cliente. Esta função deve garantir que não
haverá mais de um cliente com o mesmo código. Se quiser pode gerar o código
automaticamente.
2. Implemente uma função para cadastrar um funcionário. Esta função deve garantir que não
haverá mais de um funcionário com o mesmo código. Se quiser pode gerar o código
automaticamente.
3. Implemente uma função que cadastre uma estadia. Para cadastrar a estadia, o sistema deve
receber do usuário o código do cliente que deseja se hospedar, a quantidade de hospedes,
a data de entrada e a data de saída. A partir disso, o sistema deve encontrar um quarto que
esteja disponível para quantidade hospedes desejados. Além disso, a quantidade de diárias
deverá ser calculada com base na data de entrada e saída.
4. Implemente uma função que dê baixa em uma determinada estadia e calcule e mostre o
valor total a ser pago por um determinado cliente. Além disso, lembre-se de alterar o status
do quarto para desocupado.
5. Implemente funções para realizar pesquisa tanto para clientes quanto para funcionários, ou
seja, digitando o nome ou código apresenta na tela todas as informações do cliente ou
funcionário.
6. Implemente uma função que mostre na tela todas as estadias de um determinado cliente.
Para fazer este programa pode ser necessário criar mais funções do que as que estão descritas.
Finalmente, faça uma função main() que teste o sistema acima. A função main() deve exibir um
menu na tela, com as opções de cadastrar um cliente, um funcionário e uma estadia. Além disso,
permitir realizar as pesquisas. Este menu deve ficar em loop até o usuário selecionar a opção SAIR.
Além disso, todas as informações deverão ser persistidas/armazenadas em arquivos, portanto,
deverá ser feita leitura e escrita em arquivos.
