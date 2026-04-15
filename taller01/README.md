# Actividad Práctica (AEE)

## Taller 1: Stakeholders y Materialidad en el Sector Web

* **Fecha:** 15 de abril de 2026  
* **Duración:** 50 minutos (Sesión presencial)  
* **Módulo:** Sostenibilidad Aplicada al Sistema Productivo (1708)  
* **Peso en la nota:** 30% de la evaluación del RA6.

# 1\. Marco de Evaluación

Para que sepáis lo qué estamos midiendo hoy, este taller se enmarca en la siguiente estructura curricular:

* **UD05**. Inversión socialmente responsable, criterios ASG[^1] y planes de sostenibilidad para empresas.  
* **RA6**. Analiza un plan de sostenibilidad de una empresa del sector, identificando sus grupos de interés, los aspectos ASG materiales y justificando acciones para su gestión y medición.  
* **CE**.   
  a) Se han identificado los principales grupos de interés de la empresa.  
  b) Se han analizado los aspectos ASG materiales, las expectativas de los grupos de interés y la importancia de los aspectos ASG en relación con los objetivos empresariales.

# 2\. Introducción y Contexto

En el mundo del desarrollo web, no trabajamos en una burbuja. Nuestras aplicaciones impactan en personas, consumen energía en servidores y gestionan datos sensibles. La **materialidad** no es más que identificar qué aspectos de nuestra actividad son realmente críticos tanto para la empresa como para la sociedad.

¿De qué sirve optimizar un algoritmo si no sabemos quiénes son nuestros *stakeholders[^2]* o qué esperan de nosotros? Hoy vamos a mapear ese ecosistema utilizando herramientas de desarrollo real.

# 3\. Herramientas del Taller

Utilizaremos el stack técnico habitual, pero con un enfoque de sostenibilidad:

* **VS Code**. Para la redacción de documentación, estructuración de datos y generar un archivo de datos estructurados (stakeholders.xml).  
* **GitHub**. Como plataforma de control de versiones y entrega final.  
* **BBDD Académicas**. [Consulta obligatoria de fuentes](https://classroom.google.com/c/NzcwOTA1MDUzNTE4/m/ODQwOTQzMDYyOTc4/details) en Google Scholar, arXiv o Dialnet. Nada de copiar y pegar de un chatbot sin contrastar.

# 4\. Desarrollo de la Actividad (50 min)

## Fase 1: Investigación Rigurosa (10 min)

Identifica los 3 grupos de interés clave y los 3 temas materiales (ej. eficiencia energética del código, accesibilidad universal, privacidad de datos) para una consultora web.

**Obligatorio**. Utiliza el documento [BBDD\_Academicas](https://classroom.google.com/c/NzcwOTA1MDUzNTE4/m/ODQwOTQzMDYyOTc4/details). Busca términos como "Green IT" o "Materiality in ICT". Cita tus fuentes en formato IEEE.

## Fase 2: Estructuración en XML (20 min)

Crea un archivo llamado *materialidad.xml*. El código debe estar bien formado y contener:

* Raíz *\<empresa\_sostenible\>*.  
* Nodos *\<stakeholder\>* con atributos de importancia.  
* Nodos *\<tema\_material\>* con descripción y nivel de impacto **ASG** (Ambiental, Social o Gobernanza).

## Fase 3: Documentación y GitHub (20 min)

Subid el archivo XML y cread un *README.md* profesional.

# 5\. Normas de Entrega y Calificación

La entrega se hace indicando la URL de tu **repositorio de GitHub** en la tarea del Classroom.

**¿Qué voy a valorar para vuestra nota?**

1. **README.md (Markdown)**. Uso correcto de jerarquía de títulos, negritas para conceptos y cursivas para tecnicismos. Debe incluir la lista de fuentes citadas.  
2. **Calidad del XML**. Código limpio, bien indentado y con comentarios que expliquen la lógica de los nodos.  
3. **Gestión de Versiones**. Al menos 3 *commits* con mensajes claros (ej. docs: añadidos referencias IEEE, además: define la estructura XML y su XSD).  
4. **Rigor Académico**. Detectaré y penalizaré el uso de IA sin curación de contenidos. Busco análisis crítico.

[^1]:  ASG (Ambiental, Social y Gobernanza): Hace referencia a los tres pilares fundamentales que permiten medir el impacto y la sostenibilidad de una inversión o actividad empresarial.

[^2]:  Se definen como cualquier individuo, colectivo o entidad que puede influir en el ciclo de vida de un desarrollo tecnológico o que, de un modo u otro, se ve impactado por sus resultados. En nuestro ecosistema de desarrollo, esto no solo incluye a clientes o usuarios finales, sino también a los propios desarrolladores, a los proveedores de infraestructura en la nube y a la sociedad en general, dada la huella social y ambiental que genera nuestra actividad.