1.	 
R1 = float(input("Informe a resistência R1: "))
R2 = float(input("Informe a resistência R2: "))
escolha = input("Digite qual a sua escolha de resistor: Digite S para série ou digite R para paralelo: ")

if escolha == "S":
    resistorS = R1 + R2
    print("Resultado em série", resistorS)
else:
    resistorR = (R1 * R2) / (R1 + R2)
    print("O resultado em paralelo", resistorR)


