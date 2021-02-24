# Herramientas de visualización de comunidades

Este proyecto utiliza un contenedor Docker para ejecutar diferentes notebooks de jupyter que contienen herramientas interactivas para la visualizción de comunidades.

## Requisitos
Para poder ejecutarlo es necesario tener instalado Docker en el equipo. Las instrucciones de instalación se pueden revisar en la página oficial de [Docker](https://www.docker.com/).

## Instalación

1. Descargar el código de este proyecto y descomprimirlo.
2. Abrir la terminal en la carpeta donde hemos descomprimido el proyecto.
3. Ejecutar la instrucción `docker-compose up` en la terminal.
4. Esperar a que Docker termine de levantar el contenedor, puede tardar unos minutos.
5. Copiar de la terminal la URL que nos proporciona Jupyter para conectarnos y pegarla en un navegador.

## Contenido
El contenido de este proyecto es el siguiente:
- `/data`: Carpeta donde se encuentran los datos de las comunidades. Actualmente, tiene los datos de interacción de usuarios con obras del Museo del Prado.
- `/notebooks`: Directorio principal donde se encuentran los notebooks interactivos. Actualmente hay dos notebooks: uno para visualizar el grafo bipartito que relaciona usuario y obras artísticas; y otro para visualizar las relaciones entre cuadros o usuarios.
- `/jupyter/Dockerfile`: fichero de configuración del contenedor.
- `docker-compose.yaml`: fichero para componer la estructura del contenedor.

## Visualizaciones

## Grafo bipartito

## Grafos usuarios/cuadros