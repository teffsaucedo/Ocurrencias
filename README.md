# Ocurrencias
def conteo_palabras(str):
    palabras = str.strip().split(" ")
    for palabra in palabras: 
        if palabra in conteo:
            conteo [palabra] +=1
        else:
            conteo [palabra] = 1

archivo = open("/Users/unicorn/Downloads/PeterPan.txt","r")

conteo = dict()
palabras_dict = {}

for linea in archivo:
    #print (linea.strip())
    lista_palabras = linea.split(" ")
    #print (lista_palabras)
    conteo_palabras(linea)

print(conteo)
