import time
import os

def escribir(texto, velocidad=0.05):
    for letra in texto:
        print(letra, end="", flush=True)
        time.sleep(velocidad)
    print()

def limpiar_pantalla():
    os.system("clear")  # En Linux / GitHub Codespaces

limpiar_pantalla()

escribir("====================================")
escribir("        PRESENTACION PERSONAL       ")
escribir("====================================\n")

time.sleep(1)

escribir("Nombre: Sebastian Ropain\n")
time.sleep(0.5)

escribir("Experiencia Tecnica:\n")
time.sleep(0.5)

escribir("- Experiencia basica en Python")
time.sleep(0.5)

escribir("- Experiencia basica usando Linux")
time.sleep(0.5)

escribir("- Experiencia basica usando Terminal\n")
time.sleep(0.5)

escribir("Gracias por ver mi presentacion.")
escribir("====================================")
