# prova
calculo_de_imc.py
Nome_do_paciente = input("Digite o nome do paciente:")
altura = float(input("Digite a altura do paciente: "))
peso = float(input("Digite o peso do paciente: "))

imc = peso / (altura * altura)

if imc >= 30:
    print("⚠️ Cuidado com a Saúde")
else: 
      print("✅ Tudo ok")
if imc <=18.5:
    print("Abaixo do peso")
elif imc >=18.5  and imc <= 24.9:
     print("peso normal")
elif imc >=25.0 and imc <= 29.9:
     print("sobre peso")
elif imc >=30.0 and imc <= 34.9:	
     print("Obesidade Grau I")
elif  imc >=35.0 and imc <= 39.9:
    print("Obesidade Grau II")
elif imc >= 40.0:
     print("Obesidade Grau III (mórbida)")
