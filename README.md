# Project_Smart_Holder_Dashboard

Repositório para continuação do projeto [Project_Smart_Holder](https://github.com/Dragonrhs/Project_Smart_Holder) referente ao Trabalho T2 e T3 da materia de Microcontroladores e Sistemas Embarcados EEN251,com a supervisão dos professores Sergio Ribeiro Augusto e Rodrigo França.

# Sumário

- [Descrição](#Descrição)
- [Requisitos](#Requisitos)
- [Materiais utilizados](#Materiais-utilizados)
- [Custos Estimado](#Custos-Estimado)
- [Funcionamento](#Funcionamento)
- [Diagrama de blocos do sistema](#Diagrama-de-blocos-do-sistema)
- [Esquema Elétrico](#Esquema-Elétrico)
- [Node-RED](#Node-RED)
- [Dashboard](#Dashboard)
- [Autores](#Autores)

# Descrição 

O projeto consiste em aprimorar o Smart Holder, fazendo com que os dados medidos pelos sensores sejam captados e em sequência exibidos em um dashboard, para isso foram feitas alterações para viabilizar o aprimoramento.

# Requisitos 

O projeto deve, a partir do peso da garrafa colocada, indicar se ela esta vazia ou cheia através de leds, deve apresentar no display as informações de peso e temperatura, deve ter uma fonte de alimentação seja por meio da fonte ou opcionalmente por meio da bateria e os dados devem ser apresentados para um dashboard.


| ID    |                        Requisito                    |    Tipo        |
| :-----|-----------------------------------------------------|:--------------:|
| UR-01 | Medir a temperatura interna da garrafa              |Obrigatório     |
| UR-02 | Medir o peso da garrafa                             |Obrigatório     |
| UR-03 | Mostrar a temperatura no display                    |Obrigatório     |
| UR-04 | Leds devem ascender de acordo com o peso da garrafa |Obrigatório     |
| UR-05 | Tem que ter uma fonte de energia para alimentação   |Obrigatório     |
| UR-06 | Deve apresentar os dados medidos em um dashboard    |Obrigatório     |
| UR-07 | Uso de bateria para alimentação                     |**Desejável**   |


# Materiais utilizados

- Porta garrafa
- 1 Sensor Temperatura e Umidade DTH11 
- 1 Display OLED i2c OLED 128x32 Px 
- 1 Raspberry Pi Pico
- 1 Módulo HX711
- 1 Célula de Carga Fina 50 Kg
- 3 Leds (vermelho, amarelo, verde)
- 1 Raspberry Pi 3 model b+
- 3 resitores 220 Ω
- Jumpers

# Custo Estimado 

| Item                      |   Preço     | 
| :-------------------------|:-----------:|
| DTH11                     | R$ 8,90     |
| OLED i2c                  | R$ 10,97    |
| Raspberry Pi Pico         | R$ 33,90    |
| HX711                     | R$ 5,90     |
| Célula de carga           | R$ 7,90     |
| Leds x 3                  | R$ 0,72     |
| Porta garrafa             | R$ 18,49    |
| 1 Raspberry Pi 3 model b+ | R$ 385,60   |
| Resistor 220 Ω x3         | R$ 0,30     |
| **Total**                 |**R$ 472,68**|

# Funcionamento

## Teste do sistema com as novas funcionalidade

[![Watch the video](https://www.alura.com.br/artigos/assets/tipos-de-testes-principais-por-que-utiliza-los/tipos-de-testes-principais-por-que-utiliza-los.jpg)](https://www.youtube.com/watch?v=bH4ARBMKPck)


## Diagrama de blocos do sistema

![screenshot](imagens/diagrama.png)

## Esquema Elétrico

![screenshot](imagens/Esquema_Eletrico.jpeg)

## Node-RED

![screenshot](imagens/Red.jpeg)

## Dashboard

![screenshot](imagens/Dashboard.jpeg)

# Autores
- [Ryuske Hideaki Sato 21.00745-4](https://github.com/Dragonrhs)
- [Gabriel Henrique Baca Rado 21.01286-5](https://github.com/Gabriel-HBR)
- [Vinícius de Oliveira Berti 21.01219-9](https://github.com/ViniciusBerti)
- [Erick Eiji Nagao 21.00690-3](https://github.com/ErickNagao)


![screenshot](imagens/equipe.jpeg)
