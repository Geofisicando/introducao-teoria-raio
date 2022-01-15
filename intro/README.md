# Aula 0 - Sobre o curso, o material de apoio e as referências

[:arrow_up: Voltar](https://github.com/Geofisicando/introducao-teoria-raio#%C3%ADndice)

## Relevância da teoria do raio

O método do raio é uma extensão da teoria da propagação de ondas planas em meios de
variação suave da velocidade. Possui duas vantagens: Permite compreender fisicamente o fenômeno da propagação de ondas em modelos
razoavelmente complicados e produz algoritmos eficientes e que não exigem tanto tempo computacional
como os métodos de diferenças finitas e elementos finitos.

# Introdução

## Teoria do raio

O método do raio tem duas vantagens. Ele proporciona a compreensão do fenômeno de propagação de ondas em modelos geofísicos razoavelmente complicados, descrevendo o campo de ondas total como a soma de diferentes tipos de ondas geradas no problema a em consideração. Isto proporciona um algoritmo numérico efetivo e que não consome tanto tempo quando comparado aos métodos de diferenças finitas e elementos finitos.

Por outro lado, o método do raio sofre com o chamado problema das cáusticas, oque significa precisamente que se os raios associados com o problema da propagação da onda sob investigação tocam uma superfície 3D (ou uma curva em 2D), o espalhamento geométrico desaparece e a amplitude do raio se torna singular neste limite, enquanto o campo de ondas real se mantém finito e suave.

Esta superfície é chamada de envelope do campo de ondas, ou superfície de cáustica. Assim, o método do raio não descreve corretamente o campo de ondas na vizinhança das cáusticas. Infelizmente, nos modelos geofísicos de meios elásticos o comportamento dos raios é complicado e eles normalmente formam cáusticas de diferentes estruturas geométricas. Então, o método do raio encontra sérios problemas com as cáusticas em aplicações geofísicas.

