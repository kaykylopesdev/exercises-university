# exercises-university
This list of exercises in Python has been developed to provide students with structured and comprehensive practice of programming concepts. The exercises cover a wide range of topics, from basic fundamentals to advanced techniques, with the goal of strengthening understanding and practical application of the Python.

####
```python```
1. Faça um Programa que peça um número e então mostre a mensagem: O número informado foi [número].
   ```python
   numero: float = float(input('digite um número: '))              
   print('o número informado foi: ', numero)
   ```
   
2. Faça um Programa que peça dois números e imprima a soma.
   ```python
   numero1: float =float(input('digite o primeiro numero: '))     
   numero2: float =float(input('digite o segundo numero: '))
   soma: float = numero1 + numero2
   print('a soma dos numeros é: ', soma)
   ```
   
3. Faça um Programa que peça as 4 notas bimestrais e mostre a média.
   ```python
   nota1: float = float(input('digite sua primeira nota: '))       
   nota2: float = float(input('digite sua segunda nota: '))
   nota3: float = float(input('digite sua terceira nota: '))
   nota4: float= float(input('digite sua quarta nota: '))
   media: float = (nota1+nota2+nota3+nota4)/4
   print('sua média é: ', media)
   ```
4. Faça um Programa que converta metros para centímetros.
   ```python
   metro: float = float(input('digite o valor em metro: ')) 
   centimetro: float = metro*100
   print('seu valor em centimetros é:', centimetro)
   ```
   
5. Faça um Programa que peça o raio de um círculo, calcule e mostre sua área.
   ```python
   raio: float = float(input('digite o valor do raio: ')) 
   area: float = (raio**2)*3.14        
   print('a area da circunferencia é:', area)
   ```
   
6. Faça um Programa que calcule a área de um quadrado, em seguida mostre o dobro desta área para o usuário.
   ```python
   lado: float = float(input('digite o valor do lado do quadrado: '))
   area: float = lado**2       
   print('a area desse quadrado é: ',area)
   print('o dobro da area desse quadrado é: ',(area)*2)
   ```
   
7. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.
   ```python
   valor: float = float(input('digite o quanto voce ganha por hora: '))            
   horas = float(input('digite a quantidade de horas trabalhadas: '))
   salario: float = valor*horas
   print("seu salario é:", salario)
   ```
   
8. Faça um Programa que peça a temperatura em graus Farenheit, transforme e mostre a temperatura em graus Celsius.
   ```python
   farenheit: float = float(input('digite a temperatura em farenheit:'))          
   celsius: float = ((farenheit-32)*5)/9
   print('sua temperatura em celsius é: ',celsius,'°C')
   ```
   
9. Faça um Programa que peça a temperatura em graus Celsius, transforme e mostre em graus Farenheit.
    ```python
    celsius: float = float(input('digite sua temperatura em celsius: '))             
    farenheit: float = ((celsius*9/5)+32)
    print('sua temperatura em farenheit é: ',farenheit,'°F')
    ```
    
10. Elaborar um algoritmo que efetue a apresentação do valor da conversão em real (R$) de um valor lido em dólar (US$). O algoritmo deverá solicitar o valor da cotação do dólar e também a quantidade de dólares disponíveis com o usuário.
    ```python
    print('descubra seu novo valor em real')                   
    dolar: float = float(input('digite o valor em dolar: '))
    cotacao: float = float(input('digite a cotacao do dolar: '))
    real: float = (dolar*cotacao)
    print('seu valor em real é:',real)
    ```

11. Faça um algoritmo que receba um valor que foi depositado e exiba o valor com rendimento após um mês. Considere fixo o juro da poupança em 0,70% a. m.
    ```python
    preco_produto:float =float(input('digite o precço de custo do produto: '))               
    acrescimo: float = float(input('digite em % o valor de acréscimo do produto: '))
    valor_de_venda: float =(preco_produto*(acrescimo/100)+ preco_produto)
    print('o valor final do produto sera de: ', valor_de_venda)
    ```
12. A Loja Mamão com Açúcar está vendendo seus produtos em 5 (cinco) prestações sem juros. Faça um algoritmo que receba um valor de uma compra e mostre o valor das prestações.
    ```python
    valor: float = float(input('digite o valor da compra: '))                
    prestacoes= valor/5
    print('os valores das 5 prestaçoes ficou de: ',prestacoes)
    ```

13. Faça um algoritmo que receba o preço de custo de um produto e mostre o valor de venda. Sabe-se que o preço de custo receberá um acréscimo de acordo com um percentual informado pelo usuário.
    ```python
    preco_produto:float =float(input('digite o precço de custo do produto: '))               
    acrescimo: float = float(input('digite em % o valor de acréscimo do produto: '))
    valor_de_venda: float =(preco_produto*(acrescimo/100)+ preco_produto)
    print('o valor final do produto sera de: ', valor_de_venda)
    ```

14. Escrever um algoritmo para determinar o consumo médio de um automóvel sendo fornecida a distância total percorrida pelo automóvel e o total de combustível gasto.
    ```python
    distancia: float =float(input('digite a distancia total percorrida pelo o automovel em Km: '))               
    combustivel: float =float(input('digite o total de combustivel gasto pelo o automovel em L: '))
    consumo_medio=(distancia/combustivel)
    print('o consumo medio desse automovel é: ', comsumo_medio,'km/L')
    ```
    
15. Escreva um programa que leia três números inteiros e positivos (a, b, c) e calcule a seguinte expressão: 
d = (r+s)/2, onde  r =(a+b)**2 e s = (b+c)**2
    ```python
    a: float = float(input('digite um valor para a: '))             
    b: float = float(input('digite um valor para b: '))
    c: float = float(input('digite um valor para c: '))

    r: float = (a+b)**2
    s: float = (b+c)**2
    d: float = (r+s)/2

    print('o resultado da expressao d=(r+s)/2, sendo r=(a+b)**2 e s=(b+c)**2 é: ',d)
    ```
16. Escrever um algoritmo que leia o nome de um vendedor, o seu salário fixo e o total de vendas efetuadas por ele no mês (em dinheiro). Sabendo que este vendedor ganha 15% de comissão sobre suas vendas efetuadas, informar o seu nome, o salário fixo e salário no final do mês.
     ```python
     vendedor: str = str(input('digite o nome do vendedor: '))                 
     salario_fixo: float = float(input('digite o salario fixo do vendedor: '))
     vendas:float = float(input('digite o total de vendas em dinheiro: '))
     salario_total = ((salario_fixo )+(vendas*0.15))
     print('nome do vendedor: ',vendedor)
     print('salario fixo: ',salario_fixo)
     print('salario total: ',salario_total)
     ```

   

17. Faça um Programa que peça 2 números inteiros e um número real. Calcule e mostre: 
o produto do dobro do primeiro com metade do segundo . 
a soma do triplo do primeiro com o terceiro.     
o terceiro elevado ao cubo.
    ```python
    numero1: int = int(input('digite um número inteiro: '))               
    numero2: int = int(input('digite mais um número inteiro: '))
    numero_real: float = float(input('digite agora um numero real: '))

    resp1: float = ((2*numero1)*(numero2/2))
    resp2: float= ((3*numero1)+numero_real)
    resp3: float = (numero_real**3)


    print('o primero resultado é: ',resp1)
    print('o segundo resultado é: ',resp2)
    print('o terceiro resultado é: ',resp3)
    ```
    
