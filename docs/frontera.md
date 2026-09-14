Escribí una regla en el archivo`CLAUDE.md` en la raíz de blog-api. 
La regla es: 
Cuando termines un cambio en este repositorio, hacé vos mismo el commit siguiendo esta regla, sin excepcion.

El mensaje DEBE empezar por la etiqueta `[frontera]`, seguida del nombre del archivo principal que tocaste, y despues la descripción en imperativo

Formato exacto:

    [frontera] <archivo-principal> <descripción>

Ejemplos:

    [frontera] posts.py agregar endpoint de posts destacados
    [frontera] db.py corregir el orden de los resultados

Si el cambio toca varios archivos, usá como `<archivo-principal>` el más relevante del commit.
 
Luego ejecuté una sesión de Claude Code en blog-api, le pedí un cambio y que luego de terminar lo comiteara. El mensaje salió con el prefijo correcto, verificado con `git log --oneline`. 

Luego ejecuté una sesión de Claude code en blog-ai, le pedí un cambio y que luego de terminar lo comiteara. En este caso el comentario del commit con contenta el prefijo [frontera] ya que en el archivo CLAUDE.md de este repositorio no contiene dicha regla. Verificado con git log --oneline


