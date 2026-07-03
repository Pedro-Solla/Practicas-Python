# Practicas-Python
Codigo utilizado en las prácticas "Descubrimiento de sistemas dinámicos a partir de datos".

En Lorenz 1_Modificado.ipynb, al utilizar una aproximación puramente lineal mediante SVD con p=10, se prueba que, aunque la precisión de la regresión es elevada, las ecuaciones diferenciales resultantes pierden por completo su interpretabilidad física, presentando extensas cadenas de productos polinomiales cruzados. Esto demuestra que una transformación lineal es incapaz de desenredar adecuadamente la topología del atractor caótico. Este resultado justifica la necesidad introducir un autoencoder profundo no lineal, permitiendo que la red neuronal devuelva un espacio latente donde SINDy pueda identificar leyes físicas interpretables.