18. Tendo como dados de entrada a altura de uma pessoa, construa um algoritmo que calcule seu peso ideal, usando a seguinte fórmula: (72.7*altura) – 58.
    ```python
    altura: float = float(input('digite sua altura em m: '))          
    peso_ideal: float =((72.7*altura)-58)
    print('seu peso ideal é: ',peso_ideal)
    ```
19. Faça um programa que peça o tamanho de um arquivo para download (em MB) e a velocidade de um link de Internet (em MBps), calcule e informe o tempo aproximado de download do arquivo usando este link (em minutos).
    ```python
    tamanho_arquivo: float =float(input('digite o tamanho do arquivo em Mb: '))             
    velocidade: float = float(input('digite a velocidade de um link na internet em Mb/s: '))
    tempo: float = ((tamanho_arquivo/velocidade)/60)
    print('o tempo gasto é de: ',tempo,'Min')
    ```
20. Ler dois valores para as variáveis A e B, e efetuar as trocas dos valores de forma que a variável A passe a possuir o valor da variável B e a variável B passe a possuir o valor da variável A. Apresentar os valores trocados.
    ```python
    a: float = float(input('digite um valor para A:'))             
    b: float = float(input('digite um valor para B: '))

    a,b = (b,a)

    print('a:',a)
    print('b:',b )
    ```
21. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês, sabendo-se que são descontados 11% para o Imposto de Renda, 8% para o INSS e 5% para o sindicato, faça um programa que nos dê: 
salário bruto. 
quanto pagou ao INSS. 
quanto pagou ao sindicato. 
o salário líquido. 
calcule os descontos e o salário líquido, conforme a tabela abaixo:
Salário Bruto : R$
IR (11%) : R$
INSS (8%) : R$
Sindicato ( 5%) : R$
Salário Liquido : R$
Obs.: Salário Bruto - Descontos = Salário Líquido.
    ```python
    valor: float = float(input('digite quanto você ganha por hora: '))
    hora: float = float(input('digite a quantidade de horas trbalhadas no mês: '))
    salario_bruto = (valor * hora)
    inss = (salario_bruto * 0.08) 
    sindicato = (salario_bruto * 0.05)
    imposto_de_renda = (salario_bruto * 0.11)
    salario_liquido = ( salario_bruto - inss - sindicato - imposto_de_renda)

    print(f'o salario bruto é: {salario_bruto}')
    print(f'o valor pago ao INSS foi: {inss}')
    print(f'o valor pago ao sindicato foi: {sindicato}')
    print(f'o salario liquido é: {salario_liquido}')
    print(f'''os descontos e o salario liquido são: 
    IR(11%): R$ {imposto_de_renda}
    INSS(8%): R$ {inss}
    Sindicato(5%): R$ {sindicato}
    Salario liquido: R$ {salario_liquido}''')
    
    ```


22. Faça um Programa que peça dois números e imprima o maior deles. 
    ```python
    n1 = int(input('digite um numero: '))
    n2 = int(input('digite outro numero: '))
    if n1 > n2:
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
    elif media == 10:
        print('aprovado com Distinção!')
    else:
        print('aprovado!')
    ```
    
26. Faça um Programa que leia três números e mostre o maior deles.
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
    
27. Faça um programa que pergunte o preço de três produtos e informe qual produto você deve comprar, sabendo que a decisão é sempre pelo mais barato.
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
    
28. Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-Vespertino ou N- Noturno. Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.
    ```python
    turno: str = str(input('em qual turno você estuda?,digite M para matutino ou V para Vespertino ou N para Noturno: '))
    if turno == "M" :
         print('Bom dia!')
    else:
        if turno == "V" :
            print('Boa tarde!')
        else:
            if turno == "N" :
                print('Boa noite')
            else:
                print('valor inválido!')
     ```
    
29. As Organizações Tabajara resolveram dar um aumento de salário aos seus colaboradores e lhe contrataram para desenvolver o programa que calculará os reajustes. Faça um programa que recebe o salário de um       colaborador e o reajuste segundo o seguinte critério, baseado no salário atual: 
salários até R$ 280,00 (incluindo): aumento de 20% 
salários entre R$ 280,00 e R$ 700,00: aumento de 15% 
salários entre R$ 700,00 e R$ 1500,00: aumento de 10% 
salários de R$ 1500,00 em diante: aumento de 5% Após o aumento ser realizado, informe na tela: 
o salário antes do reajuste; 
o percentual de aumento aplicado; 
o valor do aumento; 
o novo salário, após o aumento.
    ```python
    salario: float = float(input('digite seu salario: ')) 
    porcentagem1: str = '20%'
    porcentagem2: str = '15%'
    porcentagem3: str = '10%' 
    porcentagem4: str = '5%' 


    if salario <= 280:
        print(f'o salário antes do reajuste:  {salario}')
        print(f'o percentual de aumento aplicado é: {porcentagem1}')
        print(f'o valor do aumento: {(salario*1.20) - salario:.2f}')
        print(f'o novo salário, após o aumento é de: {salario*1.20:.2f}')


    elif salario > 280 and salario < 700 :
        print(f'o salário antes do reajuste:{salario}')
        print(f'o percentual de aumento aplicado é:{porcentagem2}')
        print(f'o valor do aumento: {(salario*1.15) - salario:.2f}')
        print(f'o novo salário, após o aumento é de: {salario*1.15:.2f}')

    elif salario > 700 and salario < 1500 :
        print(f'o salário antes do reajuste: {salario}')
        print(f'o percentual de aumento aplicado é: {porcentagem3}')
        print(f'o valor do aumento: {(salario*1.10) - salario:.2f}')
        print(f'o novo salário, após o aumento é de: {salario*1.10:.2f}')

    else:
        print(f'o salário antes do reajuste: {salario}')
        print(f'o percentual de aumento aplicado é: {porcentagem4}')
        print(f'o valor do aumento: {(salario*1.05) - salario:.2f}')
        print(f'o novo salário, após o aumento é de: {salario*1.05:.2f}')               
    ```

