# 🖥️ Unidad II: Programación Estructurada

**Autor:** 🧑‍💻 Ing. Elvis Sánchez

---

## 📚 Introducción

En el mundo actual, donde la tecnología está en constante evolución, la **programación estructurada** se ha consolidado como una de las bases fundamentales del desarrollo de software. Desde aplicaciones simples hasta sistemas complejos, esta metodología nos permite organizar el código de manera clara, modular y fácil de mantener.

Anteriormente, el desarrollo del software era más complicado, ya que no se contaba con estructuras a seguir para su construcción, como los **algoritmos estructurados**, tampoco había herramientas que ayudaran con este propósito. Por eso, aprenderemos cómo aplicar principios de desarrollo estructurado, el **análisis estructurado de sistemas (AES)**, las **herramientas estructuradas**, entre otros, para construir soluciones robustas y eficientes.

A lo largo de este contenido, exploraremos conceptos fundamentales y herramientas prácticas para la aplicación de la programación estructurada en el desarrollo de software.

---

## 🛠️ Desarrollo Estructurado

El **desarrollo estructurado** es una metodología de programación que se caracteriza por dividir un problema en componentes más pequeños y manejables, lo que permite abordarlo de manera sistemática y organizada. Este enfoque no solo facilita la comprensión, implementación y mantenimiento del software, sino que también promueve la creación de programas claros, eficientes y de alta calidad mediante el uso de estructuras lógicas bien definidas, como secuencias, decisiones y ciclos.

Además, al integrar principios de ingeniería, sentó las bases para un desarrollo automatizado y disciplinado, mejorando significativamente el tiempo y la calidad del proceso de desarrollo.

Este paradigma se basa en la idea de que cualquier programa puede ser construido utilizando combinaciones de tareas elementales, procedimientos técnicos y herramientas específicas, asegurando así un diseño modular y escalable.

### Características Principales
- **🧩 Estructuras de Control:** Aplica el uso de secuencias, selecciones y repeticiones para controlar el flujo del programa.
- **📖 Legibilidad:** Escribe código fácil de leer y entender debido a la organización clara y lógica.
- **🔧 Mantenible:** Facilita la modificación y extensión del código debido a su estructura modular.
- **⚡ Eficiencia:** Vela por la optimización del rendimiento mediante el uso de algoritmos eficientes.

---

## 🔍 Análisis Estructurado de Sistemas (AES)

El **Análisis Estructurado de Sistemas (AES)** es una metodología utilizada en el desarrollo de software para analizar, diseñar y documentar sistemas de información de manera organizada y sistemática. Este enfoque se basa en la descomposición de un sistema en componentes más pequeños y manejables, lo que permite entender y modelar su funcionamiento de forma clara y precisa. El AES es especialmente útil en las etapas iniciales del ciclo de vida del desarrollo de software, donde se definen los requisitos y se establece la estructura del sistema.

Además, proporciona un marco de trabajo que facilita la identificación de los elementos clave de un sistema, como los procesos, los flujos de datos, las entidades y las relaciones entre ellos. Esta metodología no solo se enfoca en el aspecto técnico del sistema, sino también en las necesidades del usuario y los objetivos del negocio, asegurando que el sistema final esté alineado con las expectativas y requerimientos de los stakeholders (clientes).

Este también promueve la estandarización en el desarrollo de software, ya que utiliza herramientas y técnicas bien definidas. Estas herramientas no solo ayudan a visualizar el sistema, sino que también sirven como una forma de comunicación común entre los diferentes miembros del equipo, incluyendo analistas, desarrolladores, diseñadores y usuarios finales. Esto reduce la posibilidad de malentendidos y asegura que todos tengan una comprensión clara y consistente del sistema.

---

## 🧰 Herramientas de Análisis Estructurado de Sistemas

Las **herramientas del análisis estructurado de sistemas** son técnicas y recursos utilizados para modelar, analizar y documentar sistemas de información de manera clara y organizada. Estas herramientas permiten a los analistas y desarrolladores entender cómo funcionan los procesos, los flujos de datos y las interacciones dentro de un sistema, lo que facilita la identificación de requisitos, la detección de problemas y la creación de soluciones eficientes.

