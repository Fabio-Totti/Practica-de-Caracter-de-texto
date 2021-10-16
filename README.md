# Practica de Caracter de texto

# Este repositorio corresponde a una de las actividades complementarias con respecto a la unidad 2 en la asignatura de graficación.

El programa consiste en la creacion de un caracter de texto, especificamente su trazo, en un grafico producido por la herramienta GLUT de OpenGL, esto mediante el escaneo del caracter en una imagen o fotografia, tal y como lo hacen algunos software y sitios web para la creacion de fuentes de texto. Para desarrollar dicho proceso se emplearon diferentes clausulas, extenciones e implementaciones de librerias propiamente del lenguaje de programacion Java y las propias de OpenGL.

El programa se divide en tres clases principales:

-Clase "escanear", su funcion principal es importar la imagen y escanearla.

-Clase "Principal", su funcion es otorgar la ventana por la que visualizaremos la imagen importada y los botones por los cuales manejaremos el proceso de la aplicacion.

-Clase "Pantalla", su funcion principal es proporcionar el trazo que conforma el caracter de texto en la imagen mediante un plano grafico.

# Codigo fuente usando lenguaje de programacion java mediante el IDE de Netbeans Apache y OpenGL para la creación de los graficos. 
# Clase Escanear.

Se exportan las librerias correpondientes.

![1a](https://user-images.githubusercontent.com/72088585/137573324-75209d9b-e700-4947-891b-6b5e2844b55d.png)

Metodo ImageActual.

![1a](https://user-images.githubusercontent.com/72088585/137573383-20bcb53c-7953-44a9-8a15-202c39b152cc.png)

Metodo escaneador.

![1a](https://user-images.githubusercontent.com/72088585/137573462-c7fdc666-9537-43a0-a153-4a5192837cd2.png)

Metodo AlmacenA y AlmacenB.

![1a](https://user-images.githubusercontent.com/72088585/137573507-aa3c906f-5d16-44a2-9d5a-b125e99fe374.png)

# Clase Principal.

Se exportan las librerias correpondientes.

![1a](https://user-images.githubusercontent.com/72088585/137573645-9644e126-e0dc-4d23-90ed-9fa98e5d7590.png)

Metodo constructor.

![1a](https://user-images.githubusercontent.com/72088585/137573879-00cdd6e6-97a6-4146-8b72-a77a9e90f783.png)

Metodo de Componentes.

![1a](https://user-images.githubusercontent.com/72088585/137574012-f4951cfa-1d95-44bd-b866-af46351bf4d2.png)

Asignacion del evento a botones.

![1a](https://user-images.githubusercontent.com/72088585/137574084-883230b3-0afb-4e7a-a775-d667a8a72dd4.png)
![1a](https://user-images.githubusercontent.com/72088585/137574119-6fbb50e3-d126-4c97-a601-31b7e855ecf4.png)

Se genera el metodo main para ejecutar el programa.

![1a](https://user-images.githubusercontent.com/72088585/137574159-e2774765-b952-453f-aa7d-4cee7cd6050c.png)

# Clase Pantalla.

Se exportan las librerias correpondientes.

![1a](https://user-images.githubusercontent.com/72088585/137574195-8e38b511-bda3-4826-b52f-c6b61537482c.png)

Se generan las variables necesarias y el metodo main para ejecutar el programa.

![1a](https://user-images.githubusercontent.com/72088585/137574236-72bfa218-b65f-4af7-aed2-91715d35a536.png)

Metodo Constructor.

![1a](https://user-images.githubusercontent.com/72088585/137574454-cc0378ba-92bb-43eb-85d7-b50042a9d151.png)

Clase interna encargada de crear el grafico.

![1a](https://user-images.githubusercontent.com/72088585/137574547-b56c4f55-c69a-4e63-aeb7-c9291a857eb0.png)

# Grafica por pantalla.
# Aplicacion 1, letra A.

Usando la letra A, correpondiente a la fuente de texto creada durante la misma actividad, en una imagen obtenemos el siguiente trazo:

![A](https://user-images.githubusercontent.com/72088585/137574773-1a3e124b-8f2d-49fd-894d-7409f2838a84.gif)

# Aplicacion 2, letra B.

Usando la letra B, correpondiente a la fuente de texto creada durante la misma actividad, en una imagen obtenemos el siguiente trazo:

![B](https://user-images.githubusercontent.com/72088585/137574868-2dfeace7-5961-43e7-866a-be9a3cd95239.gif)

# Aplicacion 3, letra C.

Usando la letra C, correpondiente a la fuente de texto creada durante la misma actividad, en una imagen obtenemos el siguiente trazo:

![C](https://user-images.githubusercontent.com/72088585/137574951-d94297a0-c8f3-4599-bd7a-786344271a84.gif)

# Restricciones.

Debido a que esta aplicacion usa el color de los pixeles para obtener el trazo del caracter y para ello utiliza diferentes arreglos con limites asignados, es necesario que la imagen a ingresar para la capturacion del caracter no sobrepase el limite de tamaño asignado, en este caso 450x400 pixeles. Tambien es necesario que el caracter en la imagen sea obligatoriamente de color negro o muy cercanos al espectro de color negro, ya que de este se obtendra el trazo de dicho caracter; por otro lado, el fondo en el que se encuentre el caracter no debe de ser negro, por lo que la presencia de otro color no afectara la estructura del trazo como se observa en la aplicacion 3.