30. Faça um programa para o cálculo de uma folha de pagamento, sabendo que os descontos são do Imposto de Renda, que depende do salário bruto (conforme tabela abaixo) e 3% para o Sindicato e que o FGTS corresponde a 11% do Salário Bruto, mas não é descontado (é a empresa que deposita). O Salário Líquido corresponde ao Salário Bruto menos os descontos. O programa deverá pedir ao usuário o valor da sua hora e a quantidade de horas trabalhadas no mês. 
Desconto do IR: 
Salário Bruto até 900 (inclusive) - isento 
Salário Bruto até 1500 (inclusive) - desconto de 5% 
Salário Bruto até 2500 (inclusive) - desconto de 10% 
Salário Bruto acima de 2500 - desconto de 20%
    ```python
    valor_hora: float = float(input('digite o valor da sua hora: '))
    horas: float = float(input('digite a quantidade de horas trabalhadas no mês: '))
    salario_bruto: float = (valor_hora* horas)
    inss: float = (salario_bruto * (10/100))
    fgts: float = (salario_bruto * (11/100))
    imposto_de_renda1: float = (salario_bruto * 0)
    imposto_de_renda2: float = (salario_bruto * (5/100))
    imposto_de_renda3: float = (salario_bruto * (10/100))
    imposto_de_renda4: float = (salario_bruto * (20/100))



    if salario_bruto <= 900:
        print(f'SALÁRIO BRUTO: {salario_bruto}')
        print(f'(-) IMPOSTO DE RENDA (0%): R$ {imposto_de_renda1}')
        print(f'(-) INSS (10%): R$ {inss} ')
        print(f'FGTS (11%): R$ {fgts} ')
        print(f'TOTAL DE DESCONTOS: R$ {imposto_de_renda1+inss}')
        print(f'SALÁRIO LIQUIDO: R$ {salario_bruto-(imposto_de_renda1+inss)}')
    else:
         if salario_bruto > 900 and salario_bruto <=1500:
            print(f'SALÁRIO BRUTO: {salario_bruto}')
            print(f'(-) IMPOSTO DE RENDA (5%): R$ {imposto_de_renda2}')
            print(f'(-) INSS (10%): R$ {inss} ')
            print(f'FGTS (11%): R$ {fgts} ')
            print(f'TOTAL DE DESCONTOS: R$ {imposto_de_renda2+inss}')  
            print(f'SALÁRIO LIQUIDO: R$ {salario_bruto-(imposto_de_renda2+inss)}')
         else:
             if salario_bruto > 1500 and salario_bruto <=2500:
                 print(f'SALÁRIO BRUTO: {salario_bruto}')
                 print(f'(-) IMPOSTO DE RENDA (10%): R$ {imposto_de_renda3}')
                 print(f'(-) INSS (10%): R$ {inss} ')
                 print(f'FGTS (11%): R$ {fgts} ')
                 print(f'TOTAL DE DESCONTOS: R$ {imposto_de_renda3+inss}')  
                 print(f'SALÁRIO LIQUIDO: R$ {salario_bruto-(imposto_de_renda3+inss)}')
             else:
                print(f'SALÁRIO BRUTO: {salario_bruto}')
                print(f'(-) IMPOSTO DE RENDA (20%): R$ {imposto_de_renda4}')
                print(f'(-) INSS (10%): R$ {inss} ')
                print(f'FGTS (11%): R$ {fgts} ')
                print(f'TOTAL DE DESCONTOS: R$ {imposto_de_renda4+inss}')  
                print(f'SALÁRIO LIQUIDO: R$ {salario_bruto-(imposto_de_renda4+inss)}')
     ```
    
31.  Faça um Programa que leia um número e exiba o dia correspondente da semana. (1-Domingo, 2- Segunda, etc.), se digitar outro valor deve aparecer valor inválido.
     ```python
     numero: float = float(input('digite um numero: '))
     if numero == 1:
           print('o dia da semana correspondente a esse número é: DOMINGO!')
     else:
          if numero == 2:
              print('o dia da semana correspente a esse número é: SEGUNDA!')
          else:
              if numero == 3:
                  print('o dia da semana correspente a esse número é: TERÇA!')
              else:
                  if numero == 4:
                      print('o dia da semana correspente a esse número é: QUARTA!')
                  else:
                      if numero == 5:
                          print('o dia da semana correspente a esse número é: QUINTA!')
                      else:
                          if numero == 6:
                              print('o dia da semana correspente a esse número é: SEXTA!')
                          else:
                              if numero == 7:
                                  print('o dia da semana correspente a esse número é: SÁBADO!')
                              else:
                                  print('valor inválido!')
     ```
32. Faça um programa que lê as duas notas parciais obtidas por um aluno numa disciplina ao longo de um semestre, e calcule a sua média. A atribuição de conceitos obedece à tabela abaixo: 
Média de Aproveitamento  Conceito
Entre 9.0 e 10.0       A
Entre 7.5 e 9.0         B
Entre 6.0 e 7.5         C
Entre 4.0 e 6.0         D
Entre 4.0 e zero       E
O algoritmo deve mostrar na tela as notas, a média, o conceito correspondente e a mensagem “APROVADO” se o conceito for A, B ou C ou “REPROVADO” se o conceito for D ou E.
    ```python
    nota1: float = float(input('digite sua primeira nota:'))
    nota2: float = float(input('digite sua segunda nota:'))
    media: float = float(( nota1+nota2)/2)
    if media >= 9 and media <= 10:
        print('A')
        print(f'suas notas são: {nota1,nota2}')
        print(f'sua media é: {media}')
        print('APROVADO')
    else:
        if media >= 7.5 and media < 9:
            print('B')
            print(f'suas notas são: {nota1,nota2}')
            print(f'sua media é: {media}')
            print('APROVADO')
        else:
            if media >= 6 and media < 7.5:
                print('C')
                print(f'suas notas são: {nota1,nota2}')
                print(f'sua media é: {media}')
                print('APROVADO')
            else:
                if media >= 4 and media < 6:
                    print('D')
                    print(f'suas notas são: {nota1,nota2}')
                    print(f'sua media é: {media}')
                    print('REPROVADO')
                else:
                    if media >= 0 and media < 4:
                        print('E')
                        print(f'suas notas são: {nota1,nota2}')
                        print(f'sua media é: {media}')
                        print('REPROVADO')
            
    ```

33. Faça um Programa que peça os 3 lados de um triângulo. O programa deverá informar se os valores podem ser um triângulo. Indique, caso os lados formem um triângulo, se o mesmo é: equilátero, isósceles ou escaleno. 
Dicas: Três lados formam um triângulo quando a soma de quaisquer dois lados for maior que o terceiro; Triângulo Equilátero: três lados iguais; Triângulo isósceles: quaisquer dois lados iguais; Triângulo Escaleno: três lados diferentes;
    ```python
    lado1: float = float(input('digite o valor do primeiro lado do triangulo: '))
    lado2: float = float(input('digite o valor do segundo lado do triangulo: '))
    lado3: float = float(input('digite o valor do terceiro lado do triangulo: '))

    if lado1 == 0 or lado2 == 0 or lado3 == 0:
      print('valores inválidos!')
    else:
        if lado1 > lado2 + lado3 or lado2 > lado1 + lado3 or lado3 > lado1 + lado2:
             print('esses valores nao podem formar um triangulo')
        else:
            if lado1 == lado2 and lado2 == lado3:
                print('seu triangulo é equilátero!')
            else:
                if lado1 == lado2 or lado1 == lado3 or lado3 == lado2:
                    print('seu triangulo é isósceles!')
                else:
                    if lado1 != lado2 and lado1!= lado3 and  lado2 != lado3:
                        print('seu triangulo é escaleno!')
    ```

34. Faça um programa que calcule as raízes de uma equação do segundo grau, na forma ax2 + bx + c. O programa deverá pedir os valores de a, b e c e fazer as consistências, informando ao usuário nas seguintes situações: 
Se o usuário informar o valor de A igual a zero, a equação não é do segundo grau e o programa não deve fazer pedir os demais valores, sendo encerrado; 
Se o delta calculado for negativo, a equação não possui raizes reais. Informe ao usuáro e encerre o programa; 
    ```python
    a = float(input('dgite o valor do coeficiente a: '))
    if a == 0:
       print('isso não é uma equaçao do 2° grau')
    else:
       b = float(input('digite o valor do coeficiente b: '))
       c = float(input('digite o valor do coeficiente c: '))
       delta =(b**2)-(4*a*c)
       if delta < 0 :
           print('equaçao nao possui raizes reais!')
       else:
           print(f'o delta da equação é: {delta}')
     ```