Además, estas herramientas son fundamentales en las primeras etapas del ciclo de vida del desarrollo de software, ya que proporcionan un marco estructurado para capturar y organizar la información necesaria para diseñar sistemas que cumplan con las necesidades de los usuarios y los objetivos del negocio. Al utilizar estas técnicas, los equipos de desarrollo pueden asegurar que todos los aspectos del sistema estén bien definidos y documentados, lo que reduce la posibilidad de errores y malentendidos durante la implementación.

También son útiles para facilitar la comunicación entre los diferentes stakeholders involucrados en un proyecto, como los analistas de negocio, los desarrolladores, los diseñadores y los usuarios finales.

### 📊 Diagramas de Flujo de Datos (DFD)

Los **Diagramas de Flujo de Datos (DFD)** son herramientas visuales que se utilizan para representar el flujo de datos a través de un sistema, así como los procesos que los transforman y los almacenes donde se guardan. Estos diagramas permiten visualizar de manera clara y sencilla cómo los datos ingresan, se procesan, almacenan y salen del sistema, lo que facilita la comprensión de su funcionamiento y la identificación de áreas de mejora.

Estos diagramas son ampliamente utilizados en el análisis y diseño de sistemas para modelar procesos de manera clara y estructurada, permitiendo a los analistas y desarrolladores comprender la lógica detrás del funcionamiento de un sistema sin entrar en detalles técnicos o físicos específicos. Por esta misma razón, son muy útiles para presentar el funcionamiento del sistema a los usuarios finales.

#### Componentes de los DFD
- **🏢 Entidades Externas:** Representadas generalmente como rectángulos, estas son las fuentes o destinos de los datos que interactúan con el sistema, pero están fuera de su control.
- **⚙️ Procesos:** Representados por círculos u óvalos, estos describen las actividades que se realizan sobre los datos dentro del sistema.
- **➡️ Flujos de Datos:** Representados por flechas, indican la dirección en la que los datos se mueven entre las entidades externas, procesos y almacenes de datos.
- **🗄️ Almacenes de Datos:** Representados por líneas paralelas o rectángulos abiertos, estos simbolizan los lugares donde los datos son almacenados temporal o permanentemente dentro del sistema.

#### Niveles del DFD

1. **🌐 Nivel 0 (Diagrama de Contexto):** también conocido como diagrama de contexto , es el nivel más general y abstracto del DFD. Este diagrama proporciona una visión global del sistema, mostrando cómo interactúa con entidades externas sin entrar en detalles internos. En este nivel, el sistema se representa como un único proceso central, que encapsula toda la funcionalidad del sistema, y se conecta con las entidades externas (fuentes o destinos de datos) a través de flujos de datos.
2. **📂 Nivel 1 (Diagrama de Nivel Superior):** en este nivel el sistema se descompone en sus principales subsistemas o procesos clave. Este nivel proporciona una visión más detallada del flujo de datos dentro del sistema, identificando los procesos principales, los flujos de datos entre ellos y las entidades externas involucradas. Este explica cada proceso principal se representa como un nodo independiente, y se detallan las interacciones entre estos procesos, así como su conexión con las entidades externas y los almacenes de datos.
3. **🔍 Nivel 2 (Diagrama de Detalle):** es el nivel que profundiza aún más en los procesos identificados en el Nivel 1, descomponiendo los en subprocesos más específicos. Este nivel permite visualizar el flujo de datos en mayor detalle y es útil para validar el diseño del sistema con los usuarios finales. Al presentar un nivel de detalle más específico, los usuarios pueden entender mejor cómo funcionará el sistema en la práctica y proporcionar retroalimentación sobre los procesos que les afectan directamente. Esto asegura que el sistema esté alineado con las necesidades y expectativas de los usuarios, lo que es crucial para el éxito del proyecto.
4. **📑 Nivel 3 (Niveles Superiores):** en algunos casos, cuando el sistema es particularmente complejo, se pueden crear niveles adicionales para proporcionar un detalle aún mayor sobre los subprocesos específicos. Sin embargo, estos niveles suelen ser menos comunes debido a que pueden volverse demasiado técnicos y difíciles de interpretar para los usuarios no especializados.

