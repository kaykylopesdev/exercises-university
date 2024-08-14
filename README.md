# exercises-university
Esta lista de exercícios em Python foi desenvolvida para proporcionar aos alunos uma prática estruturada e abrangente dos conceitos de programação. Os exercícios cobrem uma ampla gama de tópicos, desde fundamentos básicos até técnicas avançadas, com o objetivo de fortalecer a compreensão e a aplicação prática da linguagem Python.

####
```python```

22. Faça um Programa que peça dois números e imprima o maior deles. 
    ```python
    n1=int(input('digite um numero: '))
    n2=int(input('digite outro numero: '))
    if n1>n2:
        print(n1)
    else:
        print(n2)
    ```

23. Faça um Programa que peça um valor e mostre na tela se o valor é positivo ou negativo.
    ```python
    numero=int(input('digite um numero: '))
    if numero > 0:
        print('positivo')
    elif numero == 0:
        print('neutro')
    else:
        print('negativo')
    ```

24. Faça um Programa que verifique se uma letra digitada é "F" ou "M". Conforme a letra escrever: F - Feminino, M - Masculino, Sexo Inválido.
    ```python
    letra: str = input("digite F ou M : ")
    if letra == 'F':
        print("Feminino")
    elif letra == 'M':
        print("Masculino")
    else:
        print("Sexo inválido")
    ```

25. Faça um programa para a leitura de duas notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e apresentar: 
A mensagem "Aprovado", se a média alcançada for maior ou igual a sete; 
A mensagem "Reprovado", se a média for menor do que sete; 
A mensagem "Aprovado com Distinção", se a média for igual a dez.
    ```python
    nota1: int = int(input('digite sua primeita nota: '))
    nota2: int = int(input('digite sua segunda nota: '))
    media: int = (nota1+nota2)/2
    if media < 7:
        print('reprovado!')
    if media == 10:
        print('aprovado com Distinção!')
    else:
        print('aprovado!')
    ```
25. Faça um Programa que leia três números e mostre o maior deles.
    ```python
    n1: int = int(input('digite o primeiro numero: '))
    n2: int = int(input('digite o segundo numero: '))
    n3: int = int(input('digite o terceiro numero: '))
    if n1 > n2 and n1 > n3 :
        print(n1)
    elif n2 > n1 and n2 > n3 :
        print(n2)
    else:
        print(n3)
    ```
26. Faça um programa que pergunte o preço de três produtos e informe qual produto você deve comprar, sabendo que a decisão é sempre pelo mais barato.
    ```python
    produto1: float = float(input('digite o valor do 1° produto: '))
    produto2: float = float(input('digite o valor do 2° produto: '))
    produto3: float = float(input('digite o valor do 3° produto: '))
    if produto1 < produto2 and produto1 < produto3:
        print('compre o 1° produto, pois ele é o mais barato entre os demais!')
    elif produto2 < produto1 and produto2 < produto3:
        print('compre o 2° produto, pois ele é o mais barato entre os demais!')
    else:
        print('compre o 3° produto, pois ele é o mais barato entre os demais!')
    ```
27. Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-Vespertino ou N- Noturno. Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.
    ```python
    turno: str = str(input('em qual turno você estuda?,digite M para matutino ou V para Vespertino ou N para Noturno: '))
    if turno == "M" :
        print('Bom dia!')
    elif turno == "V" :
        print('Boa tarde!')
    elif turno == "N" :
        print('Boa noite')
    else:
        print('valor inválido!')
    ```
28. 

    


