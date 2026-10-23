# perche-dev

Investigacion formulario

Cuando envié el formulario me di cuenta de que la información que escribí apareció en la barra de arriba, después del signo ?

También vi que los espacios salen con +, las tildes aparecen con unos códigos  que empiezan por % y la arroba del correo puede aparecer como %40.

Las opciones que no marqué no aparecieron en la dirección.

Esto pasa porque el formulario está usando get y por eso los datos se muestran en la URL.

Por eso no se debería usar get para formularios con contraseñas, porque esa información podría quedar visible o guardada en el historial. Para algo así sería mejor usar post.

