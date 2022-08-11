print ("Digite o nome completo");
print ("Digite a data de nascimento");

try:
    ano = int(input())
    ano = ano + 1922
    ano = ano + 2022
    
    print ("Digite a data de nascimento" + str(ano))
except:
    print("nao foi digitado um numero")
