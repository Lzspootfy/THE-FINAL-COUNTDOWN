🟥🟩🟦 **Regras do Jogo** 🟦🟩🟥  

1️⃣ O **LED RGB** pisca uma sequência de **três cores** (também mostrada no **LCD**).  
2️⃣ O jogador deve **repetir a sequência** usando os botões:  

   🔹 **Botão A** → 🟩 **Verde**  
   🔹 **Botão B** → 🟦 **Azul**  
   🔹 **Botão do Joystick** → 🟥 **Vermelho**  

3️⃣ **Se errar** o jogo **recomeça**.  

🚀🎮 **Que os reflexos estejam com você!** 🎮🚀  


# Jogo da Memória - BitDogLab

Este é um jogo da memória implementado na placa **BitDogLab** utilizando um **LED RGB**, **Joystick**, **LCD** e **buzzer**. O objetivo do jogo é repetir corretamente a sequência de cores gerada pelo sistema.

## 🎮 Como Funciona
1. O **LED RGB** pisca uma sequência de **três cores**.
2. A sequência também é exibida no **LCD**.
3. O jogador deve repetir a sequência pressionando os botões correspondentes:
   - **Botão A** → 🟩 **Verde**
   - **Botão B** → 🟦 **Azul**
   - **Botão do Joystick** → 🟥 **Vermelho**
4. **Se acertar**, um som de acerto é tocado e a dificuldade aumenta.
5. **Se errar**, um som de erro é tocado e o jogo recomeça.

## 📌 Requisitos
- **Placa**: BitDogLab
- **Componentes**:
  - LED RGB
  - Joystick
  - LCD
  - Buzzer
- **Bibliotecas Utilizadas**:
  - `pico/stdlib.h`
  - `pico/stdio_usb.h`
  - `hardware/i2c.h`
  - `hardware/uart.h`
  - `hardware/timer.h`
  - `hardware/clocks.h`
  - `ws2812.pio.h`
  - `ssd1306.h`
  - `led_matrix.h`
  - `font.h`

## 🔧 Configuração dos Pinos
| Componente       | GPIO |
|------------------|------|
| Botão A        | 5    |
| Botão B        | 6    |
| Joystick        | 22   |
| LED RGB (Red)   | 13   |
| LED RGB (Green) | 11   |
| LED RGB (Blue)  | 12   |
| LCD (SDA)       | 14   |
| LCD (SCL)       | 15   |

## 🚀 Como Executar
1. Compile o código-fonte e faça o upload para a placa BitDogLab.
2. Reinicie a placa.
3. Aguarde a exibição da mensagem "REFLEX GAME" no LCD.
4. Memorize a sequência de cores mostrada pelo LED RGB.
5. Repita a sequência utilizando os botões.
6. Veja no LCD se acertou ou errou e tente superar seu recorde! 🎯

## 📌 Observações
- A sequência aumenta de dificuldade conforme o jogador acerta.
- O tempo de resposta é reduzido conforme o progresso.
- Se errar, a rodada recomeça com uma nova sequência.

Divirta-se testando seus reflexos e memória! 🚀🎮

