# Web pública de la Dra. Gianmary Miozzi

Esta rama contiene únicamente la web pública compilada, preparada para publicarse en la raíz `/` de Vercel. Muestra el consultorio en Valencia, Carabobo, permite solicitar citas por WhatsApp e incluye una demostración visual del panel con datos ficticios.

La demostración del panel permite recorrer sus secciones, pero no guarda historiales, no crea citas y no se conecta a Google. El código del panel clínico local, historiales, citas locales y credenciales de ejemplo no se incluye en este repositorio público. Las solicitudes de cita no se confirman automáticamente.

En Vercel, importa este repositorio como **Other** y deja vacío el comando de compilación: el repositorio ya contiene `index.html` y `assets/` listos para servir desde la raíz.
