# MissionesSQF
repositorio de misiones para exportacion sqf

las exportaciones deben de modificarse y hacerse en el mapa a donde seran importadas
los ejemplos de exportaciones son todos en el mapa VR de realidad virtual, para ver un ejemplo solo copia la carpeta a tu perfil de arma 3 en Documentos/arma3/otherProfiles/nombre/missions
abrir realidad virtual y abrir escenario

para exportar a sqf, entramos en el escenario, seleccionamos la opcion de scenario esquina superior izq,
seleccionamos exportar
seleccionamos exportar a sqf.
pegamos el resultado en un .txt
colocamos el nombre de la mision en el txt y cambiamos el .txt por .sqf //EJEMPLO MISSION1.SQF
entregamos el archivo al editor o lo llamamos dentro de una mision con el codigo execVM "ruta del archivo\MISSION1.SQF"


PARA COMPLETAR O FALLAR MISIONES SE DEBE COLOCAR ESTO EN EL TRIGGER QUE ACTIVA DICHO EVENTO, EN ACTIVACION
execVM "Functions\completeMission.sqf";

PARA USAR UNIDADES CIVILES EN LAS MISIONES SE DEBE COLOCAR ESTE CODIGO EN EL INIT(recuadro gris al dar doble click a la unidad) DE LA UNIDAD
this setVariable ["scriptCiv", true];
