# Joao_Gomes_trab_1
Inicialmente, foi criada uma coluna "Notas VE" para receber as notas de VE como entradas
nas c�lulas da coluna 'A', de forma ordenada, sem necessitar colocar valores nas c�lulas
ap�s ter colocado todas as notas existentes.
Note que, foram colocadas 31 c�lulas para Notas de VE, visando uma extrapola��o do n�mero
de provas de VE realizadas (31 dias no m�s = 31 notas de VE no m�ximo).
Ap�s isso, foi criada uma coluna "Nota VC" para receber a nota de VC como entrada em uma
�nica c�lula.
Note, tamb�m, que a coluna 'F' foi ocultada na planilha, a fim de torn�-la mais visual.
Na c�lula 'F4', foi colocada uma fun��o, para que a c�lula 'F4' armazenasse a m�dia de VE.
A fun��o utilizada foi:
	'=SE(�C�L.VAZIA(A2);0;M�DIA(A2:A32))'
Al�m disso, foi criada uma terceira coluna "Nota necess�ria na VF" para fornecer como sa�da
a nota necess�ria na VF. Ent�o, na c�lula para isso destinada, foi colocada a seguinte
fun��o:
	'=SE((20-(F4+B2))/2<4;4;(20-(F4+B2))/2)'
Por fim, esse � o funcionamento do meu programa.