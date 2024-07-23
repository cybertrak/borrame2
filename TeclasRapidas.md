### [Navegación](https://yazi-rs.github.io/docs/quick-start/#navigation)

Para navegar entre archivos y directorios , puede utilizar las teclas de flecha , ←y / ↓o teclas tipo Vim como ,,, :↑→hjkl

| Clave de enlace | Clave alternativa | Acción                                         |
| --------------- | ----------------- | ---------------------------------------------- |
| k               | ↑                 | Mover el cursor hacia arriba                   |
| j               | ↓                 | Mover el cursor hacia abajo                    |
| l               | →                 | Ingresar al directorio flotante                |
| h               | ←                 | Salga del directorio actual y entre a su padre |

Se pueden encontrar más comandos de navegación en la siguiente tabla.

| Clave de enlace | Acción                                |
| --------------- | ------------------------------------- |
| K               | Mover el cursor hacia arriba 5 líneas |
| J               | Mueve el cursor hacia abajo 5 líneas  |
| g⇒g             | Mover el cursor hacia arriba          |
| G               | Mover el cursor hacia abajo           |

### [Selección](https://yazi-rs.github.io/docs/quick-start/#selection)

Para seleccionar archivos y directorios, están disponibles los siguientes comandos.

| Clave de enlace | Acción                                              |
| --------------- | --------------------------------------------------- |
| Space           | Alternar selección de archivo/directorio suspendido |
| v               | Ingrese al modo visual (modo de selección)          |
| V               | Ingrese al modo visual (modo desarmado)             |
| Ctrl+a          | Seleccionar todos los archivos                      |
| Ctrl+r          | Selección inversa de todos los archivos.            |
| Esc             | Cancelar selección                                  |

### [Operaciones](https://yazi-rs.github.io/docs/quick-start/#file-operations) de archivos

Para interactuar con archivos/directorios seleccionados, utilice cualquiera de los siguientes comandos.

| Clave de enlace | Acción                                                       |
| --------------- | ------------------------------------------------------------ |
| o               | Abrir archivos seleccionados                                 |
| O               | Abrir archivos seleccionados de forma interactiva            |
| Enter           | Abrir archivos seleccionados                                 |
| Ctrl+Enter      | Abrir archivos seleccionados de forma interactiva (algunos terminales aún no lo admiten) |
| y               | Yank archivos seleccionados (copiar)                         |
| x               | Yank archivos seleccionados (cortar)                         |
| p               | Pegar archivos extraídos                                     |
| P               | Pegar archivos extraídos (sobrescribir si el destino existe) |
| -               | Enlace simbólico a la ruta absoluta de los archivos extraídos |
| _               | Enlace simbólico a la ruta relativa de los archivos extraídos |
| YoX             | Cancelar el estado de tirón                                  |
| d               | Archivos seleccionados en la papelera                        |
| D               | Eliminar permanentemente los archivos seleccionados          |
| a               | Crear un archivo (termina en / para directorios)             |
| r               | Cambiar el nombre de los archivos seleccionados              |
| ;               | Ejecutar un comando de shell                                 |
| :               | Ejecutar un comando de shell (bloquear hasta finalizar)      |
| .               | Alternar la visibilidad de archivos ocultos                  |
| z               | Saltar a un directorio usando zóxido                         |
| Z               | Saltar a un directorio o revelar un archivo usando fzf       |

### Copiar [rutas](https://yazi-rs.github.io/docs/quick-start/#copy-paths)

Para copiar rutas, utilice cualquiera de los siguientes comandos a continuación.

*Observación: c⇒ dindica presionar la ctecla seguido de presionar la dtecla.*

| Clave de enlace | Acción                                     |
| --------------- | ------------------------------------------ |
| c⇒c             | Copie la ruta del archivo                  |
| c⇒d             | Copie la ruta del directorio               |
| c⇒f             | Copia el nombre del archivo                |
| c⇒n             | Copia el nombre del archivo sin extensión. |

### Filtrar [archivos](https://yazi-rs.github.io/docs/quick-start/#filter-files)

| Clave de enlace | Acción           |
| --------------- | ---------------- |
| f               | Filtrar archivos |

### encontrar [archivos](https://yazi-rs.github.io/docs/quick-start/#find-files)

| Clave de enlace | Acción                      |
| --------------- | --------------------------- |
| /               | Buscar el siguiente archivo |
| ?               | Buscar archivo anterior     |
| n               | Ir al siguiente encontrado  |
| N               | Ir al anterior encontrado   |

### Buscar [archivos](https://yazi-rs.github.io/docs/quick-start/#search-files)

| Clave de enlace | Acción                                                       |
| --------------- | ------------------------------------------------------------ |
| s               | Buscar archivos por nombre usando [fd](https://github.com/sharkdp/fd) |
| S               | Buscar archivos por contenido usando [ripgrep](https://github.com/BurntSushi/ripgrep) |
| Ctrl+s          | Cancelar la búsqueda en curso                                |

### [Clasificación](https://yazi-rs.github.io/docs/quick-start/#sorting)

Para ordenar archivos/directorios utilice los siguientes comandos.

*Observación: ,⇒ aindica presionar la ,tecla seguido de presionar la atecla.*

| Clave de enlace | Acción                                                   |
| --------------- | -------------------------------------------------------- |
| ,⇒m             | Ordenar por hora de modificación                         |
| ,⇒M             | Ordenar por hora de modificación (inversa)               |
| ,⇒c             | Ordenar por tiempo de creación                           |
| ,⇒C             | Ordenar por hora de creación (inversa)                   |
| ,⇒e             | Ordenar por extensión de archivo                         |
| ,⇒E             | Ordenar por extensión de archivo (inversa)               |
| ,⇒a             | Ordenar alfabéticamente                                  |
| ,⇒A             | Ordenar alfabéticamente (inversa)                        |
| ,⇒n             | Ordenar naturalmente                                     |
| ,⇒N             | Ordenar de forma natural (inversa)                       |
| ,⇒s             | Ordenado por tamaño                                      |
| ,⇒S             | Ordenar por tamaño (reverso)                             |
| ,⇒r             | Ordenar aleatoriamente (se necesita la versión nocturna) |

### [Multipestaña](https://yazi-rs.github.io/docs/quick-start/#multi-tab)

| Clave de enlace | Acción                                               |
| --------------- | ---------------------------------------------------- |
| t               | Crear una nueva pestaña con CWD                      |
| 1, 2, ...,9     | Cambiar a la enésima pestaña                         |
| [               | Cambiar a la pestaña anterior                        |
| ]               | Cambiar a la siguiente pestaña                       |
| {               | Intercambiar pestaña actual con pestaña anterior     |
| }               | Intercambiar pestaña actual con la siguiente pestaña |

## [Sabores](https://yazi-rs.github.io/docs/quick-start/#flavors)

Elija una combinación de colores que le guste de nuestro [repositorio de sabores](https://github.com/yazi-rs/flavors) o ¡ [cocine un sabor](https://yazi-rs.github.io/docs/flavors/overview#cooking) !