---

### 📚 Diccionario de Datos (DD)

El **Diccionario de Datos (DD)** es una herramienta fundamental en el Análisis Estructurado de Sistemas que actúa como un repositorio centralizado para almacenar, organizar y documentar toda la información relacionada con los datos utilizados en un sistema. Su principal objetivo es proporcionar una descripción clara, precisa y detallada de cada elemento de datos, asegurando que todos los involucrados en el desarrollo y uso del sistema (analistas, desarrolladores, diseñadores y usuarios finales) compartan una comprensión común y consistente de los mismos.

Estos sirve como una fuente de referencia confiable durante todo el ciclo de vida del sistema. Desde la fase de análisis y diseño hasta la implementación y el mantenimiento, el Diccionario de Datos proporciona información detallada sobre la estructura, el significado y las relaciones de los datos. Esto es especialmente útil cuando se realizan cambios en el sistema o cuando se integra con otros sistemas, ya que garantiza que todos los involucrados tengan acceso a la misma información actualizada y precisa.

#### Estructura del DD
- **Nombre del dato**
- **Descripción**
- **Tipo**
- **Longitud**
- **Formato**
- **Rango de valores**
- **Origen y destino**
- **Relaciones**

---

### 📝 Diccionario de Procesos (DP)

El **Diccionario de Procesos (DP)** también es una herramienta en el Análisis Estructurado de Sistemas que se utiliza para documentar y describir de manera detallada cómo se realizan los procesos dentro de un sistema. Su objetivo principal es proporcionar una comprensión clara y precisa de las actividades, reglas de negocio y lógica involucrada en cada proceso, lo que facilita su análisis, diseño, implementación y mantenimiento.

Estos especialmente útil en sistemas complejos, donde es necesario desglosar los procesos en tareas más pequeñas y específicas para entender su funcionamiento y asegurar que cumplan con los requisitos del negocio.

#### Estructura del DP
- **Nombre del proceso**
- **Descripción**
- **Entradas**
- **Salidas**
- **Reglas de negocio**
- **Responsable**

---

### 🛠️ Herramientas CASE (Computer-Aided Software Engineering)

Las **herramientas CASE (Computer-Aided Software Engineering, o Ingeniería de Software Asistida por Computadora)** son aplicaciones de software diseñadas para apoyar y automatizar diversas actividades en el ciclo de vida del desarrollo de sistemas. Estas herramientas ayudan a los analistas, diseñadores y desarrolladores a crear, gestionar y mantener sistemas de software de manera más eficiente y efectiva.

#### Tipos de Herramientas CASE

Las Herramientas CASE se clasifican en diferentes tipos según su enfoque, funcionalidad y la etapa del ciclo de vida del software en la que se utilizan. A continuación, se describen los principales tipos de herramientas CASE:

1. **🔝 Herramientas CASE de Alto Nivel (Upper CASE):** estas herramientas se centran en las etapas iniciales del ciclo de vida del software, como el análisis de requisitos y el diseño del sistema. Su objetivo es ayudar a los analistas y diseñadores a modelar y documentar los requisitos del sistema de manera clara y precisa.
   - Ejemplos: Enterprise Architect, IBM Rational Rose, Microsoft Visio.
2. **🔧 Herramientas CASE de Bajo Nivel (Lower CASE):** se enfocan en las fases finales o inferiores del ciclo de vida del desarrollo de software, como la construcción, implementación y generación de código. Estas herramientas están diseñadas para automatizar tareas técnicas específicas, como la generación de código fuente, la creación de programas de detección de errores, la depuración y la optimización del software. Su objetivo principal es reducir el esfuerzo manual en las etapas de implementación y mantenimiento, asegurando que el software sea eficiente, consistente y de alta calidad.
   - Ejemplos: Eclipse, MATLAB, JUnit.
