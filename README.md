[Proyecto_Karla_CastroM.pdf](https://github.com/KarlaCastroM/KarlaCastroM/files/6894550/Proyecto_Karla_CastroM.pdf)
[Desafio.xlsx](https://github.com/KarlaCastroM/KarlaCastroM/files/6894562/Desafio.xlsx)
[README.md](https://github.com/KarlaCastroM/KarlaCastroM/files/6894631/README.md)


---
output:
  pdf_document: default
  html_document: default
---

# Título del proyecto
Influencia de la interaccion salinidad y aumento ATPasa branquial, sobre iones plasmaticos (Cl-, Na+, K+) en smolt *Salmon salar*.

# Autor.
Karla Castro Monje

# Resumen del problema a resolver.
La esmoltificacion corresponde a un estado fisiologico en el cual el pez experimenta una serie de cambios que lo preparan para sobrevivir y crecer en agua salada. El desencadenamiento del proceso depende principalmente de las condiciones de temperatura y fotoperiodo a la cual esten expuesto los peces durante su fase de agua dulce.
Realizar una óptima esmoltificación es un tema que cobra cada día mayor relevancia entre los productores de salmónidos, ya que hay mayor conciencia acerca de la fuerte asociación entre enviar peces al mar dentro de la ventana de esmoltificación y el rendimiento de éstos durante los primeros meses en su nuevo ambiente. No obstante, la inexistencia de un indicador o índice confiable conlleva a que lotes de peces lleguen a centros de mar sin estar en óptimas condiciones fisiológicas (o con alta dispersión en la calidad de smolt), resultando en pérdida de crecimiento, menor eficiencia de alimentación y elevadas mortalidades por incapacidad osmorregulatoria asociada con una mayor susceptibilidad a enfermedades contagiosas.
Hoy en dia, los requerimientos productivos han evolucionado, siendo necesario la determinacion de la esmoltificacion en forma precisa de acuerdo a las necesidades productiva de cada empresa, de acuerdo a sus disponibilidades de recurso agua/espacio y a sus estrategias de produccion.
Por ello, en este estudio se quiere responder si en el proceso de esmoltificacion al aumentar la ATPasa branquial influye en conjunto con la salinidad en el aumento de los electrolitos plasmaticos (test de desafio) o simplemente con la salinidad de forma individual aumentan su cantidad en sangre, debido al estres del shock salino. 

# Resumen de los metodos estadisticos utilizados.
En este proyecto se utilizo un test de correlacion de Pearson, para evaluar si existe correlacion entre el peso-longitud de nuestros datos.
Se realizo una grafica de correlacion para saber que variables respuestas estaban correlacionadas.
Luego con un análisis de componentes principales de descarto las variables con fuerte correlación.
Tambien para evaluar la influencia de las Variables predictoras (interaccion ATPasa-Salinidad) sobre la variables respuesta (Na+, K+, Cl-), se realizo el modelo lineal con efectos fijos sobre las variables respuestas.
Se evaluaron los supuestos del modelo.
Tambien se realizó un modelo lineal para cada variable predictora sobre cada variable respuesta.
Se eliminaron los outliers para descartar errores y se volvio a modelar.




