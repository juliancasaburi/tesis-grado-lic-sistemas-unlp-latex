# Tesina de Licenciatura en Sistemas

# Licencia
[![CC BY 4.0][cc-by-shield]][cc-by]

Este proyecto se encuentra licenciado bajo una
[Creative Commons Attribution 4.0 International License][cc-by].

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Generación del PDF de salida

### Opción 1: Utilizando imagen de Docker creada para este proyecto

1. Asegúrate de estar en el directorio raíz del proyecto (donde se encuentra el archivo main.tex).

2. Ejecutar el siguiente comando:

```console
$ docker run --rm -v "$(pwd):/latex" -i juliancasaburi/latex-tesina
```

Al finalizar la ejecución, se habrá creado el archivo main.pdf en el directorio principal del proyecto.

### Opción 2: Usar Overleaf localmente
Otra alternativa es ejecutar Overleaf en tu entorno local. Para hacerlo, puedes seguir los siguientes pasos:

1. Instala Overleaf Community Edition siguiendo las instrucciones de su [repositorio oficial](https://github.com/overleaf/overleaf).

2. Una vez configurado, podrás acceder al proyecto desde el navegador y compilar el PDF de manera interactiva, similar a la versión en línea de Overleaf.

Esta opción tiene la ventaja de poseer una interfaz visual para editar y compilar el documento.