# Java Challenge

Este desafio tem como objetivo testar os seus conhecimentos de desenvolvedor fullstack e avaliar a sua forma de codificação e habilidades com as tecnologias propostas.

# Parking lot

![Parking lot](https://www.fecomercio.com.br/upload/img/2016/07/12/5785589778eb2-estacionamento_projeto_de_lei_n_329_2013_2.jpg)

Jacks e seu pai compraram um terreno e vão inaugurar um estacionamento.

Para ajudar, o irmão de Jacks está desenvolvendo uma aplicação para controle de
estacionamento.

Quando o veículo entra no estacionamento, o atendente observa a sua placa e a mesma é registrada, juntamente com o modelo do veículo e a sua cor. A hora de entrada é gerada automaticamente, correspondendo ao momento de registro.

O cliente ao retornar para estacionamento informa a placa do veículo ao atendente para registro da saída. O tempo de permanência é calculado pelo sistema. Considerando esse tempo de permanência é aplicada a seguinte tabela de preços.

#### Tabela de Preços

Dias | Período | Valor/h
:--------- | :------: | :------:
Segunda - Sexta | 08:00 as 12:00 | R$ 2,00
Segunda - Sexta | 12:01 as 18:00 |  R$ 3,00
Sábado e domingo | 08:00 as 18:00 | R$ 2,50

Os donos precisam de relatórios de faturamento por período. Não aceitar entrada de veiculos fora do horario da tabela de preços.

# O que deve ser entregue
* No beckend deve ter um endpoint para entrada de veículos, onde ele receba a placa e registre o horario de entrada.
* No Beckend deve ter um endpoint para saída de veículos, onde ele receba a placa e devolva o valor a pagar. 
* No Frontend você deve desenvolver uma tela onde o atendente possa dar entrada e saída dos veiculos.
* No Frontend você deve desenvolver uma tela que gere o relatório de faturamento em um determinado periodo.

# Instruções 
* [Obrigatório] disponibilizar o link do github para: daniel.mendonca@itriad.org.br
* [Obrigatório] readme.md conter as instruções para buildar e servir o aplicativo.
* [Desejavel] que disponibilize o aplicativo na plataforma [Heroku](https://www.heroku.com)

# Tecnologias Back-end (Obrigatório):
* Spring Boot;
* Banco relacional ou não relacional é de livre escolha;

# Tecnologias Front-end (Obrigatório):
#### Escolher entre os frameworks:
* Angular 
* React 
* Vue
* Svelte

# Diferenciais:
* Práticas TTD, ATDD ou semelhantes são extremamente bem vindas;
* Docker;
* TypeScript;
* Kubernetes;
* Organização e clareza nas ideias;
* Menos é mais, seja prático e não perca tempo com aspectos desnecessários;

Use o contato do Daniel (daniel.mendonca@itriad.org.br) para sanar qualquer dúvida.
