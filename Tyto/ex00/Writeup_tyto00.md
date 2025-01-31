---
title: Tyto 00
---

# Tyto 00

## Información General
- **Categoría:** OSINT
- **Autor:** @alrodri2
- **Plataforma:** Piscine Discovery de Ciberseguridad
- **Fecha:** 27/01/25

---

## Descripción del Reto
*En este proyecto vas a tener el primer contacto con OSINT. El objetivo es
simple: encuentra una cuenta de una red social con la información que se facilita.*

El equipo de seguridad de 42 Barcelona ha descubierto una actividad sospechosa desde
uno de los ordenadores y ha decidido monitorizar todo el tráfico que se envía por la red
desde ese equipo. Se ha encontrado un paquete interesante

---

## Análisis Inicial
- **Archivos proporcionados:** subject.txt

---

## Proceso de Solución
### Paso 1: Analizar información 
En el subject nos muestran un screenshot de la herramienta que utilizan para interceptar información de sus conexiones, si analizamos en detalle podemos ver que hay un "user" y un "password". 

![[S1DfYzLO1x.png]]

### Paso 2: Buscar usuario en X
Al buscar el usuario nos aparece una cuenta creada con ese nombre.

![[S15CkQIOkg.png]]

![[BJ8ElXIuJx.png]]


---

## Solución Final

![[SyZdg7Id1g.png]]

```plaintext
https://x.com/ihatetetris42
```


