# Spy Turtle
O Spy Turtle é um dispositivo multifuncional que combina a tecnologia de sensores de monitoramento da qualidade da água medindo os níveis de pH, temperatura e oxigenação com uma lixeira flutuante para a coleta de resíduos sólidos. Destinado a áreas costeiras, rios, lagos e outras massas de água, o Spy Turtle visa melhorar a saúde dos ecossistemas aquáticos e a qualidade da água. As leituras são exibidas em um display LCD e transmitidas via Serial em formato JSON.

## Componentes Necessários:
Arduino (UNO, Mega, etc.)

Display LCD I2C (20x4)

Potenciometro

Jumpers e protoboard
## Bibliotecas Utilizadas:
LiquidCrystal_I2C: Para controlar o display LCD I2C.

ArduinoJson: Para formatar os dados em JSON e enviá-los via Serial.
## Funcionalidades:
Exibição dos Dados no LCD: O display LCD mostra os valores de pH, temperatura e oxigenação da água em tempo real.

Envio dos Dados via Serial: Os dados coletados são enviados via Serial em formato JSON para facilitar a integração com outros sistemas.

## Como Usar:
Montagem do Circuito: Conecte os sensores ao Arduino conforme o mapeamento dos pinos (A0 para oxigenação, A1 para temperatura, A2 para pH).

Carregamento do Código: Faça o upload do código para o Arduino usando a IDE do Arduino.

Monitoramento: Use o Monitor Serial da IDE do Arduino para visualizar os dados em JSON e veja as leituras no display LCD.

### Integrantes do grupo:
JOSE ANTONIO KRETZER RODRIGUEZ (RM: 555523)

VICTOR ALVES DE SOUZA (RM: 555761)
