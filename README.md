
# criei uma funcao validar uma string
# que passei como parametro uma string que tera mim 10 ou max 30 caracteres
# caso atenda essas condicoes faco o print
# caso nao digite esses parametros ira se repetir infinitamente
def validaSt(pergunta, mim, max):
    x = input(pergunta)
    tam = len(x)
    while ((tam < mim) or (tam > max)):
        x = input(pergunta)
        tam = len(x)
    return x


# programa principal 


y = validaSt("digite uma palavra ? ", 10, 30)
print("voce digitou a string {}".format(y))
print(" ******* F - I - N - A - L *******")
