# Exercicio031.py
#Desenvolva um programa que pergunte a distância de uma viagem em Km. Calcule o preço da passagem, cobrando R$0,50 por Km para viagens de até 200Km e R$0,45 parta viagens mais longas.

t = float(input('Digite a distancia: '))

'''if t <= 200:
    passagem = t * 0.50
else:
    passagem = t * 0.45'''

passagem = t * 0.50 if t <= 200 else t * 0.45

print('sua passagem é de: {:.2f}'.format(passagem))
