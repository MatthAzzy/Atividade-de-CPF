# Atividade-de-CPF
 Vai ser a prog toda aqui, então vou atualizando conforme eu for aprimorando
import re

def formatCpf (cpfInput):
    formatedCpf = cpfInput
    formatedCpf = cpfInput.replace(".", "")
    return formatedCpf
#cpf = input('Insira seu cpf: ') <- isso é um teste

def isNumericDigit (digit):
    if len(digit) < 0 and len(digit) > 9:
        return False
    else:
        return True

def validadeCpfFormat (formatedCpf):

#def calculateValidationDigit (cpfPrefix):

#def numericalCharToValue (numericalChar):

#def validadeValidationDigits (formatedCpf):

#def validadeCpf (cpfInput):

