# Repositório dedicado as aulas de Otimizão Aplicada à Ciência de dados da faculdade
- **Regressao_erros_minimos.ipynb** - Casos em que temos apenas uma covariável (x) como variável explicativa (como o exemplo acima), dizemos estar em uma regressão linear simples.

**Regressão Linaear Simples:**
Casos em que temos apenas uma covariável (x) como variável explicativa, dizemos estar em uma regressão linear simples.

Para minimizar a função, aplicamos derivadas parciais, em respeito a 
^
β
0
 e 
^
β
1
, e igualamos a zero. Como minimizar uma função?

Para minimizar uma função 
f
(
x
)
, calculamos sua derivada e igualamos a zero. Para verificar que 
f
′
(
x
)
= 0 é um ponto de mínimo, devemos observar o sinal da segunda derivada, 
f
′′
(
x
)
.

![regressao](https://github.com/ViniciusCantanhede/imagens/raw/90b1280e0d696e78cf83e969b76dfe92964f7e51/Captura%20de%20tela%202024-03-26%20213217.png)

**Forma Matricial:** 
O modelo visto acima pode ser representado matricialmente, generalizando para o caso em que temos mais de uma variável explicativa.
Como estimar os parâmetros com a representação matricial? Mesma ideia: minimizar os erros

**Decomposição do QR:**
Operações envolvendo a inversa de uma matriz podem ser bastante custosas do ponto de vista computacional, principalmente quando a matriz cresce em dimensões. 

Uma alternativa bastante utilizada é a decomposição Sendo Xn × P uma matriz de posto completo (n > p, rank=p), então podemos decompor X em:
 **X = QR** 

 em que:

**Q** tem dimensões n × p e **Q′Q =I**
**R** tem dimensões p × p e é uma matriz triangular superior


![ychapeu](https://github.com/ViniciusCantanhede/imagens/raw/ab0034094d12f27c3bfda8e6a2ca4bdeedd834c2/ychapeu.png)

----------------------------------------------------------------------------------
- **GradientDescent.ipynb** - 
  