35. Se o delta calculado for igual a zero a equação possui apenas uma raiz real; informe-a ao usuário; 
Se o delta for positivo, a equação possui duas raiz reais; informe-as ao usuário;
    ```python
    a = float(input('dgite o valor do coeficiente a: '))
       if a == 0:
          print('isso não é uma equaçao do 2° grau')
       else:
          b = float(input('digite o valor do coeficiente b: '))
          c = float(input('digite o valor do coeficiente c: '))
          delta =(b**2)-(4*a*c)
          if delta < 0 :
              print('equaçao nao possui raizes reais!')
          else:
              if  delta == 0 :
                  print('a equaçao possui apenas uma reaiz real!')
                  x1 = -b/(2*a)
                  print(f'a raiz é: {x1}')
              else:
                  print('a equaçao possui duas raizes reais!')
                  x1 = float((-(b)-(delta)**(1/2))/(2*a))
                  x2 = float((-(b)+(delta)**(1/2))/(2*a))
                  print('as raizes da equaçao são: ')
                  print(f'x1: {x1}')
                  print(f'x2: {x2}')
    ```
    
36. Faça um Programa que peça um número correspondente a um determinado ano e em seguida informe se este ano é ou não bissexto.
    ```python
    if ano % 4 != 0:
       print('esse ano não é bissexto')
    else:
       if ano % 100 == 0 and ano % 400 != 0:
          print('esse ano não pode ser bissexto')
       else:
            print(f' o ano : {ano} é bissexto')

    ```
    
37. Faça um Programa para leitura de três notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e apresentar: 
A mensagem "Aprovado", se a média for maior ou igual a 7, com a respectiva média alcançada; 
A mensagem "Reprovado", se a média for menor do que 7, com a respectiva média alcançada; 
A mensagem "Aprovado com Distinção", se a média for igual a 10.
    ```python
    nota1: float = float(input('digite sua primeita nota: '))
    nota2: float = float(input('digite sua segunda nota: '))
    nota3: float = float(input('digite sua terceira nota: '))
    media = (nota1+nota2+nota3)/3
    print(f'sua média é: {media :.2f} ')
    if media < 7:
        print('reprovado!')
    else:
        if media == 10:
            print('aprovado com Distinção!')
        else:
            print('aprovado!')
    ```

39. Faça um Programa para um caixa eletrônico. O programa deverá perguntar ao usuário a valor do saque e depois informar quantas notas de cada valor serão fornecidas. As notas disponíveis serão as de 1, 5, 10, 50 e 100 reais. O valor mínimo é de 10 reais e o máximo de 600 reais. O programa não deve se preocupar com a quantidade de notas existentes na máquina. 
Exemplo 1: Para sacar a quantia de 256 reais, o programa fornece duas notas de 100, uma nota de 50, uma nota de 5 e uma nota de 1; 
Exemplo 2: Para sacar a quantia de 399 reais, o programa fornece três notas de 100, uma nota de 50, quatro notas de 10, uma nota de 5 e quatro notas de 1. 
    ```python
    saque = int(input('Valor de saque: '))

    notaUm = notaCinco = notaDez = notaCinquenta = notaCem = 0

    if saque < 10 or saque > 600:
      print('Valor Inválido')
    else:
      if saque >= 100:
        notaCem = saque // 100
        saque = saque % 100
      if saque >= 50:
        notaCinquenta = saque // 50
        saque = saque % 50
      if saque >= 10:
        notaDez = saque // 10
        saque = saque % 10
      if saque >= 5:
        notaCinco = saque // 5
        saque = saque % 5
      if saque >= 1:
        notaUm = saque // 1
        saque = saque % 1

     if notaCem > 0:
       print(notaCem, 'Nota(s) de R$100')
     if notaCinquenta > 0:
       print(notaCinquenta, 'Nota(s) de R$50')
     if notaDez > 0:
       print(notaDez, 'Nota(s) de R$10')
    if notaCinco > 0:
      print(notaCinco, 'Nota(s) de R$5')
    if notaUm > 0:
      print(notaUm, 'Nota(s) de R$1')

    ```
    
40. Faça um Programa que peça um número inteiro e determine se ele é par ou impar.
    ```python
    numero: int = int(input('digite um número: '))
    if numero % 2 == 0:
       print('seu número é par')
    else:
       print('seu número é impar')
    ```
    
41. Faça um Programa que leia 2 números e em seguida pergunte ao usuário qual operação ele deseja realizar. O resultado da operação deve ser acompanhado de uma frase que diga se o número é: 
par ou ímpar; 
positivo ou negativo; 
inteiro ou decimal.
    ```python
    numero1: float = float(input('digite seu primero numero: '))

    numero2: float = float(input('digite seu segundo numero: '))

    operacao: float = float(input('''digite a sua operaçao:
        ADIÇÃO: 1
        SUBTRAÇÃO: 2
        MULTIPLICAÇÃO: 3
        DIVISÃO: 4 \n'''))

    soma = numero1 + numero2
    subtracao = numero1 - numero2
    multiplicacao = numero1 * numero2
    if operacao == 1:
        print(f'o numero é:{soma}')
        if soma % 2 == 0:
            print('par')
        else:
            print('impar')
        if soma > 0:
            print('positivo')
        else:
            if soma == 0:
                print('nulo')
            else:
                print('negativo')
        if soma != int(soma):
            print('decimal')
        else:
            print('inteiro')

    if operacao == 2:
        print(f'o numero é: {subtracao}')
        if subtracao % 2 == 0:
            print('par')
        else:
            print('impar')
        if subtracao > 0:
            print('positivo')
        else:
            if subtracao == 0:
                print('nulo')
            else:
                print('negativo')
        if subtracao != int(subtracao):
            print('decimal')
        else:
            print('inteiro')

    if operacao == 3:
        print(f'o numero é: {multiplicacao}')
        if multiplicacao % 2 == 0:
            print('par')
        else:
            print('impar')
        if multiplicacao > 0:
            print('positivo')
        else:
            if multiplicacao == 0:
                print('nulo')
            else:
                print('negativo')
        if multiplicacao != int(multiplicacao):
            print('decimal')
        else:
            print('inteiro')

    if operacao == 4:
        if numero2 == 0:
            print('operacao invalida, pois  o denominador nao pode ser igual a 0')
        else:
            divisao = numero1 / numero2
            print(f'o numero é: {divisao}')
            if divisao % 2 == 0:
                print('par')
            else:
                print('impar')
            if divisao > 0:
                print('positivo')
            else:
                 if divisao == 0:
                    print('nulo')
                 else:
                     print('negativo')
            if divisao != int(divisao):
                print('decimal')
            else:
                print('inteiro')
    ```
    
42. Faça um programa que faça 5 perguntas para uma pessoa sobre um crime. As perguntas são: 
"Telefonou para a vítima?" 
"Esteve no local do crime?" 
"Mora perto da vítima?" 
"Devia para a vítima?" 
"Já trabalhou com a vítima?" O programa deve no final emitir uma classificação sobre a participação da pessoa no crime. Se a pessoa responder positivamente a 2 questões ela deve ser classificada como "Suspeita", entre 3 e 4 como "Cúmplice" e 5 como "Assassino". Caso contrário, ele será classificado como "Inocente".
    ```python
    respostas = 0

    pergunta1 = input('Telefonou para a vitima? Digite sim ou não')
    if pergunta1 == 'sim':
      respostas += 1
    pergunta2 = input('Esteve no local do crime? Digite sim ou não')
    if pergunta2 == 'sim':
      respostas += 1
    pergunta3 = input('Mora perto da vitima? Digite sim ou não')
    if pergunta3 == 'sim':
      respostas += 1
    pergunta4 = input('Devia para a vitima? Digite sim ou não')
    if pergunta4 == 'sim':
      respostas += 1
    pergunta5 = input('Ja trabalhou com a vitima? Digite sim ou não')
    if pergunta5 == 'sim':
      respostas += 1

    if respostas != 'sim' or respostas != 'não':
      print('invalido')
    else:
      if respostas == 2:
        print('Suspeita')
      else:
        if respostas >=3 and respostas <=4:
          print('Cúmplice')
        else:
          if respostas == 5:
            print('Assassino')
          else:
            print('Inocente')
    ```

