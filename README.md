# Plantilla para el proyecto web

Este repositorio es una plantilla para elaborar el proyecto web de la asignatura Proyectos para la web. 

## Recomendaciones para el flujo de trabajo

- Designad a un miembro del grupo como responsable de la gestión del repositorio (en adelante _admin_)
- Cuando empecéis a trabajar en el contenido de un apartado, 
    1. decidid qué subsecciones tendrá cada documento;
        + (lo más lógico sería que acordéis un esquema para la unidad en la que estás trabajando durante alguna de vuestras reuniones _en persona_)
    2. introducid ese esquema en el/los documento(s);
        + (esto podría ser una tarea que realice el admin de vuestro grupo, para evitar conflictos entre versiones en este punto) 
    3. estableced quién redactará cada parte/subsección del esquema.
    
    Así es más fácil que GitHub sea capaz de resolver los conflictos por sí mismo
- Cuando estéis trabajando individualmente en la(s) parte(s) que os corresponden, 
    1. cread un nuevo branch, por ejemplo `cap-1.2.3` para trabajar el subapartado 1.2.3 de vuestro esquema (que habréis decidido y definido en una reunión del equipo, como se ha detallado en el punto anterior);
    2. realizad vuestras ediciones y commits en ese branch;
    3. cuando ese trabajo (el subapartado 1.2.3) esté listo para ser revisado por el resto de compañeros, haced un pull request en vuestro repositorio de grupo;
        + (debatid en el pull request, y seguid haciendo cambios y commits en el branch, hasta que estéis satisfechos con el contenido)
    4. cuando todos estéis de acuerdo en que ese contenido está finalizado y listo para ser incluido en el trabajo, haced merge del pull request (preferiblemente, decidid que sea sólo el usuario admin quien haga los merges). En este momento el contenido del subapartado 1.2.3 estará incluido en el branch principal o master de vuestro proyecto;
    + eliminad el branch de trabajo `cap-1.2.3`

Recordad que este trabajo, aunque lo realicemos mediante texto plano y estemos trabajando sobre fragmentos breves cada vez, tiene que cumplir con las [Normas de presentación de trabajos escritos](https://alud.deusto.es/mod/resource/view.php?id=123494) tal y como exige la universidad, y tiene que estar redactado utilizando [Markdown](https://github.com/DeustoPWEB/pweb2017/blob/master/markdown.md) (a través de un editor de texto plano, para vuestra comodidad) tal y como exigen los requerimientos de esta asignatura.

No caigáis en la tentación de trabajar "fuera" de Sublime/GitHub (por ejemplo, en Word o Google Docs) y luego, de vez en cuando, volcar el trabajo realizado en algún otro sitio en vuestro repositorio. El proceso de trabajo con GitHub es parte del aprendizaje de esta asignatura.

Por supuesto, si tenéis cualquier duda a lo largo de vuestra elaboración del proyecto con GitHub, ya sea durante alguna reunión del equipo o cuando estéis trabajando individualmente, **por favor comunicadlo** a través de un issue bien en vuestro repositorio de equipo o incluso en el [repositorio de la asignatura](https://github.com/DeustoPWEB/pweb2017/issues) (si es alguna cuestión más general), mencionándome con una @ (@mberasategi, para que pueda recibir una notificación y atender vuestra consulta).
