Teoria de funcionamento
O funcionamento do sistema baseia-se na detecção da intensidade luminosa por meio de um
fotodiodo. Quando a luz atravessa ou é transmitida por uma amostra, uma parte dessa radiação pode
ser absorvida pela substância. A quantidade de luz que chega ao detector, portanto, está relacionada às
propriedades ópticas da amostra.

O fotodiodo converte a luz incidente em um pequeno sinal elétrico, cuja intensidade varia de acordo
com a quantidade de radiação recebida. Como esse sinal pode ser muito pequeno, utiliza-se o LM358
como amplificador operacional para amplificar e tornar o sinal produzido pelo fotodiodo mais
adequado para medição.
O resistor participa do circuito de conversão e condicionamento do sinal elétrico produzido pelo
fotodiodo, enquanto a bateria fornece a alimentação necessária ao circuito. O protoboard permite
realizar as conexões entre os componentes de maneira simples e adequada para um protótipo didático.
De forma simplificada, o processo pode ser representado como:
Fonte de luz → amostra → fotodiodo → sinal elétrico → amplificação pelo LM358 → medição
A partir da comparação entre a intensidade da luz incidente e a intensidade da luz transmitida pela
amostra, pode-se avaliar quanto da radiação foi absorvida. Essa relação é a base da
espectrofotometria, técnica amplamente utilizada para caracterizar substâncias e determinar
concentrações.

A absorção pode ser expressa pela absorbância (A), calculada pela seguinte relação:

A = -log10(I / I₀)
onde:
A = absorbância;
I₀ = intensidade da luz incidente, antes de atravessar a amostra;
I = intensidade da luz transmitida pela amostra.

Assim, quanto menor for a intensidade de luz transmitida em relação à intensidade incidente, maior
será a absorbância da amostra.
O projeto demonstra, de maneira experimental e acessível, a relação entre luz, interação com a
matéria e conversão de uma grandeza óptica em um sinal elétrico mensurável, permitindo sua
utilização como ferramenta de ensino na disciplina de Métodos Biofísicos de Análise.
