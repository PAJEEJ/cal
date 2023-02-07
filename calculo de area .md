import math

print("Escolha a opção desejada:")
print("1 - Calcular área de um retângulo")
print("2 - Calcular área de um círculo")
opcao = int(input("Opção: "))

if opcao == 1:
    largura = float(input("Largura: "))
    altura = float(input("Altura: "))
    area = largura * altura
    print("Área do retângulo:", area)
elif opcao == 2:
    raio = float(input("Raio: "))
    area = math.pi * raio**2
    print("Área do círculo:", area)
else:
    print("Opção inválida")
