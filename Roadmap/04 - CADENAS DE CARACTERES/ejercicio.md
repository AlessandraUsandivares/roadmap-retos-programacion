# #04 CADENAS DE CARACTERES
> #### Dificultad: Media | Publicación: 22/01/24 | Corrección: 29/01/24

## Ejercicio

```
/*
 * EJERCICIO:
 * Muestra ejemplos de todas las operaciones que puedes realizar con cadenas de caracteres
 * en tu lenguaje. Algunas de esas operaciones podrían ser (busca todas las que puedas):
 * - Acceso a caracteres específicos, subcadenas, longitud, concatenación, repetición, recorrido,
 *   conversión a mayúsculas y minúsculas, reemplazo, división, unión, interpolación, verificación...
 *
 * DIFICULTAD EXTRA (opcional):
 * Crea un programa que analice dos palabras diferentes y realice comprobaciones
 * para descubrir si son:
 * - Palíndromos
 * - Anagramas
 * - Isogramas
 */
```
s1 = "Hola"
s2 = "Python"

# Concatenación
print(s1 + ", " + s2 + "!")

# Repetición
print(s1 * 3)

# Indexación
print(s1[0] + s1[1] + s1[2] + s1[3])

# Longitud
print(len(s2))

# Slicing (porción)
print(s2[2:6])
print(s2[2:])
print(s2[0:2])
print(s2[:2])

# Busqueda
print("a" in s1)
print("i" in s1)

# Reemplazo
print(s1.replace("o", "a"))

# División
print(s2.split("t"))

# Mayúsculas, minúsculas y letras en mayúsculas
print(s1.upper())
print(s1.lower())
print("kimberly contreras".title())
print("kimberly contreras".capitalize())

# Eliminación de espacios al principio y al final
print("kimberly contreras ".strip())

# Búsqueda al principio y al final
print(s1.startswith("Ho"))
print(s1.startswith("Py"))
print(s1.endswith("la"))
print(s1.endswith("thon"))

s3 = "kimberly contreras @kim1007"

# Búsqueda de posición
print(s3.find("Contreras"))
print(s3.find("Contreras"))
print(s3.find("C"))
print(s3.lower().find("c"))

# Búsqueda de ocurrencias
print(s3.lower().count("m"))

# Formateo
print("Saludo: {}, lenguje: {}!".format(s1, s2))

# Interpolación
print(f"Saludo: {s1}, lenguje: {s2}!")

# Tranformación en lista de caracteres
print(list(s3))

# Transformación de lista en cadena
l1 = [s1, ", ", s2, "!"]
print("".join(l1))

# Transformaciones numéricas
s4 = "123456"
s4 = int(s4)
print(s4)

s5 = "123456.123"
s5 = float(s5)
print(s5)

# Comprobaciones varias
s4 = "123456"
print(s1.isalnum())
print(s1.isalpha())
print(s4.isalpha())
print(s4.isnumeric())
#### Tienes toda la información extendida sobre el roadmap de retos de programación en **[retosdeprogramacion.com/roadmap](https://retosdeprogramacion.com/roadmap)**.

Sigue las **[instrucciones](../../README.md)**, consulta las correcciones y aporta la tuya propia utilizando el lenguaje de programación que quieras.

> Recuerda que cada semana se publica un nuevo ejercicio y se corrige el de la semana anterior en directo desde **[Twitch](https://twitch.tv/mouredev)**. Tienes el horario en la sección "eventos" del servidor de **[Discord](https://discord.gg/mouredev)**.
