# This is the README.md file for the **github-final-project**

A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest
Output
   simple interest = p*t*r/100
Para la Opción 1: Envío y Evaluación Calificada por IA:

Copia y guarda la URL pública del repositorio de GitHub de README.md en un archivo de texto, que contiene los detalles sobre un calculador de interés simple.
Para la Opción 2: Envío y Evaluación Calificada por Pares:

Guarda la URL del repositorio llamado github-final-project y la URL del archivo README.md en un archivo de texto para enviarlo más tarde.
Opcional - Puedes continuar actualizando el archivo README a medida que desarrollas tu proyecto. Puedes encontrar algunas ideas para contenido útil en README en los siguientes recursos:

Github README
Make a README
Awesome README
Tarea 2: Agregar un archivo de licencia
Como parte de la Tarea 1, elegiste una licencia al crear el repositorio.
Abre el archivo LICENSE y verifica que su contenido se refiera a Apache License 2.0.
Para la Opción 1: Envío y Evaluación Calificada por IA y Para la Opción 2: Envío y Evaluación Calificada por Pares

Copia y guarda la URL pública del repositorio de GitHub de Apache License 2.0 en un archivo de texto para enviar más tarde.
Tarea 3: Agregar un código de conducta
Un código de conducta ayuda a establecer las reglas básicas para el comportamiento de los participantes de tu proyecto. Define estándares sobre cómo participar en una comunidad.

GitHub proporciona plantillas para códigos de conducta comunes para ayudarte a agregar uno rápidamente a tu proyecto. Para agregar un código de conducta a tu proyecto, completa los siguientes pasos:

Agrega un nuevo archivo llamado CODE_OF_CONDUCT.md en la carpeta raíz del repositorio con la plantilla de "Contributor Covenant".

Ve a la página principal de tu repositorio y verifica si se ha creado el archivo.

Para Opción 1: Envío y Evaluación Calificados por IA y Para Opción 2: Envío y Evaluación Calificados por Pares

Copia y guarda la URL pública del repositorio de GitHub de CODE_OF_CONDUCT.md en un archivo de texto para enviarlo más tarde.
Tarea 4: Agregar directrices de contribución
Las directrices de contribución indican a los participantes del proyecto cómo contribuir al proyecto. Para agregar las directrices de contribución, completa los siguientes pasos:

Crea un nuevo archivo llamado CONTRIBUTING.md en el directorio raíz del repositorio con la siguiente información:

plaintext

Todas las contribuciones, informes de errores, correcciones de errores, mejoras en la documentación, mejoras y ideas son bienvenidas.
Opcionalmente, puedes revisar las siguientes guías para ejemplos de directrices de contribución y actualizar este archivo.

Contribuyendo a Legit Info, un proyecto de Call for Code for Racial Justice
Contribuyendo a OpenEEW
Contribuyendo a Atom
Cómo contribuir a Ruby on Rails
Confirma el archivo en la rama principal y verifica si está listado en la página de inicio del repositorio.
Para la Opción 1: Envío y Evaluación Calificada por IA y Para la Opción 2: Envío y Evaluación Calificada por Pares

Copia y guarda la URL pública del repositorio de GitHub de CONTRIBUTING.md en un archivo de texto para enviarlo más tarde.
Tarea 5: Hospedar el archivo de script
Crea un nuevo archivo llamado simple-interest.sh en el directorio raíz del repositorio.

Agrega el siguiente código en el nuevo archivo:

bash

   #!/bin/bash
   # Este script calcula el interés simple dado el capital,
   # la tasa anual de interés y el período de tiempo en años.

   # No usar esto en producción. Solo para fines de muestra.

   # Autor: Upkar Lidder (IBM)
   # Autores adicionales:
   # <tu nombre de usuario de GitHub>

   # Entrada:
   # p, cantidad principal
   # t, período de tiempo en años
   # r, tasa anual de interés

   # Salida:
   # interés simple = p*t*r

   echo "Ingresa el capital:"
   read p
   echo "Ingresa el período de tiempo en años:"
   read t
   echo "Ingresa la tasa de interés por año:"
   read r

   s=$(echo "scale=2; $p * $t * $r / 100" | bc)
   echo "El interés simple es: "
   echo $s
