# Eletronica e Eletricidade básica

INTRODUÇÃO
- Eletricidade: Altas potencias e baixas potencias (Sistemas de abastecimento)
- Eletronica: Baixas potencias e altas frequencias (celular)

Aplicativos Simuladores
AUTODESK TINKERCAD: https://www.tinkercad.com/dashboard
CIRCUIT SIMULATOR APPLET: https://www.falstad.com/circuit/


# Circuitos elétricos:

1. TENSÃO (Voltagem):
A tensão é como a pressão da água em um cano. Quanto maior a pressão, mais rápido a água (ou a eletricidade) vai fluir.

    Em termos elétricos, a tensão é o que "empurra" os elétrons pelo circuito. Ela é medida em volts (V).
    Exemplo: Se você tiver uma pilha de 9V, ela está aplicando uma tensão de 9 volts, empurrando a corrente através do circuito.


2. Corrente - "Fluxo de água"

A corrente é a quantidade de água que flui pelo cano. Em eletricidade, é a quantidade de elétrons que passam por um ponto do circuito a cada segundo.

    Em termos elétricos, a corrente é medida em amperes (A).
    Exemplo: Se você tiver um fio e uma lâmpada conectados, a corrente é a quantidade de eletricidade que flui pelo fio até a lâmpada.


3. Resistência - "Obstrução no cano"

A resistência é como o tamanho do cano ou obstáculos dentro dele que dificultam o fluxo da água. Quanto maior a resistência, menos água (ou eletricidade) vai passar.

    Em termos elétricos, a resistência é medida em ohms (Ω).
    Exemplo: Se você colocar um fio fino no lugar de um grosso, a resistência aumenta, dificultando o fluxo de corrente.


# Lei de Ohm (V = I × R)

A Lei de Ohm é a relação entre tensão (V), corrente (I) e resistência (R). Ela afirma que a tensão em um resistor é igual à corrente que passa por ele multiplicada pela sua resistência.

Fórmula:
V=I×RV=I×R

    V (Tensão): Medido em volts (V).
    I (Corrente): Medido em amperes (A).
    R (Resistência): Medido em ohms (Ω).

Exemplo:
Imagine um resistor de 10Ω e uma corrente de 2A passando por ele. Qual é a tensão?
V = I × R = 2A × 10Ω = 20V
Ou seja, a tensão que precisa ser aplicada para que a corrente de 2A passe por esse resistor é 20V.


# Leis de Kirchhoff

As Leis de Kirchhoff são duas regras que ajudam a analisar a distribuição de corrente e tensão em circuitos mais complexos.

1. Lei das Correntes de Kirchhoff (LCK)

A LCK afirma que a soma das correntes que entram em um nó (ponto de interseção de fios) é igual à soma das correntes que saem desse nó. Isso é devido à conservação de carga elétrica.

Fórmula:
∑Ientrando = ∑Isaindo

Exemplo:
Em um ponto (nó) de um circuito, se a corrente que entra é 5A e 3A, a corrente que sai deve ser 8A.
Lei das Tensões de Kirchhoff (LTK)

A LTK afirma que a soma das tensões ao longo de qualquer malha fechada de um circuito é igual a zero. Isso porque a energia elétrica fornecida pelas fontes de tensão é consumida pelos componentes resistivos.

Fórmula:
∑Vfontes = ∑Vresistores

Exemplo:
Se você tiver uma malha com uma fonte de 12V e dois resistores (um de 4Ω e outro de 2Ω), a soma das quedas de tensão nos resistores deve ser igual a 12V.
Como Usar as Leis de Kirchhoff em Prática?

    Primeiro, identifique as fontes de tensão e as correntes no circuito.
    Segundo, aplique a Lei das Correntes de Kirchhoff (LCK) nos nós para balancear as correntes.
    Terceiro, aplique a Lei das Tensões de Kirchhoff (LTK) nas malhas para balancear as tensões.

Exemplo Prático

Considerando um circuito com três resistores e uma fonte de 12V, podemos usar as leis para calcular as correntes e as quedas de tensão. Vamos supor que tenhamos resistores de 4Ω, 2Ω e 6Ω conectados em série com a fonte. Primeiro, calculamos a resistência total:

Rtotal = 4Ω + 2Ω + 6Ω = 12Ω

Agora, usando a Lei de Ohm, podemos calcular a corrente:

I = V/R = 12V/12Ω = 1A

Em seguida, usamos a LTK para calcular as quedas de tensão em cada resistor, lembrando que a soma das quedas de tensão precisa ser igual à tensão da fonte.

    Para o resistor de 4Ω: V1 = I × R1 = 1A ×4Ω =4V
    Para o resistor de 2Ω: V2 = I × R2 = 1A ×2Ω =2V
    Para o resistor de 6Ω: V3 = I × R3 = 1A ×6Ω =6V

A soma das quedas de tensão é 4V + 2V + 6V = 12V, o que corresponde à tensão fornecida pela fonte.