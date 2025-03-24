# #03 ESTRUCTURAS DE DATOS
> #### Dificultad: Media | Publicación: 15/01/24 | Corrección: 22/01/24

## Ejercicio

```
/*
 * EJERCICIO:
 * - Muestra ejemplos de creación de todas las estructuras soportadas por defecto en tu lenguaje.
 * - Utiliza operaciones de inserción, borrado, actualización y ordenación.
 *
 * DIFICULTAD EXTRA (opcional):
 * Crea una agenda de contactos por terminal.
 * - Debes implementar funcionalidades de búsqueda, inserción, actualización y eliminación de contactos.
 * - Cada contacto debe tener un nombre y un número de teléfono.
 * - El programa solicita en primer lugar cuál es la operación que se quiere realizar, y a continuación
 *   los datos necesarios para llevarla a cabo.
 * - El programa no puede dejar introducir números de teléfono no numéricos y con más de 11 dígitos.
 *   (o el número de dígitos que quieras)
 * - También se debe proponer una operación de finalización del programa.
```
# Listas
my_list: list = ["Red", "Yelow", "Green", "Blue"]
print(my_list)
my_list.append("Colors")  
my_list.append("Colors")
print(my_list)
my_list.remove("Red")  
print(my_list)
print(my_list[1])  
my_list[1] = "Colores"  
print(my_list)
my_list.sort()  
print(my_list)
print(type(my_list))

# Tuplas
my_tuple: tuple = ("kim", "cotreras", "@kim1007", "20")
print(my_tuple[1])  
print(my_tuple[3])
my_tuple = tuple(sorted(my_tuple))
print(my_tuple)
print(type(my_tuple))

# Sets
my_set: set = {"kim", "contreras", "@kim1007", "20"}
print(my_set)
my_set.add("kim1006@gmail.com") 
my_set.add("kim1006@gmail.com")
print(my_set)
my_set.remove("Contreras")  
print(my_set)
my_set = set(sorted(my_set)) 
print(my_set)
print(type(my_set))

# Diccionario
my_dict: dict = {
    "name": "Kim",
    "surname": "contreras",
    "alias": "@kim1007",
    "age": "20"
}
my_dict["email"] = "kim1006@gmail.com"  
print(my_dict)
del my_dict["surname"]  
print(my_dict)
print(my_dict["name"])  
my_dict["age"] = "21"  
print(my_dict)
my_dict = dict(sorted(my_dict.items()))  
print(my_dict)
print(type(my_dict))
#### Tienes toda la información extendida sobre el roadmap de retos de programación en **[retosdeprogramacion.com/roadmap](https://retosdeprogramacion.com/roadmap)**.

Sigue las **[instrucciones](../../README.md)**, consulta las correcciones y aporta la tuya propia utilizando el lenguaje de programación que quieras.

> Recuerda que cada semana se publica un nuevo ejercicio y se corrige el de la semana anterior en directo desde **[Twitch](https://twitch.tv/mouredev)**. Tienes el horario en la sección "eventos" del servidor de **[Discord](https://discord.gg/mouredev)**.
