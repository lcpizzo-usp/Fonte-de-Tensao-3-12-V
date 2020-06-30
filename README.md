# Fonte de Tensão Ajustável
Fonte de tensão ajustável desenvolvida para a disciplina [SSC0180 - Eletrônica para Computação](https://uspdigital.usp.br/jupiterweb/obterDisciplina?sgldis=SSC0180&verdis=2) do Curso de Ciência da Computação da USP - São Carlos

## Lista de Componentes
Componente           | Especificações            | Quantidade          | Valor (un.)        
:--------------------|:--------------------------|:--------------------|:-------------
[Resistor](https://www.baudaeletronica.com.br/resistor-200r-5-1-4w.html)      | 200RΩ | 1 |   R$0,08
[Resistor](https://www.baudaeletronica.com.br/resistor-2k-5-1-4w.html)      | 2k Ω | 1 |   R$0,08
[Potenciômetro](https://www.baudaeletronica.com.br/potenciometro-linear-de-10k-10000.html) | 10k | 1 | R$1,54
[Capacitor](https://www.baudaeletronica.com.br/capacitor-eletrolitico-470uf-16v.html)     | 470μF | 1 |   R$0,43
[Diodo](https://www.baudaeletronica.com.br/diodo-zener-zmm-22v-0-5w.html)         | 22V / 0,5W | 4 |   R$0,15
[Diodo Zener](https://www.baudaeletronica.com.br/diodo-zener-bzx55c-36v-0-5w.html)  | 13V / 0,5W | 1 | 0,09
[Transistor](https://www.baudaeletronica.com.br/transistor-npn-2n3904.html)    | 2N3904 | 1 |   R$0,18 
[Transformador](https://www.baudaeletronica.com.br/transformador-trafo-1a-24v.html) | 12V / 0,5mA | 1 |   R$36,00

Total: R$39,00

### Explicação dos Componentes
1. Transformador: O transformador é usado para reduzir a tensão da tomada de 127V, no caso, para 24V. Foi usado um transformador com razão 24/127;
2. Diodo: Os diodos são usados em configuração de ponte retificadora de corrente alternada, invertendo uma das fases da corrente alternada;
3. Capacitor: O capacitor é usado para fornecer energia ao circuito em momentos em que a corrente tende a zero;
4. Diodo Zener: O diodo zener é usado para regular a tensão que passa pela saída do circuito;
5. Pontenciômetro: O potenciômetro é usado para ajustar a tensão de saída do circuito;
6. Resistor: o resistor de 200R é usado para reduzir a corrente que passa pelo diodo zener; o resistor de 1k5 é usado para oferecer um "valor mínimo" de 3V no circuito, sem ele, ao reduzir a resistência no potenciômetro a tensão na saída seria zero.
## Imagens
### Simulação do Circuito 
(imagens/falstad.png)
Simulação feita pelo falstad: http://tinyurl.com/y85cx9n7
### Diagrama do Circuito 
(/schematic.png)
### PCB (Printed Circuit Board) 
(/imagens/pcb.png)

## Participantes

* **Leonardo Chagas Pizzo** - [lcpizzo-usp](https://github.com/lcpizzo-usp)
