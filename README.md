Versão Antiga:

#!/usr/bin/python3
import os
import time
print("Bem vindo ao script")
print("Carregando")    
time.sleep(2)
os.system("clear")
time.sleep(3)
print("░░░░░░░░░░░███████░░░░░░░░░░░")
print("░░░░░░░████░░░░░░░████░░░░░░░")
print("░░░░░██░░░░░░░░░░░░░░░██░░░░░")
print("░░░██░░░░░░░░░░░░░░░░░░░██░░░")
print("░░█░░░░░░░░░░░░░░░░░░░░░░░█░░")
print("░█░░████░░░░░░░░██████░░░░░█░")
print("█░░█░░░██░░░░░░█░░░░███░░░░░█")
print("█░█░░░░░░█░░░░░█░░░░░░░█░░░░█")
print("█░█████████░░░░█████████░░░░█")
print("█░░░░░░░░░░░░░░░░░░░░░░░░░░░█")
print("█░░░░░░░░░░░░░░░░░░░░░░░░░░░█")
print("█░░░████████████████████░░░░█")
print("░█░░░█▓▓▓▓▓▓▓▓█████▓▓▓█░░░░█░")
print("░█░░░░█▓▓▓▓▓██░░░░██▓██░░░░█░")
print("░░█░░░░██▓▓█░░░░░░░▒██░░░░█░░")
print("░░░██░░░░██░░░░░░▒██░░░░██░░░")
print("░░░░░██░░░░███████░░░░██░░░░░")
print("░░░░░░░███░░░░░░░░░███░░░░░░░")
print("░░░░░░░░░░█████████░░░░░░░░░░")
print(" ")
print(" ")
print("1:Atualizar Termux")

escolha = False

while escolha == False:
    nivel = int(input("Qual opção?: "))
    if (nivel == 1):
        os.system("pkg update && pkg upgrade")

Versão atual:

#!/usr/bin/python3
import os
import time
print(" ")
print(" ")    
time.sleep(2)
os.system("clear")
time.sleep(3)
print("░░░░░░░░░░░███████░░░░░░░░░░░")
time.sleep(0.1)
print("░░░░░░░████░░░░░░░████░░░░░░░")
time.sleep(0.1)
print("░░░░░██░░░░░░░░░░░░░░░██░░░░░")
time.sleep(0.1)
print("░░░██░░░░░░░░░░░░░░░░░░░██░░░")
time.sleep(0.1)
print("░░█░░░░░░░░░░░░░░░░░░░░░░░█░░")
time.sleep(0.1)
print("░█░░████░░░░░░░░██████░░░░░█░")
time.sleep(0.1)
print("█░░█░░░██░░░░░░█░░░░███░░░░░█")
time.sleep(0.1)
print("█░█░░░░░░█░░░░░█░░░░░░░█░░░░█")
time.sleep(0.1)
print("█░█████████░░░░█████████░░░░█")
time.sleep(0.1)
print("█░░░░░░░░░░░░░░░░░░░░░░░░░░░█")
time.sleep(0.1)
print("█░░░░░░░░░░░░░░░░░░░░░░░░░░░█")
time.sleep(0.1)
print("█░░░████████████████████░░░░█")
time.sleep(0.1)
print("░█░░░█▓▓▓▓▓▓▓▓█████▓▓▓█░░░░█░")
time.sleep(0.1)
print("░█░░░░█▓▓▓▓▓██░░░░██▓██░░░░█░")
time.sleep(0.1)
print("░░█░░░░██▓▓█░░░░░░░▒██░░░░█░░")
time.sleep(0.1)
print("░░░██░░░░██░░░░░░▒██░░░░██░░░")
time.sleep(0.1)
print("░░░░░██░░░░███████░░░░██░░░░░")
time.sleep(0.1)
print("░░░░░░░███░░░░░░░░░███░░░░░░░")
time.sleep(0.1)
print("░░░░░░░░░░█████████░░░░░░░░░░")
time.sleep(2)
print(" ")
print(" ")
print(" ")
print(" ")
print(" ")
print(" ")
print("1:Atualizar Termux")

escolha = False

while escolha == False:
    print(" ")
    nivel = int(input("Qual opção?: "))
    if (nivel == 1):
        os.system("pkg update && pkg upgrade") 