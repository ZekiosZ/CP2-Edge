# 🍷 Sistema de Monitoramento Ambiental – Vinharia Agnello

Este projeto simula um sistema inteligente de monitoramento ambiental desenvolvido para a **vinharia fictícia Agnello**. Utilizando uma placa Arduino, sensores diversos e uma tela LCD, o sistema monitora **luminosidade**, **umidade** e **temperatura**, garantindo que os vinhos sejam armazenados em condições ideais.

🔗 [Acesse o projeto no Wokwi](https://wokwi.com/projects/430694768548792321)

---

## 🧰 Componentes Utilizados

- Arduino Uno  
- Sensor DHT22 (temperatura e umidade)  
- Sensor LDR (luminosidade)  
- LEDs (vermelho, amarelo, verde)  
- Buzzer  
- Display LCD 16x2 com interface I2C  
- Resistores  
- Cabos jumpers  
- Protoboard virtual (simulado no Wokwi)

---

## 🎯 Objetivo

O sistema visa monitorar continuamente as condições ambientais em uma adega, com os seguintes critérios:

| Parâmetro     | Condições Monitoradas                | Ação do Sistema                         |
|---------------|--------------------------------------|------------------------------------------|
| Temperatura   | Alta ou baixa demais                 | LED vermelho + som de buzzer             |
| Umidade       | Alta ou baixa demais                 | LED amarelo + som de buzzer              |
| Luminosidade  | Luz ideal                            | LED verde                                |
| Todos         | Exibição ao vivo no display LCD      |                                          |

A detecção de **valores fora da faixa ideal** aciona LEDs específicos e um **buzzer de alerta sonoro**.

---

## 🖥️ Interface LCD

A tela LCD 16x2 exibe em tempo real:
- Temperatura atual
- Umidade relativa do ar
- Estado da luminosidade

Isso permite um monitoramento local direto, facilitando o controle ambiental da adega.

---

## ▶️ Como Executar

1. Acesse o link do projeto no Wokwi.
2. Clique em **“Start Simulation”**.
3. Observe:
   - Os valores em tempo real no display LCD.
   - LEDs acendendo conforme as condições ambientais.
   - O buzzer acionando em situações críticas (temperatura/umidade fora dos limites).

---

## 🌱 Possíveis Expansões

- Integração com módulo Wi-Fi (ESP32) para envio remoto dos dados
- Registro de dados em cartão SD ou banco de dados online
- Sistema de automação (ex: ativar ventilação ou iluminação conforme necessidade)

---

## 👥 Integrantes do Grupo

- **Walter Henrique Pereira de Toledo** – RM: 562476  
- **Arthur Serrano Veloso** – RM: 561542  
- **Hyann dos Santos Espindas** – RM: 563421  
- **José Rafael Tejeda Mantilla** – RM: 561849  
- **Theodoro Sievers** – RM: 562036  

---
