# JVS · Mi Agenda Estratégica

Aplicación web estática para gestionar tareas mediante la matriz de Eisenhower y planificar obligaciones recurrentes por mes.

## Publicación en GitHub Pages

1. En GitHub, crea un repositorio llamado `jvs-agenda-estrategica` (público para usar GitHub Pages en cuentas gratuitas; comprueba las condiciones de tu plan).
2. Sube a la **raíz del repositorio** los archivos `index.html` y `.nojekyll` de esta carpeta.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`. Guarda.
5. Tras publicarse, abre `https://TU-USUARIO.github.io/jvs-agenda-estrategica/`.

## Datos y privacidad

- El repositorio contiene solo el código de la aplicación; **no contiene tus tareas**.
- Las tareas se almacenan en `localStorage`, exclusivamente en el navegador y origen web donde se utilice la aplicación.
- El almacenamiento del HTML local y el de la web publicada son **independientes**. Exporta una copia JSON desde la versión local e impórtala en la web si quieres trasladar los datos.
- La información **no se sincroniza** entre dispositivos, navegadores ni perfiles. Exporta periódicamente una copia de seguridad.
- No subas tus archivos JSON de datos personales al repositorio. Si el repositorio es público, cualquiera puede acceder al código y a la interfaz.
- Si necesitas sincronización y acceso privado, hace falta una segunda fase con autenticación y almacenamiento remoto (por ejemplo, Supabase o Firebase), con reglas de acceso configuradas correctamente.

## Desarrollo local

Abre `index.html` en un navegador moderno. No requiere compilación, instalación ni dependencias externas.
