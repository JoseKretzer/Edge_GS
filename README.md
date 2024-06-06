Projeto de Monitoramento de Qualidade da Água
Este projeto utiliza um Arduino para monitorar a qualidade da água, medindo os níveis de pH, temperatura e oxigenação. As leituras são exibidas em um display LCD e transmitidas via Serial em formato JSON.

Componentes Necessários
Arduino (UNO, Mega, etc.)
Display LCD I2C (20x4)
Sensores de pH, temperatura e oxigenação
Jumpers e protoboard
Bibliotecas Utilizadas
LiquidCrystal_I2C: Para controlar o display LCD I2C.
ArduinoJson: Para formatar os dados em JSON e enviá-los via Serial.
Funcionalidades
Exibição dos Dados no LCD: O display LCD mostra os valores de pH, temperatura e oxigenação da água em tempo real.
Envio dos Dados via Serial: Os dados coletados são enviados via Serial em formato JSON para facilitar a integração com outros sistemas.