43. Um posto está vendendo combustíveis com a seguinte tabela de descontos: 
Álcool: 
até 20 litros, desconto de 3% por litro 
acima de 20 litros, desconto de 5% por litro 
Gasolina: 
até 20 litros, desconto de 4% por litro 
acima de 20 litros, desconto de 6% por litro.
Escreva um programa que leia o número de litros vendidos, o tipo de combustível (codificado da seguinte forma: A-álcool, G-gasolina), calcule e imprima o valor a ser pago pelo cliente sabendo-se que o preço do litro da gasolina é R$ 2,50 o preço do litro do álcool é R$ 1,90.
    ```python
    tipo: str = input('digite o tipo de combustivel utilizado: ')
    if tipo == 'alcool':
       alcool: float = float(input('digite a quantidade de litros: '))
       if alcool<= 20:
           print(f'o valor pago do alcool será de: {alcool*1.90*0.97}')
       else:
           print(f'o valor pago do alcool será de: {alcool*1.90*0.95}')
    else:
        gasolina: float = float(input('digite a quantidade de litros: '))
        if gasolina <= 20:
           print(f'o valor pago da gasolina será de: {gasolina*2.50*0.97}')
        else :
           print(f'o valor pago da gasolina será de: {gasolina*2.50*0.95}')
    ```
    
44. Uma fruteira está vendendo frutas com a seguinte tabela de preços: 
                Até 5 Kg                Acima de 5 Kg 
Morango         R$ 2,50 por Kg          R$ 2,20 por Kg
Maçã            R$ 1,80 por Kg          R$ 1,50 por Kg
Se o cliente comprar mais de 8 Kg em frutas ou o valor total da compra ultrapassar R$ 25,00, receberá ainda um desconto de 10% sobre este total. Escreva um algoritmo para ler a quantidade (em Kg) de morangos e a quantidade (em Kg) de maças adquiridas e escreva o valor a ser pago pelo cliente.
    ```python
    kg_morango: float = float(input('digite quantos kg de morango você comprou: '))
    kg_maca: float = float(input('digite quantos kg de maçã você comprou: '))
    preco_morango = 2.50
    preco_maca = 1.80
    preco_morango_desconto = 2.20
    preco_maca_desconto =  1.50
    if kg_morango + kg_maca > 5:
        valor_morango = kg_morango * preco_morango_desconto
        valor_maca = kg_maca * preco_maca_desconto
    else:
        valor_morango = kg_morango * preco_morango
        valor_maca = kg_maca * preco_maca

    valor_total = valor_maca + valor_morango

    if (kg_morango + kg_maca ) > 8 or valor_total > 25:
        valor_total *= 0.90
        print('você ganhou um desconto de 10%')

    print(f' o valor a ser pago pelo os morangos é: R$ {valor_morango:.2f}')
    print(f' o valor a ser pago pela as maças é: R$ {valor_maca:.2f}')
    print(f' o valor total a ser pago é: R$ {valor_total:.2f}')

    ```

45. Elabore um algoritmo que dada a idade de um nadador classifica-o em uma das seguintes categorias:  infantil A = 5 - 7 anos; infantil B = 8-10 anos; juvenil A = 11-13 anos; juvenil B = 14-17 anos; adulto = maiores de 18 anos.
    ```python
    idade: int = int(input('digite a idade do nadador: '))
    if idade < 5:
      print ('idade não permitida')
    else:
      if idade >= 5 and idade <= 7:
        print('a categoria do nadador será : Infantil A')
      else:
        if idade >= 8 and idade <= 10:
          print('a categoria do nadador será : Infantil B')
        else:
          if idade >= 11 and idade <= 13:
            print('a categoria do nadador será : Juvenil A')
          else:
            if idade >= 14 and idade <= 17:
              print('a categoria do nadador será : Juvenil B')
            else:
              if idade >= 18:
                print('a categoria do nadador será : Adulto')
    
    ```

45. Tendo como dados de entrada a altura e o sexo de uma pessoa, construa um algoritmo que calcule seu peso ideal, utilizando as seguintes fórmulas: para homens: (72.7*h) – 58 e para mulheres: (62.1*h) - 44.7 (h = altura)
    ```python
    sexo:str = str(input('digite o seu sexo (masculino ou feminino): '))

    if sexo != 'feminino' and sexo != 'masculino':
      print('sexo inválido!')
    else:

        altura:float = float(input('digite a sua altura em Metros: '))

        if sexo == 'masculino':
          peso_ideal = (72.7*altura) - 58
          print(f'o seu peso ideal é: {peso_ideal:.2f} kg ')
        else:
          if sexo == 'feminino':
            peso_ideal = (62.1 *altura)- 44.7
            print(f'o seu peso ideal é: {peso_ideal:.2f} kg ')
  

     ```

46. Escreva um programa que calcula a média de 30 alunos e informa a situação (reprovado, aprovado ou recuperação).
    ```python
    for i in range(1,31):
      nota1: float = float(input('digite a 1° nota do aluno: '))
      nota2: float = float(input('digite a 2° nota do aluno: '))
      media = (nota1 + nota2) / 2
      if nota1 < 0 or nota2 < 0 or nota1 > 10 or nota2 > 10:
        print('notas inválidas!') 
      else:
        if media >= 7:
           print(f'a média do aluno foi: {media:.2f} e a situação desse aluno é : aprovado')
        else:
          if media >= 4.5 and media < 7:
            print(f'a média do aluno foi: {media:.2f} e a situação desse aluno é : recuperação')
          else:
            if media < 4.5:
              print(f'a média do aluno foi: {media:.2f} e a situação desse aluno é : reprovado')

    ```

47. Escreva um programa que leia 10 números e informe o maior e o menor número.
    ```python
    num: int = int(input('digite o 1° número: '))
    numMaior = numMenor = num

    for i in range (2,11):
      num: int = int(input(f'digite o {i}° número: '))

      if numMaior > num:
        numMaior = num 
      else:
          if numMenor < num:
            numMenor = num

    print(f'o maior numero é: {numMaior}')
    print(f'o menor numero é: {numMenor}')


    ```
    
48. Escreva um programa que calcula o fatorial de um dado número N.
    ```python

    num: int = int(input('digite o número o qual você quer calcular o fatorial: '))
    fatorial = 1

    if num < 0:
      print('valor inválido, pois não existe fatorial negativo!') 
    else:
      for i in range (num ,0, -1 ):
        fatorial *= i
      print(f'{num}! = {fatorial}')

    ```

49. Faça um programa para somar os números pares positivos < 1000 e ao final escrever o resultado.
    ```python
    soma = 0

    for i in range (2,1000,2):
       soma += i
    print(f'a soma dos pares positivos menores que 1000 é : {soma}')

    ```

 50. Faça um programa para calcular a área de N quadriláteros. Fórmula: Área = Lado * Lado.
     ```python
     quad:int  = int(input('digite a quantidade de quadrilateros que você quer calcular a area: '))

     for i in range(quad):
        lado1: float = float(input('digite o valor do  1° lado do quadrilátero: '))
        lado2: float = float(input('digite o valor do  2° lado do quadrilátero: '))
        area = (lado1 * lado2)
        print(f'a area do quadrilátero é: {area:.2f} ')


     ```

