print("Notas disponiveis 2 5 10 20 50")
print("Saque minimo 5 reais e saque maximo 1000")
print("A maquina não faz troco exemplo se pedir para sacar 51 reais ira sacar apenas 50")
valordosaque = int(input("Informe o valor do saque:")) # 187

if valordosaque >= 100:
    Quantidade100 = valordosaque // 100
    valordosaque = valordosaque % 100
    print("Notas de 100:", Quantidade100)
if valordosaque >= 50 and valordosaque <= 99:
    Quantidade50 = valordosaque // 50
    valordosaque = valordosaque % 50
    print("Notas de 50:", Quantidade50)
if valordosaque >= 20 and valordosaque < 49:
    Quantidade20 = valordosaque // 20
    valordosaque = valordosaque % 20   
    print("Notas de 20:", Quantidade20)
if valordosaque >= 10 and valordosaque < 19:
    Quantidade10 = valordosaque // 10
    valordosaque = valordosaque % 10
    print("Notas de 10:", Quantidade10)
if valordosaque >= 5 and valordosaque < 9:
    Quantidade5 = valordosaque // 5
    valordosaque = valordosaque % 5
    print("Notas de 5:", Quantidade5)
if valordosaque >= 2 and valordosaque < 4:
    Quantidade2 = valordosaque // 2
    print("Notas de 2:", Quantidade2)



