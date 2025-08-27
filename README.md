# Passo a Passo para Montagem de um Servo Motor com ESP32

## 1° Passo: Conectar a placa ESP32 na protoboard
![foto](https://github.com/CaioHMAquino/ESP32ServoMotor/blob/main/imagens/esp32%20na%20board.jpeg)

## 2° Passo: Identifique onde cada cabo deve ser conectado no Servo Motor
![foto](https://github.com/CaioHMAquino/ESP32ServoMotor/blob/main/imagens/Conex%C3%A3o%20dos%20Fios.jpeg)

**Legenda:**
- Marrom/Roxo indica o GND/Ground
- Vermelho indica V+/Energia (5V)
- Amarelo indica o cabo Digital

## 3° Passo: Conecte os cabos no Motor e na Protoboard
![foto](https://github.com/CaioHMAquino/ESP32ServoMotor/blob/main/imagens/Resultado%20das%20liga%C3%A7%C3%B5es.jpeg)

## 4° Passo: Faça a programação para ser passada pelo cabo digital
![foto](https://github.com/CaioHMAquino/ESP32ServoMotor/blob/main/imagens/Programa%C3%A7%C3%A3o.jpeg)

**Legenda:**
- Esta programação faz o motor, ligado no pino digital 18, girar sua hélice em 90° a cada 1 segundo (o Servo Motor apenas gira em 180°, após chegar neste limite ele fará o processo inverso, como apresentado no loop do código), utilizando a biblioteca ESP32Servo.
- O driver CP210 é necessário para conectar o ESP32 ao Arduino IDE.

## 5° Passo: Envie a programação para o ESP32 através de um cabo e utilizando o programa Arduino IDE
![foto](https://github.com/CaioHMAquino/ESP32ServoMotor/blob/main/imagens/transfer%C3%AAncia%20de%20dados.jpeg)

**Legenda:**
- O cabo utilizado para transferência de dados foi um cabo micro-USB.

**Aviso:** 
- Imagem apresentada apenas exibe o cabo e a placa conectados no computador, nenhum outro componente está em uso.

## Observação:
Em alguns modelos do ESP32 pode ser necessário segurar o botão **BOOT** para permitir que a programação seja enviada.
