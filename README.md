# ChallengeFront

Mejoras realizadas:

1. Se dividió el componente en dos: un grupo maneja exclusivamente la lógica y estados del componente y otra que realiza el renderizado en sí.


Errores encontrados:

1. Hace falta un "}" para cerrar el constructor.
2. Hace falta un "return res.json()" ya que el metodo fetch obtiene la una respuesta HTTP, por lo que es necesario convertir la respuesta a un formato json para su posterior tratamiento.
