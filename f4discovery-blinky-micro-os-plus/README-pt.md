# Blinky demo para STM32F4DISCOVERY, usando µOS++

Este programa de demonstração pisca os quatro LEDs no STM32F4DISCOVERY.

Ele demonstra:

 - Como organizar o projeto usando o conteúdo de vários xPacks, incluindo o 
   código do **µOS++ IIIe / CMSIS++**;
 - Como integrar o código de inicialização do CubeMX
 
Este projeto **não** demonstra alguma recurso do µOS++, o único recurso de RTOS
usado é o relógio de sistema `sleep_for()`, para atrasar a execução por um número 
de ticks.

Até o utilitário XCDL estár disponível, a pasta de `preparação` (generated)
é criada com o script `scripts/generate.sh`.