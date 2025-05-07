# 📚 Analizador Léxico en Java con JFlex y Swing

Bienvenido a este repositorio 👋. Aquí encontrarás un **analizador léxico** construido en **Java** utilizando **JFlex** como generador de analizadores y una **interfaz gráfica (GUI)** hecha con **Swing**, para que puedas escribir tu código de prueba y ver los tokens generados de forma ordenada y visual.

---

## 📖 ¿Qué es un Analizador Léxico?

Un **analizador léxico** es la primera etapa de un compilador o intérprete. Su función es leer un texto de entrada (generalmente código fuente) y descomponerlo en **tokens**: las unidades básicas del lenguaje (palabras reservadas, operadores, identificadores, números, cadenas, etc).

---

## 📌 ¿Qué hace este proyecto?

✅ Permite escribir código en un área de texto dentro de una aplicación gráfica.  
✅ Analiza el código utilizando **JFlex**.  
✅ Muestra en una tabla los tokens encontrados con:
- Tipo de token (palabra reservada, operador, número, identificador, etc.)
- Valor detectado.
- Línea y columna donde aparece.

✅ Muestra errores léxicos si se detectan caracteres no válidos.  
✅ Incluye su propio archivo `sym.java` donde se definen todos los tokens que reconoce.  
✅ No necesitas modificar nada en JFlex, solo escribir tu código y ver el resultado.

---

## 📂 Estructura del Proyecto

/src
├── AnalizadorJava.flex # Archivo con las reglas del lexer en JFlex
├── sym.java # Definiciones de los tokens
├── Analizador.java # Interfaz gráfica en Swing

### 📥 Requisitos previos:

- Java SE 17+  
- JFlex (versión 1.9 o superior)
