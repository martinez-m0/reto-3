# reto-3
#  Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.

    n : entero
    i : entero
    j : entero
    Inicio
        Leer n
        Para i desde 2 hasta n hacer
            primo ← Verdadero
            Para j desde 2 hasta i-1 hacer
                Si i mod j = 0 entonces
                    primo ← Falso
                    Salir del para
                FinSi
            FinPara
            Si primo = Verdadero entonces
                Escribir i
            FinSi
        FinPara
    Fin
