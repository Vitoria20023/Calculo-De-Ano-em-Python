#VARIÁVEIS
nome = input ("Digite seu nome: ")
idade = int (input ("Digite sua idade: "))
saldo = float (input ("Digite seu saldo: "))
per = int (input ("Digite o percentual de aumento: "))
ano = 2023 - idade
saldo_total = (saldo*per)/100 + saldo

#CÓDIGO
print ("------------------------------------")
print (nome, "ano que você nasceu é:",2023 - idade)
print ("Seu saldo é:",saldo)
print ("Seu saldo com acréscimo:", (saldo*per)/100 + saldo)
print (f"Você {nome} que naseu em {ano} terá um saldo de {per}%, que será de R${saldo_total}")
