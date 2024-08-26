# LIsta-exerc-cios-js

Js lista II

Exercício
/*1) Faça um programa no qual o usuário digite dois números e mostre na tela a multiplicação desses números.*/

var numero1, numero2
var resultado

numero1 = prompt('Digite o primeiro número')
numero2 = prompt('Digite o segundo número')
resultado = numero1 * numero2

alert(numero1 + ' * ' + numero2 + ' = ' + resultado)


exercício
/*2) Desenvolva uma programação que peça ao usuário para digitar o ano do seu nascimento no formato (YYYY) e o ano atual também no formato (YYYY).
Em seguida mostre na tela qual a idade do usuário em anos, em meses, em dias e em semanas.*/

var anoNascimento, anoAtual
var anos, meses, semanas, dias

anoNascimento = prompt('Que ano você nasceu?')
anoAtual = prompt('Em que ano estamos?')

anos = anoAtual - anoNascimento
meses = anos * 12
semanas = anos * 52
dias = anos * 365

alert('Acabei de calcular a sua idade em anos: ' + anos + '\nMeses: ' + meses + '\nSemanas: ' + semanas + '\nE dias: ' + dias)

Exercício
/*3) Programar a conversão de uma temperatura digitada pelo usuário em graus Celsius para Fahrenheit. Mostrar o resultado na tela.*/

var celcius, fahrenheit

calcius = prompt('Indique a temperatura em Celcius')

fahrenheit = (celcius * (9/5)) + 32

alert('O resultado é: ' + fahrenheit + 'fahrenheit')

Exercício
/*4) Uma cidade pretende apurar os votos de sua eleição. Faça um programa para ler o número total de eleitores.
 Em seguida o número de votos do candidato X, o número de votos do candidato Y,
 total de votos brancos e total de votos nulos (a soma desses quatro, deve ser igual ao total de eleitores).
 Calcular e escrever o percentual que cada um representa em relação ao total de eleitores.*/

 var eleitores
 var votosCandidatoX, votosCandidatoY
 var votosBrancos, votosNulos
 var somaVotos

 eleitores = prompt('Quantas pessoas votaram na cidade?')
 votosCandidatoX = prompt('Quantas pessoas votaram no candidato X?')
 votosCandidatoY = prompt('Quantas pessoas votaram no canditato Y?')
 votosBrancos = prompt('Quantas pessoas votaram em branco?')
 votosNulos = prompt('Quantas pessoas votaram nulo?')
somaVotos = eleitores + votosCandidatoX + votosCandidatoY + votosBrancos + votosNulos

if (somaVotos != eleitores) {
    alert('Verifique se você digitou o numero corretamente')
}

alert('A quantidade de votos para o candidato X foi de ' + votosCandidatoX / eleitores + '% do total de eleitores')
alert('A quantidade de votos para o candidato Y foi de ' + votosCandidatoY / eleitores + '% do total de eleitores')
alert('A quantidade de votos Brancos foi de ' + votosBrancos / eleitores + '% do total de eleitores')
alert('A quantidade de votos nulos foi de ' + votosNulos / eleitores + '% do total de eleitores')

Exercício
/*5) Criar um programa que calcule o IMC, no qual o usuário deve digitar o seu peso e altura, realizar o cálculo (peso / altura * altura) e mostrar o resultado na tela. */

var peso, altura
var resultado

peso = prompt('Qual é o seu peso?')
altura = prompt('Quan é a sua altura?')
resultado = peso / altura * altura

alert('O seu IMC é de valor: ' + resultado)

Exercício
/*6) Em uma fábrica de reciclagem de materiais, cada 10kg de plástico rendem R$2,00 cada 30kg de papel rendem R$3,00 e cada 50kg de metal rendem R$5,00.
Perguntar ao usuário a quantidade (kg) de cada material que deseja entregar na fábrica e mostrar o total que receberá em reais.*/

var plastico, papel, metal

plastico = prompt('Quantos kilos de plastico você têm')
papel = prompt('Quantos kilos de papel você têm')
metal = prompt('Quantos kilos de papel você')

alert('Baseado nos pesos, com suas vendas você ganhara ' + plastico * 0,2 + ' reais de plástico, ' + papel * 0,1 + ' reais de papel, e ' + metal * 0,1 + 'reais de metal.')

Exercício
/*7) Em uma festa de família alemã, 45 pessoas foram convidadas para beber. Para tanto, foram comprados 300 litros de chopp.
Criar um programa que calcule a média de litros bebidos por pessoa, considerando ainda a quantidade de chopp (litros) desperdiçado e a quantidade de chopp (litros) que sobrou.
Esses dados devem ser digitados pelo usuário.
Caso não tenha havido desperdício e não tenha sobrado chopp, digitar 0 para ambos. Ao final, mostrar a média de litros bebidos por pessoa na festa.*/

var choppDesperdiçado, sobraChopp
var mediaChopp

choppDesperdiçado = prompt('Quantos litros de chopp foram desperdiçados(digite 0 se não ouve desperdicio)?')
sobraChopp = prompt('Quantos litreos de chopp sobraram(digite 0 se não ouve desperdicio)?')
mediaChopp = 300 - choppDesperdiçado - sobraChopp / 45


