- [Reto 1 Impresión 3D: Guías y Exposición de Tipologías](#reto-1-impresión-3d-guías-y-exposición-de-tipologías)
  - [1) Problema (real) y propósito](#1-problema-real-y-propósito)
  - [2) Reglas de impresión (para todos los equipos)](#2-reglas-de-impresión-para-todos-los-equipos)
  - [3) Tipologías (asignación sin solape entre equipos)](#3-tipologías-asignación-sin-solape-entre-equipos)
  - [6) Entregables (estructura de repositorio)](#6-entregables-estructura-de-repositorio)
  - [Checklist rápido (para corrección)](#checklist-rápido-para-corrección)


# Reto 1 Impresión 3D: Guías y Exposición de Tipologías

**Duración:** 3 semanas · **2 h/semana**  
**Contexto:** 1 sola impresora 3D en el aula (aula activa, clases en marcha).  
**Formato de entrega:** Todo en **Markdown** dentro del repositorio de clase (fork → commits → **Pull Request**).

---

## 1) Problema (real) y propósito
Tenemos una impresora 3D infrautilizada. Falta **orientación práctica** para saber **qué se puede imprimir** y **cómo**. Solución: crear **guías claras** y una **exposición didáctica** con **modelos ejemplo** de varias **tipologías** (voladizos/puentes, tolerancias, engranajes, mallas/flex, uniones/snap-fit, etc.) que muestren posibilidades y límites.

**Objetivo del reto:**  
Cada equipo producirá **1 muestra de exposición** + **1 infografía tamaño A4** con información y detalles sobre la pieza imprimida.

---

## 2) Reglas de impresión (para todos los equipos)
- **Piezas pequeñas o medianas**.    
- **Operativa en aula:** solo uno del equipo, **rol Técnico/a** usa la impresora.
- **La impresora es compartida**: hay que coordinarse con otros equipos.
- **Aprobación previa**: cada equipo propone su pieza y recibe feedback por parte del profesor antes de imprimir.

---

## 3) Tipologías (asignación sin solape entre equipos)
- **Voladizos/puentes:** ángulos 30–60°, puentes 10–30 mm.  
- **Tolerancias y ajustes:** pegs/holes 0,2–0,6 mm; deslizantes vs. presión.  
- **Engranajes:** par pequeño de rectos (módulo bajo) para mostrar **backlash**.  
- **Mallas/Flex:** pared fina + patrón (gyroid/hex) que demuestre flexibilidad.  
- **Uniones/Snap-fit:** clip simple; rigidez vs. fragilidad.  
- **Texturas/Relieves:** altura de capa/boquilla y orientación de capa visibles.
- **Multicolor/Multimaterial:** si la impresora lo permite (filamento dual o similar).
- **Otra tipología propuesta por el equipo** (a validar con el profesor).

Referencias:

- [Ejemplos de modelos 3D](https://www.thingiverse.com/)
- [David Malawey](https://www.youtube.com/@davidmalawey)

> A nivel de clase, hay que cubrir cubrir **todas** las tipologías.


## 6) Entregables (estructura de repositorio)

![alt text](images/image.png)

En el repositorio de clase, en 3D → muestras,cada equipo crea una carpeta con el nombre del modelo de exposición que va a imprimir, y dentro de esa carpeta agregará tanto el fichero markdown como los archivos de diseño e impresión, así como la infografía final en PDF de tamaño A4.

A su vez, se ha de crear un enlace al fichero de la muestra del equipo en el fichero 3D/README.md, para que quede constancia de todas las piezas que se han impreso.[Ver ejemplo de prueba](muestras/catalogo.md)

Una vez que el equipo haya completado su reto, se hace un **Pull Request** al repositorio de clase para que el profesor pueda revisar y aprobar la entrega.

**Flujo Git:**
1) **Fork** del repo de clase.  
2) Crear una rama nueva.
3) Commits pequeños con mensajes claros.  
4) **Pull Request** al repo de clase.
5) Revisión y aprobación por parte del profesor.



## Checklist rápido (para corrección)

- [ ] **Infografía A4**: parámetros + QC + imagen/diagrama + legible A4 + enlace/QR? 
- [ ] **guia.md**: pasos + capturas + parámetros + tiempos + fixes + links a STL/GCODE  
- [ ] **Modelo**: STL + GCODE + fuente (CAD/SCAD)
- [ ] **Repo/PR**: estructura, enlaces, rama, commits, PR
