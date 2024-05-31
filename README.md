# REST API de UPZ-APOCALYPSE para Minimo 2 de DSA.

Funcionalidad que permita realizar una denuncia de un abuso con la siguiente información: fecha, nombre, comentario.

T1: Implementar un nuevo Servicio en BACKEND con una única ruta en la API que
permita denunciar un abuso. El servicio únicamente mostrará por la consola la
denuncia (JSON) recibida -->  COMPLETADA

- En GameManager se ha definido la función addDenuncia. Además de preparar la función getDenuncias para poder dar una lista.
- En GameManagerImpl se ha usado HashMap para generar la lista de denuncias y se ha dado funcionalidad a addDenuncia y getDenuncias.
- En GameService se han definido las llamadas a la API para añadir denuncias y dar la lista de estas.
- Creada clase Denuncia con sus respectivos campos.