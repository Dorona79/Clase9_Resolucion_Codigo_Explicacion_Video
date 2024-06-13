# RESOLUCIÓN DEL CÓDIGO

# 1.From datetime import datetime:

Importa la clase datetime del módulo datetime, que se usará para manejar fechas.

# 2.Clase Tarea:

Es la clase base para todas las tareas.
El método __init__ inicializa una tarea con nombre, descripción y prioridad.
El método mostrar devuelve una cadena con la información de la tarea.


# 3.Clase TareaGeneral:

Hereda de Tarea.
No agrega funcionalidad adicional, solo llama al constructor de la clase padre.


# 4.Clase TareaConFecha:

También hereda de Tarea.
Añade un atributo fecha en su constructor.
Sobrescribe el método mostrar para incluir la fecha en el formato deseado.


# 5.Clase ListaDeTareas:

Mantiene una lista de tareas.
agregar_tarea añade una tarea a la lista.
eliminar_tarea elimina una tarea por su índice.
mostrar_tareas muestra todas las tareas en la lista.


# 6.Función main:

Crea una instancia de ListaDeTareas.
Inicia un bucle que muestra un menú y procesa las opciones del usuario:

Opción 1: Agrega una tarea general.
Opción 2: Agrega una tarea con fecha.
Opción 3: Elimina una tarea.
Opción 4: Muestra todas las tareas.
Opción 5: Sale del programa.


Para agregar tareas (opciones 1 y 2):

Solicita nombre, descripción y prioridad.
Valida que la prioridad sea correcta.
Para tareas con fecha, solicita y valida una fecha.
Crea la tarea apropiada y la añade a la lista.


Para eliminar tareas (opción 3):

Solicita el índice de la tarea a eliminar.


Para mostrar tareas (opción 4):

Llama al método mostrar_tareas de la lista.

# 7.if __name__ == "__main__"::

Asegura que main() solo se ejecute si el script se está ejecutando directamente y no siendo importado como módulo.

