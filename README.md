La herencia múltiple, como su nombre lo indica, permite que un objeto pueda heredar los atributos de sus predecesores para evitar tener código duplicado e inútil dentro de los objetos. Esto se logra agregando "extends clasePadre" en la clase donde nos encontremos, lo que nos permite evitar redundancias y hacer buen uso del espacio y código existentes.

Sin embargo, en Java no se soporta la herencia múltiple. Este problema, conocido como "el problema del diamante", nos indica que no podemos tener dos herencias en una clase al mismo tiempo, ya que sería muy difícil distinguir el tipo de objeto que se desea que sea.

Por lo tanto, aunque usemos "this" o alguna otra herramienta dentro de Java, no sería posible hacer un uso correcto de los atributos de la clase padre o clases en el contexto de la herencia múltiple.

![Image text](https://github.com/SantiagoLunaMir/Herencia/blob/main/dP11JiCm44NtFiKigH0N81kW8B50g28dCFQGM7BiQ6QAg53lZXEvZgjaXRpoz___pVY1HPCS1w-KCbupmm69O_XL07VG2hdGGT03DhFm5etspreGFXr9R_KfwTE1M-XGtfFnPdUVSyqiSvQhhbspH9vopnGhxILPNjVWL7A-pF.png)
