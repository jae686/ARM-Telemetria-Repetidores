# Sistema de Telemetria para instalação nos repetidores da ARM

## Objetivo

Desenvolver sistema para monitorar os repetidores da ARM (também referido como telemetria), entre os quais repetidores que estão dependentes de combinação de painel solar + bateria.

## Requisitos

- Medição da Tensão e Corrente:
  - Consumo de corrente do repetidor
  - Valor da tensão da bateria
  - Potencia fornecida pelo painel solar a bateria
- Registro local dos dados, em cartão SD.
- Envio dos dados via Meshcore para recolha remota dos dados.
- Deve ter o menor consumo energético possivel

>[!NOTE]
> O Uso do meshcore está a ser considerado devido a possibilidade da instalação de um repetidor na mesma localização do repetidor da Serra da Cabreira.

## Hardware candidato

| Componente | Nome | Preço |
| ---------- | ---- | ----- |
| Modulo Wifi / LoRA | [Heltec V3 433MHz - Kit desenvolvimento WiFi LoRa 32 (V3) 433MHz com ecrã oled integrado](https://mauser.pt/095-9148/heltec-v3-433mhz-kit-desenvolvimento-wifi-lora-32-v3-433mhz-com-ecra-oled-integrado) | 25,85 |
| Sensor Corrente e Tensão | [JOY-IT SBC-DVA](https://mauser.pt/095-4225/joy-it-sbc-dva-modulo-de-monitorizacao-de-corrente-e-tensao-i2c-compativel-com-arduino) | 8,91 |


## Status Atual

30.05.2026 - Inicio da definição dos requisitos.


