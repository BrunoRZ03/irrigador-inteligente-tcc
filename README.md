# Irrigador Inteligente — Sistema de Irrigação Automatizada com Controle PID e IoT

**Projeto de Trabalho de Conclusão de Curso — Engenharia de Computação**

Desenvolvimento de um sistema de irrigação automatizada utilizando sensores de umidade do solo, microcontrolador ESP32, controlador PID e monitoramento remoto por meio de uma plataforma IoT.

---

## Sobre o projeto

O Irrigador Inteligente consiste no desenvolvimento de um sistema automatizado para monitorar e controlar a umidade do solo, utilizando um controlador PID para ajustar o acionamento de uma bomba d'água de acordo com a necessidade de irrigação.

O sistema utiliza um ESP32 para realizar a leitura dos sensores, processar as informações e controlar o funcionamento da bomba. Além disso, permite o monitoramento e a alteração de parâmetros remotamente por meio da plataforma Blynk.

O projeto também contempla uma etapa experimental, na qual são avaliados o comportamento do sistema e seu desempenho em comparação com um método de irrigação manual.

## Objetivos

* Desenvolver um sistema de irrigação automatizada.
* Monitorar a umidade do solo por meio de sensores.
* Implementar um controlador PID para regular o acionamento da bomba.
* Permitir o monitoramento remoto por meio de uma plataforma IoT.
* Avaliar experimentalmente o funcionamento do sistema e o consumo de água.

## Funcionamento do sistema

O funcionamento do irrigador ocorre a partir da leitura da umidade do solo realizada pelo sensor capacitivo. Os dados são enviados ao ESP32, que compara a umidade medida com o valor desejado.

Com base nessa diferença, o controlador PID calcula a intensidade de acionamento da bomba, permitindo ajustar a irrigação de acordo com as condições identificadas.

O sistema também disponibiliza informações e parâmetros de funcionamento por meio da plataforma Blynk.

## Componentes utilizados

* ESP32
* Sensor capacitivo de umidade do solo HW-390
* Sensor de temperatura e umidade DHT22
* Sensor de chuva FC-37
* Ponte H L298N
* Bomba d'água RS-385
* Reservatório de água
* Mangueira para irrigação
* Fonte de alimentação e regulador de tensão

## Tecnologias utilizadas

* C++ (Arduino IDE)
* ESP32
* Blynk IoT
* MQTT
* Controle PID

## Registros do projeto

Nesta seção serão disponibilizadas fotografias e vídeos que demonstram as etapas de desenvolvimento, montagem e funcionamento do protótipo.

### Fotografias

*As imagens serão adicionadas conforme a organização dos registros experimentais.*

### Vídeos demonstrativos

*Os vídeos de funcionamento do sistema serão disponibilizados nesta seção.*

## Código-fonte

O código-fonte utilizado no desenvolvimento do sistema está disponível neste repositório, incluindo a implementação do controlador PID, leitura dos sensores, acionamento da bomba e comunicação com a plataforma IoT.

## Resultados experimentais

Esta seção apresenta os dados obtidos durante os experimentos, incluindo registros de umidade do solo, comportamento do controlador, volume de água utilizado e comparação entre os métodos de irrigação.

Os resultados serão apresentados juntamente com as respectivas análises realizadas no trabalho.

## Documentação completa

O documento completo do Trabalho de Conclusão de Curso está disponível abaixo:

**[Visualizar TCC em PDF](documentos/TCC.pdf)**

## Autores

* Bruno Ricci Zanoni
* Giulio Passetti Figueiredo

**Instituição:** Universidade São Francisco (USF)
**Curso:** Engenharia de Computação
**Orientador:** Luiz Carlos Freitas Junior

---

Este repositório reúne os materiais complementares desenvolvidos durante a realização do Trabalho de Conclusão de Curso.
