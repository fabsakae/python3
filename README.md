# python3
km = float(input('Quantos quilometros rodados?'))
dias = float(input('Por quantos dias foi alugado?'))
#preco_dia = 60 * dias
#preco_km = km * 0.15
#custo = preco_km + preco_dia
custo = (60 * dias) + (km * 0.15)
print('O valor a ser pago será de R$ {:.2f} '.format(custo))
