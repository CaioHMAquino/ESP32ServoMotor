# Passo a Passo para Montagem de um Servo Motor com ESP32

## 1° Passo: Conectar a placa ESP32 na protoboard
![foto]((https://github.com/CaioHMAquino/ESP32ServoMotor/blob/main/imagens/esp32%20na%20board.jpeg))

## 2° Passo: Identifique onde cada cabo deve ser conectado no Servo Motor
![foto](URL_DA_IMAGEM)

**Legenda:**
- Marrom indica o GND/Ground
- Vermelho indica V+/Energia (5V)
- Amarelo indica o cabo Digital

## 3° Passo: Conecte os cabos no Motor e na Protoboard
![foto](URL_DA_IMAGEM)

## 4° Passo: Faça a programação para ser passada pelo cabo digital
![foto](URL_DA_IMAGEM)

**Legenda:**
- Esta programação faz o motor girar sua hélice a cada 90°, utilizando a biblioteca ESP32Servo.
- O driver CP210 é necessário para conectar o ESP32 ao Arduino IDE.

## 5° Passo: Envie a programação para o ESP32 através de um cabo e utilizando o programa Arduino IDE
![foto](URL_DA_IMAGEM)

**Legenda:**
- O cabo utilizado para transferência de dados foi um cabo micro-USB.
**Aviso:** Imagem apresentada apenas exibe o cabo e a placa conectados no computador, nenhum outro componente está em uso.

## Observação:
Em alguns modelos do ESP32 pode ser necessário segurar o botão **BOOT** para permitir que a programação seja enviada.
