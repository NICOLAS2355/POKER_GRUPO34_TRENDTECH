
# 09 · Gestión de riesgos

En este documento identificamos y valoramos los riesgos de implementar en Reserva El Páramo - Turismos Ambientales la maqueta impresa en 3D del páramo con etiquetas descriptivas, que el guía usará como apoyo visual y táctil durante la práctica ambiental de las universidades. La solución maneja pocos datos: los modelos 3D, el contenido de las etiquetas y los datos mínimos de contacto del grupo universitario que el coordinador ya recibe al agendar la visita. La usará a diario el guía del páramo. Por decisión del equipo, trabajamos solo con herramientas gratuitas.

Valoramos cada riesgo con la fórmula **Nivel = Probabilidad (1-5) × Impacto (1-5)**: 1-4 bajo, 5-9 medio, 10-16 alto y 20-25 crítico.

## Matriz de riesgos

| ID | Riesgo | Categoría | P | I | Nivel | Tratamiento | Acción | Responsable | Fecha |
|---|---|---|---|---|---|---|---|---|---|
| R1 | Piezas 3D frágiles o con fallas de impresión | Tecnológico | 4 | 3 | 12 (Alto) | Mitigar | Imprimir con mayor grosor de pared y piezas de repuesto, y probar la resistencia manipulando la maqueta antes de la práctica de prueba. | PR | 6 de noviembre |
| R2 | Pérdida de archivos del proyecto | Datos y ciberseguridad | 2 | 2 | 4 (Bajo) | Mitigar | Guardar los modelos 3D y los textos de las etiquetas en el repositorio de GitHub y en una copia en almacenamiento gratuito, con acceso limitado al equipo. No subir datos de contacto del grupo. | LP | 14 de noviembre |
| R3 | El guía no usa la maqueta en el recorrido | Personas y adopción | 3 | 5 | 15 (Alto) | Mitigar | Hacer una sesión corta de entrenamiento con el guía y entregarle una guía de una página con el orden sugerido para señalar las piezas. Recoger su opinión tras la práctica de prueba. | UX | 10 de noviembre |
| R4 | Costos de material superan lo gratuito | Financiero | 3 | 3 | 9 (Medio) | Mitigar | Usar solo software gratuito (diseño y laminado), imprimir únicamente las piezas esenciales de la v0.1 y reutilizar material de pruebas previas. | AP | 12 de noviembre |
| R5 | Datos del grupo sin autorización (Ley 1581) | Legal | 3 | 4 | 12 (Alto) | Evitar | No recolectar datos personales de estudiantes (nombres, fotos o contactos) para la prueba. Los datos de contacto de la solicitud de visita los maneja solo el coordinador, con autorización y aviso de privacidad conforme a la Ley 1581 de 2012. | LP | 7 de noviembre |
| R6 | Etiquetas erróneas o maqueta no disponible | Operativo | 2 | 2 | 4 (Bajo) | Aceptar | Revisar el contenido de las etiquetas con el coordinador antes de imprimirlas y dejar la maqueta guardada en un lugar fijo, definido con el guía. | PR | 14 de noviembre |

## Riesgos altos y críticos: plan de respuesta

No identificamos riesgos críticos. Los tres riesgos altos son R3, R1 y R5.

### R3 · El guía no usa la maqueta en el recorrido (nivel 15)
- **Por qué preocupa:** la hipótesis del prototipo depende de que el grupo vea y toque la maqueta mientras el guía explica. Si no se usa, la solución no cambia el proceso.
- **Plan:** entrenamos al guía en una sesión corta y le entregamos una guía de una página con el orden de explicación. Durante la práctica de prueba observamos si usa la maqueta y le preguntamos qué ajustaría.
- **Responsable y fecha:** UX, 10 de noviembre.
- **Señal de alerta:** el guía explica sin señalar las piezas o el grupo no las toca.

### R1 · Piezas 3D frágiles o con fallas de impresión (nivel 12)
- **Por qué preocupa:** la maqueta será manipulada por varias personas y puede usarse en un entorno húmedo, por lo que las piezas pequeñas pueden romperse o despegarse.
- **Plan:** aumentamos el grosor de las piezas delgadas, imprimimos repuestos de las piezas más expuestas y probamos la manipulación antes de la práctica de prueba.
- **Responsable y fecha:** PR, 6 de noviembre.
- **Señal de alerta:** una pieza se rompe o se despega durante las pruebas internas.

### R5 · Datos del grupo sin autorización (Ley 1581) (nivel 12)
- **Por qué preocupa:** la Ley 1581 de 2012 exige autorización previa, informada y con finalidad clara para tratar datos personales. Una práctica con estudiantes puede llevarnos a recolectarlos sin necesidad.
- **Plan:** evitamos el riesgo recolectando solo lo indispensable. En la prueba no pedimos nombres ni tomamos fotos identificables sin permiso. El coordinador mantiene los datos de contacto de la solicitud de visita bajo su custodia, con aviso de privacidad y autorización.
- **Responsable y fecha:** LP, 7 de noviembre.
- **Señal de alerta:** surge la necesidad de pedir datos o imágenes personales que no estaban previstos.

![Mapa de calor de riesgos](../assets/matriz-riesgos.png)

### Cómo leer el mapa de calor

Cada riesgo aparece en la casilla donde se cruzan qué tan probable es que ocurra (de abajo hacia arriba) y cuánto daño haría si ocurre (de izquierda a derecha). El color va del verde, que es tranquilo, al rojo, que es urgente, así que lo más preocupante queda arriba y a la derecha. En nuestro proyecto, lo más alto y a la derecha es «El guía no usa la maqueta en el recorrido»: si el guía no la usa, la solución no cambia nada en la práctica de la universidad. Cerca están «Piezas 3D frágiles o con fallas de impresión», porque la maqueta se toca y se mueve mucho, y «Datos del grupo sin autorización (Ley 1581)», porque trabajamos con estudiantes y debemos cuidar su información. Por eso lo primero que haremos es entrenar al guía, reforzar las piezas y definir qué datos no vamos a recolectar. «Costos de material superan lo gratuito» queda en zona media y lo seguimos con un control sencillo de materiales. «Pérdida de archivos del proyecto» y «Etiquetas erróneas o maqueta no disponible» están en verde, porque son poco probables y fáciles de corregir, y basta con vigilarlos.

## Conclusión

Los riesgos más importantes de la maqueta 3D no son técnicos, sino de uso por parte del guía, de resistencia de las piezas y de manejo de datos conforme a la Ley 1581 de 2012.
Con acciones de bajo costo y herramientas gratuitas, y con todas las fechas antes del 18 de noviembre, dejamos los riesgos controlados para la práctica de prueba.
