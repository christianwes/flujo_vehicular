# **Series de Tiempo - Determinacion del flujo vehicular**


El dataset utilizado es brindado por el Gobierno de la Ciudad Buenos Aires de [aquí](https://data.buenosaires.gob.ar/dataset/flujo-vehicular-por-unidades-peaje-ausa).  Se tomrán los datos de los años 2017, 2018 y 2019 para analizar el flujo vehicular de la autopista Illia y predecir el mismo para el ultimo trimestre de 2019.

A su vez encontrará en el repositorio la segunda parte del proyecto donde se utilizó la libreria Alphabet, que fue desarrollada recientemente por Facebook, para poder predecir el flujo vehicular en el ultimo trimestre de 2019. En el desarrollo de este notebook se detectaron outliers en la serie de tiempo, pero estos no fueron tratados. Ademas se implementa un metodo de tratamiento de los mismos para eliminarlos como tales y reemplazar su valor por uno apropiado para que la serie siga siendo continua.

Por otro lado, se compara si la tendencia es la misma para transporte pesado y transporte liviano. Es decir, los que cambiaron al metodo de pago telepase fueron todso los autos(livianos), o también los camiones(pesados)? Asimismo, se analiza si la caida en el metodo de pago de tipo efectivo en la autopista Illia, se corresponde con un crecimiento a algun otro metodo de pago
