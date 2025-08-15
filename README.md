palavra = input("Digite uma palavra: ")
vogais = "aeiouAEIOU" # Incluímos maiúsculas e minúsculas
contador_vogais = 0

# O 'for' vai passar por cada 'letra' na 'palavra'
for letra in palavra:
    # Verificamos se a letra atual está na nossa string de vogais
    if letra in vogais:
        contador_vogais += 1 # Se for vogal, incrementamos o contador
        
print(f"A palavra '{palavra}' tem {contador_vogais} vogais.")

