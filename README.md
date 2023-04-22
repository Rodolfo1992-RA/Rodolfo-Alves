# Rodolfo-Alves
n = int(input('numero: '))
par = n % 2

if n % 2 != 0:
  print('Weird')

if n % 2 == par and n in range(2,5):
  print('not Weird')

elif n % 2 == par and n in range(6,20):
  print('Weid')

else:
  if n % 2 == par and n > 20:
    print('not Weird')