51. Faça um programa para calcular um valor A elevado a um expoente B. Os valores A e B deverão ser lidos. Não usar A** B e sim uma estrutura de repetição.
    ```python
    A: float = float(input('digite o valor da Base: '))
    B: int = int(input('digite o valor do expoente: '))
    potencia = 1
    for i in range(B):
      potencia *= A 
    print(potencia)

    ```

52. Sendo H = 1 + 1/2 + 1/3 + 1/4 + ... + 1/N. Faça um programa para gerar e mostrar o número H. O número N será fornecido como entrada.
    ```python
    N = int(input('Digite o valor de N: '))
    H = 0
    for i in range(1, N + 1):
        H += 1 / i
        print(f'1/{i} = {1 / i}')
    
    print(f'H = {H}')


    ```

53. Faça um programa para: 
a) Ler um valor x qualquer
b) Calcular Y = (x+1)+(x+2)+(x+3)+(x+4)+(x+5)+…(x+100).
    ```python
    X: int = int(input('digite um valor para X: '))
    resultado = 0
    variavel = 0

    for i in range(1,101,1):
      variavel += 1
      Y = (X + variavel)
      resultado += Y
  
    print(f'o resultado de Y é : {resultado}')

    ```


54. Fazer um programa que calcule e escreva a soma dos 50 primeiros termos da seguinte série:
    ```python
    numerador = 1003
    denominador = 0
    resultadoFinal = 0

    for i in range(0,51):

      numerador -= 3
      denominador += 1
      soma = numerador / denominador
      print(f'{numerador} / {denominador}')
      resultadoFinal += soma

    print(f' a Soma dos 50 primeiros termos é: {resultadoFinal}')

    ```

55. Faça um programa que recebe o número real x como entrada e devolva uma aproximação do arco tangente de x (em radianos) através da série:
    ```python
    x: float = float(input('digite o valor de X: '))

    sinal = 1
    expoente = 1 
    arctang = 0

    for i in range(50):
      arctang += sinal * (x**expoente/ expoente)  
      expoente += 2
      sinal *= -1

    print(f' o arco tanente de {x}° em radiano é: {arctang}')

    ```
56.	Faça um programa que mostre os n termos da Série a seguir: 

      S = 1/1 + 2/3 + 3/5 + 4/7 + 5/9 + ... + n/m. 
      Imprima no final a soma da série.
      ```python
      n: int = int(input('digite o valor de n(quantidade de termos): '))
      numerador = 1
      denominador = 1
      soma = 0

      for i in range(n):
        termo = (numerador / denominador)
        soma += termo
        print(f'{numerador} / {denominador} = {termo}')
        numerador += 1
        denominador += 2
  
      print(f'o resultado da soma é: {soma}')


      ```

57. Cada espectador de um cinema respondeu a um questionário no qual constava sua idade e a sua opinião em relação ao filme: ótimo - 3, bom - 2, regular - 1. Faça um programa que receba a idade e a opinião de 15 espectadores, calcule e imprima:
a)	A média das idades das pessoas que responderam ótimo;
b)	A quantidade de pessoas que responderam regular;
c)	A porcentagem de pessoas que responderam bom entre todos os espectadores analisados.
    ```python
    otimo = 0
    bom = 0
    regular = 0
    idade_total = 0
    rep = 0

    for i in range(15):
      idade:int = int(input('digite a sua idade: '))
      nota: int = int(input('''digite a sua opinião ao filme:
    otimo - (3)
    bom - (2)
    regular - (1)   :  '''))
  
      rep += 1
      if nota == 1:
        regular += 1
      else:
        if nota == 2:
          bom += 1 
      
        else:
          if nota == 3:
            otimo += 1
            idade_total += idade
          else:
            print('valor inválido')

    if otimo > 0:
      media_idade = (idade_total / otimo)
    else:
      media_idade = 0

    porcentagem_bom =(bom / 15) * 100 
  

    if rep == 15:
        print(f'a media das idades das pessoas que respoderam (Òtimo)  no questionário é: {media_idade} ')
        print(f'a quantidade de pessoas que respoderam (Regular) no questionário é: {regular} ')
        print(f'a porcentagem de pessoas que respoderam (Bom) entre todos os espectadores analisados é: {porcentagem_bom:.2f}% ')

    ```

58. Faça um programa que receba dois números inteiros e gere os números inteiros que estão no intervalo compreendido por eles.
    ```python
    n1: int = int(input('digite um valor: '))
    n2: int = int(input('digite outro valor: '))
    if (n1 - 1) == n2 or (n2 - 1) == n1:
      print(f'não existe intervalo inteiro entre os numeros {n1} e {n2} !')
    else:
      if n1 != n2:
        if n1 > n2:
          for i in range(n2 + 1 , n1):
            print(i)

        else:
          if n1 < n2:
           for i in range (n1 + 1 , n2):
             print(i)

      else:
       print(f'não existe intervalo inteiro entre os numeros {n1} e {n2} !')


    
    ```

 59. Desenvolva um gerador de tabuada, capaz de gerar a tabuada de qualquer número inteiro entre 1 a 10. O usuário deve informar de qual numero ele deseja ver a tabuada. A saída deve ser conforme o exemplo abaixo: 
    Tabuada de 5:
    5 X 1 = 5
    5 X 2 = 10
    ...
    5 X 10 = 50

     ```python
      x = int(input('digite o numero o qual voce deseja ver a tabuada: '))
      while x < 0:
          print('valor inválido, por favor digite outro valor para X')
 
          x = int(input('digite o numero o qual voce deseja ver a tabuada: '))
 
      for y in range (1,11):
          tabuada = y * x
          print( x, "x", y, "=", tabuada)
 
     ```

60. Faça um programa que peça um número inteiro e determine se ele é ou não um número primo. Um número primo é aquele que é divisível somente por ele mesmo e por 1.
    ```python
    quant = 0
    numero:int  = int(input('Digite um número: '))

    while numero <= 0:
      print('Valor inválido! Tente novamente.')

      numero = int(input('Digite um número: '))
    print(f'os numeros divisores foram : ')
    for i in range(1,numero + 1):
      if numero % i == 0:
        print(i, end=(' '))
        quant += 1
    print(f'\nO número {numero} foi divisível {quant} vezes.')
    if quant == 2 :
      print('O número é primo.')
    else:
      print('O número não é primo.')

    ```

61. Faça um programa que peça para n pessoas a sua idade, ao final o programa devera verificar se a média de idade da turma varia entre 0 e 25, 26 e 60 e maior que 60; e então, dizer se a turma é jovem, adulta ou idosa, conforme a média calculada.
    ```python
    nPessoas = int(input('Digite a quantidade de pessoas: '))
    idadeTotal = 0

    for i in range(nPessoas):
        idade = int(input(f'Digite a idade da pessoa { i + 1 } : '))

        while idade < 0:
            print("Valor inválido. Idade não pode ser negativa.")
            idade = int(input('Digite outra idade válida: '))
    
        idadeTotal += idade
    
    media = idadeTotal / nPessoas

    if media <= 25:
        print('A turma é jovem!')
    else:
       if media <= 60:
           print('A turma é adulta!')
       else:
          if media > 60:
           print('A turma é idosa!')

   
    ```

