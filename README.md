# Placar com Display de 7 Segmentos e Contador

Este é um módulo em Verilog que implementa um placar com display de 7 segmentos e um contador em uma FPGA. Ele é projetado para ser utilizado em placas ou circuitos que exigem a exibição de contagens e cronometragem em displays de 7 segmentos.

## Funcionalidades

- **Entradas e Saídas**: Define entradas e saídas para sinais de controle, botões, sinais de clock e blocos de display de 7 segmentos.
- **Acumulador de 7 Bits**: Realiza operações de soma/subtração binária com entrada dos botões para controlar o placar.
- **Contador de 5 Bits**: Implementa um contador controlado por um clock externo, com funcionalidades de pausa e reinício.
- **Conversão Binário para BCD**: Converte valores binários do contador e do acumulador para código BCD.
- **Comparação de Valores BCD**: Compara o valor BCD do placar com 99 para gerar um alerta se exceder esse valor.
- **Conversão BCD para 7 Segmentos**: Converte valores BCD do contador e do cronômetro para exibição em displays de 7 segmentos.
- **Divisor de Frequência e Demultiplexador**: Divide o sinal de clock para controlar os blocos de display de 7 segmentos individualmente.
- **Multiplexador de Saída**: Seleciona os valores corretos para exibição nos displays de 7 segmentos com base no estado do contador e do cronômetro.

## Como Usar

1. Integre o módulo em seu projeto Verilog.
2. Conecte as entradas e saídas do módulo conforme necessário para interagir com seu sistema.
3. Certifique-se de fornecer os sinais de controle apropriados para operar o placar e o contador.
4. Utilize os botões conectados às entradas para controlar a contagem e operações do placar.


