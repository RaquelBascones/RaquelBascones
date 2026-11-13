# ¡Hola! Soy Raquel 👋

**Estudiante de Doble grado en Ingeniería Robótica e Inteligencia Artificial e Ingeniería Informática- UCJC**

Lo que más me interesa es aplicar la IA a problemas concretos. Me gusta trabajar con imágenes y datos, probar distintos modelos y entender por qué funcionan mejor en unos casos que en otros. En robótica, me interesa cómo un robot usa lo que capta con la cámara y el LiDAR para entender su entorno.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/raquel-bascones-gonz%C3%A1lez-506442308/)

## 🛠️ Tecnologías

**IA y datos**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-B54400?style=for-the-badge&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-C90000?style=for-the-badge&logo=keras&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-BD3725?style=for-the-badge&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-8D4A0A?style=for-the-badge&logo=scikitlearn&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-40317D?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-1F638B?style=for-the-badge&logo=numpy&logoColor=white)

**Robótica y simulación**  
![ROS](https://img.shields.io/badge/ROS-344B71?style=for-the-badge&logo=ros&logoColor=white) ![ROS 2](https://img.shields.io/badge/ROS%202-27344D?style=for-the-badge&logo=ros&logoColor=white) ![Gazebo](https://img.shields.io/badge/Gazebo-8E490F?style=for-the-badge&logo=gazebo&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-007B80?style=for-the-badge&logo=arduino&logoColor=white)

**Software y web**  
![Java](https://img.shields.io/badge/Java-A63220?style=for-the-badge) ![C](https://img.shields.io/badge/C-485E9C?style=for-the-badge&logo=c&logoColor=white) ![R](https://img.shields.io/badge/R-2167A8?style=for-the-badge&logo=r&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=24292f&labelColor=F7DF1E) ![HTML5](https://img.shields.io/badge/HTML5-B6381D?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-5848A4?style=for-the-badge&logo=css&logoColor=white)

**Bases de datos y herramientas**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-135B80?style=for-the-badge&logo=sqlite&logoColor=white) ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-006671?style=for-the-badge&logo=apacheairflow&logoColor=white) ![Git](https://img.shields.io/badge/Git-BF3526?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-215EB4?style=for-the-badge&logo=githubactions&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-AD3611?style=for-the-badge&logo=ubuntu&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-9E4300?style=for-the-badge&logo=jupyter&logoColor=white)

## 💻 Proyectos

### IA y robótica

- **Percepción con TurtleBot3** · *En curso*. En equipo, adaptamos Faster R-CNN con MobileNetV3 para detectar objetos en Gazebo y evaluamos las predicciones en vistas reservadas. El nodo de fusión en ROS Noetic proyecta los retornos del LiDAR sobre la imagen y solo asigna distancia cuando hay correspondencia geométrica.
- **Clasificación de imágenes con CNN**. Entrené y evalué redes convolucionales con TensorFlow y Keras. Antes de dividir el conjunto de datos, agrupé imágenes similares para reducir el riesgo de que ejemplos casi idénticos quedaran repartidos entre entrenamiento y evaluación.
- **[Web-Crawler · Extracción y clasificación de contenido web](https://github.com/RaquelBascones/Web-Crawler)**. En equipo, conectamos la descarga y extracción de texto con la generación de resúmenes, el almacenamiento en SQLite y un informe HTML. El clasificador combina TF-IDF y Naive Bayes multinomial para asignar una categoría a la página analizada.
- **Diagnóstico de registros ROS 2**. Amplié un analizador de rosbag2 con comprobaciones sobre medidas de distancia. Comparé registros de referencia y de fallo para localizar caídas de frecuencia y aumentos de latencia entre nodos. Automaticé las pruebas unitarias y de regresión con GitHub Actions.

### Desarrollo de software

- **[ShapeLang · Lenguaje de programación visual](https://github.com/RaquelBascones/ShapeLang)**. Las figuras geométricas representan números, operadores y estructuras de control. El intérprete convierte expresiones a notación polaca inversa con *shunting-yard* y las ejecuta en una máquina de pila. La interfaz web muestra cómo cambia la pila en cada paso, también dentro de bucles y condicionales.
- **[Entorno 3D generado por código en Godot](https://github.com/RaquelBascones/VR-environment-GeometricLanguage)**. Construí una escena interior en GDScript a partir de mallas primitivas. Programé una cámara orbital, combiné iluminación direccional, puntual y focal, y ajusté el marco de las texturas a sus proporciones originales.
- **[Escritorio interactivo en Java Swing](https://github.com/RaquelBascones/SSOO-Raquel)**. Desarrollé un escritorio con pantalla de inicio, reloj, terminal y acceso a aplicaciones. Incluí Sudoku, Wordle y un ajedrez que separa el tablero de las clases que representan cada tipo de pieza.

### Datos y sistemas

- **Acceso a datos y rendimiento en PostgreSQL**. Trabajé con transacciones y reutilización de conexiones desde Python con psycopg. Usé `COPY` para cargar datos y comparé planes de ejecución antes y después de añadir índices simples y compuestos.
- **Administración de Ubuntu Server**. Configuré una máquina virtual con Ubuntu Server y OpenSSH. En una práctica de equipo, configuré usuarios, grupos y listas de control de acceso (ACL), y comprobé con distintas cuentas que cada perfil tuviera los permisos previstos.
- **[MenuFiles · Gestión interactiva de archivos en Bash](https://github.com/RaquelBascones/MenuFiles)**. En equipo, creamos una utilidad de terminal que reúne operaciones de creación, movimiento y borrado de archivos y directorios. Organizamos cada operación en una función y usamos un bucle para volver al menú tras cada acción.
