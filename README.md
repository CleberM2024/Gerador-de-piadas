# Gerador-de-piadas
Gerador piadas aleatórias 
import random

piadas = [
    "Por que o livro de matemática se suicidou? Porque tinha muitos problemas.",
    "O que é um pontinho amarelo na estrada? É um fandango atropelado.",
    "Qual é o cúmulo do egoísmo? Cagar na rede e cortar a corda."
]

def gerar_piadas():
    return random.choice(piadas)

if __name__ == "__main__":
    print(gerar_piadas())
