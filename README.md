## Proyectos INF-323

## 1 Requisitos

Para ejecutar los programas, puedes seguir una de las siguientes opciones:

### Opción 1: Usar Open Live Server

1. Instalar la extensión **Open Live Server** en **Visual Studio Code**.
2. Abrir el archivo HTML desde Visual Studio Code.
3. Ejecutar **Open Live Server** desde el menú contextual o la barra de estado.

### Opción 2: Usar un servidor web local

Instalar uno de los siguientes servidores web en tu máquina:
- **WampServer**
- **AppServ**
- **Apache**
- **XAMPP**

Configura el servidor web local para apuntar al directorio donde están tus archivos y accede desde el navegador.

```plaintext
http://localhost/nombre-del-proyecto
```

## 2. Descripción de Proyectos

### Proyecto 1: Creación de una Escena con Primitivas en 2D
Desarrollo de una escena interactiva utilizando primitivas geométricas básicas en 2D, como líneas y triángulos. Se exploran las capacidades de **WebGL 2.0** para manejar formas bidimensionales con colores y transformaciones básicas.

### Proyecto 2: Interacción en una Cuadrícula con Objetos en 2D
Implementación de un sistema interactivo en 2D con WebGL, donde al hacer clic en un objeto, este se mueve como una pieza de ajedrez en un tablero. El objetivo es recoger zanahorias distribuidas en el tablero, y el sistema maneja eventos de usuario para actualizar la posición del objeto y cambiar sus propiedades visuales, como el color, al interactuar con los elementos del entorno.

### Proyecto 3: Colisiones entre Objetos en 2D
se enfoca en detectar colisiones entre un círculo y un cuadrado en 2D. Utiliza una función que calcula la distancia entre el centro del círculo y el punto más cercano del cuadrado, considerando una colisión si la distancia es menor o igual al radio del círculo. Este sistema permite modificar las propiedades visuales de los objetos al detectar la colisión.

### Proyecto 4: Uso de Sprites en Escenas 2D
Integración de **sprites** (imágenes 2D) en una escena bidimensional utilizando **WebGL 2.0**. Los sprites se usan para representar elementos decorativos o interactivos dentro de un entorno 2D.

### Proyecto 5: Lectura de Modelos 3D en Formato JSON
Creación de un lector de archivos 3D en formato **JSON** para cargar y renderizar modelos tridimensionales. Los datos incluyen geometrías y colores.

### Proyecto 6: Lectura de Modelos 3D en Formato OBJ
Implementación de un sistema que permite importar modelos tridimensionales en formato **OBJ**. Se utilizan las capacidades avanzadas de **WebGL 2.0** para renderizar geometrías complejas con eficiencia, incluyendo materiales y texturas asociados.


