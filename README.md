# perche-dev

Investigacion formulario

Cuando envié el formulario me di cuenta de que la información que escribí apareció en la barra de arriba, después del signo ?

También vi que los espacios salen con +, las tildes aparecen con unos códigos  que empiezan por % y la arroba del correo puede aparecer como %40.

Las opciones que no marqué no aparecieron en la dirección.

Esto pasa porque el formulario está usando get y por eso los datos se muestran en la URL.

Por eso no se debería usar get para formularios con contraseñas, porque esa información podría quedar visible o guardada en el historial. Para algo así sería mejor usar post.

Hoy trabajé en la página de Parche Dev 2026. Primero organicé los archivos del proyecto y fui creando cada una de las páginas que pedía la actividad.

En la página de inicio agregué la información principal del evento. Después hice la agenda usando una tabla, donde aprendí a utilizar colspan y rowspan para organizar las dos salas y los horarios.

También hice la página de los ponentes. A cada uno le agregué una imagen, una pequeña descripción y enlaces para poder ir directamente a sus charlas dentro de la agenda.

Después realicé el formulario de inscripción. Utilicé diferentes tipos de campos como texto, correo, teléfono, radio, checkbox, select y textarea. También agregué algunas validaciones para que no se pueda enviar el formulario si faltan los campos obligatorios.

Al probar el formulario pude ver cómo los datos aparecen en la URL cuando se utiliza el método get. También hice la página de confirmación que aparece después de enviar el formulario.

Luego realicé el código de conducta, donde agregué un índice para poder ir a cada parte de la misma página y enlaces para volver al inicio del contenido.

Durante la actividad también tuve algunos errores con Git y GitHub al momento de hacer los push, pero los fui solucionando y haciendo los commits correspondientes a cada parte del proyecto.

Por último revisé los archivos, corregí algunos errores del HTML y completé el README con la información del proyecto, algunas decisiones que tomé y lo que aprendí durante la actividad.

Pruebas con Lighthouse

Revisé las páginas principales en modo celular usando Lighthouse.

Inicio

![Lighthouse inicio](img/lighthouse/inicio.png)

Agenda

![Lighthouse agenda](img/lighthouse/agenda.png)

Inscripción

![Lighthouse inscripción](img/lighthouse/inscripcion.png)