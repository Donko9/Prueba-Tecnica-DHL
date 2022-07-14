# Prueba-Tecnica-DHL
Kenneth Saul Cornejo Vertiz

El programa es capaz de filtrar de manera precisa o buscando similitudes de busqueda, es decir, que de solo poner una sola letra en el buscador;
-este identificara cualquier similitud dentro de la celda colocada.
Cuenta con sistema de error en dado caso de colocar un valor inexistente dentro de la tabla.
Esta programada de tal forma que pueda seguir siendo operable si se le añaden o retiran datos

Los archivos estan separados entre 3 modulos, 1 User Form y 1 Datasheet

En la Data sheet u Hoja de calculo, cree una celda de cambio variable para que recibiera en tiempo real los cambios provocados por los filtros.

En los modulos estan registradas:
  °Configuracion del boton Query
  °Filtro avanzado para mostrar unicamente la informacion deseada
  °El retorno de la tabla a su estado natural despues de haber aplicado el Filtro Avanzado

Dentro del User form se configuraron
  °Una cuadro combinado para la opcion de Genre ya que solo eran 2 opciones
  °Una List box de 5 columnas en la que se muestra la coincidencia de Busqueda
  °Mensajes de error por no haber llenado una casilla dentro de el formulario
  °Mensajes de error si no se encuentra ningun valor con las caracteristicas colocadas
  °Configuracion del boton cancelar para retornar la Tabla a la normalidad y salir de la ventana emergente
  °Configuracion para que con 1 click en la List Box se Filtre la tabla y nos muestre unicamente el valor deseado
  
