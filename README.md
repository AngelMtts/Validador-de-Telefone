# Validador-de-Telefone
import re

# Definindo a regex para validar o número
regex = r'^\d{11}$'

# Solicitando ao cliente que digite um número de telefone que contenha 11 digitos obrigatoriamente
numero = input("Digite um número de telefone ou celular: ")

# Verificando se o número digitado é válido
if re.match(regex, numero):
    print("O número é válido.")
else:
    print("O número é inválido.")
