print('Olá, tudo bem? A seguir a calculadora de IMC')

peso = float(input('Digite seu peso em KG: '))
altura = float(input('Digite sua altura em Metros: '))

imc = peso / (altura ** 2)

print(f'Seu IMC é: {imc:.2f}')

if imc <18.5:
  print('abaixo do peso.')

elif imc <24.9:
  print('peso normal.')

else:
  print ('sobrepeso')
