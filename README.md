Simulador de Combate con Clases en Python

Descripción

Este proyecto es una práctica para aprender programación orientada a objetos en Python. Consiste en un simulador de combate por turnos entre dos personajes: un Guerrero y un Mago, que heredan de una clase base llamada Personaje. Cada personaje tiene atributos como fuerza, inteligencia, defensa, vida y un objeto especial (espada para el guerrero, libro para el mago). El programa permite simular un combate donde los personajes se atacan hasta que uno muere o ambos empatan.

Características

Clase Base Personaje: Define atributos comunes (nombre, fuerza, inteligencia, defensa, vida) y métodos como atacar, verificar si está vivo, calcular daño, subir de nivel y morir.

Clase Guerrero: Hereda de Personaje y añade un atributo espada. Permite cambiar el arma (Acero Valyrio o Matadragones) y calcula el daño basado en la fuerza y el valor de la espada.

Clase Mago: Hereda de Personaje y añade un atributo libro. Calcula el daño basado en la inteligencia y el valor del libro.

Sistema de Combate: Un bucle por turnos donde cada personaje ataca al otro, mostrando el daño causado y la vida restante hasta que uno muere o ambos caen.

Herencia y Polimorfismo: Utiliza herencia para compartir métodos y polimorfismo para personalizar el cálculo del daño y la visualización de atributos.

Tecnologías Utilizadas

Python 3: Para la lógica del programa, usando clases, herencia y entrada/salida por consola.

Instrucciones de Configuración

Para ejecutar este proyecto localmente, sigue estos pasos:

Clonar el Repositorio:

git clone https://github.com/tu-usuario/tu-nombre-repositorio.git

Navegar al Directorio del Proyecto:

cd tu-nombre-repositorio

Ejecutar el Programa:

Asegúrate de tener Python 3 instalado.

Ejecuta el archivo principal (por ejemplo, combate.py):

python combate.py

Estructura de Archivos (asumida):

tu-nombre-repositorio/
├── combate.py
└── README.md

Uso

Ejecución: Al correr el programa, se crea un guerrero ("Guts") y un mago ("Vanessa") con atributos predefinidos y se inicia un combate automático.

Combate: El programa muestra los turnos, las acciones de cada personaje (ataques y daño causado), la vida restante y el resultado final (quién gana o si hay empate).

Interactividad: El método cambiar_arma del guerrero permite al usuario elegir un arma, aunque no se usa en el combate automático actual.

Salida: La consola muestra mensajes como:

Turno 0
>>> Accion de Guts:
Guts ha realizado 76 puntos de daño a Vanessa
Vanessa ha muerto
>>> Accion de Vanessa:
Vanessa ha realizado 71 puntos de daño a Guts
La vida de Guts es 29
Ha ganado Guts

Mejoras Futuras

Agregar una interfaz de usuario para elegir personajes, atributos o acciones durante el combate.

Implementar más tipos de personajes (por ejemplo, Arquero, Clérigo) con habilidades únicas.

Añadir efectos de estado (veneno, curación) o habilidades especiales.

Permitir al usuario controlar los turnos o las acciones de los personajes en lugar de un combate automático.

Mejorar el manejo de errores para entradas inválidas en cambiar_arma.
