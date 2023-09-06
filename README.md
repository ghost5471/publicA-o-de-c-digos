# Transformando metros;
#Onde o usuário dgitará oq ele quer:

a2 = int(input('digite os metros'))
b2= input("""Vai quer que transforme em: 
          quilometros;
          hectometros;
          decametros;  
          decimetros; 
          decimetros; 
          milimetros ou centimetros?
          digite no lado-""")
#a parte da estrutura onde o programa irá identifcar quql o verdadeiro , ou seja , qual a pessoa escolheu(a função "or' foi colocada caso não tenha o acento no "o" quando o usuário não tenha colocado )

i = b2 in 'decimetros' or b2 in'decímetros'
i2 = b2 in 'centimetros' or b2 in 'centímetros'
i3 = b2 in 'milimetros' or b2 in 'milímetros'
i4 = b2 in 'quilômetros' or b2 in'quilometros'
i5 = b2 in 'hectômetros' or b2 in'hectometros'
i6 = b2 in 'decâmetros' or b2 in'decametros'

#efetuação dos if:
if i2== True:
    e = a2*100
    print(e,'centímetros')

elif i==True:
    e = a2*10
    print( e,'decímetros')

elif  i3== True :
    e = a2*1000
    print('milimetros')

elif i4== True:
    e = a2/1000
    print(e,'quilômetros')

elif i5==True:
    e = a2/100
    print( e,'hectômetros')

elif i6== True :
    e = a2/100
    print(e,'decâmetros')
else:
    print('não entendi , tente novamente')
    #fim
    
