# **Capítulo V: Product Implementation, Validation & Deployment.
La implementación, validación y despliegue del producto son esenciales para asegurar que la visión del producto se convierta en una realidad funcional y accesible para nuestros usuarios. Estas etapas nos permiten transformar el diseño conceptual en una aplicación real, probada y lista para su uso, lo que nos ayuda a validar nuestras ideas, identificar posibles problemas y ofrecer una experiencia de usuario óptima.
## 5.1. Software Configuration Management.
La gestión de la configuración del software es crucial para nuestro trabajo, ya que nos permite mantener un control preciso sobre los elementos de nuestro proyecto, como el código fuente, los documentos de diseño y los activos digitales. Esto garantiza que todos los miembros del equipo estén trabajando con la misma versión de los archivos y facilita la colaboración entre desarrolladores, diseñadores y otros profesionales involucrados en el proyecto.
### 5.1.1. Software Development Environment Configuration.
- ### Project Management:
    * ### Whatsapp:
      Una plataforma de comunicación instantánea, compatible con sistemas operativos Android e iOS, desarrollada por Meta. También dispone de una versión en línea para su uso a través de navegadores web. <br>
      [Link De Descarga](https://www.whatsapp.com/download//?l=uz&lang=es)
      Link de Descarga: https://www.whatsapp.com/download//?l=uz&lang=es
    * ### Discord:
      Una herramienta de mensajería instantánea diseñada para organizar y facilitar reuniones internas semanales. <br>
      [Link De Descarga](https://discord.com/download)
      Link de Descarga: https://discord.com/download
    * ### Trello:
      Una aplicación de gestión de proyectos que facilita el seguimiento de las tareas individuales de cada miembro del equipo de manera sencilla. <br>
      [Link De Registro o Inicio De Sesión](https://trello.com/es)
      Link de Registro: https://trello.com/es
- ### Requirement Management:
    * ### Miro:
      Un sistema que ofrece una amplia gama de plantillas diseñadas para abordar diversos aspectos en la creación y gestión de proyectos. <br>
      [Link De Registro o Inicio De Sesión](https://miro.com/es/login/)
      Link de Registro: https://miro.com/es/login/
    * ### UXPressia:
      Es una herramienta en línea que simplifica el proceso de mapeo y comprensión de las necesidades del cliente en un proyecto determinado. <br>
      [Link De Registro o Inicio De Sesión](https://uxpressia.com)
      Link de Registro: https://uxpressia.com
    * ### Structurizr:
      Se trata de una suite de herramientas que posibilita la creación colaborativa de modelos C4 para representar de forma gráfica nuestros productos. <br>
      [Link De Registro o Inicio De Sesión](https://structurizr.com)
      Link de Registro: https://structurizr.com
    * ### Vertabelo:
      Una plataforma de colaboración que nos permite diseñar conjuntamente el diagrama de nuestra base de datos. <br>
      [Link De Registro o Inicio De Sesión](https://vertabelo.com)
      Link de Registro: https://vertabelo.com
- ###  Product UX/UI Design:
    * ### Figma:
      Una herramienta de colaboración que facilita el desarrollo conjunto de wireframes y mockups. <br>
      [Link De Registro,Inicio De Sesión y Descarga](https://www.figma.com/downloads/)
      Link de Registro: https://www.figma.com/downloads/
    * ### LucidChart:
      Una herramienta colaborativa que posibilita la creación conjunta de wireframes flow y mockups flow. <br>
      [Link De Registro o Inicio De Sesión ](https://www.lucidchart.com/pages/es)
      Link de Registro: https://www.lucidchart.com/pages/es
- ###  Software Development:
    * ### HTML5:
      Es un lenguaje de etiquetado utilizado para crear la estructura a páginas web. Lo utilizamos para incluir componentes como texto, imágenes, enlaces, botones y videos en nuestras páginas web. <br>
      [Informacion Relacionada](https://www.esic.edu/rethink/tecnologia/html5-que-es-caracteristicas-y-como-funciona-c#:~:text=El%20HTML5%20es%20un%20estándar,%2C%20estilo%20de%20letra%2C%20etc.)
      Información Relacionada: https://www.esic.edu/rethink/tecnologia/html5-que-es-caracteristicas-y-como-funciona-c#:~:text=El%20HTML5%20es%20un%20estándar,%2C%20estilo%20de%20letra%2C%20etc.
    * ### CSS:
      Un lenguaje de diseño gráfico utilizado para dar formato y estilo a la presentación de un documento escrito en HTML. <br>
      [Informacion Relacionada](https://developer.mozilla.org/es/docs/Web/CSS)
      Información Relacionada: https://developer.mozilla.org/es/docs/Web/CSS
    * ### JavaScript:
      Un lenguaje de programación orientado a objetos dinámico que utilizamos para implementar funcionalidades en un documento HTML. <br>
      [Informacion Relacionada]( https://developer.mozilla.org/es/docs/Web/JavaScript )
      Información Relacionada: https://developer.mozilla.org/es/docs/Web/JavaScript
    * ### WebStorm:
      Un entorno de desarrollo integrado (IDE) que emplearemos para trabajar con JavaScript. <br>
      [Link De Descarga]( https://www.jetbrains.com/es-es/webstorm/)
      Link de Descarga: https://www.jetbrains.com/es-es/webstorm/
- ###  Software Testing:
    * ### Lenguaje Gherkin:
      Se trata de un Lenguaje Específico de Dominio (DSL), diseñado específicamente para abordar un problema particular. Es un lenguaje comprensible para los desarrolladores, destinado a resolver necesidades concretas. <br>
- ###  Software Documentation:
    * ### Github:
      Se trata de una plataforma utilizada para el alojamiento de versiones del código fuente de un proyecto. Es una herramienta ampliamente popular en el trabajo colaborativo de programadores. <br>
      [Link De Descarga]( https://desktop.github.com)
      Link de Descarga: htts://desktop.github.com
      [Link De Registro o Inicio De Sesión](https://github.com/login)
      Link de Registro: https://github.com/login
- ###  Software Deployment:
    * ### Github Pages:
      Una plataforma que posibilita la realización de despliegues simples directamente desde un repositorio de GitHub. <br>

### 5.1.2. Source Code Management.
Landing Page Repository: [Landing Page Repository](https://github.com/SecurCar/LandingPage_SecurCar.git) https://github.com/SecurCar/LandingPage_SecurCar.git
- #### GitFlow Implementation:
Para implementar el flujo de trabajo Gitflow utilizando Git como nuestra herramienta de control de versiones, nos basamos en la entrada de blog "A successful Git branching model" de Vincent Driessen. Esta referencia nos permitió establecer las convenciones detalladas que serán aplicadas en nuestro proyecto
![Gitflow Vincent Driessen ](assets/Gitflow_graphic.png)

### **Master o Main branch**
La rama principal de desarrollo del proyecto es la Master branch. En esta rama reside el código que actualmente se encuentra en producción.
#### Notación: master o main

### **Develop branch**
La rama "Develop" albergará las más recientes actualizaciones y cambios agregados que serán incluidos en la próxima versión del proyecto. Esta rama sirve como un espacio para la integración y prueba continua de los cambios antes de ser fusionados con la rama principal "Master" para su despliegue en producción.
#### Notación: develop

### **Release branch**
La rama de lanzamiento (Release branch) facilitará la preparación de una nueva versión del producto. Esta rama permitirá la corrección de errores y permitirá que la rama Develop reciba más actualizaciones.
<br>Debe derivarse de la rama Develop.
<br>Debe fusionarse con la rama Develop y Master.
#### Notación: release


### **Feature branch**
Las ramas de características (Feature branches) serán empleadas para desarrollar nuevas funcionalidades o características del producto que se agregarán en la siguiente versión o en versiones futuras. Estas funcionalidades deberán fusionarse eventualmente con la rama Develop.
<br>Debe derivarse de la rama Develop.
<br>Debe fusionarse de vuelta a la rama Develop.
#### Notación: release


### **Hotfix branch**
La rama de corrección rápida (Hotfix branch) se empleará para resolver y actuar de manera inmediata ante posibles errores en la versión en producción del producto. La característica principal de esta rama es que permite preparar una solución rápida mientras el resto del equipo continúa trabajando en otras funcionalidades o mejoras.
<br>Debe derivarse de la rama Master
<br>Debe fusionarse con la rama Develop y Master
#### Notación: hotfix


### **Conventional Commits**
"Conventional Commits" es una convención para estructurar los mensajes de confirmación (commits) en un formato estándar y semántico. Este formato ayuda a comunicar claramente los cambios realizados en el código y facilita la generación de registros de cambios automáticos. Los "Conventional Commits" suelen seguir un formato que incluye un encabezado, un cuerpo opcional y un pie de página opcional, y se utilizan para describir de manera sucinta y clara los cambios realizados en el código, lo que facilita su seguimiento y comprensión por parte de los desarrolladores y otros miembros del equipo.
<br>
La estructura de un commit debe seguir las siguientes pautas:
~~~
git commit -m “<type>[optional scope]: <title>“ -m “<description”
~~~
**Tipos De Conventional Commits**
~~~
1. **feat**: Se usa para describir una nueva característica o funcionalidad añadida al código.
2. **fix**: Indica una corrección de errores o solución a un problema.
3. **docs**: Se emplea para cambios o mejoras en la documentación del código.
4. **style**: Describe cambios relacionados con el formato del código, como espacios en blanco, sangrías, etc., que no afectan su funcionalidad.
5. **refactor**: Se utiliza para modificaciones en el código que no corrigen errores ni añaden nuevas funcionalidades, sino que mejoran su estructura o legibilidad.
6. **test**: Indica la adición o modificación de pruebas unitarias o funcionales.
7. **chore**: Se usa para cambios en el proceso de construcción o tareas de mantenimiento que no están directamente relacionadas con el código en sí.
8. **perf**: Describe mejoras de rendimiento en el código.
~~~

### 5.1.3. Source Code Style Guide & Conventions.
Como norma general, se espera que todo el código desarrollado por los miembros del equipo esté completamente redactado en inglés.
- ### HTML
    - #### Use Lowercase Element Names:
      Es recomendable utilizar minúsculas o lowercase para los nombres de los elementos HTML.
        ~~~ 
      <body>
            <p>Esto es un párrafo</p>
      <body>
       ~~~
    - #### Close All HTML Elements:
      Es recomendable cerrar todos los elementos HTML correctamente.
        ~~~ 
      <body>
            <p>Esto es un párrafo</p>
            <p>Esto es otro párrafo</p>
      <body>
       ~~~
    - #### Use Lowercase Attribute Names:
      Es recomendable utilizar minúsculas para los nombres de los atributos HTML.
      ~~~ 
      <a href="https://www.w3schools.com/html/">Visit our HTMLtutorial</a>
       ~~~
    - #### Always Specify alt, width, and height for Images:
      Es recomendable seguir estas convenciones en caso de que la imagen no se pueda mostrar, lo que ayuda a mejorar la accesibilidad del contenido.
      ~~~ 
      <img src="html5.gif" alt="HTML5" 
      style="width:128px;height:128px">
      ~~~ 
    - #### Spaces and Equal Signs:
      Se recomienda no utilizar espacios en blanco entre las entidades para mejorar la legibilidad.
      ~~~ 
      <link rel="stylesheet" href="styles.css">
      ~~~ 
- ### CSS
    - #### ID and Class Naming
      Es recomendable utilizar nombres de clases y IDs significativos que expresen claramente el propósito del elemento.
      ~~~ 
      #gallery {}
      #login {}
      .video {}
       ~~~
    - #### ID and Class Name Style
      Se recomienda utilizar nombres cortos para nombrar IDs o clases, pero lo suficientemente descriptivos para entender su propósito.
      ~~~ 
      #nav {}
      .author {}
      ~~~
    - #### Shorthand Properties
      Se recomienda utilizar propiedades CSS de forma abreviada siempre que sea posible para hacer el código más eficiente y comprensible.
       ~~~ 
       border-top: 0;
       font: 100%/1.6 palatino, georgia, serif;
       padding: 0 1em 2em;
       ~~~ 
    - #### 0 and Units
      Es recomendable evitar especificar la unidad después del valor 0 en propiedades que lo permitan, ya que esto ayuda a reducir el tamaño del código y mejora su legibilidad.
       ~~~ 
       margin: 0;
       padding: 0;
       ~~~
    - #### Declaration Order
      Se recomienda ordenar las declaraciones en orden alfabético para facilitar el mantenimiento y la recordación del código.
      ~~~ 
       background: fuchsia;
       border: 1px solid;
       border-radius: 4px;
       color: black;
       text-align: center;
       text-indent: 2em;
      ~~~  
- ### JAVASCRIPT
    - #### Use expanded syntax
      Cada línea de JavaScript debería estar en una nueva línea, con la llave de apertura en la misma línea de su declaración y la llave de cierre en una nueva línea al final.
      ~~~ 
      function myFunc() {
       console.log('Hello!');
      };
      ~~~
    - #### Variable naming
      Para el nombre de las variables, se recomienda utilizar lowerCamelCase.
      ~~~ 
      let playerScore = 0;
      let speed = distance / time;
      ~~~  
    - #### Declaring variables
      Para la declaración de variables, es recomendable utilizar las palabras reservadas let y const en lugar de var.
      ~~~ 
      const myName = 'Chris';
      console.log(myName);
      let myAge = '40';
      myAge++;
      console.log('Happy birthday!');
      ~~~ 
    - #### Function naming
      Para el nombre de las funciones, se recomienda utilizar lowerCamelCase.
      ~~~ 
      function sayHello() {
      alert('Hello!');
      };
      ~~~
- ### Java
  - #### CamelCase Naming Convention
    Esta convención sugiere nombrar variables, métodos y clases utilizando CamelCase, donde cada palabra en el identificador comienza con una letra mayúscula, excepto la primera palabra.
    ~~~ 
    int miVariable;
    void miMetodoNombre() {
        // Cuerpo del método
    }
    class MiClase {
        // Miembros de la clase
    }
    ~~~
  - #### Constants Naming Convention
    Las constantes generalmente se nombran utilizando letras mayúsculas con guiones bajos para separar palabras y distinguirlas de las variables regulares.
    ~~~ 
    final int VALOR_MAXIMO = 100;
    ~~~
  - #### Comments Convention
    Los comentarios deben utilizarse para explicar la funcionalidad del código, especialmente en secciones complejas o no intuitivas, utilizando un lenguaje claro y conciso.
    ~~~ 
    // Este método calcula la suma de dos números
    int suma(int num1, int num2) {
        return num1 + num2;
    }
    ~~~ 
  - #### Method Naming Convention
    Los nombres de los métodos deben ser descriptivos y comenzar con un verbo en minúsculas, seguido de un sustantivo (o sustantivos) que describa la acción del método.
    ~~~ 
    void calcularSuma() {
        // Cuerpo del método
    }
    ~~~
  - #### Indentation Convention
    La indentación consistente mejora la legibilidad del código. Cada nivel de anidamiento de código debe ser indentado por un número fijo de espacios o tabulaciones.
    ~~~ 
    public class MiClase {
        public static void main(String[] args) {
            if (condicion) {
                // Bloque de código indentado
                System.out.println("¡Hola, Mundo!");
            }
       
        }
    }
    ~~~
   - ### TypeScript
    - #### CamelCase Naming Convention
      Esta convención sugiere nombrar variables, métodos y clases utilizando CamelCase, donde cada palabra en el identificador comienza con una letra mayúscula, excepto la primera palabra.
      ~~~ 
      let miVariable: number;
      function miFuncionNombre() {
          // Cuerpo de la función
      }
      class MiClase {
          // Miembros de la clase
      }
      ~~~
   - #### PascalCase Naming Convention
     PascalCase es similar a CamelCase, pero la primera letra de cada palabra en el identificador se capitaliza, incluida la primera palabra.
     ~~~ 
     let MiVariable: number;
     function MiFuncionNombre() {
         // Cuerpo de la función
     }
     class MiClase {
         // Miembros de la clase
     }
     ~~~
   - #### Uppercase Constants
     Las constantes se nombran en mayúsculas con guiones bajos para separar palabras.
     ~~~ 
     const VALOR_MAXIMO: number = 100;
     ~~~ 
   - #### Descriptive Comments
     Los comentarios deben explicar la funcionalidad del código de manera clara y concisa.
     ~~~ 
     // Esta función calcula la suma de dos números
     function sumar(num1: number, num2: number): number {
         return num1 + num2;
     }
     }
     ~~~
   - #### Indentation Convention
     Es importante mantener una indentación consistente para mejorar la legibilidad del código.
     ~~~ 
     class MiClase {
         metodo(): void {
             if (condicion) {
                 // Bloque de código indentado
                 console.log("Hola, Mundo!");
             }
      
         }
     }
     ~~~
- ### LENGUAJE GHERKIN
    - #### Descriptive and concise titles for scenarios
      Utilizar títulos descriptivos y concisos para los escenarios.
      ~~~ 
      Feature: Login
        Scenario: Successful login
          Given a user is on the login page     
          When they enter valid credentials     
          Then they should be logged in successfully      
      ~~~
    - #### Follow the Given-When-Then structure consistently.
      Seguir la estructura de Given-When-Then de manera consistente.
      ~~~ 
      Scenario: Adding items to the shopping cart
        Given the user is on the shopping page
        When they add an item to the cart
        Then the item should appear in the cart 
      ~~~
    - #### Focus on business-readable language
      Centrarse en un lenguaje legible para el negocio, evitando detalles técnicos de implementación.
      ~~~ 
      Scenario: Changing user settingst
        Given the user is logged in
        When they navigate to the settings page
        Then they should be able to update their profile
      ~~~
    - ####  Utilize Scenario Outline for scenarios with multiple similar cases.
      Utilizar Scenario Outline para escenarios con múltiples casos similares.
      ~~~ 
      Scenario Outline: Searching for products
        Given the user is on the search page
        When they search for "<product>"
        Then they should see search results for "<product>"
      
      Examples:
        | product  |
        | Laptop   |
        | Smartphone |
      ~~~
    - #### Add comments to provide additional context
      Agregar comentarios para proporcionar contexto adicional o explicaciones cuando sea necesario.
      ~~~ 
      # This scenario checks the functionality of the logout feature
      Scenario: User logout
        Given the user is logged in
        When they click on the logout button
        Then they should be redirected to the login page      
      ~~~
### 5.1.4. Software Deployment Configuration.
- Creacion Landing Page:<br>
1. Se crea un repositorio remoto en GitHub
   ![CreacionRepositorio](assets/Creacion_repo_OpenSource.png)
2. Agregar a participantes
   ![CreacionRepositorio](assets/Members.png)
3. Habilitmos Gitgub Pages en branch "master" y ruta "/(root)"
   ![CreacionRepositorio](assets/Github_pages.png)

## 5.2. Landing Page, Services & Applications Implementation.
La implementación de la página de inicio, los servicios y las aplicaciones es un paso fundamental en nuestro proceso de desarrollo. Nos permite materializar el diseño y la funcionalidad planificados, transformando los conceptos en productos tangibles y listos para su uso. Esta fase nos permite traducir las especificaciones y requisitos en código, desarrollando la estructura de la página, los servicios y las aplicaciones de acuerdo con las necesidades identificadas.
### 5.2.1. Sprint 1
El primer sprint es un hito importante en nuestro proceso de desarrollo ágil. Durante este período, nos enfocamos en la implementación de las características y funcionalidades prioritarias identificadas en la planificación inicial. Esto implica traducir los requisitos y especificaciones en código funcional, desarrollando las bases de nuestro producto de manera iterativa.
#### 5.2.1.1. Sprint Planning 1.
En este sección, están las reuniones que se realizaron para llevar a cabo la landing page.<br>

| Sprint # | Sprint #1 |
| -------- | --------|
| Sprint Planning Background |
| Date | 2024-04-07 |
| Time | 05:25 PM |
| Location | Discord (virtual) |
| Prepared by | Gallo Quintana, David Ivanoff |
| Attendes (to planning meeting) | Gallo Quintana, David Ivanoff / Mallma Quispe, Ruben / Paredes Zapata, Luiggi Gianfranco / Sanchez Zamora, Fabrizio Alessandro / Talizo Balbin, Joan Jefferson / Louis |
| Sprint Goal & User Stories |    |
| Sprint 1 Goal | Realizar la Landing Page |
| Sprint 1 Velocity | 20 |
| Sum of Story Points | 8 |

#### 5.2.1.2. Sprint Backlog 1.
| id   | Title                  | Id  | Title                                                    | Description                                                                                                   | Estimations(Hours) | Assigned To   | Status(To-do /InProcess/ToReview/Done) |
| ---- | ---------------------- | --- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ------------------ | ------------- | -------------------------------------- |
| US31 | Navegar a la Página de Inicio     | TS01 |Header and NavBar responsivos (Desarrollado en HTML, CSS y JS).          | Implementación del header y la barra de navegación, siguiendo los estándares “Responsive”  | 3                  | Luiggi  | Done                                   |
| US32 | Obtener mayor información acerca de los beneficios    | TS02 | Sección de Testimonios (Desarrollado en HTML, CSS y JS).       | Implementación de la sección de testimonios en la Landing Page, siguiendo los estándares “Responsive”  | 3                  | Balbín | Done                                   |
| US33 | Contacto con soporte           | TS03 | Sección del Footer (Desarrollado en HTML, CSS y JS).                              | Implementación del footer en la Landing Page, siguiendo los estándares “Responsive”.           | 2                  | David   | Done                                   |


#### 5.2.1.3. Development Evidence for Sprint Review.
| Repository   | Branch                                      | Commit Id | Commit Message                   | Commit Message Body | Commited on (Date) |
| ------------ | ------------------------------------------- | --------- | -------------------------------- | ------------------- | ------------------ |
| LandingPage_SecurCar  | main | d978b63    | feat: added HTMLParte  | Feat:….  | 10/04/2024         |
| LandingPage_SecurCar   | main | be2b1b4    | feat:added section offer and images      | Feat:…. | 09/04/2024         |
| LandingPage_SecurCar   | main | a46db65 | feat: added section mapas and images  |Feat:…. | 09/04/2024         |
| LandingPage_SecurCar   | main | f284b3d    | feature(LandingPage):Add SectionAboutUs   |Feat:….  | 10/04/2024         |
| LandingPage_SecurCar  | main  | 1096c95  | feat: added stylessx and contact section   |Feat:….   | 10/04/2024         |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.
En esta entrega, no se incluyeron los componentes relacionados con los servicios web, ya que en este caso solo se implemento la Landing Page.
#### 5.2.1.5. Execution Evidence for Sprint Review.
Se puede visualizar el video en el siguiente enlace: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e475_upc_edu_pe/EQ802LC1j8hDmhP_sOLedJYBdbplYqsSNMldJEnZQhtfvg?e=t0KGDa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
En esta entrega, nos enfocamos en Landing page, por lo que no fue necesario ningún servicio adicional.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
En este caso se uso GitHub Pages, para desplegar la Landing page, el cual nos sirvio para, a partir de un código en un repositorio poder desplegar la página. Enlace de la landing page: securcar.github.io/LandingPage_SecurCar/
#### 5.2.1.8. Team Collaboration Insights during Sprint.
Para llevar a cabo este proyecto se usaron distintas herramientas como Visual Studio Code, Rider, Webstorm; junto con Git. En este caso se dividio la landing page mostrada anteriormente en sectores, a partir de esto cada uno presentó su parte y luego un miembro realizó el styles para finalmente tener el resultado deseado.
![CommitsChanges](/feature/assets/commits.png)

### 5.2.2. Sprint 2
El primer sprint es un hito importante en nuestro proceso de desarrollo ágil. Durante este período, nos enfocamos en la implementación de las características y funcionalidades prioritarias identificadas en la planificación inicial. Esto implica traducir los requisitos y especificaciones en código funcional, desarrollando las bases de nuestro producto de manera iterativa.
#### 5.2.2.1. Sprint Planning 1.
En este sección, están las reuniones que se realizaron para llevar a cabo la landing page.<br>

<table>
        <tr>
            <td colspan="1">Sprint #</td>
            <td colspan="1">Sprint 2</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td>Date</td>
            <td>2024-04-29</td>
        </tr>
          <tr>
            <td>Time</td>
            <td>05:25 PM</td>
        </tr>
            <tr>
            <td>Location</td>
            <td>Discord (virtual)</td>
        </tr>
            <tr>
            <td>Prepared by</td>
            <td>Gallo Quintana, David Ivanoff</td>
        </tr>
            <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Gallo Quintana, David Ivanoff / Mallma Quispe, Ruben / Paredes Zapata, Luiggi Gianfranco / Sanchez Zamora, Fabrizio Alessandro / Talizo Balbin, Joan Jefferson / Louis</td>
        </tr>
            <tr>
            <td>Sprint 2 Review Summary</td>
            <td>El proceso del sprint 2 concluyó en términos de avances y mejoras de los productos y entregables dado junto con la colaboración general del equipo y la comunicación. Los logros alcanzados junto a la retroalimentación con la recopilación durante esta revisión proporcionan una buena y sólida base para la construcción y realización del siguiente sprint (3), además de reforzar el compromiso del equipo con la calidad y la entrega responsable.</td>
        </tr>
            <tr>
            <td>Sprint 2 Retrospective Summary</td>
            <td>Para la retrospectiva del Sprint 2 tuvimos que reflexionar sobre nuestro desempeño grupal como individual de cada integrante, además de identificar todas las secciones posibles donde podemos mejorar como también del uso de recomendaciones. Esto nos servira como una buena base para impulsar aun más la mejora continua y optimizar el trabajo del equipo en los próximos sprints durante el ciclo de vida del proyecto.</td>
        </tr>
            <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
              <tr>
            <td>Sprint 2 Goal</td>
            <td>Alcanzar una métrica de cumplimiento del 100%, lo que indicará que se ha logrado todos los objetivos del sprint 2 con todas las historias de usuario y otros materiales necesarios.</td>
        </tr>
              <tr>
            <td>Sprint 2 Velocity</td>
            <td>Con el equipo para este sprint 2 decidimos aceptar 8 Story Points</td>
        </tr>
              <tr>
            <td>Sum of Story Points</td>
            <td>La suma de los Story Points para los User Stories que se están incluyendo en este Sprint 2 es 47</td>
        </tr>
    </table>

#### 5.2.2.2. Sprint Backlog 2.
| id | Title | Id | Title | Description | Estimations | Assigned To | Status |
| - | - | - | - | - | - | - | - |
| US01 | Protección contra robos y alertas de seguridad | TS01 | Sección de ajustes de notificaciones sobre alertas en información del vehículo | Como joven conductor, quiero activar la función de seguridad en la aplicación para proteger mi automóvil contra robos y recibir alertas instantáneas en caso de actividad sospechosa. | 2 hora(s) y 30 minuto(s) | David | Done |
| US02 | Geolocalización y rastreo en tiempo real. | TS01 | Sección de nombre del vehículo con rastrear elemento en información del vehículo | Como joven conductor, quiero activar la función de seguridad en la aplicación para proteger mi automóvil contra robos y recibir alertas instantáneas en caso de actividad sospechosa. | 1 hora(s) y 0 minuto(s) | David | Done |
| US03 | Recomendaciones personalizadas de seguridad. | TS02 | Sección de recomendaciones de seguridad en mensajes | Como propietario de un automóvil, quiero recibir recomendaciones personalizadas sobre medidas de seguridad adicionales según las áreas de alto riesgo de robo en mi área. | 1 hora(s) y 0 minuto(s) | Rubén | Done |
| US05 | Compartir ubicación con contactos de confianza. | TS03 | Compartir la ubicación del vehículo dentro de la sección de compartir vehículo | Como conductor joven, quiero poder compartir mi ubicación en tiempo real con contactos de confianza a través de la aplicación para garantizar mi seguridad. | 1 hora(s) y 30 minuto(s) | David | Done |
| US10 | Recordatorios de límites de velocidad y normativas viales. | TS02 | Dentro de mensajes donde se muestra información importante | Como conductor joven, quiero recibir recordatorios de límites de velocidad y normativas viales en tiempo real para conducir de manera responsable. | 1 hora(s) y 0 minuto(s) | Rubén | InProcess |
| US13 | Gestión de perfiles de conductores múltiples. | TS04 | Sección de perfiles como cambio dentro del apartado pefil | Como conductor joven, quiero poder gestionar múltiples perfiles de conductores en la aplicación para compartir mi vehículo con otros conductores de confianza. | 1 hora(s) y 30 minuto(s) | Joan | Done |
| US19 | Programación de mantenimientos preventivos. | TS04 | Sección de  |Como conductor de flotas, quiero programar mantenimientos preventivos para los vehículos de la empresa en la aplicación para garantizar su buen estado y durabilidad | 2 hora(s) y 30 minutos(s) | Luois | ToDo |

#### 5.2.2.3. Development Evidence for Sprint Review.
| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on date |
| - | - | - | - | - | - |
| FrontEnd | main | 5f99030 | feat: added GPSinformation Component | En esta sección se añadió la información sobre el dispositivo GPS a la branch main | 30/04/2024 |
| FrontEnd | main | 46c79fd | feat: added vehicle information page | Se añadió la sección de información del vehículo a la rama principal | 29/04/2024 |
| FrontEnd | main | 414cecd | feat: added Initial section | Se añadió la sección de inicio a la branch main | 28/04/2024 |
| FrontEnd | main | 055dff0 | feat(login): added html, ts and css | Aquí se añadió la página de login (ingresar cuenta) de nuestra aplicación | 28/04/2024 |
| FrontEnd | main | e55e5c8 | feat: added Profile | Incluído la sección de perfil del conductor (usuario) | 30/04/2024 |
| FrontEnd | main | b2b31b5 | feat: added ratreo branch | Se añadió la sección de rastreo a la rama 'main' | 30/04/2024 |
| FrontEnd | main | 2bcd954 | feat: added register section branch | Creada la sección de registro de usuario a la rama principal | 26/04/2024 |
| FrontEnd | main | b795994 | feat: added Share ubicaction components | En esta sección se añadió el apartado de compartir ubicación a la rama principal | 29/04/2024 |
| FrontEnd | main | 46c79fd | feat: added vehicle information page | Se programó la parte de infomación del vehículo a la rama principal | 29/04/2024 |

#### 5.2.2.4. Execution Evidence for Sprint Review.
Se puede visualizar el video en el siguiente enlace: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e475_upc_edu_pe/EQ802LC1j8hDmhP_sOLedJYBdbplYqsSNMldJEnZQhtfvg?e=t0KGDa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
#### 5.2.2.5. Services Documentation Evidence for Sprint Review.
En esta entrega no usamos servicios externos por lo que no se usó ningún servicio adicional.
#### 5.2.2.6. Software Deployment Evidence for Sprint Review.
Usamos el entorno local para poder desarrollar primero la ejecución y el recorrido de la página para poder después llevarla a producción o a un entorno más complejo.
#### 5.2.2.7. Team Collaboration Insights during Sprint.
Para llevar a cabo este proyecto se usaron distintas herramientas como Visual Studio Code, Rider, Webstorm; junto con Git. En este caso se dividió el FrontEnd mostrada anteriormente en sectores, a partir de esto cada uno presentó su parte y luego un miembro realizó el styles para finalmente tener el resultado deseado.
![CommitsChanges](/feature/assets/comits-sprint2.png)

### 5.2.3 Sprint 3.
En esta sección se registra y explica el avance en términos de producto y trabajo colaborativo para el Sprint número 3. Todo el avance descriptivo se muestra aquí junto a su desarrollo, historial y avance en conjunto dado por cada intengrante del equipo de trabajo. Todas las especificaciones siguen desde el Product Backlog del Capitulo 3 de requerimientos.

#### 5.2.3.1 Sprint Planning 3.
En esta sección se explicaran los detalles presentados y analizados durante la reunión del Sprint Planning para el número 3. El objetivo principal de esta reunión es establecer un plan claro y realista para el sprint, identificando las tareas a realizar y comprometiéndose con un conjunto de entregables concretos que contribuyan al avance del proyecto. A continuación, se presenta el resumen del Sprint Planning Meeting, que proporcionará una visión general de los temas discutidos y las decisiones tomadas durante la reunión.

*Tabla del planeamiento a profundidad del Sprint 3.*
<table>
        <tr>
            <td colspan="1">Sprint #</td>
            <td colspan="1">Sprint 3</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td>Date</td>
            <td>24-05-2024</td>
        </tr>
          <tr>
            <td>Time</td>
            <td>20:52</td>
        </tr>
            <tr>
            <td>Location</td>
            <td>Discord</td>
        </tr>
            <tr>
            <td>Prepared by</td>
            <td>Gallo Quintana, David Ivanoff</td>
        </tr>
            <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Gallo Quintana, David Ivanoff / Mallma Quispe, Ruben / Paredes Zapata, Luiggi Gianfranco / Sanchez Zamora, Fabrizio Alessandro / Talizo Balbin, Joan Jefferson / Louis</td>
        </tr>
            <tr>
            <td>Sprint 3 Review Summary</td>
            <td>Para este Sprint 3, hemos decidido principalmente implmentar aquellas historias de usuario que añadan valor significativo a nuestro proyecto ya que consideramos otras funcionalidades extras (o que necesitan de otras) aún no necesarias puesto que priorizamos primero las historias de usuario que sean de gran importancia y valor primero. Además, en este Sprint 3, hemos decidido implementrar las correciones indicadas por el profesor como correciones o posibles mejoras a nuestro FrontEnd (Aplicación Web) y también mejoras a nuestro reporte.</td>
        </tr>
            <tr>
            <td>Sprint 3 Retrospective Summary</td>
            <td>Para la retrospectiva de Sprint 3, hemos analizado en conjunto el uso de nuestro tiempo como equipo para poder organizarnos mejor. Usamos herramientas como Trello para poder asignar tareas y coordinarlas para que de esta forma poder tener mejor control de nuestro proyecto. Por defecto a la asignación de tareas, hemos decidido asignar cada tarea a procesos más pequeños para que todo podamos trabajar eficientemente. Esta organización consiste en los dominios y dividir nuestro proyecto grande en pequeñas partes más manejables.</td>
        </tr>
            <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
              <tr>
            <td>Sprint 3 Goal</td>
            <td>La meta para este Sprint 3 fue hacer las primeras versiones de nuestro BackEnd (como primeras impresiones y versiones). También, hemos incluído entre nuestras metas hacer la mejora continua de nuestro repositorios (FrontEnd, Reporte y LandingPage). Internamente, como grupo, nos propusimos a mejorar nuestra organización por medio de aplicativos como Trello o ClickUp. De esta forma, hemos definido nuestras metas correctamente.</td>
        </tr>
              <tr>
            <td>Sprint 3 Velocity</td>
            <td>Para este Sprint 3, nuestro Sprint 3 Velocity es de 8 puntos.</td>
        </tr>
              <tr>
            <td>Sum of Story Points</td>
            <td>La suma de las historias de usuario para el Sprint 3, alcanza un valor de 65 puntos en total</td>
        </tr>
    </table>

#### 5.2.3.2 Sprint Backlog 3.
En esta sección se revisará todo el proceso dado para el Sprint Backlog 3, en el cual nuestro equipo de trabajo se centró principalmente en el diseño, estructuración y organización de la lógica de negocio agregada en nuestra aplicación web con el uso de servicios diferenciados y modelos de base de datos, además de proporcionar a futuro un modelo de intercambio de información entre el FrontEnd y el BackEnd estable. Hemos separado toda la construcción del BackEnd en 10 historias de usuario, donde cada integrante del grupo hizo al menos dos. Gracias a este proceso, para el final del Sprint Backlog 3, hemos conseguido tener una página web estable, con buenos modelos de interfaz, conexiones con APIs externas, y entre otros.

*Tabla principal del planeamiento del Sprint Backlog 3.*
<table>
        <tr>
            <td colspan="2">Sprint #</td>
            <td colspan="6">Sprint 3</td>
        </tr>
        <tr>
            <td colspan="2">User Story</td>
            <td colspan="6">Work-Item / Task</td>
        </tr>
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Descripcion</td>
            <td>Estimation (Hours)</td>
            <td>Assigned To</td>
            <td>Status (To-do / In / Process / ToReview / Done)</td>
        </tr>
        <tr>
            <td>US04</td>
            <td>Inicio de sesión</td>
            <td>TS01</td>
            <td>Sección o apartado para iniciar sesión dentro de la aplicación web</td>
            <td>Como usuario ya registrado, quiero poder iniciar sesión dentro de la aplicación web para poder usar las funcionalidades que brinda mi cuenta.</td>
            <td>1 hora y 30 minutos</td>
            <td>Rubén</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US20</td>
            <td>Permitir cerrar sesión para usar diferentes cuentas</td>
            <td>TS01</td>
            <td>Agregar aparatado para que el usuario pueda salir de la sesión (cerrar)</td>
            <td>Como usuario ya registrado de la aplicación web, quiero poder cerrar sesión y que mis datos estén guardados correctamente para poder usar diferentes cuentas o cerrar mi sesión.</td>
            <td>1 hora y 10 minutos</td>
            <td>Luiggi</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US09</td>
            <td>Registro de conductor joven (o común)</td>
            <td>TS02</td>
            <td>Añadir inicio de sesión a ambos segmentos objetivos: en este caso para conductores jóvenes</td></td>
            <td>Como conductor joven (o conductor en general), quiero poder registrarme dentro de la aplicación web para poder crear una cuenta a base de mis criterios y usar las funcionalidades que me brinda la app.</td>
            <td>2 hora y 30 minutos</td>
            <td>Fabrizio</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US14</td>
            <td>Registro de conductor corporativo</td>
            <td>TS02</td>
            <td>Añadir inicio de sesión a ambos segmentos objetivos: en este caso para conductores corporativos</td>
            <td>Como conductor corporativo o perteneciente a una flota vehicular, quiero poder registrarme dentro de la aplicación web para poder crear una cuenta a base de mis criterios y usar las funcionalidades que me brinda la app.</td>
            <td>2 hora y 30 minutos</td>
            <td>Fabrizio</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US15</td>
            <td>Permitir el registro usando un email</td>
            <td>TS02</td>
            <td>Permitir que los nuevos usuarios utilicen su correo electrónico para crear un nuevo registro de usuario</td>
            <td>Como próximo usuario de la aplicación web, quiero poder registrarme usando un correo electrónico para poder usar este correo como mis credenciales al momento de la autenticación de mi cuenta.</td>
            <td>1 hora y 0 minutos</td>
            <td>Fabrizio</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US23</td>
            <td>Mostrar el perfil del usuario</td>
            <td>TS03</td>
            <td>Permitir que el usuario pueda ver su información personal sobre el registro que hizo en un apartado de perfil</td>
            <td>Como usuario de la aplicación, quiero ver mi perfil para verificar que mis datos estén correctamente validados.</td>
            <td>2 hora y 30 minutos</td>
            <td>David</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US24</td>
            <td>Mostrar los vehículos registrados</td>
            <td>TS04</td>
            <td>Mostrar los vehículos registrados del usuario en un aparatado como inicio</td>
            <td>Como usuario de la aplicación, quiero ver mis vehículos registrados para poder tener registro de ellos cuando necesite.</td>
            <td>2 hora y 30 minutos</td>
            <td>Luiggi</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US26</td>
            <td>Eliminar vehículo registrado</td>
            <td>TS04</td>
            <td>Permitir que el usuario pueda eliminar un vehículo registrado</td>
            <td>Como usuario de la aplicación, quiero poder eliminar un registro de vehículo cuando necesite.</td>
            <td>2 hora y 0 minutos</td>
            <td>Luiggi</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US25</td>
            <td>Mostrar los dispositivos registrados de cada vehículo</td>
            <td>TS05</td>
            <td>Mostrar los dispositivos vinculados con todos los vehículo registrados del usuario</td>
            <td>Como usuario de la aplicación, quiero ver todos los dispositivos vinculados a todos mis vehículos cuando necesite.</td>
            <td>2 hora y 30 minutos</td>
            <td>Louis</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US30</td>
            <td>Eliminar dispositivo registrado</td>
            <td>TS05</td>
            <td>Permitir que el usuario pueda eliminar un vehículo y a la par eliminar correctamente el dispositivo vinculado</td>
            <td>Como usuario de la aplicación, quiero poder eliminar un registro de dispositivo cuando un vehículo sea eliminado.</td>
            <td>2 hora y 0 minutos</td>
            <td>Louis</td>
            <td>Done</td>
        </tr>
    </table>

Con el fin de que la lista de tareas en el sprint pueda ser visualizada a más profundidad, se mostrara un enlace directo a la sección de trabajo designada por el equipo junto a todas las actividades de forma completa. Hemos usado Trello como nuestra herramienta para planificar actividades: [Clic aquí](https://trello.com/b/GxUePWp8/securcar)

*Presentación de la tabla de actividades designada para el Sprint 3 en Trello.*

<img src="assets/Trello-Sprint3.png" alt="Lista de Tareas del Sprint 3 En Trello">

#### 5.2.3.3 Development Evidence for Sprint Review.
En esta sección se explica y presenta los avances en implementación con relación a los productos de la solución según el alcance del Sprint 3 referente a los Web Services. Aquí se dejara cada uno de los commits ya implementados dentro del repositorio de Github, junto a toda la información referente y a los cambios concluidos.

###### Tabla 32
*Tabla de los commits realizados y relacionados con el desarrollo de todas las secciones del Sprint Backlog 3*
| Repository | Branch| Commit Id| Commit Message| Commit Message Body|Commited on (Date) |
|------------|-------|----------|---------------|--------------------|-------------------|
| securcar-platform | main | 005857abf51982a224aad9cd4234e51b7aee2687 | chore: initial commit | Creation of the initial commit | 05/06/2024 |
| LandingPage_SecurCar | main | 8fb0b3943cde28f91b441ca17fe8c3c9ec1e7c4c | refactor: added call to action buttons | Added call to action buttons | 19/05/2024 |
| OSFrontEnd | develop | bbb3b28735dc447facedacfa672213ace12cf465 | chore: added router features and use of fake apis | Added fake APIs | 04/06/2024 |
| OSFrontEnd | develop | 17fa163bc8a344745325a340863abe9b72613d46 | feat: added component routes add vehicles | Added components routes and vehicles | 25/05/2024 |
| securcar-platform | develop | f81153f97a3c6dfff1de818d284660b613134619 | feat(entities): add documentation with JavaDoc | Add documentation with JavaDoc | 05/06/2024 |
| securcar-platform | develop | 14f973c0e33266415850707fd1cdb803f16872e5 | feat(iam): add iam bounded context | Add iam bounded context | 06/06/2024 |
| LandingPage_SecurCar | develop | 5baf2e7e7f6bdca47277a2c259ad5be92955c670 | feat: added videoaboutproduct | Added videoaboutproduct | 05/06/2024 |
| LandingPage_SecurCar | develop | 56e20117ebecab60ca018b3b1385ca84c0fa0abe | feat: added video about the team | Added video about the team | 05/06/2024 |

### 5.2.3.4 Testing Suite Evidence for Sprint Review. 
En esta sección presentaremos la evidencia detallada de las pruebas rigurosas realizadas durante el sprint. Para garantizar la calidad y funcionalidad del producto, hemos empleado la metodología Gherkin para definir escenarios de prueba claros y concisos. Cada uno de estos escenarios se ha registrado meticulosamente en commits específicos en nuestro repositorio de código, lo que proporciona un registro completo y transparente de nuestro proceso de prueba.

###### Tabla 33
*Tabla de los modelos de pruebas realizados y relacionados con el desarrollo de todas las secciones del Sprint Backlog 3*
| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| Gherkins | main | 29339897eac896e5f70ec021f5b006418f9c0a88 | Initial commit | Creation of repository 'Gherkins' | 06/06/2024 |
| Gherkins | main | a709ce1f72f44e905b4070db3c41fbde741658e6 | feat(Gherkins): added gherkins for Sprint 3 | Added gherkin validations for Sprint 3 | 06/06/2024 |

#### 5.2.3.5 Execution Evidence for Sprint Review. 
El equipo ha logrado implementar las características clave de la API principal de la startup junto a toda su lógica de negocio y la base de datos. Todas las historias de usuario asignadas para este sprint fueron completadas exitosamente.

*Muestra con evidencia de inicio de sesión (Login)*

<img src="assets/Evidencia-Login.png" alt="Evidencia de inicio de sesión en la Aplicación Web">

*Muestra con evidencia de registro para ambos segmentos objectivos (Register)*

<img src="assets/Evidencia-Registro-CommonDriver.png" alt="Evidencia del registro de usuario común en la Aplicación Web">

<img src="assets/Evidencia-Registro-CorporateDriver.png" alt="Evidencia del registro de usuario corporativo en la Aplicación Web">

*Muestra con evidencia de información de usuario*

<img src="assets/Evidencia-UserInformation.png" alt="Evidencia de información de usuario en la Aplicación Web">

*Muestra con evidencia de información de vehículo*

<img src="assets/Evidencia-VehicleInformation.png" alt="Evidencia de información de vehículo en la Aplicación Web">

*Muestra con evidencia de información de dispositivo*

<img src="assets/Evidencia-DeviceInformation.png" alt="Evidencia de información de dispositivo en la Aplicación Web">

#### 5.2.2.6 Services Documentation Evidence for Sprint Review. 
En esta sección, presentamos la relación de EndPoints documentados con OpenAPI utilizando Swagger como herramienta visual. Ajuntamos evidencias de la implementación de los EndPoints.

<img src="assets/Evidencia-EndPoint-1.png" alt="Evidencia de información de dispositivo en la Aplicación Web">

<img src="assets/Evidencia-EndPoint-2.png" alt="Evidencia de información de dispositivo en la Aplicación Web">

#### 5.2.2.7 Software Deployment Evidence for Sprint Review.

Dentro del Sprint 3, realizamos el despliegue de:
##### Landing Page
Mejoramos el landing page a base de las recomendaciones de nuestro profesor y las heurísticas realizadas. Principalmente, añadimos Call-To-Action y otros cambios en general. El link a nuestra Landing Page: [Clic aquí para ir a Landing Page](https://landingsecurcar.web.app/)

<img src="assets/Deployment-LandingPage-1.png" alt="Evidencia del deployment de nuestra Landing Page.">

<img src="assets/Deployment-LandingPage-2.png" alt="Evidencia del deployment de nuestra Landing Page.">

##### Front End
Entre varios cambios y mejoras, hemos incluído Fake-APIs a nuestro Front-End por el momento para después conectar y crear la comunicación de ambas partes. Dejamos el link de nuestro Front End: [Clic aquí para ir a Aplicación Web](https://os-front-end-amber.vercel.app/login)

<img src="assets/Deployment-FrontEnd-1.png" alt="Evidencia del deployment del Front End.">

<img src="assets/Deployment-FrontEnd-2.png" alt="Evidencia del deployment del Front End.">

##### Back End
Presentamos la primera versión den nuestro BackEnd. Esta primera versión contiene EndPoints que añadan valor a nuestro negocio, implementando capas de seguridad como características primarias de registro e inicio de sesión.

<img src="assets/Deployment-BackEnd.png" alt="Evidencia del deployment del Back End.">

#### 5.2.2.8 Team Collaboration Insights during Sprint.
Durante el Sprint 3, nos enfocamos en el desarrollo colaborativo del BackEnd del Web Application de SecurCar junto a la mejora del FrontEnd y nuestro Landing Page donde cada miembro del equipo contribuyó con sus habilidades y conocimientos. Esta colaboración se refleja en los numerosos commits, pull request, y reuniones que realizados en nuestro repositorio de código y herramientas externas, los cuales están respaldados por capturas de pantalla adjuntas para una documentación detallada. 

Nuestro equipo se reunió tanto en persona como virtualmente para asignar tareas y discutir la estrategia de desarrollo del proyecto. Estas reuniones fueron cruciales para clarificar nuestras responsabilidades individuales y asegurar un desempeño óptimo. Para maximizar la eficiencia, decidimos asignar a cada miembro del equipo una sección específica del BackEnd para desarrollar, lo que nos permitió avanzar rápidamente y cumplir con los plazos establecidos.

Además, programamos sesiones regulares de brainstorming y resolución de problemas, donde compartimos ideas y abordamos cualquier duda o dificultad que surgiera durante el proceso de desarrollo. Estas reuniones fueron fundamentales para resolver obstáculos de manera efectiva y garantizar un progreso constante en la elaboración del BackEnd del Web Application.

<img src="assets/GitHub-Report-Pulse.png" alt="Pulse for Rubén collaboration in Report.">

<img src="assets/GitHub-Back-Pulse.png" alt="Pulse for Rubén collaboration in Report.">

### 5.2.4. Sprint 4
#### 5.2.4.1. Sprint Planning 4.
En esta sección se explicaran los detalles presentados y analizados durante la reunión del Sprint Planning para el número 4. El objetivo principal de esta reunión es establecer un plan claro y realista para el sprint, identificando las tareas a realizar y comprometiéndose con un conjunto de entregables concretos que contribuyan al avance del proyecto. A continuación, se presenta el resumen del Sprint Planning Meeting, que proporcionará una visión general de los temas discutidos y las decisiones tomadas durante la reunión. <br>
<br>Tabla del planeamiento a profundidad del Sprint 4. <br>

<table>
        <tr>
            <td colspan="1">Sprint #</td>
            <td colspan="1">Sprint 4</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td>Date</td>
            <td>22-06-2024</td>
        </tr>
          <tr>
            <td>Time</td>
            <td>20:52</td>
        </tr>
            <tr>
            <td>Location</td>
            <td>Discord</td>
        </tr>
            <tr>
            <td>Prepared by</td>
            <td>Sanchez Zamora, Fabrizio Alessandro</td>
        </tr>
            <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Gallo Quintana, David Ivanoff / Mallma Quispe, Ruben / Paredes Zapata, Luiggi Gianfranco / Sanchez Zamora, Fabrizio Alessandro / Talizo Balbin, Joan Jefferson / Louis</td>
        </tr>
            <tr>
            <td>Sprint 4 Review Summary</td>
            <td>Para este Sprint 4, nuestro enfoque principal fue mejorar e implementar características que se habían desarrollado en entregables anteriores. En el lado del frontend de nuestra aplicación, trabajamos en temas como la navegación por rutas y la refactorización de componentes mínimos. Por otro lado, en el backend, nos centramos en la autenticación del usuario mediante Json Web Token y en la creación de vehículos para cada usuario. En resumen, en este sprint 4 se han agregado tanto detalles mínimos pendientes como aspectos clave para nuestra aplicación web.</td>
        </tr>
            <tr>
            <td>Sprint 4 Retrospective Summary</td>
            <td> En la retrospectiva del Sprint 4, evaluamos en grupo la planificacíon de nuestro tiempo para llegar a una correcta organización. Hicimos uso de la herramienta Trello nuevamente para asignar tareas y coordinarlas, lo que tuvo como resultado un mejor control sobre nuestro proyecto. Además, optamos por dividir las tareas en procesos más pequeños para trabajar de manera más eficiente. Esta estrategia nos ayudó a abordar nuestro proyecto grande dividiéndolo en partes más manejables.       </td>
            </tr>
            <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
              <tr>
            <td>Sprint 4 Goal</td>
            <td>Para este últimos sprint, se tuvo como objetivo culminar con los puntos pendientes mejorar nuestro reporte del trabajo, asi como un enfoque especia en el desarrollo de funcionalidades finales del lado fronted y backend de nuestra aplicación. Dichos objetivos se lograron gracias a las reuniones semanales que se hicieron a lo largo del plazo dado para este entregable.  </td>
        </tr>
              <tr>
            <td>Sprint 4 Velocity</td>
            <td>Para este Sprint 4, nuestro Sprint 3 Velocity es de 8 puntos.</td>
        </tr>
              <tr>
            <td>Sum of Story Points</td>
            <td>La suma de las historias de usuario para el Sprint 4, alcanza un valor de 65 puntos en total</td>
        </tr>
    </table>

#### 5.2.4.2. Sprint Backlog 4.
En esta sección se revisará todo el proceso dado para el Sprint Backlog 4, en el cual nuestro equipo de trabajo se centró principalmente en la implementación de los puntos faltantes de la entrega anterior tales como autenticacion de usuarios y funcionalidades del lado backend, además de haber realizado una correcta comunicación entre el FrontEnd y el BackEnd de manera estable. Para este sprint, hemos separado toda la construcción de la aplicación en 12 historias de usuario, donde cada integrante del grupo hizo al menos dos. Gracias a este proceso, para el final del Sprint Backlog 4, hemos conseguido tener una página web estable, con buenos modelos de interfaz, conexiones con APIs externas, y entre otros. <br>

*Tabla principal del planeamiento del Sprint Backlog 4.* <br>

<table>
        <tr>
            <td colspan="2">Sprint #</td>
            <td colspan="6">Sprint 4</td>
        </tr>
        <tr>
            <td colspan="2">User Story</td>
            <td colspan="6">Work-Item / Task</td>
        </tr>
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Descripcion</td>
            <td>Estimation (Hours)</td>
            <td>Assigned To</td>
            <td>Status (To-do / In / Process / ToReview / Done)</td>
        </tr>
        <tr>
            <td>US04</td>
            <td>Inicio de sesión</td>
            <td>TS01</td>
            <td>Sección o apartado para iniciar sesión dentro de la aplicación web</td>
            <td>Como usuario ya registrado, quiero poder iniciar sesión dentro de la aplicación web para poder usar las funcionalidades que brinda mi cuenta.</td>
            <td>1 hora y 30 minutos</td>
            <td>Rubén</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US09</td>
            <td>Registro de conductor joven (o común)</td>
            <td>TS02</td>
            <td>Añadir inicio de sesión a ambos segmentos objetivos: en este caso para conductores jóvenes</td></td>
            <td>Como conductor joven (o conductor en general), quiero poder registrarme dentro de la aplicación web para poder crear una cuenta a base de mis criterios y usar las funcionalidades que me brinda la app.</td>
            <td>2 hora y 30 minutos</td>
            <td>Fabrizio</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US14</td>
            <td>Registro de conductor corporativo</td>
            <td>TS02</td>
            <td>Añadir inicio de sesión a ambos segmentos objetivos: en este caso para conductores corporativos</td>
            <td>Como conductor corporativo o perteneciente a una flota vehicular, quiero poder registrarme dentro de la aplicación web para poder crear una cuenta a base de mis criterios y usar las funcionalidades que me brinda la app.</td>
            <td>2 hora y 30 minutos</td>
            <td>Fabrizio</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US15</td>
            <td>Permitir el registro usando un email</td>
            <td>TS02</td>
            <td>Permitir que los nuevos usuarios utilicen su correo electrónico para crear un nuevo registro de usuario</td>
            <td>Como próximo usuario de la aplicación web, quiero poder registrarme usando un correo electrónico para poder usar este correo como mis credenciales al momento de la autenticación de mi cuenta.</td>
            <td>1 hora y 0 minutos</td>
            <td>Fabrizio</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US20</td>
            <td>Permitir cerrar sesión para usar diferentes cuentas</td>
            <td>TS01</td>
            <td>Agregar aparatado para que el usuario pueda salir de la sesión (cerrar)</td>
            <td>Como usuario ya registrado de la aplicación web, quiero poder cerrar sesión y que mis datos estén guardados correctamente para poder usar diferentes cuentas o cerrar mi sesión.</td>
            <td>1 hora y 10 minutos</td>
            <td>Luiggi</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US23</td>
            <td>Mostrar el perfil del usuario</td>
            <td>TS03</td>
            <td>Permitir que el usuario pueda ver su información personal sobre el registro que hizo en un apartado de perfil</td>
            <td>Como usuario de la aplicación, quiero ver mi perfil para verificar que mis datos estén correctamente validados.</td>
            <td>2 hora y 30 minutos</td>
            <td>David</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US24</td>
            <td>Mostrar los vehículos registrados</td>
            <td>TS04</td>
            <td>Mostrar los vehículos registrados del usuario en un aparatado como inicio</td>
            <td>Como usuario de la aplicación, quiero ver mis vehículos registrados para poder tener registro de ellos cuando necesite.</td>
            <td>2 hora y 30 minutos</td>
            <td>Luiggi</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US26</td>
            <td>Eliminar vehículo registrado</td>
            <td>TS04</td>
            <td>Permitir que el usuario pueda eliminar un vehículo registrado</td>
            <td>Como usuario de la aplicación, quiero poder eliminar un registro de vehículo cuando necesite.</td>
            <td>2 hora y 0 minutos</td>
            <td>Luiggi</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US25</td>
            <td>Mostrar los dispositivos registrados de cada vehículo</td>
            <td>TS05</td>
            <td>Mostrar los dispositivos vinculados con todos los vehículo registrados del usuario</td>
            <td>Como usuario de la aplicación, quiero ver todos los dispositivos vinculados a todos mis vehículos cuando necesite.</td>
            <td>2 hora y 30 minutos</td>
            <td>Louis</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US30</td>
            <td>Eliminar dispositivo registrado</td>
            <td>TS05</td>
            <td>Permitir que el usuario pueda eliminar un vehículo y a la par eliminar correctamente el dispositivo vinculado</td>
            <td>Como usuario de la aplicación, quiero poder eliminar un registro de dispositivo cuando un vehículo sea eliminado.</td>
            <td>2 hora y 0 minutos</td>
            <td>Louis</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US31</td>
            <td>Acceso rápido al perfil desde la página de inicio.</td>
            <td>TS06</td>
            <td>Permitir que el usuario pueda acceder a su perfil a travás de un boton para acceder a la informacion de su cuenta rapidamente</td>
            <td>Como usuario registrado, deseo tener un acceso fácil y rápido a mi perfil desde la página de inicio, para poder gestionar mis datos personales, configuraciones y preferencias de forma conveniente.</td>
            <td>1 hora y 0 minutos</td>
            <td>Louis</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US32</td>
            <td>Registro de usuarios desde la página de inicio</td>
            <td>TS07</td>
            <td>Permitir que un nuevo usuario pueda registrarse en la página que la aparece al ingresar a la aplicacion web</td>
            <td>Como usuario interesado en utilizar los servicios del proyecto, deseo poder registrarme desde la página de inicio para comenzar a utilizar las funcionalidades disponibles.</td>
            <td>1 hora y 30 minutos</td>
            <td>Louis</td>
            <td>Done</td>
        </tr>
    </table>

#### 5.2.4.3. Development Evidence for Sprint Review.
En esta sección, se describen los avances en la implementación de los productos de la solución relacionados con los Web Services, según el alcance del Sprint 4. Aquí se presentarán los commits ya implementados en el repositorio de GitHub, junto con toda la información relevante y los cambios realizados.<br><br>
Tabla de los commits realizados y relacionados con el desarrollo de todas las secciones del Sprint Backlog 3. <br>

| Repository | Branch  | Commit Id| Commit Message                                                                                  | Commit Message Body                                    | Commited on (Date) |
|------------|---------|----------|-------------------------------------------------------------------------------------------------|--------------------------------------------------------|--------------------|
| securcar-platform | develop | 7826791 | refactor(application): add JpaAuditing                                                          | Add JPA Auditing                                       | 19/06/2024         |
| securcar-platform | develop | 14f973c0e33266415850707fd1cdb803f16872e5 | refactor(iam): refactoring something for regular functionality                                  | Refactoring Functionality                              | 19/06/2024         |
| OSFrontEnd | develop | 125dab7 | feat(app-login): merging with backend                                                           | Merging with Backend                                   | 23/06/2024         |
| OSFrontEnd | develop | 6cf6bac | feat(device-information & vehicle-information): added endpoint for register and get information | Addeing endpoint for register and get user information | 23/05/2024         |
| OSFrontEnd | develop | 9e0d353 | feat: implemented enviroment                                                                    | Adding use of emviroments                              | 23/05/2024         |


#### 5.2.4.4. Testing Suite Evidence for Sprint Review.
*Tabla de los modelos de pruebas realizados y relacionados con el desarrollo de todas las secciones del Sprint Backlog 4*

| Repository | Branch | Commit Id | Commit Message                              | Commit Message Body                    | Commited on (Date) |
|---|---|---|---------------------------------------------|----------------------------------------|--------------------|
| Gherkins | main | 29339897eac896e5f70ec021f5b006418f9c0a88 | Initial commit                              | Creation of repository 'Gherkins'      | 06/06/2024         |
| Gherkins | main | a709ce1f72f44e905b4070db3c41fbde741658e6 | feat(Gherkins): added gherkins for Sprint 4 | Added gherkin validations for Sprint 4 | 23/06/2024         |

#### 5.2.4.5. Execution Evidence for Sprint Review.

En este sprint 4, hemos logrado implementar las características clave de la API principal de la startup junto a toda su lógica de negocio y la base de datos. Todas las historias de usuario asignadas para este sprint fueron completadas exitosamente. <br><br>
### *Muestra con evidencia  de Registro)* <br>
![Registro Image](assets/imgF01.jpg) <br>
### *Muestra con evidencia de inicio de sesión (Login)* <br>
![Login Image](assets/imgF02.jpg) <br>
### *Muestra con evidencia de verificacion de usuario* <br>
![Verificacion Image](assets/imgF03.jpg) <br>
### *Muestra con evidencia de información de usuario* <br>
![User Information Image](assets/imgF04.jpg) <br>
### *Muestra con evidencia de agregar vehículo* <br>
![Add Vehicle Image](assets/imgF05.jpg) <br>
### *Muestra con evidencia de información de vehículo* <br>
![Vehicle Information Image](assets/imgF06.jpg) <br>


#### Video Demostrativo
![Video Demostrativo](assets/ExecutionTF.png)
[Enlace de video en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213652_upc_edu_pe/ESnFMKc2EbdHjdfuRfmb9gMBJfALulx_R4p4NVOo14QrVQ?e=vVF6OP&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

#### 5.2.4.6. Services Documentation Evidence for Sprint Review.
En esta sección, se describen los EndPoints documentados con OpenAPI mediante la herramienta Swagger para el sprint 4. Esto permite una visualización clara de los puntos de acceso de la API y sus características. Además, se adjuntan evidencias de la implementación de dichos EndPoints. <br> <br>
![Endpoints Image](assets/endpoints_sprint4.png)

|EndPoints| Acciones Implementadas                                                                                                    |
|---|---------------------------------------------------------------------------------------------------------------------------|
 |/api/v1/authentication/sign-up | Permite la creación de un nuevo usuario, teniendo como atributos username, password y rol( tipo de usuario)               |
| /api/v1/authentication/sign-in | Permite que un usuario existente pueda hacer login dentro de la aplicación teniendo como requisito el username y password |
| /api/v1/roles | Permite la asignación de roles a un usuario                                                                               |
| /api/v1/users | Permite obtener la informacion de los usuarios registrados en la base de datos de la apliación                            |
| /api/v1/users/{userId}| Permite obtener a un usuario teniendo como parametro su id                                                                |


#### 5.2.4.7. Software Deployment Evidence for Sprint Review.
Para este sprint 4, se realizo un deploy de los elementos faltantes, como la autenticación de usuarios y funcionalidades del lado backend. Se logró una correcta comunicación entre el FrontEnd y el BackEnd de manera estable. <br><br>

##### Fronted Deployment
![Fronted Deployment Image](assets/FDP01.jpg) <br>
![Fronted Deployment Image](assets/FDP02.jpg) <br>
![Fronted Deployment Image](assets/FDP03.jpg) <br>
![Fronted Deployment Image](assets/FDP04.jpg) <br>
![Fronted Deployment Image](assets/FDP05.jpg) <br>
![Fronted Deployment Image](assets/FDP06.jpg) <br>

##### Backend Deployment
![Backend Deployment Image](assets/imgB01.jpg) <br>
![Backend Deployment Image](assets/imgB02.jpg) <br>
![Backend Deployment Image](assets/imgB03.jpg) <br>
![Backend Deployment Image](assets/IMGB04.jpg) <br>
![Backend Deployment Image](assets/imgB05.jpg) <br>
![Backend Deployment Image](assets/imgB06.jpg) <br>


#### 5.2.4.8. Team Collaboration Insights during Sprint.
Para este sprint 4, hemos continuado con la metodología de trabajo en equipo que hemos venido utilizando en los sprints anteriores. Hemos mantenido una comunicación constante a través de reuniones semanales y el uso de herramientas de colaboración como Trello y Discord. Además, hemos seguido asignando tareas y responsabilidades a cada miembro del equipo, lo que ha permitido un progreso constante y una distribución equitativa de la carga de trabajo.
<br><br> Dicha comunicación ha sido clave para el éxito de nuestro proyecto, ya que nos ha permitido abordar los desafíos y obstáculos de manera efectiva y trabajar juntos para encontrar soluciones. Además, hemos seguido compartiendo ideas y conocimientos entre nosotros, lo que ha enriquecido nuestro proceso de desarrollo y nos ha permitido aprender unos de otros.

<img src="assets/GitHub-Report-Pulse.png" alt="Pulse for Rubén collaboration in Report.">

<img src="assets/GitHub-Back-Pulse.png" alt="Pulse for Rubén collaboration in Report.">


## 5.3. Validation Interviews.

### 5.3.1. Diseño de Entrevistas.
#### Saludo y presentación
Comenzamos con una introducción breve de los entrevistados para recordar quiénes son ya que han sido entrevistados anteriormente.

1. ¿Cómo se llama?
2. ¿Cuántos años tiene?
3. ¿En qué distrito vive?

#### Preguntas
Estas preguntas nos ayudarán a saber cuál es la experiencia de usuario, si nuestro producto llenó las expectativas del usuario, y también saber las posibles mejoras, comentarios y quejas sobre nuestro producto.

1. ¿Qué piensas de la interfaz de usuario de la aplicación web? ¿Es fácil de navegar?
2. ¿Encuentras que las funciones de la aplicación web son intuitivas y fáciles de usar?
4. ¿Hay alguna función que crees que debería estar en la aplicación web que actualmente no está?
5. ¿Cómo calificarías la experiencia general de uso de la aplicación web?
6. ¿Qué te gusta más y qué te gusta menos de la aplicación web?
7. ¿Te sentirías cómodo usando regularmente nuestra aplicación web?
8. ¿Cómo crees que nuestra aplicación web se comparan con otras similares que hayas utilizado?
9. ¿Hay algo que te confunda o te resulte difícil de entender en la aplicación web?
10. ¿Considerarías recomendarnos a tus amigos o familiares?
11. ¿Tienes alguna sugerencia para mejorar la experiencia del usuario en nuestra aplicación web?

### 5.3.2. Registro de Entrevistas.
  - **Taxistas Experimentados:**

  **Entrevista #2** <br>
  Nombre y apellidos: Maykol Valencia <br>
  Edad: 22 años <br>
  Distrito: Selva Alegre <br>
  ![URL de entrevista](assets/Registro_ReviewEntrevista_Seg01_MaykolValencia.png)<br>
  Inicio de Entrevista: 00:01 <br>
  [URL_De_Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223781_upc_edu_pe/ETf3Yo1xS1tNiR092WP4suMBwr2uSH10JhYYjoKxnJ342A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=PAF0Ei)<br>
  
  Resumen de entrevista: Maykol Valencia, de 22 años, evaluó positivamente la aplicación web SecurCar, diseñada para prevenir el robo de vehículos. Destacó la comodidad, orden y facilidad de uso de la interfaz, señalando que las funciones son intuitivas y bien detalladas. Calificó su experiencia como muy agradable y menos estresante en comparación con otras aplicaciones. Aunque no sugiere mejoras inmediatas, está dispuesto a recomendarla a amigos y familiares, especialmente a quienes usan vehículos para servicios de taxi, por considerarla innovadora y útil para la prevención de robos.
    
  **Entrevista #3** <br>
  Nombre y apellidos: Rubén Mallma <br>
  Edad: 49 años <br>
  Distrito: Villa María del Triunfo <br>
  ![URL de entrevista](assets/Registro_ReviewEntrevista_Seg01_RubénMallma.png)<br>
  Inicio de Entrevista: 00:01 <br>
  [URL_De_Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214234_upc_edu_pe/EYn6HNIEpvlBsXRrKCI6FDwBcjkvdHXff0sF8fUeI2UVHA?e=1Bhava)<br>

  Resumen de entrevista: El señor Rubén ahora nos da su opinión acerca de nuestra primera versión de la aplicación web que estamos desarrollando. Nos comenta además que quisiera que la aplicación funcione completamente ya que es difícil dar una opinión sólida sobre algo que aún no está terminado.
- **Conductores Jovenes:**
  **Entrevista #1**<br>
  Nombre y apellidos: Renzo Enciso <br>
  Edad: 20 años <br>
  Distrito: Chorrillos <br>
  ![URL de entrevista](assets/ValidationTest_OpenSource.png)<br>
  Inicio de Entrevista: 00:00 <br>

  Resumen de entrevista: El usuario encuentra la interfaz de la aplicación web atractiva y fácil de navegar, destacando la organización clara de los menús y opciones. Las funciones son intuitivas y fáciles de usar, pero sugiere agregar notificaciones en tiempo real para mejorar la seguridad. Califica la experiencia general como muy positiva, apreciando la rapidez y la eficacia, aunque señala la falta de notificaciones en tiempo real como una desventaja.
 <br> <br> En comparación con otras aplicaciones, destaca su simplicidad y rapidez, y no encuentra nada confuso o difícil de entender. El usuario recomendaría la aplicación a amigos y familiares por su utilidad y facilidad de uso. También sugiere agregar tutoriales interactivos para mejorar la experiencia del usuario y aumentar la confianza en la aplicación.
  <br> [URL_De_Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213652_upc_edu_pe/EdSnLql-TytMp5kcwwU_joYBB3CsmTrE_xqth_SVaAjicA?e=mwYuGL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)<br>


  - **Conductores Jovenes:**
  **Entrevista #2**<br>
   Nombre y apellidos: Daniela Chavez <br>
  Edad: 21 años <br>
  Distrito: Magdalena del Mar <br>
  ![URL de entrevista](assets/InterviewImageDanielaChavez.png)<br>
  Inicio de Entrevista: 00:00 <br>

  Resumen de entrevista: En este caso la señorita Daniela comunica que la página si cumple con su función, ademas que definitivamente resulta intuitiva. Aún así considera que hay campo de mejora, por ejemplo menciona que cree que los botones importantes de redirección deberian de ser de un color más distintivo. Finalmente menciona que es una página que si recomendaría, puesto que es importante asegurar nuestros vehículos.<br>
  **Entrevista #4**<br>
   Nombre y apellidos: Alonso Carrillo <br>
  Edad: 23 años <br>
  Distrito: Santiago de Surco <br>
  ![URL de entrevista](assets/InterviewAlonso4.png)<br>
  Inicio de Entrevista: 00:00 <br>

  Resumen de entrevista: En este caso Alonso menciona en varias ocasiones que la página es intuitiva y fácil de utilizar. Sugiere agregar poder compartir la ubicación en tiempo real para mejorar la seguridad. Califica su experiencia general como positiva, finalmente añadió que si recomendaría nuestra app web, porque la seguridad de un bien material es tema muy importante.

**Entrevista #6**<br>
Nombre y apellidos: Leonardo Lopez  <br>
Edad: 20 años <br>
Distrito: Santiago de Surco <br>

![Imagen_Entrevista](assets/EntrevistaLeo.JPG)
<br>

Resumen de entrevista:En el video, Leonardo López comenta sobre el progreso de una aplicación web en la que están trabajando. Expresa que está contento con el avance actual del proyecto, pero también menciona que considera necesario realizar algunos cambios para mejorar la aplicación. Aunque no especifica los detalles de estos cambios, su enfoque parece ser en optimizar y mejorar la funcionalidad o el diseño de la web app para asegurar su éxito. .


### 5.3.3. Evaluaciones según heurísticas.
UX Heuristics & Principles Evaluation
Usability – Inclusive Design – Information Architecture
CARRERA: Ingeniería de Software
CURSO: Desarrollo de Aplicaciones Open Source
SECCIÓN: SV55
PROFESORES: Alberto Wilmer Sanchez Seña
AUDITOR: Grupo 03 – Vet Connect
CLIENTE(S): Grupo 02 - SecurCar

SITE o APP A EVALUAR:
SecurCar
https://securcaropens.web.app/login



TAREAS A EVALUAR:
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
1. Registro de un usuario nuevo
2. Inicio de Sesión
3. Búsqueda de un paquete turístico
4. Reserva de un viaje
5. Cancelación de una reserva
6. Agregar ítems a un pedido
 
ESCALA DE SEVERIDAD:
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad
Nivel
Descripción
1
Problema superficial: puede ser fácilmente superado por el usuario u ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.
2
Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release.
3
Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.
4
Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.
 
TABLA RESUMEN:
 
| # | Problema | Escala de Severidad | Heuristica violada |
|---|----------|---------------------|-------------------|
| 1 | Botón “Ingresar”, “Registrar” y “¿Olvidaste tu contraseña?”  no cumplen su función. | 4 | Usability: Visibilidad del estado del Sistema y control y libertad del usuario. |
| 2 | El botón “Register” no funciona. | 4 | Usability: Visibilidad del estado del Sistema. | 
| 3 | En el apartado Main no funciona el mapa y ningún botón cumple su función. | 4 | Usability: Inconsistencia en el diseño o el uso de iconos que no se adhieren a los estándares de la web. | 
| 4 | En el apartado Profile no se puede realizar ninguna acción y el botón de regresar no sirve. | 4 | Inclusive Design:  Control y libertad del usuario. |
| 5 | En el apartado Device Info no se puede realizar ninguna acción, el botón de regresar no sirve y el mapa está estático. | 4 | Usability: Visibilidad del estado del Sistema y control y libertad del usuario. | 
| 6 | En el apartado Vehicle Info ningún botón funciona y el mapa está estático. | 4 | Usability: Visibilidad del estado del Sistema y control y libertad del usuario. | 
| 7 | En el apartado Vehicle Tracking ningún botón funciona y el mapa está estático. | 4 | Usability: Visibilidad del estado del Sistema y control y libertad del usuario. |
| 8 | En el apartado Vehicle Add el botón “Cancelar” no funciona y el botón “Agregar” solo redirecciona. | 4 | Usability: Visibilidad del estado del Sistema y control y libertad del usuario. |
| 9 | Botón con Símbolo de Perfil no redirecciona al Perfil. | 3 | Inclusive Design: Consistencia y estándares. |

 
 
## DESCRIPCIÓN DE PROBLEMAS:

### PROBLEMA #1: Botón “Ingresar”, “Registrar” y “¿Olvidaste tu contraseña?”  no cumplen su función.
Severidad: 4
Heurística violada: Usability: Visibilidad del estado del Sistema.
Problema:
Al momento de presionar los botones “Ingresar”, “Registrar” y “¿Olvidaste tu contraseña?” no cumplen con su función ni redirecciona a otra pantalla con interfaz.

![HeuristicImage1](assets/heuristic1.png)

Recomendación:
Se recomienda que los botones cumplan sus funciones como registrar que lleve a su respectivo apartado.

### PROBLEMA #2: El botón “Register” no funciona.
Severidad: 4
Heurística violada: Usability: Visibilidad del estado del Sistema.
Problema:   Al momento de rellenar datos e interactuar con el botón “Register” no hace nada.

![HeuristicImage2](assets/heuristic2.png)

Recomendación:
Se recomienda que el botón “Register” redireccione al Main o al Login.

### PROBLEMA #3: En el apartado Main no funciona el mapa y ningún botón cumple su función.
Severidad: 4
Heurística violada: Usability: Inconsistencia en el diseño o el uso de iconos que no se adhieren a los estándares de la web.
Problema: Al interactuar con la pantalla, los botones “Vehículos”, “Dispositivos” y los símbolos como el +, mensaje o perfil no realizan ninguna acción.

![HeuristicImage3](assets/heuristic3.png)

Recomendación:
Se recomienda que los botones cumplan su función.

### PROBLEMA #4: En el apartado Profile no se puede realizar ninguna acción y el botón de regresar no sirve.
Severidad: 4
Heurística violada: Inclusive Design:  Control y libertad del usuario.
Problema:
Es una pantalla estática que no se pueden rellenar datos de prueba y no se puede regresar al Main.

![HeuristicImage4](assets/heuristic4.png)

Recomendación:
Que se pueda rellenar el perfil y que el botón de regreso funcione

### PROBLEMA #5: En el apartado Device Info no se puede realizar ninguna acción, el botón de regresar no sirve y el mapa está estático.
Severidad: 4
Heurística violada: Usability: Visibilidad del estado del Sistema y control y libertad del usuario.
Problema:
La pantalla de Device Info es estática, tiene una imagen de mapa y al interactuar con el botón de regreso no hace nada.

![HeuristicImage5](assets/heuristic5.png)

Recomendación:
Se recomienda que los botones realicen sus acciones correspondientes y un api de Google maps.

### PROBLEMA #6: En el apartado Vehicle Info ningún botón funciona y el mapa está estático.
Severidad: 4
Heurística violada: Usability: Visibilidad del estado del Sistema y control y libertad del usuario.
Problema:
Es una pantalla estática, no se puede regresar al Main con su botón, los botones no sirven y tiene mapa no interactivo.

![HeuristicImage6](assets/heuristic6.png)

Recomendación:
Se recomienda que los botones cumplan sus funciones y tengan un api de Google maps.

### PROBLEMA #7: En el apartado Vehicle Tracking ningún botón funciona y el mapa está estático.
Severidad: 4
Heurística violada: Usability: Visibilidad del estado del Sistema y control y libertad del usuario.
Problema:
Es una pantalla estática, no se puede regresar al Main con su botón, los botones no sirven y tiene mapa no interactivo.

![HeuristicImage7](assets/heuristic7.png)

Recomendación:
Se recomienda que los botones cumplan sus funciones y tengan un api de Google maps.

### PROBLEMA #8: En el apartado Vehicle Add el botón “Cancelar” no funciona y el botón “Agregar” solo redirecciona.
Severidad: 4
Heurística violada: Usability: Visibilidad del estado del Sistema y control y libertad del usuario.
Problema:
Al interactuar con el botón “Cancelar” no ocurre ninguna acción y el botón “Agregar” lleva a una pantalla estática vista anteriormente, y tampoco se puede regresar ni ir al perfil con el icono.

![HeuristicImage8](assets/heuristic8.png)

### PROBLEMA #9: Botón con Símbolo de Perfil no redirecciona al Perfil.
Severidad: 3
Heurística violada: Inclusive Design: Consistencia y estándares.
Problema:
Hay botones con Símbolo de perfil en diferentes pantallas que no hacen nada al presionarlos.

![HeuristicImage9](assets/heuristic9.png)

Recomendación:
Se recomienda darle alguna funcionalidad que redireccione al perfil del usuario.







### 5.4. Video About-the-Product.
![VideoAboutProduct](assets/AboutProduct_OpenSource.png)
- URL Microsoft Stream: https://upcedupe-my.sharepoint.com/:v:/r/personal/u202223781_upc_edu_pe/Documents/Video%20About%20the%20Product%20TB2-%20SecurCar.avi?csf=1&web=1&e=QmqpNf&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
- URL Youtube: https://youtu.be/Y1SmEH7C4O8?si=aTUiONZ2rxXLHo0-
## Conclusiones 
- Para tener éxito durante la elaboración del proyecto es necesario que todos los integrantes participen y colaboren de manera equitativa, para que el proyecto pueda ser finalizado de manera rápida.

- Es bastante importante la realización de User stories junto con product backlog para definir las necesidades de los usuarios asi como clasificarlos por su importancia, esto con el objetivo de realizar las necesidades más importantes primero.

- Para tener éxito, es esencial abordar el riesgo de errores funcionales mediante pruebas y mejoras continuas.


## Video About The Team

En este segmento, mostramos la elaboración de la parte de seguridad del backend, esto en una llamada grupal en la cual resolvimos la problematica de la implementación.
Asimismo cada uno explica como lograron los Student Outcomes correspondientes gracias a la aplicación del proyecto.

### Secuencia:
- 00:00:00 Inicio de video
- 00:01:35 Comienzo de testimonios
- 00:01:36 Testimonio Luiggi Paredes
- 00:03:28 Testimonio David Gallo
- 00:04:47 Testimonio Fabrizio 
- 00:05:45 Testimonio Ruben
- 00:07:07 Testimonio Joan
- 00:08:08 Testimonio Louis
![VideoTeam](assets/Video_About_Team.png)
- URL Microsoft Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e475_upc_edu_pe/ERYRR1AV5fZBuEEZx-_c1J4BpFzLOwGt9G_3M11XnAomoQ?e=AAV3JN&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
- URL Youtube: https://youtu.be/h7UpEr2w0HA 

### Anexos:
- Validation Interviews:
  https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213652_upc_edu_pe/ETljkQ8IsKlJkrd8arOcC4gBngqJtaqyIAduIj2nTpH5Pw?e=znZ0BL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


- Video De Exposicion TB2:
  https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213652_upc_edu_pe/EYcsWnC4oa1JqRPBshhNwdMBse7gX6EpD-V2gdgukqriwg?e=fkcSEu&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

