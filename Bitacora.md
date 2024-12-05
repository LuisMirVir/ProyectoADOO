# Bitácora
Este documento tiene  la finalidad de funcionar como bitácora para ir señalando los cambios y avances realizados durante el desarrollo del proyecto, en ella, 
simplemente, se registrará la fecha y un resumen de lo que se ha creado, aunque no existan evidencias en el repositorio.

Es necesario tener en cuenta que el proyecto a realizar es únicamente para la parte del ADOO, por lo que solamente se van a tener evidencias del proceso y no como tal
programas o códigos para el proyecto y de esta forma poder comprobar la funcionalidad del proyecto, ya que únicamente se generaran artefactos no programables.

Nos enfocaremos en la parte de *inception* y *elaboración* del proyecto.

---
13-16 Septiembre 2024

 Se generó una propuesta de proyecto cuya descripción. 
 
---
19 Septiembre 2024

Se subió la propuesta de proyecto a la plataforma. Pendiente de aprobación por parte del docente.

---
22 Septiembre 2024

Se generó el repositorio en GitHub despues de haber estudiado y aprendido cosas referentes a GitHub.

Se subió la propuesta de proyecto, PENDIENTE DE APROBACIÓN al repositorio.

Se creó la bitácora para ir constatando los cambios y avances obtenidos durante el proyecto.

Se inicia la fase de inception, la cual durara un lapso de 5 semanas.

