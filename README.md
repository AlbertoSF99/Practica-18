# Práctica 18 - Uso del Machine Learning

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 3 - Sesión 8

En esta práctica, se hizo uso de IA para predecir el total de rentas de bicicletas dependiendo de diversos factores, como fecha, temporada vacacional, día de la semana, clima, humedad, etc. Todo esto por medio del Machine Learning.

--------------------------------------------------------

#### Requerimientos
- Cuenta de Azure con suscripción.

--------------------------------------------------------

#### Pasos a seguir

1. Accedemos al siguiente link: [https://ml.azure.com/home](https://ml.azure.com/home) y le damos en ‘Create workspace’, rellenamos los datos que nos pide para crear el espacio de trabajo y le damos en ‘Create’.

![P18I1](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2001.PNG)

2. Entramos al workspace creado, y vamos a la pestaña de ‘Proceso’, después a ‘Instancias de procesos’ y le damos en ‘Nuevo’ para crear una nueva instancia y llenamos los datos necesarios para su creación (esta instancia es en realidad una VM) y escogemos también el tamaño de la máquina virtual (se recomienda el uso de D11_v2) y le damos en ‘Crear’.

![P18I2](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2002.PNG)

![P18I3](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2003.PNG)

3. Ahora nos vamos al apartado de datos, le damos en ‘Crear’ y ‘De archivos web’ y pegamos en el apartado que dice link el siguiente: [https://aka.ms/bike-rentals](https://aka.ms/bike-rentals) y de nombre le ponemos “Renta de bicis”, como tipo de conjunto de datos ponemos ‘Tabular’ y le damos en siguiente. Después, ponemos en encabezados la opción de ‘Solo el primer archivo tiene encabezados’ y en ‘Delimitador’ elegimos ‘Coma’ y le damos en siguiente. Finalmente, le damos en ‘Crear’.

![P18I4](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2004.PNG)

![P18I5](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2005.PNG)

![P18I6](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2006.PNG)

4. Una vez habiendo terminado el proceso del paso anterior, vamos al apartado que dice ‘ML Automatizado’ y le damos en ‘Nuevo trabajo’ para después seleccionar la data correspondiente a la renta de bicis que acabamos de crear. Le damos en siguiente y en ‘Nombre del modelo’. Le damos un nombre al modelo y en ‘Columna de destino’ elegimos ‘rentals’. Abrimos en otra ventana la pestaña de ‘Proceso’ y en el apartado de ‘Clusters de proceso’ le damos en ‘Nuevo’ y seleccionamos el tamaño de la VM que permita y en siguiente podremos elegir el nombre y el número máximo de nodos, el cual en este caso será máximo de 2 nodos y le damos en ‘Crear’. Regresamos a la pestaña en la que estábamos y en ‘Seleccionar un tipo de proceso’ ponemos ‘Clúster de proceso’ y en ‘Seleccionar Clúster de proceso’ escogemos el clúster recién creado y le damos en ‘Siguiente’.

![P18I7](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2007.PNG)

![P18I8](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2008.PNG)

![P18I9](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2009.PNG)

![P18I10](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2010.PNG)

5. Estando en ‘Seleccionar la tarea y la configuración’ seleccionamos ‘Regresión’ y le damos en ‘Siguiente’. En la siguiente sección no modificamos nada, así que le damos en ‘Finalizar’. Esperamos un rato hasta que finalice la implementación en la cual obtendremos los resultados.

![P18I11](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2011.PNG)

![P18I12](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2012.PNG)

![P18I13](https://github.com/AlbertoSF99/Practica-18/blob/main/Images/Sesi%C3%B3n%207%20-%20P18%2013.PNG)
