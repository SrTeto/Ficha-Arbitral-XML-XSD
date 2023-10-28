# Ficha-Arbitral-XML-XSD
#CADA

Usalo a tu disposicion. 

Actas Arbitrales Federacion Española en XML XSD

Este proyecto fue creado gracias a una actividad evaluada del grado que estoy cursando actualmente.

La finalidad de estos archivos es crear una estructura organizada y esquematizada teniendo como modelo el documento que deben llenar los arbitros en España cada vez que termine un partido de Futbol.
en este se puede completar:
Contenido XML
Fechas
Temporadas
Jornadas
Lugar del Evento

El equipo: 
  con un codigo de Equipo UNICO y correspondiente que permite la identificacion en distintos niveles de la estructura para asi tener relacionalidad
Cuerpo Tecnico del equipo desde Entrenadores hasta los Delegados del campo
No cuenta con un campo "director Tecnico" ya que este no es necesario para efectos del resultado del partido.
Jugadores con su numero de camiseta, su documento de identificacion DNI O pasaporte (TODOS LOS EJEMPLOS EXPUESTOS SON FICCTICIOS Y SI EXISTEN NO CORRESPONDEN CON LOS NOMBRE QUE ALLI APARECEN)
Comentarios Sobre pasaporte y DNI: Todos los datos Fueron generados por un pagina web de manera aleatoria (https://generadordni.es)

Resultado Final:  
  que cuenta con Tiempo. En el se pueden registran tantos tiempos sean necesarios puesto que un partido puede variar desde 2 tiempos hasta 4.
Tiene atributo del codigo del Equipo para hacer referencia a los equipos que actuan
goles y hora de inicio de los partidos en distintos tiempos. 

Sustituciones :
  Referencia al codigo de equipo quien hace el cambio, el jugador que entra y el que sale , ambos con su numero de camiseta correspondiente y el minuto donde se efectua el cambio.
  
Goles :
  se divide por goles, referencia al equipo que marco el gol,el minuto en el que se hizo, jugador y numero de camiseta.

Tarjetas:
  se divide por tarjetas, referencia al equipo,el minuto en que se realizo, jugador y numero de camiseta. tipo de tarjeta: Amarilla o Roja

Amonestaciones:
  Amonestacion : Referencia al equipo del jugador al que se le hace la amonestacion, luego tiene un espacio maximo de 250 caracteres para hacer la explicacion de la amonestacion.
  expulsiones: Referencia al equipo del jugador , el minuto donde sucede la expulsion , numero de camiseta , nombre Jugador, Motivo (Breve descripcion) 
  Otras Incidencias: Un campo de texto donde el arbitro puede escribir cualquier otro tipo de incidencia, Maximo 250 caracteres (valor por defecto Ninguna)
  Amonestacion a Tecnicos: Un campo de texto donde el arbitro puede escribir cualquier otro tipo de incidencia, Maximo 250 caracteres (valor por defecto Ninguna)
  Otras Incidencias tecnicas: Un campo de texto donde el arbitro puede escribir cualquier otro tipo de incidencia, Maximo 250 caracteres (valor por defecto Ninguna)
  Publico: Un campo de texto donde el arbitro puede escribir cualquier otro tipo de incidencia, Maximo 250 caracteres (valor por defecto Normal)
  DEFICIENCIAS OBSERVADAS EN EL TERRENO DE JUEGO E INSTALACIONES (valor por defecto Ninguna) 
  OTRAS OBSERVACIONES O AMPLIACIONES A LAS ANTERIORES (valor por defecto Ninguna) 
  
