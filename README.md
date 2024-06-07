# prova_aula_2
print("-----"*10)
print("\n\n")
print("Cálculo da Multa de Velocidade Máxima da Via")
print("\n\n")
print("-----"*10)

print("\n\n")
velocidade = int(input(f"Qual a velocidade do veículo: "))
multa = float((velocidade - 80) * 20)

print("\n\n")

print("-----"*10)
print("\n\n")
if(velocidade > 80 ):
    print(f"O usuário foi MULTADO!")
    print("\n\n")
    print(f"O valor da multa é: R${multa:.2f}")
else:
    print(f"Velocidade dentro a permitida, pode prosseguir!")
print("\n\n")
print("-----"*10)
