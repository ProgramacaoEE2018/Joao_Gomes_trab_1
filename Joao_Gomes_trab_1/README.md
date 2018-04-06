# Joao_Gomes_trab_1
Inicialmente, foi criada uma coluna "Notas VE" para receber as notas de VE como entradas
nas células da coluna 'A', de forma ordenada, sem necessitar colocar valores nas células
após ter colocado todas as notas existentes.
Note que, foram colocadas 31 células para Notas de VE, visando uma extrapolação do número
de provas de VE realizadas (31 dias no mês = 31 notas de VE no máximo).
Após isso, foi criada uma coluna "Nota VC" para receber a nota de VC como entrada em uma
única célula.
Note, também, que a coluna 'F' foi ocultada na planilha, a fim de torná-la mais visual.
Na célula 'F4', foi colocada uma função, para que a célula 'F4' armazenasse a média de VE.
A função utilizada foi:
	'=SE(ÉCÉL.VAZIA(A2);0;MÉDIA(A2:A32))'
Além disso, foi criada uma terceira coluna "Nota necessária na VF" para fornecer como saída
a nota necessária na VF. Então, na célula para isso destinada, foi colocada a seguinte
função:
	'=SE((20-(F4+B2))/2<4;4;(20-(F4+B2))/2)'
Por fim, esse é o funcionamento do meu programa.