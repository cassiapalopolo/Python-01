# Python-01
Faça um algoritmo para ler os seguintes números: A, B e C. Após, calcular o valor de D segundo a expressão: D = B² - 4AC, e mostrar os valores lidos e o resultado. Ainda deve ser escrito o valor de D dividido por 2.
a = int(input("Digite um número: "))
b = int(input("Digite um segundo número: "))
c = int(input("Digite um terceiro número: "))
d = (b**2) - (4*a*b)

print("\nO valor de A digitado é: ", a)
print("O valor de B digitado é: ", b)
print("O valor de C digitado é: ", c)
print("O resultado de b²-4ac é: ", d, "e a divisão do resultado por 2 é: ", d/2)
print("A divisao do resultado por 2 é:", d/2)
