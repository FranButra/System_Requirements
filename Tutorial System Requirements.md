Para hacer los diagramas de requisitos:

Seguid el modelo del diagrama "User Requirements", que está completamente terminado

El diagrama "System Requirements" sólo tiene "packages" que organizan cada uno de los requisitos. Para acceder a vuestros diagramas (los que tenéis que rellenar), en la vista de Papyrus debéis ir al "Model Explorer". Ahí, abrís RootElement->System Requirements->Vuestro paquete (e.g. "1. Functional Requirements")->Diagrama. Es AHÍ donde tenéis que construir el diagrama.

El paquete "Usability Requirements" está empezado, para que tengáis una idea de cómo seguir. Le podéis echar un vistazo.

Cada diagrama tiene un RATIONALE explicando el contenido del diagrama, y un COMMENT donde viene: Nombre del diagrama Versión (ponedle el día en que lo acabéis donde pone xx) Autor: xd

Cada requisito debe tener una IDENTIFICACIÓN (id) y un contenido (TEXT).

La identificación tiene que seguir unas reglas. Empieza siempre con las iniciales de vuestro diagrama (e.g. "UR" para el diagrama de Usability Requirements). El primer requisito es el 1 (e.g. "UR1), el siguiente el 2 (e.g. "UR2"), etc. Si hay requisitos anidados, seguid la serie "UR1.1", "UR1.2", "UR1.2.1.57", etc. Tenéis un ejemplo en el diagrama "Usability Requirements"

El texto lo dejo a vuestra brillantez y creatividad. Sólo hay una norma: los requisitos se escriben con "shall" (e.g. "Requirements specifications shall be stated using 'shal'"). Si hay cosas "deseables" pero que no son exigibles, se puede usar "should" (e.g. "Requirementes should be written in perfect English xD")

Idealmente podéis incluir la trazabilidad del requisito. Ponéis al final del texto "Traced to:" y ponéis los identificadores del requerimiento del "User Requirements" del que proviene. Tenéis un ejemplo en "Usability Requirements". En realidad es lo que hay que hacer pero es mucho trabajo. Sed honrados y dedicadle el tiempo que podáis. Si no lo haceis ahora, habrá que hacerlo en Navidades igualmente.

Vamos a intentar hacer bien los branch, los commits y los merge para que no se pierda el trabajo de nadie.

Tened en cuenta que tengo que hacer captura de pantalla de los diagramas y meterlos en un documento pdf. Intentad que os quepan en lo que sería un A4. Si es imposible, tenemos que crear subdiagramas. En ese caso avisadme y os explico cómo se hace

Eso es todo. Disfrutad :)

EXTRA: Cómo hacer que el cuadrito de Requirements muestre la id y el texto (requested by Fran):

En SysML rellenáis el nombre, la id y el texto En Appearance os vais abajo del todo. En la tabla marcáis el tick de "In Compartment" en la fila de "Requirement". Acto seguido quitáis el tick de todos los items que no sean "text" e "id" Por último, quitáis y ponéis el tick de "text" para que "id" salga arriba y "text" salga abajo

C'est tout
