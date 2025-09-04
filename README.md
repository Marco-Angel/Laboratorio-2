# 🤖 Laboratorio con 2-Conociendo a Pepper

En este laboratorio se investigaron las librerías principales utilizadas en el desarrollo para Pepper, se exploró el uso de la herramienta **Choregraphe** para la creación de una coreografía sencilla y se probó la conexión al robot mediante **SSH** para ejecutar un script desde la terminal. Finalmente, se compararon ambas formas de trabajo.

---

## 📚 Librerías utilizadas en Pepper

- **qi**: Es la librería base del SDK de Pepper. Permite establecer sesiones con el robot y acceder a todos sus servicios.  
- **argparse**: Se utiliza para manejar parámetros y argumentos desde la línea de comandos, lo que hace más flexible la ejecución de scripts.  
- **sys**: Ofrece utilidades relacionadas con el intérprete de Python, como la finalización del programa en caso de errores.  
- **os**: Permite trabajar con el sistema operativo, gestionar rutas, archivos y procesos.  
- **almath**: Biblioteca matemática propia de SoftBank, orientada a cálculos de movimiento y posiciones de Pepper.  
- **math**: Proporciona funciones matemáticas estándar como trigonometría, potencias y redondeos.  
- **motion**: Controla los movimientos del robot, incluyendo posturas, articulaciones y desplazamientos.  
- **httplib**: Permite comunicación por HTTP, útil para servicios o integración con APIs.  
- **json**: Facilita la lectura y escritura de datos en formato JSON, muy usado en configuraciones y comunicación con servicios.  

---

## 🛠️ Uso de Choregraphe

Choregraphe es la herramienta oficial de SoftBank para programar a Pepper de manera gráfica.  
- Funciona a través de bloques visuales que representan movimientos, sonidos, diálogos y acciones del robot.  
- Estos bloques pueden encadenarse para formar una **coreografía** sin necesidad de programar directamente en código.  
- El usuario puede conectarse al robot, probar la secuencia y ajustarla en tiempo real.  
- Está pensado para usuarios con poca experiencia en programación, ya que ofrece una interfaz intuitiva y visual.  

---

## 🖥️ Uso de SSH en Pepper

Otra forma de trabajar con Pepper es conectándose directamente a su sistema mediante **SSH**:  
- Se accede desde la terminal del computador, ingresando al robot con el usuario por defecto.  
- Una vez dentro, es posible crear archivos en Python, editarlos y ejecutarlos directamente en el robot.  
- Esto da acceso completo a las librerías mencionadas anteriormente y permite crear secuencias de movimientos personalizadas.  
- SSH otorga mayor control y flexibilidad, pero requiere conocimientos en programación.  

---

## 🔍 Comparación: Choregraphe vs Terminal con SSH

- **Choregraphe**:  
  - ✅ Visual, sencillo y accesible.  
  - ✅ Ideal para usuarios principiantes.  
  - ❌ Menos flexible para personalizar comportamientos complejos.  

- **SSH con Python**:  
  - ✅ Permite un control total del robot.  
  - ✅ Flexibilidad para programar cualquier secuencia o integración avanzada.  
  - ❌ Requiere experiencia en programación y mayor conocimiento técnico.  

---

## 📌 Conclusión

El laboratorio permitió comprender cómo diferentes herramientas ofrecen alternativas complementarias para interactuar con Pepper:  
- **Choregraphe** simplifica el diseño de coreografías básicas y facilita la interacción inicial.  
- **SSH con Python** habilita un nivel de control más profundo y profesional para personalizar movimientos y comportamientos.  
- Las librerías investigadas forman la base para desarrollar tanto desde el entorno gráfico como desde la terminal.  

---
