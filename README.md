# PROBLEMA-1870-URI

Em um feriado, os empregados da empresa fabricante de ventiladores Irmãos Fulano, mais conhecida como IF, propuseram uma gincana. Dada uma caixa retangular, de grandes dimensões, formadas por compartimentos, contendo apenas a parede frontal e traseira, com todos os compartimentos acessíveis internamente, ventiladores pequenos, mas potentes, e sem a grade de proteção, foram amarrados internamente na caixa, em alguns compartimentos. Após isto, um balão é solto dentro da caixa, na reta de uma determinada coluna de compartimentos. Cada ventilador estará ligado com um determinado nível de força. Então, é verificado o ventilador mais próximo à esquerda e à direita do balão. Se ambos estiverem com o mesmo nível de força, o balão continua descendo normalmente. Caso seja diferente, o balão será empurrado para o lado do ventilador com o nível mais fraco, e o mesmo se deslocará tantas colunas forem a diferença entre o maior nível e o menor entre os ventiladores. Veja o caso abaixo em todos os detalhes:

Balão solto na coluna 6;
Na primeira linha, o ventilador mais próximo à direita do balão tem dois níveis a mais que o mais próximo da esquerda, deslocando o balão para a coluna 4;
Na segunda linha, o ventilador mais próximo à direita do balão tem dois níveis a mais que o mais próximo da esquerda, deslocando o balão para a coluna 2;
Na terceira linha, o ventilador mais próximo à direita do balão tem o mesmo nível em relação ao mais próximo da esquerda, mantendo o balão na coluna 2;
Na quarta linha, o ventilador mais próximo à direita do balão tem dois níveis a menos que o mais próximo da esquerda, deslocando o balão para a coluna 4, saindo sem estourar;
Se, na mesma caixa, o balão fosse solto na coluna 2, o balão teria estourado na linha 1 e coluna 1, nas hélices do ventilador que se encontra neste local.

Escreva um programa que, dada uma matriz, representando a caixa e uma coluna, na qual o balão será solto, e verifique se o mesmo passa por todos os ventiladores sem estourar.
