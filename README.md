<a href="http://utp.edu.co"><img src="https://upload.wikimedia.org/wikipedia/commons/2/2c/Logo_U.T.P.png" title="UTPLogo" alt="UTPLogo" width="20%" height="20%" align="right"></a>

# Compiladores - Analizador léxico (Mini Pascal)

### Integrantes

- <h3>Santiago Sosa Herrera</h3>
- <h3>Santiago Sanchez Pulgarín</h3>

<a href="lexer image"><img src="https://homepages.cwi.nl/~steven/pascal/book/lex-1.gif" title="Genetic" alt="Genetic" align="center"></a>

---

## Instalación

### Clonar el repositorio

- Para clonar el repositorio, utilizar el comando `git clonehttps://github.com/santiagoSSAA/pascal_lexer.git`.

### Instalar el módulo de Ply

- Teniendo previamente instalado pip en el equipo, `pip install ply`.
- Utilizar el comando `pip list` para confirmar que el módulo ha sido instalado exitosamente.

### ejecutar el código

- Una vez clonado el repositorio, ejecutamos el comando `cd ruta_destino/pascal_lexer`
- Para ejecutar el código, utilizar el comando . `python3 lexer.py Test/input.pas` en caso de tener python 3x, y `python lexer.py Test/input.pas` en caso de tener python 2.7.

---

## Objetivo general

Crear la primera fase de un compilador para un lenguaje determinado (pascal), que consiste en la creación de un programa que recibe como entrada un archivo que contiene una secuencia de caracteres, y produce una salida compuesta de tokens (componentes léxicos) o símbolos. 

## Objetivo específico

Aprender el estado del arte del analizador léxico, y como este realiza su tarea de reconocimiento de tokens en una entrada de caracteres, mediante el aprendizaje práctico utilizando tecnologías tales como **Python** y el módulo **Ply** para la implementación del analizador en un programa.

---

## Lista de tokens

- Palabras Reservadas

- Símbolos

- Identificadores

- Números
