## Forecast agregado más desagregación top/down

En este folder se encuentra un modelo de fcst agregado a nivel de departamento (predecir cuántos productos en total se van a vender en los 7 departamentos que hay en los datos). Hacer la predicción a 28 días a futuro

Luego de tener ese forecast agregado, se procede a realizar una desagregación utilizando un modelo (por ejemplo un top/down) para hacer la predicción a nivel de "id de cada departamento"

Esta es una vuelta larga, PERO, **el objetivo es probar cómo sería entrenar un modelo que haga el forecast a nivel "departamento" y luego encontrar la forma de desagregarlo a nivel "id" manteniendo la relación de que la suma del forecast a nivel id tiene que ser igual al forecast a nivel transporte**

**Es una condición para este ejemplo que se haga primero el forecast a nivel departamento y luego buscar una forma de desagregarlo a nivel id**. Sería más fácil hacerlo a nivel id y luego sumar para tener a nivel departamento, pero para este ejemplo, esto no se puede hacer