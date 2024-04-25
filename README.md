# Lista-de-exercicio-02
# Exercícios - Lógica de programação em Python

# Input - para os exercícios abaixo você precisará utilizar o método input() para requisitar dados externos ao programa:

#  0 - Criar um algoritmo que ao receber o nome de um usuario imprima a mensagem: Seja bem vindo { nome do usuário }
print ("Exercicio 0")
nome = input ("Digite seu nome: ")
print ("Seja bem vindo", nome)

# 1  - Crie um algoritmo em que o usuário informe uma frase qualquer e exiba a frase na tela (terminal) quando executado.
print ("Exercicio 1")
frase = input ("Digite sua mensagem: ")
print (frase)
# 2  - Crie um algoritmo em que o usuário informe o nome completo e exiba o nome completo na tela (terminal) quando executado.
print ("Exercicio 2")
nome_completo = input ("Digite seu nome completo: ")
print (nome_completo)

# 3  - Crie um algoritmo em que o usuário informe a idade e exiba a idade na tela (terminal) quando executado.
print ("Exercicio 3")
idade = input ("Digite sua idade: ") 
print (idade)

# 4  - Crie um algoritmo em que o usuário informe dois números inteiros (n1 e n2) e exiba os números na tela (terminal) quando executado.
print("Exercicio 4: Digite 2 números")
n = input ("Digite um numero inteiro: ")
n1 = input ("Digite outro numero: ")
print (f"{n}, {n1}")

# 5  - Crie um algoritmo em que o usuário informe dois números inteiros (n1 e n2) e exiba a soma dos números na tela (terminal) quando executado.
print ("Exercicio 5: Calcule a soma dos números")
n2 = int (input (" Digite um numero inteiro: "))
n3 = int (input (" Digite outro numero inteiro: "))
print (f"a soma de {n2} + {n3} é igual a {n2 + n3}")

# 6  - Crie um algoritmo em que o usuário informe dois números inteiros (x1 e x2) e exiba a diferença dos números na tela (terminal) quando executado.
print ("Exercicio 6: Calcule a diferença dos números")
x = int (input ("Digite um numero inteiro: "))
x1 = int (input ("Digite outro numero inteiro: "))
print (f"A diferença de {x} e {x1} é igual a {x - x1}")

# 7  - Crie um algoritmo em que o usuário informe dois números inteiros (a1 e a2) e exiba o produto dos números na tela (terminal) quando executado.
print("Exercicio 7: Calcule o produto dos números")
n4 = int (input (" Digite um numero inteiro: "))
n5 = int (input (" Digite outro numero inteiro: "))
print (f"O produto de {n4} e {n5} é igual a {n4 * n5}")

# 8  - Crie um algoritmo em que o usuário informe dois números inteiros (x e y) e exiba o quociente dos números na tela (terminal) quando executado.
print ("Exercicio 8: Calcule o quociente dos números")
x2 = int (input ("Digite um numero "))
y = int (input("Digite outro numero "))
print (f"O quociente dos numero {x2} e {y} é {x2 / y}")
# 9  - Crie um algoritmo em que o usuário informe quatro notas (n1, n2, n3 e n4). Após, calcule a média aritmética e exiba a média na tela (terminal) quando executado.
print ("Exercicio 9: Calcule a média dos numeros")
n6 = int (input ("Digite um numero "))
n7 = int (input ("Digite um numero "))
n8 = int (input ("Digite um numero "))
n9 = int (input ("Digite um numero "))
print (f"A media aritimetica dos numeros {n6}, {n7}, {n8}, {n9} é { (n6 + n7 + n8 + n9) / 4}")
# 10 - Crie um algoritmo em que o usuário informe quatro notas (n1, n2, n3 e n4) e seus respectivos pesos. Após, calcule a média ponderada e exiba a média na tela (terminal) quando executado.
print ("Exercicio 10: Calcule a média das notas")
nome = input ("Digite o nome do aluno ")
n10 = int (input("Digite a primeira nota "))
n11 = int (input("Digite a segunda nota "))
n12 = int (input("Digite a terceira nota "))
n13 = int (input("Digite a quarta nota "))
print (f"A media das notas do aluno {nome} é {(n10 + n11 + n12 + n13) / 4}")
