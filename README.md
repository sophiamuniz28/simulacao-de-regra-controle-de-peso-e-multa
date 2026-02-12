🐟 Regulamento de Pesca – Exercício em Python

📌 Descrição

Este projeto foi desenvolvido como exercício prático de lógica de programação em Python.

O objetivo é simular o controle de peso de peixes pescados, considerando a seguinte regra:

⚖️ Limite permitido: 50 kg

💸 Se ultrapassar: multa de R$ 4,00 por quilo excedente

🎁 Se não ultrapassar: bonificação de R$ 1,00 por quilo pescado

O programa calcula automaticamente a multa ou bonificação e exibe os valores formatados com duas casas decimais.

💻 Código do Programa:
peso = float(input('Digite o peso pescado (kg): '))
regulamento_pesca_sp = 50

if peso > regulamento_pesca_sp:
    excesso = peso - regulamento_pesca_sp
    multa = excesso * 4
    
    print('Você ultrapassou o limite permitido.')
    print(f'Excesso: {excesso:.2f} kg')
    print(f'Multa a pagar: R$ {multa:.2f}')
else:
    bonificacao = peso * 1
    
    print('Você não ultrapassou o limite.')
    print(f'Bonificação: R$ {bonificacao:.2f}')
🧠 Lógica Utilizada
✔ Entrada de dados

Utiliza input() para receber o peso digitado pelo usuário e float() para permitir números decimais.

✔ Estrutura condicional

A estrutura if/else verifica se o peso ultrapassou o limite de 50 kg.

✔ Cálculo do excesso

Se o peso for maior que 50:

excesso = peso - regulamento_pesca_sp

✔ Cálculo da multa

Cada quilo excedente custa R$ 4,00:

multa = excesso * 4

✔ Bonificação

Caso não haja excesso:

bonificacao = peso * 1

✔ Formatação

Os valores são exibidos com duas casas decimais utilizando:

{valor:.2f}

🎯 Conceitos Praticados

Variáveis

Operações matemáticas

Estrutura condicional (if/else)

Entrada de dados com input()

Conversão de tipos (float)

Formatação de saída com f-string

Organização e clareza no código

🚀 Objetivo Acadêmico

Exercício desenvolvido para reforçar a lógica condicional e a organização de código em Python, como parte dos estudos iniciais em programação e aplicação de regras de negócio simples.
