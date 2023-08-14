# programa-de-placar-de-jogo
inicio = int (input("informe o primeiro numero: "))
fim = int (input(informe o numero final:" ))
salto = int(input("informe o saldo"))
texto = "calculo:"
soma = 0
for numero in range(inicio , fim , salto):
    soma = soma + numero
    texto = 




time1= int(input("sao paulo: "))
time2= int(input("GAIVOTAS: "))


print(f"sao paulo {time1}-{time2} GAIVOTAS")
if (time1 > time2):
    print ("são paulo ganhou")
elif (time1 < time2):
    print ("GAIVOTAS ganhou")
elif (time1 == time2 ):
    print ("EMPATE")