Diagrama de Fases para la planeación del proyecto 
[Plan de fase](https://docs.google.com/spreadsheets/d/1Xcqhgwcz1kIMeJJtNfw12pi4Ewt-2plnp11zW5H0CSo/edit?usp=sharing)


---
1 Octubre 2024

Inception del proyecto
[Inception del proyecto](https://docs.google.com/document/d/1XEQQfUm2zQGOCbRWLspc9hInDOv21CmQQpK9UiW-opE/edit?usp=sharing)

Se generó un inicio de catálogo de casos de uso

|       Id      |     Caso de uso       |
|:---------------:|:-----------------------:|
|  CU-01        |       CRUD Estudiante           |
|  CU-02        |       CRUD Bibliotecario        |
|  CU-03        |       CRUD Libro                |
| CU-04         | Prestar Libro     |
| CU-05         | Devolver Libro                  |
| CU-06        | Generar informe                 |

---
6 Octubre 2024

Se inicia el proceso de elaboración, de manera solo téorica.

Se inicia la primera iteración de la elaboración del software.

Artefactos obtenidos para el proceso de elaboración
[Hoja con los casos de uso](https://docs.google.com/document/d/1AWval-TtFqC5Wu3j3r3lXO2FV17zrWqh0oRDB_2BRrk/edit?usp=sharing)

---
14 Octubre 2024

Se revisó el documento con la sintaxis para el desarrollo adecuado de casos de uso

--- 
16 Octubre 2024

Con base en lo aprendido y modificado en el documento anterior, se procedió a realizar la actualización de los casos de uso ya escritos con anterioridad y 
modificarlos para que cumplieran con las nuevas pautas dispuestas.

---
23 Octubre 2024

Se obtuvo retroalimentación de la iteración, en ella pudimos observar que los objetivos planteados para esta primera iteración, se cumplieron de forma rápida sin convenientes, es por ello, que al utilizar una estructura similar para el CU-01 y CU-03, se optó por intentar cubrir estos dos casos de uso durante la próxima iteración, en lugar de solo el CU-01 que se tenía planeado, sin embargo, al ser tan parecidos en la estructura, se optó por esta medida.

---
28 Octubre 2024

Inicio de la Segunda iteración

Los artefactos obtenidos se van a ir guardando en el documento de Hoja con los casos de uso, desctríta en la iteración anterior

---
13 Noviembre 2024

Se terminaron de generar el código para ambos casos de usó cumpliendo de esta forma con los objetivos planteados para esta iteración.

Además se han realizado las sugerencias propuestas para mejorar la iteración 1, y se han desarrollado las pruebas pertinentes de test y de cohesión del sítema con lo desarrollado en la primera iteración.

El sistema será mostrado el 14 de noviembre a los bibliotecarios para que nos proporcione una retroalimentación del sistema y tomar en cuenta sus sugerencias para la siguiente iteración.

---
14 Noviembre 2024

Se realizó la presentación de los avances realizados durante la iteración al bibliotecario.
El bibliotecario al realizar las pruebas nos indicó que la funcionalidad que se le había dado se le hizo correcta y fácl de utilizar, sin embargo el bibliotecario nos indicó que nuestro sistema tenia un elemento faltante y que no hemos considerado que es el poder cambiar su password en caso de que se le haya olvidado.

Al verificar nos dimos cuenta de que era verdad y que es necesario agregar el reset password. con elaboración pendiente para las siguientes iteraciones.


- Planificación de iteración 3
  
Con base en la retroalimentación obtenida, se ajustan los requisitos. Se selecciona para Esta iteración la gestión de libros.

Se desglosa en un subconjunto de funcionalidades, como CU-04 y CU-05. Además de que se realiza el cambio de contraseña señalado en la iteración anterior.

Debido a que el tiempo de entrega se ha reducido, el tiempo entre iteraciones también se ha reducir a solo un lapso de 2 semanas.

- Desarrollo de iteración 3
  
Durante la primera mitad de semana, se desarrolla una descripción más detallada del caso de uso para el CU-04 y CU-05 y se realizan las correcciones de la retroalimentación de la iteración anterior, agregando la funcionalidad para recuperar o cambiar contraseña.

Después del modelado y descripción, se debería empezar a desarrollar el código, en el lapso de una semana, usando como guía la descripción de caso de uso obtenida en la primera mitad de semana. Además, se deben realizar pruebas de integración, para asegurarse de que funcione correctamente.

- Revisión y ajuste
  
Para los días restantes, se revisa si se cumplieron los objetivos planteados, para la iteración. Si no es posible, se reduce el alcance, moviendo algunas funcionalidades a la siguiente iteración.

Se realiza una demostración del sistema al bibliotecario para recibir retroalimentación y conocer si ya se cumplieron con las observaciones de la tercera iteración.

---
18 Noveimbre 2024

Se realizaron la descripción de los CU-04 Y CU-05, la descripción se encuentra en la hoja de casos de uso.

Artefactos obtenidos para el proceso de elaboración
[Hoja con los casos de uso](https://docs.google.com/document/d/1AWval-TtFqC5Wu3j3r3lXO2FV17zrWqh0oRDB_2BRrk/edit?usp=sharing)

Al realizar la descripción de los CU nos dimos cuenta de que era necesario agregar otro atributo al usuario estudiante con la finalidad de utilizarlo como puntaje para conocer si puede o no pedir préstamos de libros, por lo que se actualizara su diagrama añadiendo este nuevo atributo.

---
25 Noviembre 2024

Con base en el desarrollo de los casos de uso, en el siguiente documento se va a realizar la especificación suplementaria parcial de los otros requisitos.

[Hoja con especificaciones suplementaria](https://docs.google.com/document/d/1x2daMq7bGKFJHFM6ETxRxbyhaiAACglqJNOOdYd0FfE/edit?usp=sharing)

---
26 Noviembre 2024

Se realizó una segunda revisión de la visión que ya se había desarrollado, tomando en cuenta las indicaciones del libro. 

Para encontrar la primera versión de la visión ir a la siguiente liga
[Inception del proyecto](https://docs.google.com/document/d/1XEQQfUm2zQGOCbRWLspc9hInDOv21CmQQpK9UiW-opE/edit?usp=sharing)

La nueva versión de la visiín se va a desarrollar en la siguiente parte
[Hoja con especificaciones suplementaria](https://docs.google.com/document/d/1x2daMq7bGKFJHFM6ETxRxbyhaiAACglqJNOOdYd0FfE/edit?usp=sharing)

---
27 Noviembre 2024

Se realizó la descripción de el glosario y de las reglas de negocio, para encontrar esta información se debe ir a la siguiente liga

[Hoja con especificaciones suplementaria](https://docs.google.com/document/d/1x2daMq7bGKFJHFM6ETxRxbyhaiAACglqJNOOdYd0FfE/edit?usp=sharing)

---
1 Diciembre 2024

Como en un principio se utiliza el recurso de documentos de Google para realizar los artefactos de las entregas debido a que en él se puede visualizar de manera similar las versiones y modificaciones que se le han hecho a los documentos con base en su historial, se decidió usar este recurso, sin embargo, con la finalidad de que se muestre de mejor manera este propósito se decidió realizar una carpeta dentro del repositorio y agregar diferentes versiones de los documentos los cuales fueron evolucionando de manera iterativa. Si se desea ver este proceso se debe ver el historial de cambios de los documentos de Google Docs; sin embargo, si se desea visualizar este proceso de una manera más sencilla justamente se va a subir estos documentos con las diferentes versiones que se han realizado con el fin de que se muestre más fácilmente este proceso.

---
3 Diciembre 2024
Al ya no ajustar de tiempo para la planeación de la 4ta y última iteración se realizó únicamente la descripción del CU-06 y se anexó a los otros CU de la hoja
[Hoja con los casos de uso](https://docs.google.com/document/d/1AWval-TtFqC5Wu3j3r3lXO2FV17zrWqh0oRDB_2BRrk/edit?usp=sharing)

---
4 Diciembre 2024

Los días restantes van a servir para mejorar la redacción y ortografía del repositorio, además de unificar la sintaxis utilizada en los documentos.
