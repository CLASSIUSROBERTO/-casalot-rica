# -casalot-rica
Programa que faz o cálculo de jogos de todas os níveis de 6 até 15 dezenas faz o troco e retorna.#funcões
'''def sena6(valor,valorjogo):
  s6=valor//valorjogo
  print(s6)
  
def sena7(a,b):
    s7=a+b
    print(s7)

def sena8(a,b):
    s8=a+b
    print(s8)

  ##programa principal

sena6(100,3.5)'''

#loteria
#constantes
aposta6 = (3.50)
aposta7 = (24.50)
aposta8 = (98.00)
aposta9 = (294.00)
aposta10 = (735.00)
aposta11 = (1617.00)
aposta12 = (3234.00)
aposta13 = (6006.00)
aposta14 = (10510.50)
aposta15 = (17517.50)
#variáveis
aposta = (0)
troco = (0)
quant_num = (0)
valor = (0)
lista=(0)
menu=()


import random
#estrutura condicionais do sistema
while valor < aposta6:
    valor = int(input('Digite o valor em R$ a  ser apostado: '))
    while valor < aposta6:
        print('valor minimo de', aposta6)
        break

while quant_num < 6 or quant_num > 15:
    quant_num = int(
        input('Digite a quantidade de números a ser apostado no  cartão:  '))
    while quant_num < 6 or quant_num > 15:
        print('valor minimo de é de 6 dezenas')
        break
        menu=str(input(''))
        if menu==s or S:
          
 
##Área de definições de funcões 
##sena de 6 numeros.

def sena6():
    aposta = valor // aposta6
    troco = valor % aposta6
    print('quantidade de jogos', aposta)
    print('Seu troco é R$', troco)
    print('deseja que o sistema escolha os números aleatórios ??? para o seus' ,aposta,'jogos')
    


##sena de 7 números.

def sena7():
    aposta = valor // aposta7
    troco = valor % aposta7
    print('quantidade de jogos', aposta)
    print('Seu troco é', troco)

###sena de 8 dezenas.

def sena8():
    aposta = valor // aposta8
    troco = valor % aposta8
    print('quantidade de jogos', aposta)
    
    print('Seu troco é', troco)  

###sena de 9 dezenas.

def sena9():
    aposta = valor // aposta9
    troco = valor % aposta9
    print('quantidade de jogos', aposta)
    print('Seu troco é', troco)

####sena de 10 dezenas

def sena10():
    aposta = valor // aposta10
    troco = valor % aposta10
    print('quantidade de jogos', aposta)
    print('Seu troco é', troco)

##sena de 11 dezenas.

def sena11():
    aposta = valor // aposta11
    troco = valor % aposta11
    print('quantidade de jogos', aposta)
    print('Seu troco é', troco)


def sena12():
    aposta = valor // aposta12
    troco = valor % aposta12
    print('quantidade de jogos', aposta)
    print('Seu troco é', troco)  

def sena13():
    aposta = valor // aposta13
    troco = valor % aposta13
    print('quantidade de jogos', aposta)
    print('Seu troco é', troco)

def sena14():
    aposta = valor // aposta14
    troco = valor % aposta14
    print('quantidade de jogos', aposta)
    print('Seu troco é', troco)

def sena15():
    aposta = valor // aposta15
    troco = valor % aposta15
    print('quantidade de jogos', aposta)
    print('Seu troco é', troco)


if quant_num == 6:
  sena6()
  
elif quant_num == 7:
    sena7()

elif quant_num == 8:
  sena8()
  
elif quant_num == 9:
  sena9()
   
elif quant_num == 10:
    sena10()

elif quant_num == 11:
  sena11()
    
elif quant_num == 12:
  sena12()
    


elif quant_num == 13:
    sena13()



elif quant_num == 14:
   sena14()


else:
    quant_num == 15
    sena15()
##funções de números aleatórios
