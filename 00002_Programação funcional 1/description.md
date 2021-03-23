Defina a função `composicao` que recebe 3 argumentos, nessa ordem:

* Uma função, `f`
* Outra função, `g`
* Um número, `x`

A função `composicao` deve, então, executar _f_ a _x_ e, em seguida, _g_  sobre o resultado. Matematicamente, isso equivale a _(g ∘ f)(x)_ ou, se preferir, _g(f(x))_.

Por exemplo, se _f_ calcula o dobro de _x_ e _g_ soma 3 ao seu argumento, então `composicao(f, g, 7)` deve retornar 17, pois o dobro de 7 é 14, que ao ser acrescido de 3, retulta 17.
