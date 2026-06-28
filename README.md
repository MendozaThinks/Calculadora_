🧮 Calculadora en Python

Una calculadora de consola hecha en Python que evalúa expresiones matemáticas escritas como texto, respetando el orden de operaciones (primero multiplicación/división, luego suma/resta).


✨ Características


Suma, resta, multiplicación y división de números enteros
Respeta la precedencia de operadores (PEMDAS/BODMAS)
Soporte para números negativos (ej: -5+3)
Manejo de errores: expresiones inválidas y división por cero
Interfaz sencilla por consola



▶️ Cómo ejecutarlo

Necesitás tener Python 3.10 o superior instalado (se usa match/case).

bashpython Calculadora.py

Una vez ejecutado, el programa te pedirá que ingreses una expresión:

Si desea salir, ingrese salir.
Ingresa la expresion: 10+5*2
El resultado de 10+5*2 es 20

Para salir, escribí salir y presioná Enter.


📌 Ejemplos de uso

ExpresiónResultado5+3810-4*22100/5+323-5+1056*-2-12


⚙️ Cómo funciona internamente

El programa tiene varias funciones con responsabilidades separadas:

FunciónQué hacesolucion()Lee la expresión carácter a carácter y separa números y operadoresresolver_expresion()Aplica primero * y /, luego + y -resolver_operacion()Llama a la función correcta según el operadorsuma() / resta()Operaciones básicas con Pythonmultiplicacion()Multiplica sumando repetidamente (sin usar *)division()Divide restando repetidamente (sin usar /)concatenar_numero()Construye un número dígito a dígitoverificar_operador()Verifica si un carácter es +, -, * o /verificar_es_numero()Verifica si un carácter (o símbolo) es un número


⚠️ Limitaciones actuales


Solo trabaja con números enteros (no decimales)
La división devuelve solo el cociente entero (sin resto)
No soporta paréntesis en las expresiones




🛠️ Tecnologías


Lenguaje: Python 3.10+
Librerías: Ninguna (solo código estándar)



👤 Autor

Proyecto desarrollado como ejercicio de lógica en Python.
