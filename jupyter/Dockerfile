# Especificamos la imagen docker, en este caso la de jupyter
FROM jupyter/datascience-notebook

# Imprimimos la versión de Python
RUN python --version

# Indicamos las librerías adicionales que queremos instalar
RUN pip install -U plotly tqdm pyvis

# Activamos los widgets interactivos en jupyter
RUN jupyter nbextension enable --py widgetsnbextension

# Añadimos el volumen /notebooks y lo establecemos como directorio de trabajo
VOLUME /notebooks
WORKDIR /notebooks