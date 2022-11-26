print('Seja bem vindo ao quiz do Rafa \n Sobre GTA!')
answer_user = input('Quer começar? (S/N)')

if answer_user != "S":   
    quit()


score=0    
    
print('Começando..')
print("Quem desenvolvel o jogo (GTA)? \n (A)Rockstar Games \n (B)Activision \n (C)Ubisoft \n (D)EA \n")
answer_1= input("Resposta: ")
if answer_1 == "A":
    print("Correto!")
    score = score + 1
else:
    print("Incorreto!")   

print("Qual o nome do protagonista do jogo do GTA san andreas?  \n (A)Carl jonhson \n (B)Carl bruno \n (C)Carl jaque \n (D)Carlos \n")
answer_1= input("Resposta: ")
if answer_1 == "A":
    print("Correto!")
    score = score + 1
else:
    print("Incorreto!")  


print("Qual ano o jogo do GTA san andreas foi lançado?  \n (A)1998 \n (B)2004 \n (C)2000 \n (D)2001 \n")
answer_1= input("Resposta: ")
if answer_1 == "B":
    print("Correto!")
    score = score + 1
else:
    print("Incorreto!")



print("Porque GTA é para 18 anos?  \n (A)Porque tem conteúdo sexual, drogas e violência.\n (B)Porque nao tem violencia \n (C)Porque uma criaça nao consegue jogar\n (D)porque é dificil de jogar \n")
answer_1= input("Resposta: ")
if answer_1 == "A":
    print("Correto!")
    score = score + 1
else:
    print("Incorreto!")  


print(" Quando o Grand Theft Auto VI deve ser lançado?  \n (A)2022\n (B)2023 \n (C)2029\n (D)2024 \n")
answer_1= input("Resposta: ")
if answer_1 == "D":
    print("Correto!")
    score = score + 1
else:
    print("Incorreto!")
    
print(f"PARABÉNS QUIZ ACABOU... Pontuação: {score}/5 ")