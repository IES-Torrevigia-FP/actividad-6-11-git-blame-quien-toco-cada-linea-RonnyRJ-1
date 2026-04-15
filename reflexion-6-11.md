Yo usaria git blame para depurar bugs porque ayuda a identificar que cambio introdujo un error,al igual que para entender mejor el codigo viendo el contexto de cada line y su evolucion, y tambien para saber a quien preguntar cuando necesito aclarar por que se hizo una modificacion concreta

Es mala idea usar git blame para señalar culpables ya que el objetivo del comando no es asignar responsabilidades a personas, lo mejor es entender el codigo. De forma constructiva se usa para aprender del cambio, aprender o entender porque se modifico una linea, analizar el commit y mejorar el codigo.

Dos buenas practicas serian mantener una conveccion de estilo coherente en todo el proyecto y separar los cambios de refactorizacion de los cambios funcionales asi es mas facil entender que se modofico y porque en cada linea.