3. **🔄 Herramientas CASE Integradas (I-CASE):** estas herramientas cubren todo el ciclo de vida del software, desde el análisis y diseño hasta la implementación y el mantenimiento. Proporcionan un entorno integrado que conecta las diferentes etapas del desarrollo. A diferencia de las herramientas CASE de Alto Nivel (Upper CASE) o de Bajo Nivel (Lower CASE), que se enfocan en fases específicas del desarrollo, las herramientas I-CASE proporcionan un entorno integrado que conecta y sincroniza todas las etapas del proceso de desarrollo de software. Por ello, son mas complicadas de usar, pero permiten centrar todo el desarrollo del sistema en una solo aplicación.
   - Ejemplos: EasyCASE, PowerDesigner, Oracle Designer.
4. **📅 Herramientas CASE para Gestión de Proyectos:** estas herramientas se centran en la planificación, seguimiento y control de proyectos de software. Su objetivo es ayudar a los gerentes de proyecto a organizar y gestionar los recursos, tareas y plazos. Ademas, estas herramientas reducen riesgos y optimizan el uso de recursos. Su uso es especialmente importante en proyectos complejos o de gran escala, donde la coordinación y el control son críticos para cumplir con los objetivos del negocio y las expectativas de los stakeholders.
   - Ejemplos: Microsoft Project, Asana, Jira.
5. **🧪 Herramientas CASE para Pruebas y Calidad:** estas herramientas están diseñadas para apoyar las actividades de pruebas y aseguramiento de la calidad del software. Su objetivo es garantizar que el sistema cumpla con los requisitos y estándares de calidad. Estas mejoran la eficiencia, reducen costos y aumentan la confianza en el producto final. Su uso es fundamental en proyectos de desarrollo de software, especialmente en entornos ágiles o de integración continua, donde la calidad y la rapidez son críticas para el éxito.
   - Ejemplos: Selenium, LoadRunner, SonarQube.
6. **📂 Herramientas CASE para Gestión de Configuración:** estas herramientas se enfocan en el control de versiones y la gestión de cambios en el código y la documentación. Su objetivo es mantener un registro preciso de las modificaciones realizadas en el software. En un entorno donde la complejidad y la colaboración son críticas, estas herramientas se han convertido en aliados indispensables para los equipos de desarrollo de software.
   - Ejemplos: Git, Mercurial, Jenkins.
7. **📄 Herramientas CASE para Documentación:**     Estas herramientas facilitan la creación y mantenimiento de la documentación técnica y de usuario. Su objetivo es asegurar que la documentación esté actualizada y sea accesible. Estas herramientas permiten a los equipos de desarrollo generar documentación de manera eficiente, asegurando que esté actualizada, organizada y accesible para todos los stakeholders involucrados en el proyecto. La documentación es un componente crítico en el ciclo de vida del software, ya que proporciona información esencial sobre el diseño, funcionalidades, requisitos y uso del sistema
---

## 🗃️ Modelado de Datos

El **modelado de datos** es el proceso de crear una representación visual y estructurada de cómo se deben almacenar, organizar y relacionar los datos dentro de un sistema de información. Este proceso es fundamental para garantizar que los datos sean consistentes, accesibles y útiles para las necesidades de una organización.

### Tipos de Modelos de Datos
- **Modelo Conceptual:** Visión abstracta de alto nivel.
- **Modelo Lógico:** Define las estructuras de datos sin detalles técnicos.
- **Modelo Físico:** Detalla cómo se implementarán los datos en una base de datos específica.

---

## 🔄 Workflow (Flujo de Trabajo)

El **Workflow (o flujo de trabajo)** es un conjunto de actividades relacionadas que se realizan en un orden específico para alcanzar un objetivo determinado. Es una forma de estructurar los pasos necesarios para completar un proceso operativo, asegurando que las tareas se realicen de manera eficiente y consistente.

### Beneficios del Workflow
- **Optimización de tiempo y recursos.**
- **Reducción de errores humanos.**
- **Mejora de la productividad.**
- **Clarificación de responsabilidades.**

---
