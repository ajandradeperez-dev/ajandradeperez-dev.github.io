# ajandradeperez-dev.github.io

Este repositorio solo sirve `/.well-known/assetlinks.json` en la raíz del dominio.

Android lo pide para verificar que la app **CiberLab** (`io.github.ajandradeperez.estudio`, el APK de
[estudio](https://github.com/ajandradeperez-dev/estudio)) pertenece a este sitio, y así abrirla a pantalla
completa, sin barra de dirección (Trusted Web Activity).

- La huella SHA-256 es la del certificado con que se firma el APK. Es **pública** por diseño: no es una clave.
- `.nojekyll` hace que GitHub Pages publique la carpeta `.well-known` (Jekyll ignora las que empiezan con punto).
- La app vive en <https://ajandradeperez-dev.github.io/estudio/>.
