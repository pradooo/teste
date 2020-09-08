# teste
teste calculadora
#declaracao das variaveis
num1 = float(input("Digite o primeiro valor: "))
num2 = float(input("Digite o segundo valor: "))
#menu de operacoes
print("Menu\n1 - SOMA\n2 - SUBTRACAO\n3 - MULTIPLICACAO\n4 - DIVISAO")
#variavel menu
menu = int(input("Digite a operacao desejada: "))
#condicoes
if (menu==1):
  soma = num1 + num2
  print(soma)
  
elif(menu==2):
  sub = num1 - num2
  print(sub)
  
elif(menu==3):
  mult = num1*num2
  print(mult)
  
elif(menu==4):
  div = num1/num2
  print(div)
  
else:
  print("Opcao invalida")
  
