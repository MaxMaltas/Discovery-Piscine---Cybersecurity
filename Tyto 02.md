---
title: Tyto 02

---

# Tyto 02

## Información General
- **Categoría:** OSINT
- **Autor:** @alrodri2
- **Plataforma:** Piscine Discovery de Ciberseguridad
 - **Fecha:** 27/01/25

---

## Descripción del Reto
*Este proyecto se pone un poco más interesante... Tendrás que encontrar
dónde se ha tomado una fotografía, pero antes tienes que localizar la fotografía, y quizá
Bluesky no sea la red social ideal para imágenes..*

La investigación casi ha finalizado, pero toasdavía necesitamos algo más: la localización
del usuario. ¿Dónde está escondido? Lamentablemente no podemos encotrarlo por ningún
lado... ¿Podrás hacerlo tú?

---

## Análisis Inicial
- **Archivos proporcionados:** subject.txt

---

## Proceso de Solución
### Paso 1: Buscar otros perfiles de Liam 
Para esta parte seguimos recopilando informacion, nos dan una pista muy grande cuando en la info incial nos dicen
*"quizá Bluesky no sea la red social ideal para imágenes..."*. Esto nos hace pensar en una app que esta pensada para colgar nuestras fotos

![Screenshot from 2025-01-30 16-00-11](https://hackmd.io/_uploads/S18z4zFdJe.png)


### Paso 2: Buscar informacion sobre la publicacion
Liam tiene una sola publicacion con una foto de ina iglesia y un comentario donde dice que es el mejor sitio para vivir.

![Screenshot from 2025-01-30 16-14-04](https://hackmd.io/_uploads/BJIuwMtd1l.png)

---

### Paso 2: Localizacion de la iglesia
Con google lens podemos identificar la iglesia, exactamente es la Iglesia de Sant Bartolome de Argañín.

![Screenshot from 2025-01-30 16-27-22](https://hackmd.io/_uploads/H15wcMtuJl.png)


---

## Solución Final

```plaintext
Argañín
```

![Screenshot from 2025-01-30 16-30-44](https://hackmd.io/_uploads/SkABjGtdkx.png)