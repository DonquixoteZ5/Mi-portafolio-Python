# Hola, Soy Luis
## soy programador de python

Esta es una serie de algoritmos creados 
Espero que les guste 
---
### Analizador de texto 


texto = input("Ingrese texto: ")
letra_1 = input("Ingrese la letra: ").lower()
letra_2 = input("Ingrese la letra: ").lower()
letra_3 = input("Ingrese la letra: ").lower()
lista = [letra_1, letra_2, letra_3]

print(texto)
print(lista)
print(f"La letra {letra_1}: aparece {texto.count(lista[0])} veces en el texto")
print(f"La letra {letra_2}: aparece {texto.count(lista[1])} veces en el texto")
print(f"La letra {letra_3}: aparece {texto.count(lista[2])} veces en el texto")
texto_lista = texto.split()
print(f"El texto tiene {len(texto_lista)} palabras")
#print(f"La primera letra: {texto_lista[0]}")
#print(f"La ultima letra: {texto_lista[len(texto_lista)-1]}")
print(f"La primera letra: {texto[0]}")
print(f"La ultima letra: {texto[-1]}")
print(" ".join(texto_lista[::-1]))
resultado = {True: "SI", False: "NO"}
print(f"La palabra python aparece en el texto?" in texto.lower())


