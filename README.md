P = int(input("Digite a posição da porta P (0 ou 1): "))
R = int(input("Digite a posição da porta R (0 ou 1): "))if P == 0:
    print("C")elif R == 1:
    print("A")else:
    print("B")if P == 0:
    print("C")
elif R == 1:
    print("A")
else:
    print("B")elif R == 1:
    print("A")
else:
    print("B")else:
    print("B")temperatura = int(input("Digite a temperatura em graus Celsius: ")) 
if temperatura < 15: 
    print("____") 
____ temperatura <= 25: 
    print("Agradável") 
____: 
    ____ ("Quente") P = int(input("Posição da porta P (0 ou 1): ")) 
R = int(input("Posição da porta R (0 ou 1): ")) 

if P == 0: 
    print("C") 
if P == 1: 
    if R == 1: 
        print("A") 
    else: 
        print("B") 
else: 
    print("C")   def calcula_idade_maior(idade_monica, idade_filho1, idade_filho2):idade_filho3 = idade_monica - idade_filho1 – idade_filho2idade_maxima = max(idade_filho1, idade_filho2, idade_filho3)def calcula_idade_maior(idade_monica, idade_filho1, idade_filho2): 
idade_filho3 = idade_monica - idade_filho1 - idade_filho2 
idade_maxima = max(idade_filho1, idade_filho2, idade_filho3) 
return idade_filho3, idade_maximaresultado = calcula_idade_maior(68, 12, 30) (26, 30)
print(resultado)def calcula_idade_maior(idade_monica, idade_filho1, idade_filho2): 
    idade_filho3 = idade_monica - idade_filho1 - idade_filho2 
    idade_mais_velho = max(idade_filho1, idade_filho2, idade_filho3) 
    return idade_mais_velho def calcula_pontuacao(jogador1, jogador2, jogador3): 
    # Complete o código aqui def avaliar_musica(nota): 
    if nota > 7 
        print(f"A música é popular com nota {nota}!") def calcula_lider(tempo_total, tempo1, tempo2):  
tempo3 = tempo_total - tempo1 - tempo2  
mais_experiente = max(tempo1, tempo2, tempo3)  
return tempo3, mais_experiente 
nome1 = input("Nome do primeiro candidato: ")  
nome2 = input("Nome do segundo candidato: ")  
nome3 = input("Nome do terceiro candidato: ") 
tempo1 = int(input("Tempo de experiência do primeiro candidato: "))  
tempo2 = int(input("Tempo de experiência do segundo candidato: "))  
tempo_total = int(input("Tempo total de experiência dos três: ")) 
tempo3, mais_experiente = calcula_lider(tempo_total, tempo1, tempo2)  
print("Tempo de experiência do terceiro candidato:", tempo3)  
print("O mais experiente tem:", mais_experiente, "anos de experiência.") 
