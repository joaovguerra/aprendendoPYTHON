#DECLARANDO VARIÁVEL#
nome = 'João'
idade = 18
peso = 70.5
print('Seu nome é :' ,nome)
print('Sua idade é :' ,idade)
print('Seu peso é :' ,peso)



#INTERAGINDO COM O USUÁRIO#
nome = input('Qual seu nome ?')
idade = input('Qual sua idade ?')
peso = input('Qual seu peso ?')
print("Nome :" ,nome)
print('Idade' ,idade)
print('Peso :' ,peso)


#SOMA DE DOIS NÚMEROS#
n1 = int(input('Digite um número :'))
n2 = int(input('Digite outro número :'))
print('A soma é :' ,n1+n2)


#PROGRAMA QUE DESEJA BEM VINDO AO USUÁRIO
nome = input('Digite seu nome :')
print('Seja bem vindo {} !' .format(nome))  #O DADO RECEBIDO , IRÁ APAREER DENTRO DAS CHAVES#


#{:20}<-ESCREVE A PALAVRA DENTRO DE 20 LINHAS , PODENDO SER CENTRALIZADA({:^20})#
nome = 'João'
input('Olá , {:20}!' .format(nome)) 

#CENTRALIZADO
nome = 'João'
input('Olá , {:^20}!' .format(nome))


#'\n' SERVE PARA PASSAR A FRASE SEGUINTE PARA A PRÓXIMA LINHA#
print ('Olá \nComo você está ?')


#CALCULA MÉIDA DAS NOTAS#
n1 = int(input('Digite a nota 1 :'))
n2 = int(input('Digite a nota 2 :'))
s = n1+n2
m = s/2
print('A média das notas é {}' .format( m))