62. A série de FETUCCINE é gerada da seguinte forma: os dois primeiros termos são fornecidos pelo usuário; a partir daí, os termos são gerados com a soma ou subtração dos dois termos anteriores, ou seja:
    ```python
    i = 2
    qntd = 0
    while qntd < 3:
      qntd = int(input("Digite a quantidade de números da série (serão necessários pelo menos três termos): "))

    primeiro_termo = int(input("Insira o primeiro termo da série: "))
    segundo_termo = int(input("Insira o segundo termo da série: "))
    print(f"1° - {primeiro_termo}")
    print(f"2° - {segundo_termo}")
    while i < qntd:
      if i % 2 == 0:
        novo_termo = segundo_termo + primeiro_termo
     else:
        novo_termo = segundo_termo - primeiro_termo
     print(f"{i + 1}° - {novo_termo}")
     primeiro_termo = segundo_termo
     segundo_termo = novo_termo
     i += 1

    ```

63. Escreva um programa que imprima os N termos de uma Progressão Aritmética, conforme fórmula a seguir. O usuário deverá fornecer o valor de: n (número de termos), r (razão) e a1 (primeiro termo da série).
    ```python
    
    a1: int = int(input("Digite o valor de a1 (primeiro termo): "))
    r: int  = int(input("Digite o valor de r (razão): "))
    termos: int = int(input("Digite o número de termos: "))

    if termos <= 0:
        print("O número de termos deve ser maior que zero.")
    else:
        for i in range(termos):
            an = a1 + i * r
            print(an)


    ```

64. O Departamento Estadual de Meteorologia lhe contratou para desenvolver um programa que leia um conjunto indeterminado de temperaturas, e informe ao final a menor e a maior temperatura informada, bem como a média das temperaturas.
    ```python
    
    temperatura: int = int(input('Informe uma temperatura: '))
    maior = menor = temperatura
    soma = 0
    soma += temperatura
    contador = 1

    condicional = input('Deseja continuar? S - Sim / N - Não  ').strip().upper()

    while condicional == 'S':
        temperatura = int(input('Digite uma temperatura: '))
        soma += temperatura
        contador += 1

        if temperatura > maior:
            maior = temperatura
        if temperatura < menor:
            menor = temperatura

        condicional = input('Deseja continuar? S - Sim / N - Não  ').strip().upper()

    if contador > 0:
        media = soma / contador
        print(f'A MAIOR temperatura digitada foi: {maior}')
        print(f'A MENOR temperatura digitada foi: {menor}')
        print(f'A MÉDIA das temperaturas informadas foi: {media:.2f}')
    else:
        print('Nenhuma temperatura foi informada.')

   
    ```

65. Faça um programa que receba o valor de uma dívida e mostre uma tabela com os seguintes dados: valor da dívida, valor dos juros, quantidade de parcelas e valor da parcela. 
Os juros e a quantidade de parcelas seguem a tabela abaixo: 
Quantidade de Parcelas  % de Juros sobre o valor inicial da dívida
    1      			 0
	3   		    	10
	6       			15
	
   Exemplo de saída do programa: 
   Valor da Dívida     Valor dos Juros           Quantidade de Parcelas                 Valor da Parcela
   R$ 1.000,00              0                         1                                 R$  1.000,00
   R$ 1.100,00             100                        3                                 R$    366,00
   R$ 1.150,00             150                        6                                 R$    191,67

   ```python

   divida: float = float(input('Informe o valor da dívida: '))

   parcela3 = 10 / 100
   parcela6 = 15 / 100

   juros3 = divida * parcela3
   juros6 = divida * parcela6

   valParcela3 = (divida + juros3) / 3
   valParcela6 = (divida + juros6) / 6

   if divida <= 0:
       print('valor inválido')
   else:
       print('\nValor da Dívida   Valor dos Juros   Quantidade de Parcelas   Valor da Parcela')
       print(f'{divida:>15.2f}           0.00                 1       {divida:>20.2f}')
       print(f'{divida + juros3:>15.2f} {juros3:>15.2f}                3       {valParcela3:>20.2f}')
       print(f'{divida + juros6:>15.2f} {juros6:>15.2f}                6       {valParcela6:>20.2f}')
   

    


   ```


66. Uma grande firma deseja saber qual é o empregado mais recente e qual é o mais antigo. Desenvolver um programa para ler um número indeterminado de informações contendo o número do empregado e o número de meses de trabalho deste empregado e imprimir o mais recente e o mais antigo. Obs.: A última informação contém os dois números iguais a zero. Não existem dois empregados admitidos no mesmo mês
    ```python
    

    anosTrabalhadorVelho = -1
    anosTrabalhadorNovo = float('inf')
    numeroDoEmpregadoNovo = numeroDoEmpregadoVelho = None

    condicional = "S"

    while condicional == "S":
        numeroDoEmpregado = int(input('Informe o numero de registro do empregado: '))
        anosDeTrabalho = int(input('Informe há quanto tempo este trabalhador está na empresa: '))

        if anosDeTrabalho > anosTrabalhadorVelho:
            anosTrabalhadorVelho = anosDeTrabalho
            numeroDoEmpregadoVelho = numeroDoEmpregado

        if anosDeTrabalho < anosTrabalhadorNovo:
            anosTrabalhadorNovo = anosDeTrabalho
            numeroDoEmpregadoNovo = numeroDoEmpregado

        condicional = input('Deseja continuar? S - Sim / N - Não: ').strip().upper()

    if numeroDoEmpregadoNovo is None or numeroDoEmpregadoVelho is None:
        print('Nenhum trabalhador foi registrado.')
    else:
        print(f'\nO trabalhador mais novo na empresa possui registro: {numeroDoEmpregadoNovo} e está aqui há {anosTrabalhadorNovo} ano(s)')
        print(f'O trabalhador mais antigo na empresa possui registro: {numeroDoEmpregadoVelho} e está aqui há  {anosTrabalhadorVelho} ano(s)')

   
    ```

67. A prefeitura de uma cidade fez uma pesquisa entre seus habitantes, coletando dados sobre o salário e número de filhos. A prefeitura deseja saber:
   a)	Média do salário da população;
   b)	Média do número de filhos;
   c)	Maior salário;
   d)	Percentual de pessoas com salário até R$250,00.
   Desenvolver um programa para calcular e escrever o que foi pedido nos itens a, b, c e d. O final da leitura de dados se dará com a entrada de um salário negativo.
   ```python

   salario250 = totalFilhos = totalSalario = 0
   contador = 0
   maiorSal = float('-inf')

   continuar = "S"

   while continuar == "S":
       Salario = int(input('Digite o salario deste habitante (ou um valor negativo para encerrar): '))

       if Salario < 0:
           continuar = "N"
           continue

       totalSalario += Salario
       contador += 1

       if Salario > maiorSal:
           maiorSal = Salario

       if Salario <= 250:
           salario250 += 1

       Nfilhos = int(input('Digite a quantia de filhos deste habitante: '))
       if Nfilhos > 0:
           totalFilhos += Nfilhos

       continuar = input('Deseja continuar? S - Sim / N - Não: ').strip().upper()

   if contador > 0:
       mediaSalario = totalSalario / contador
       mediaFilhos = totalFilhos / contador
       percentualSalario250 = (salario250 / contador) * 100

       print(f'\nA) A média salarial da população foi de: {mediaSalario}')
       print(f'B) A média do número de filhos da população foi de: {mediaFilhos}')
       print(f'C) O maior salário registrado foi de: {maiorSal}')
       print(f'D) O percentual de pessoas com salário de até R$250 foi de: {percentualSalario250}')
   else:
       print("Nenhum dado válido foi registrado.")



   ```


