# Advent_of_Code_23

## Day 1: Trebuchet?!
Desafio:
O objetivo era calcular a soma de todos os valores(números) presentes em um documento.
Cada linha do documento continha um valor que era formado pelos primeiros e últimos dígitos da linha, combinados para formar um número de dois dígitos.

Exemplo:
1abc2 -> 12
pqr3stu8vwx -> 38
a1b2c3d4e5f -> 15
treb7uchet -> 77

Parte dois:
Na parte dois, alguns dígitos foram escritos com letras (one, two, three, ..., nine), que também são válidos como dígitos.
Foi necessário encontrar  o primeiro e o último dígito real em cada linha e calcular a soma de todos os valores. 


## Day 2: Cube Conundrum
Desafio:
O objetivo era determinar quais jogos eram possíveis dado um número limitado de cubos de cores diferentes dentro de uma bolsa.
Cada jogo foi listado com subconjuntos de cubos revelados da bolsa.
Foi necessário verificar se todos os subconjuntos poderiam ser extraídos da bolsa sem exceder os limites estabelecidos.

Exemplo:
Jogo 1: 3 azul, 4 vermelho; 1 vermelho, 2 verde, 6 azul; 2 verde
Jogo 2: 1 azul, 2 verde; 3 verde, 4 azul, 1 vermelho; 1 verde, 1 azul
...

Limites:
12 cubos vermelhos, 13 cubos verdes, 14 cubos azuis.

Parte dois:
Para cada jogo, era necessário determinar o menor número de cubos de cada cor que estava presente na bolsa para que o jogo fosse possível.
Tinha que calcular a soma dos produtos desses números para todos os jogos.


## Day 4: Scratchcards
Desafio:
Precisava calcular quantos pontos valiam os cartões de raspadinha que possuem listas de números vencedores e números que o "usuário" possuia.
Cada número vencedor encontrado no conjunto do usuário duplicava o valor do cartão, começando com 1 ponto para o primeiro acerto.

Exemplo:
Card 1: 41 48 83 86 17 | 83 86 6 31 17 9 48 53
Card 2: 13 32 20 16 61 | 61 30 68 82 17 32 24 19
Card 3: 1 21 53 59 44 | 69 82 63 72 16 21 14 1
Card 4: 41 92 73 84 69 | 59 84 76 51 58 5 54 83
Card 5: 87 83 26 28 32 | 88 30 70 12 93 22 82 36
Card 6: 31 18 13 56 72 | 74 77 10 23 35 67 36 11

Parte dois:
Processando os cartões de raspadinha e suas cópias, era necessário determinar com quantos cartões de raspadinha o usuário acabaria no total, incluindo os originais.


