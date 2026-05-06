#
# Actividad: Diseño de Base de Datos – Sistema de Biblioteca Digital (ReadFlow)

## Información general
- **Modalidad:** Individual  
- **Herramientas permitidas:** draw.io, drawsql, Programiz SQL Online Compiler, GitHub  

## Contexto
La empresa **ReadFlow** es una plataforma digital que permite gestionar **libros, usuarios, préstamos y reseñas**. Actualmente, la información se maneja de forma desorganizada, lo que genera problemas como:
- Dificultad para controlar préstamos
- Pérdida de información de usuarios
- Falta de historial
- Desconocimiento de la disponibilidad de libros

## Objetivo
Diseñar una base de datos completa que permita gestionar la información de la plataforma, pasando por:
- Modelo conceptual
- Modelo lógico
- Normalización hasta **Tercera Forma Normal (3FN)**
- Modelo físico
- Script SQL

## Requerimientos
1. **Libros:** título, ISBN único, año, género, estado y múltiples copias.  
2. **Usuarios:** nombre, email único, teléfono y fecha de registro.  
3. **Préstamos:** un usuario puede tener varios préstamos, con fechas de préstamo y devolución.  
4. **Reseñas:** calificación, comentario y fecha, asociadas a usuario y libro.  
5. **Categorías:** un libro puede pertenecer a varias categorías.  

## Restricciones
1. El **ISBN** debe ser único.  
2. El **email** del usuario debe ser único.  
3. Un libro no puede prestarse si no está disponible.  
4. Todo préstamo debe estar asociado a un usuario.  
5. Las reseñas deben estar asociadas a usuario y libro.  

## Actividades a desarrollar (entregables)
1. Modelo conceptual (diagrama E-R con entidades, atributos y relaciones).
2. Conversión del modelo conceptual al modelo lógico.
3. Normalización hasta 3FN.
4. Conversión del modelo lógico al modelo físico.
5. Construcción del script SQL.

## Imagenes

https://ibb.co/7xcVD4cG


https://ibb.co/ynm8wcXb# Actividad
