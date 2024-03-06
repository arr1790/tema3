# tema3
Apuntes teoricos del tema 3
# DISEÑO Y REALIZACION DE PRUEBAS


[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

ANOTACIONES QUE VAMOS HABLAR:
- Identificar los diferentes tipos de pruebas.
- Definir casos de prueba.
- Efectuar pruebas unitarias de clases y funciones.
- Efectuar pruebas de integración, de sistema y de aceptación.
- Realizar medidas de calidad sobre el software desarrollado.



## PRUEBAS

* PRUEBAS DINÁMICAS:
La prueba dinámica se centra en ejecutar el software y observar su comportamiento real durante la ejecución. Implica probar las funciones, la interoperabilidad, el rendimiento y la respuesta del sistema en situaciones diversas. El objetivo es validar el funcionamiento correcto del software en un entorno de ejecución real.

* PRUEBAS ESTATICAS:
La prueba estática se realiza sin ejecutar el programa. Consiste en revisar y analizar el código fuente, documentos y otros artefactos relacionados con el software para identificar posibles errores, defectos o mejoras. 

Y tiene una estrategia llamada cajas.
-Pruebas de Caja Negra:
Objetivo: Evaluar la funcionalidad del software sin conocer su implementación interna.
Enfoque: Se centra en las entradas y salidas del sistema.
Tipos: Pruebas funcionales, de integración, de sistema.

-Pruebas de Caja blanca:
Objetivo: Evaluar la estructura interna del código y la lógica.
Enfoque: Se analiza el código fuente y se prueba la lógica interna del programa.
Tipos: Pruebas unitarias, de integración, de camino, de flujo de datos.

![](https://media.telefonicatech.com/telefonicatech/uploads/2021/1/7145_pruebas.jpg)


## Tipos de prueba

Los tipos de prueba puede ser:
- Funcionales: Evalúan las funciones específicas del software, verificando que cumplan con los requisitos establecidos.
- No Funcionales: Evalúan aspectos no relacionados directamente con las funciones, como el rendimiento, la seguridad o la usabilidad del software. Se centran en cómo el sistema se comporta en diversas condiciones.

Las pruebas funcionales y no funcionales se clasifican por diferentes pruebas.
### funcionales tenemos:
1.**Pruebas Unitarias** :

Son como pruebas pequeñas para revisar que cada parte del código que escribes funcione bien.  Ejemplo:Es como probar cada pieza de Lego antes de armar el castillo.

2.**Pruebas de Regresión**:

Son pruebas se aseguran de que lo nuevo no rompa lo que ya estaba funcionando bien.  Ejemplo:Es como revisar que tus nuevas adiciones no estropeen el juego anterior.

3.**Pruebas de Integración**:

Después de asegurarte de que cada pedacito del código funciona bien por sí mismo, estas pruebas comprueban que todas esas piezas encajen juntas.Ejemplo: Es como ver si las piezas del Lego construyen el castillo correctamente.

4.**Pruebas de Sistema**:

 Aquí ya estás revisando cómo todo como se comporta en conjunto. Ejemplo:Es como jugar el videojuego completo para ver si todas las partes trabajan bien juntas.
 
5.**Pruebas de Alfa y Beta**:


La prueba Alfa es cuando los propios creadores del juego (tú y tus compañeros) lo prueban internamente. La Beta es cuando dejas que personas externas (amigos, familiares) lo prueben antes de lanzarlo oficialmente. Es como hacer pruebas secretas primero y luego abrirlo al público para ver cómo reaccionan.

6.**Prueba de Aceptación**:


El cliente debe validar si se ha realizado el trabajo bien como lo pedia.Ejemplo antes de lanzarlo el juego al público general lo deben probar, dejas que jugadores reales lo prueben para asegurarte de que sea divertido y funcional. Es como mostrar tu juego a tus amigos para ver si les gusta y funciona bien.

### NO Funcionales tenemos:
1.**Usabilidad**:

 Evalúa la facilidad de uso y la experiencia del usuario al interactuar con el sistema. Se centra en la amigabilidad y comprensión intuitiva.
 
2.**Rendimiento**:

 Examina la velocidad, eficiencia y capacidad del sistema bajo diferentes condiciones de carga para garantizar un funcionamiento óptimo.
 
3.**Estrés (Stress)**:

 Analiza cómo el sistema responde y se comporta bajo condiciones extremas o situaciones de carga máxima, verificando su robustez y resistencia.
 
4.**Seguridad**:

 Identifica y aborda posibles vulnerabilidades y riesgos de seguridad para proteger el sistema contra amenazas y accesos no autorizados.
 
5.**Compatibilidad**: 

Asegura que el sistema funcione correctamente en diferentes entornos, navegadores, dispositivos o sistemas operativos, garantizando una experiencia consistente.

6.**Portabilidad**:

Evalúa la capacidad del sistema para ser trasladado o adaptado fácilmente a diferentes entornos sin perder funcionalidad ni eficiencia.







### Mecanismos de prueba:
En los mecanismos de prueba se clasifican en:
```Manual
Pruebas Manuales: Ejecutadas por humanos sin automatización.
Pruebas Automatizadas: Uso de herramientas para ejecutar casos de prueba automáticamente.
```

Soporte del depurador:
* Puntos de Ruptura:

Descripción: Marcadores en el código donde la ejecución se detiene para permitir la inspección del estado del programa.
Uso: Ayudan a examinar y comprender el comportamiento del código en momentos específicos.
* Ejecución Paso a Paso:

Descripción: Permite ejecutar el programa línea por línea para observar su comportamiento detallado.
Uso: Facilita la identificación de errores y la comprensión del flujo de ejecución.
* Análisis de Variables:

Descripción: Examinar y evaluar los valores de las variables durante la ejecución del programa.
Uso: Ayuda a entender cómo cambian las variables y a detectar posibles problemas en el código.

#### FRAMEWORKS DE PRUEBAS(Xunit)
Framework es un marco de trabajo que esta compuesto:

```
- Un conjunto de las mejores practicas y suposiciones
- Herramientas comunes
- Biblioteca
- Permite unificar el proceso de desarrollo entre desarrolladores
```
Xunit: Existen varios Frameworks de desarrollo guiado por pruebas que han llegado como XUnit.
El diseño general de Frameworks XUnit depende de varios componentes:

**Accesorios de Prueba** :
Descripción: Herramientas y recursos que facilitan la creación y ejecución de pruebas.
Ejemplos: Conjuntos de datos de prueba, archivos de configuración, generadores de datos.

**Ejecución de Pruebas**:
Descripción: Proceso que realiza la ejecución de casos de prueba, captura resultados y proporciona informes.
Ejemplos: Motores de ejecución, integración continua, registros de resultados.


Aquí hay algunos frameworks de prueba populares para los lenguajes de programación:

```sh
Java:
JUnit: Para pruebas unitarias en Java.
TestNG: Alternativa a JUnit, con funcionalidades adicionales.
```
```sh
C++:
Google Test (gtest): Framework de pruebas unitarias para C++.
```
```sh
PHP:
PHPUnit: Utilizado para pruebas unitarias en PHP.
```
```sh
JavaScript:
Jest: Framework de prueba para JavaScript, especialmente diseñado para proyectos basados en React.
Mocha: Versátil framework para pruebas en JavaScript, compatible con navegadores y Node.js.
```
Estos frameworks son ampliamente utilizados en sus respectivos lenguajes y ofrecen características que facilitan la creación y ejecución de pruebas, lo que ayuda a mantener la calidad del software durante su desarrollo.

### JUnit5 ANOTACIONES
En JUnit 5, las anotaciones son marcadores especiales que se colocan sobre métodos o clases para indicar cómo deben ser tratadas las pruebas y cómo deben ejecutarse. Aquí tienes algunas de las anotaciones clave en JUnit 5:

**@Test**:
Indica que el método es una prueba.

**@BeforeEach y @AfterEach**:
Anotan métodos que se ejecutan antes y después de cada prueba, respectivamente.

**@BeforeAll y @AfterAll**:
Anotan métodos que se ejecutan antes y después de todas las pruebas en la clase, respectivamente.

**@Disabled**:
La anotación @Disabled en JUnit 5 se utiliza para desactivar temporalmente una prueba. Cuando aplicas esta anotación a un método de prueba, JUnit no ejecutará ese método durante la ejecución de las pruebas. Esto es útil cuando tienes pruebas que no son relevantes en un momento específico o están en proceso de desarrollo y no deben ejecutarse.
}

#### TDD (TEST DRIVEN DEVELOPMENT)
 Enfoque de desarrollo donde las pruebas automatizadas se escriben antes de escribir el código de producción.
Proceso:
* Red (Rojo): Escribir una prueba que falle, ya que el código aún no existe.
* Green (Verde): Escribir el código mínimo necesario para que la prueba pase.
* Refactor (Refactorizar): Mejorar el código manteniendo su funcionalidad.
* Ciclo: Repetir el proceso Red-Green-Refactor para cada nueva funcionalidad.
* Beneficios: Mejora la calidad del código, facilita la detección temprana de errores y promueve el diseño modular y mantenible

### INTEGRACIÓN
#### FORMAS DE INTEGRACIÓN
```sh
* Integración big bang:combinacion y analisís de grandes conjuntos de datos.
* Integración Descendente: Estrategia empresarial.Puede mejorar la eficiencia,la coordinación y la competividad.
* Integración Ascendente:Estrategia empresarial.Puede aumentar el control sobre la calidad , la disponibilidad y la eficiencia.
* Integración Continua (CI): Es una practica en el desarrollo de software que implica la interación automatica y frecuente de cambios de código fuente.
```
##### Servidores de Integración Continua 
CI: INTEGRACIÓN CONTINUA
CD:ENTREGA CONTINUA

*Jenkins*:
 Servidor de integración continua de código abierto y altamente extensible.
Características: Soporte para una amplia variedad de plugins, automatización de construcción y despliegue.

*Bamboo*:
Herramienta de integración continua desarrollada por Atlassian.
Características: Integración con otras herramientas Atlassian, automatización del ciclo de vida de desarrollo.

*Travis CI*:
Servicio de integración continua basado en la nube.
Características: Integración directa con repositorios de GitHub, pruebas automáticas en entornos virtuales.

*CircleCI*:
Servicio de integración continua basado en la nube.
Características: Configuración flexible mediante archivos YAML, ejecución de pruebas en contenedores Docker.

#### COBERTURA DE CÓDIGO
¿QUE ES LA COBERTURA DE CÓDIGO?
La cobertura de código es una métrica utilizada en el desarrollo de software que indica la proporción o el porcentaje de código fuente que ha sido ejecutado durante la ejecución de pruebas automatizadas. En otras palabras, mide cuánto del código fuente está siendo "cubierto" por las pruebas.
* Es aconsejable que sea lo mas cercano a 100%
* Si es del 100% entonces se ha ejecutado todo el código fuente durante las pruebas.
* Si es menor del 100% entonces existe codigo de fuente que no se ha ejecutado durante las pruebas
* Es posible realizar la cobertura tanto desde el IDE como desde un servicio web apropiado.

### CALIDAD
La calidad, se refiere a la medida en que un producto o servicio cumple con los requisitos, expectativas o estándares establecidos , en donde necesitamos hacer pruebas.
#### CALIDAD DEL PROCESO/PRODUCTO (QA/QC)
![ ](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjvlcSWLqB9w0K-sgHMgukbjqO7xTxpFhXH98tSpiGnRXuPVcEcylnU6EYJ3-KsDvD-O7SuTgR9eqTA6A1o6MsEnlWqjNUuVqlx38rNY8Lgwzck1UGuGTZQUD7IaDA-zSBFlgrfYrxGvEHJKjr53b3TDnliWa6f6bd4q1xL12cc5ELPdm_03EFx90Es/s320/qaqc.png)

**QA** es un conjunto de actividades para garantizar la calidad en los procesos mediante los cuales se desarrollan los productos.
**QC** es un conjunto de actividades para garantizar la calidad de los productos.Las actividades se centran en identificar defectos en los productos reales producidos.

```sh
QA = QUALITY ASSURANCE
QC = QUALITY CONTROL
```

#### FACTORES DE CALIDAD

![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhUCwaLOJzZEqzfV_i8P0IvSQ4-fYj_SZrlC5jzcvB3SAYOdNsTnYYJ3UXyfY2s8K4Xa6Q3p8Ozi34du_gHevreY4FstuZMZHTnSregPivqd_-_hnamhTw5I0_-XetWAetJjhZP80S9PGs/s1600/Nueva+imagen.bmp)

El modelo de calidad de McDall define 11 factores de calidad.
Estos factores se agrupan en 3 ambitos:
* OPERACIÓN DEL PRODUCTO
* REVISIÓN DEL PRODUCTO
* TRANSICIÓN DEL PRODUCTO

##### OPERACIÓN DEL PRODUCTO:
**Corrección**:
Capacidad para corregir defectos y errores.
Importancia: Garantiza que el producto funcione sin errores y cumpla con las expectativas del usuario.

**Fiabilidad**:
Capacidad del producto para realizar sus funciones de manera consistente y predecible durante un período prolongado.
Importancia: Contribuye a la confianza del usuario en la estabilidad y consistencia del producto.

**Eficiencia**:
Uso eficiente de los recursos del sistema, como tiempo, memoria y procesamiento.
Importancia: Asegura un rendimiento óptimo y minimiza el desperdicio de recursos.

**Seguridad**:
Protección contra amenazas internas y externas, garantizando la integridad y confidencialidad de los datos.
Importancia: Esencial para proteger al usuario y los datos contra posibles riesgos y vulnerabilidades.

**Facilidad de Uso**:
Grado en el cual el producto es fácil de entender, aprender y utilizar.
Importancia: Contribuye a una experiencia del usuario positiva, reduce errores y acelera la adopción del producto.

##### REVISIÓN DEL PRODUCTO
**Mantenibilidad**:
Capacidad del producto para ser modificado y mejorado de manera eficiente.
Importancia: Facilita la incorporación de cambios, correcciones y actualizaciones sin afectar negativamente la funcionalidad existente.

**Flexibilidad**:
Grado en el cual el producto puede adaptarse a cambios o evolucionar fácilmente.
Importancia: Permite ajustes y ampliaciones sin requerir cambios extensos o costosos en la estructura del software.

**Facilidad de Uso**:
Grado en el cual el producto es fácil de entender, aprender y utilizar.
Importancia: Contribuye a la satisfacción del usuario, minimiza errores y facilita la adopción del producto.

##### TRANSICIÓN DEL PRODUCTO

**Portabilidad**:
Facilidad con la que el producto puede ser transferido o adaptado a diferentes entornos, plataformas o sistemas operativos.
Importancia: Permite al producto ser utilizado en diversos contextos sin requerir modificaciones sustanciales.

**Reusabilidad**:
Capacidad de los componentes del producto para ser reutilizados en diferentes partes del sistema o en otros proyectos.
Importancia: Reduce el tiempo y los recursos necesarios para el desarrollo al aprovechar componentes ya existentes.

**Interoperatividad**:
Capacidad del producto para interactuar y operar eficientemente con otros sistemas, hardware o software.
Importancia: Garantiza la integración sin problemas con otros sistemas, mejorando la colaboración y la compatibilidad.


REALIZADO POR 
##### ANA RUANO





 