68. Faça um programa que leia uma quantidade não determinada de números positivos. Calcule a quantidade de números pares e ímpares, a média de valores pares e a média geral dos números lidos. O número que encerrará a leitura será zero.
       ```python
	valor = valorPedido = valorTotal = 0

	item100 = item101 = item102 = item103 = item104 = item105 = item106 = 0

	valItem100 = valItem101 = valItem102 = valItem103 = valItem104 = valItem105 = 0

	print("Especificação 	    Código 	 	 Preço")
	print("Cachorro Quente 	  100     	R$ 1,20")
	print("Bauru Simples         101     	R$ 1,30")
	print("Bauru com ovo         102     	R$ 1,50")
	print("Hambúrguer            103     	R$ 1,20")
	print("Cheeseburguer         104     	R$ 1,30")
	print("Refrigerante          105     	R$ 1,00")

	comidaCod = str(input("\nInforme o codigo do lanche desejado: "))
	if comidaCod == "100" or comidaCod == "101" or comidaCod == "102" or comidaCod == "103" or comidaCod == "104" or comidaCod == "105":
    	quantia = int(input("Informe a quantia: "))

	if comidaCod == "100":
    	valor = 1.2
    	valorPedido = valor * quantia
    	item100 += quantia
    	valItem100 += valor * quantia
	elif comidaCod == "101":
    	valor = 1.3
    	valorPedido = valor * quantia
    	item101 += quantia
    	valItem101 += valor * quantia
	elif comidaCod == "102":
    	valor = 1.5
    	valorPedido = valor * quantia
    	item102 += quantia
    	valItem102 += valor * quantia
	elif comidaCod == "103":
    	valor = 1.2
    	valorPedido = valor * quantia
    	item103 += quantia
    	valItem103 += valor * quantia
	elif comidaCod == "104":
    	valor = 1.3
    	valorPedido = valor * quantia
    	item104 += quantia
    	valItem104 += valor * quantia
	elif comidaCod == "105":
    	valor = 1.3
    	valorPedido = valor * quantia
    	item105 += quantia
    	valItem105 += valor * quantia
	elif comidaCod != "100" or comidaCod != "101" or comidaCod != "102" or comidaCod != "103" or comidaCod != "104" or comidaCod != "105":
    	print("Voce digitou um codigo invalido.")

	valorTotal += valorPedido

	condicional = str(input("\nDeseja continuar comprando? S - Sim / N - Não  ")).upper()

	while condicional not in "N":
    	comidaCod = str(input("\nInforme o codigo do lanche desejado: "))
    	if comidaCod == "100" or comidaCod == "101" or comidaCod == "102" or comidaCod == "103" or comidaCod == "104" or comidaCod == "105":
        	quantia = int(input("Informe a quantia: "))

    	if comidaCod == "100":
        	valor = 1.2
        	valorPedido = valor * quantia
        	item100 += quantia
        	valItem100 += valor * quantia
    	elif comidaCod == "101":
        	valor = 1.3
        	valorPedido = valor * quantia
        	item101 += quantia
        	valItem101 += valor * quantia
    	elif comidaCod == "102":
        	valor = 1.5
        	valorPedido = valor * quantia
        	item102 += quantia
        	valItem102 += valor * quantia
    	elif comidaCod == "103":
        	valor = 1.2
        	valorPedido = valor * quantia
        	item103 += quantia
        	valItem103 += valor * quantia
    	elif comidaCod == "104":
        	valor = 1.3
        	valorPedido = valor * quantia
        	item104 += quantia
        	valItem104 += valor * quantia
    	elif comidaCod == "105":
        	valor = 1.3
        	valorPedido = valor * quantia
        	item105 += quantia
        	valItem105 += valor * quantia
    	elif comidaCod != "100" or comidaCod != "101" or comidaCod != "102" or comidaCod != "103" or comidaCod != "104" or comidaCod != "105":
        	print("Voce digitou um codigo invalido.")

    	valorTotal += valorPedido

    	condicional = str(input("\nDeseja continuar comprando? S - Sim / N - Não  ")).upper()

	if condicional == "N":
    	print("\n(100) Voce pediu um total de:", item100, ",Somando: ", valItem100)
    	print("(101) Voce pediu um total de:", item101, ",Somando: ", valItem101)
    	print("(102) Voce pediu um total de:", item102, ",Somando: ", valItem102)
    	print("(103) Voce pediu um total de:", item103, ",Somando: ", valItem103)
    	print("(104) Voce pediu um total de:", item104, ",Somando: ", valItem104)
    	print("(105) Voce pediu um total de:", item105, ",Somando: ", valItem105)
    	print("\nO total da sua compra foi de: ", valorTotal, "Reais")

      ```

70. Você foi contratado para escrever um algoritmo que calcule quantos pontos fez um time num campeonato de futebol. Para os que não conhecem futebol uma vitória vale três pontos, um empate vale 1 ponto e a derrota não vale ponto. A entrada será composta por pares de números indicando o resultado de cada jogo. O primeiro número sempre corresponde ao total de gols que o time fez no jogo. A leitura dos dados será finalizada quando for fornecido um número de gols negativo.
	```python
 	pontos = 0

	print("AVISO: Para interromper o programa, digite uma quantidade negativa de gols.")

	continuar = True

	while continuar:
 	   golsFeitos = int(input("Informe quantos gols o time fez: "))
           golsSofridos = int(input("Informe quantos gols o time sofreu: "))

   	 if golsFeitos < 0 or golsSofridos < 0:
    	    continuar = False
   	 else:
       	     if golsFeitos > golsSofridos:
       	         pontos += 3
       	     elif golsFeitos == golsSofridos:
          	  pontos += 1

	print("\nO time fez um total de:", pontos, "pontos!")
 
 
 	```

71. Faça um programa que receba um número e verifique se ele é ou não triangular.  OBS: um número é triangular quando é resultado do produto de 3 números consecutivos. Exemplo: o número 24 é triangular, pois, 24 = 2 * 3 * 4.
	```python

	print("Verifique se um numero é triangular")

	numero = int(input("Digite o valor do numero: "))

	i = 1

	while i*(i+1)*(i+2) < numero:
    	i = i + 1

	if i*(i+1)*(i+2) == numero:
    	print(numero, "é o produto", i, "", i+1, "", i+2)

	else:
    	print("Não é triangular:", numero)
 
 
 	```
72. Faça um programa para validar o login e a senha de um usuário. Caso o usuário informe algum valor inválido informar o erro e pedir novamente os dados. A leitura dos dados deve ser encerrada quando o usuário digitar 3 vezes um valor inválido (login ou senha). Considere o login válido como "kezia" e a senha como "123".
    ```python
    

    contador = validacao = 0

    while contador < 3:
        login = str(input("Informe o seu login: "))
        senha = str(input("Informe sua senha: "))
        if login != "kezia" or senha != "123":
            contador += 1
         print("\nsenha ou login invalidos, tente novamente")
            validacao += 0

        else:
            print("\nBem vinda, Kezia!")
            contador += 3
            validacao += 1

    if contador >= 3 and validacao == 0:
        print("\nTente novamente mais tarde.")
    ```
