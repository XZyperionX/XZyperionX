# Primeiro Projeto iCev 
def calcular(value1, value2, value3): 
    calc = float((value1 * (value2 / 100)) / (value3 / 100)) 
    return calc 


salario = float(input("Valor do salário base: "))

gratificacao = float(input("Porcentagem da gratificação ganha: "))

imposto = float(input("Porcentagem do imposto pago: "))


final = calcular(salario, gratificacao, imposto)

print("O valor final do salario é ", final)
