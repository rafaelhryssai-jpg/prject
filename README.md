# ==========================================
# CENTRAL DE DESAFIOS LÓGICOS EM PYTHON
# ==========================================

def simulador_fliper():
    print("\n--- 1. SIMULADOR DE FLÍPER ---")
    p = int(input("Digite a posição da porta P (0 ou 1): "))
    r = int(input("Digite a posição da porta R (0 ou 1): "))
    
    if p == 0:
        caminho = "C"
    elif r == 1:
        caminho = "A"
    else:
        caminho = "B"
        
    print(f"Resultado: A bolinha caiu na saída {caminho}!")

def classificador_clima():
    print("\n--- 2. CLASSIFICADOR DE TEMPERATURA ---")
    temp = int(input("Digite a temperatura atual em °C: "))
    
    if temp < 15:
        status = "Frio"
    elif temp <= 25:
        status = "Agradável"
    else:
        status = "Quente"
        
    print(f"Sensação térmica: {status}.")

def desafio_dona_monica():
    print("\n--- 3. A IDADE DE DONA MÔNICA ---")
    idade_monica = int(input("Idade de Dona Mônica: "))
    filho1 = int(input("Idade do 1º filho: "))
    filho2 = int(input("Idade do 2º filho: "))
    
    filho3 = idade_monica - filho1 - filho2
    mais_velho = max(filho1, filho2, filho3)
    
    print(f"O 3º filho tem {filho3} anos.")
    print(f"O filho mais velho tem {mais_velho} anos.")

def torneio_jogadores():
    print("\n--- 4. PLACAR DO TORNEIO ---")
    j1 = int(input("Pontuação do Jogador 1: "))
    j2 = int(input("Pontuação do Jogador 2: "))
    j3 = int(input("Pontuação do Jogador 3: "))
    
    total = j1 + j2 + j3
    maior = max(j1, j2, j3)
    
    print(f"Pontuação total da equipe: {total} pontos.")
    print(f"Maior pontuação individual: {maior} pontos.")

def avaliador_musical():
    print("\n--- 5. AVALIADOR DE MÚSICAS ---")
    musica = input("Nome da música: ")
    nota = float(input("Dê uma nota de 0 a 10: "))
    
    if nota > 7:
        print(f"A música '{musica}' é popular com nota {nota}!")
    else:
        print(f"A música '{musica}' ainda está ganhando público (nota {nota}).")

def selecao_lider():
    print("\n--- 6. SELEÇÃO DE LÍDER DE EQUIPE ---")
    nome1 = input("Nome do 1º candidato: ")
    tempo1 = int(input(f"Anos de experiência de {nome1}: "))
    
    nome2 = input("Nome do 2º candidato: ")
    tempo2 = int(input(f"Anos de experiência de {nome2}: "))
    
    nome3 = input("Nome do 3º candidato: ")
    tempo_total = int(input("Tempo TOTAL de experiência somado dos três: "))
    
    tempo3 = tempo_total - tempo1 - tempo2
    mais_experiente = max(tempo1, tempo2, tempo3)
    
    print(f"\nExperiência calculada de {nome3}: {tempo3} anos.")
    print(f"O candidato mais experiente tem {mais_experiente} anos de experiência.")

# ==========================================
# MENU PRINCIPAL (LOOP DE EXECUÇÃO)
# ==========================================
def iniciar_sistema():
    while True:
        print("\n" + "="*35)
        print("   MENU - CENTRAL DE PROGRAMAS")
        print("="*35)
        print("1 - Jogo do Flíper")
        print("2 - Classificador de Temperatura")
        print("3 - Idade de Dona Mônica")
        print("4 - Pontuação de Jogadores")
        print("5 - Avaliar Música")
        print("6 - Seleção de Líder")
        print("0 - Sair")
        
        opcao = input("\nEscolha uma opção: ")
        
        if opcao == "1":
            simulador_fliper()
        elif opcao == "2":
            classificador_clima()
        elif opcao == "3":
            desafio_dona_monica()
        elif opcao == "4":
            torneio_jogadores()
        elif opcao == "5":
            avaliador_musical()
        elif opcao == "6":
            selecao_lider()
        elif opcao == "0":
            print("Encerrando o sistema. Até mais!")
            break
        else:
            print("Opção inválida! Tente novamente.")

# Inicia o programa
if __name__ == "__main__":
    iniciar_sistema()
Use o código com cuidado.

O que esse projeto aplica na prática:

• Modularização: Cada exercício virou uma função (def) independente e organizada.
• Estruturas Condicionais (if / elif / else): Usadas tanto na lógica interna dos exercícios quanto para controlar a navegação do menu.
• Laço de Repetição (while True): Mantém o programa rodando para que você teste vários exercícios sem precisar reiniciar o código.
Se quiser evoluir ou adaptar esse código para entregar em algum trabalho, me diga:
• Você precisa de interface gráfica (usando Tkinter, por exemplo) ou apenas terminal
• Deseja adicionar tratamento de erros (para o programa não travar se alguém digitar letras no lugar de números)
• Quer transformar tudo em um único tema (ex: um sistema completo de RH ou um jogo de RPG)
Posso ajustar o código exatamente para o que você precisa.
As respostas da IA podem conter erros. Saiba mais
                        
