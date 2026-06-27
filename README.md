# Tarraga Sole Asociados SCP - web estática

Web estática preparada para publicarse gratis con GitHub Pages.

## Archivos principales

- `index.html`: página principal.
- `styles.css`: estilos visuales y diseño responsive.
- `script.js`: menú móvil, año automático y animaciones suaves.
- `aviso-legal.html`: aviso legal orientativo con datos pendientes.
- `privacidad.html`: política de privacidad orientativa con datos pendientes.
- `CNAME`: dominio personalizado configurado como `tarragasoleasocidos.com`.
- `robots.txt` y `sitemap.xml`: archivos básicos para buscadores.
- `assets/`: logotipo, favicon y patrón gráfico.

## Publicación gratuita con GitHub Pages

1. Crea una cuenta en GitHub.
2. Crea un repositorio público, por ejemplo `tarraga-sole-web`.
3. Sube todos estos archivos a la raíz del repositorio.
4. En GitHub, entra en `Settings` -> `Pages`.
5. En `Build and deployment`, elige `Deploy from a branch`.
6. Selecciona la rama `main` y la carpeta `/root`.
7. Guarda. GitHub generará una URL gratis del tipo `https://usuario.github.io/tarraga-sole-web/`.

## Dominio .com

El archivo `CNAME` deja preparada la web para `tarragasoleasocidos.com`, pero para que funcione ese dominio hay que registrarlo y configurar DNS. Si el dominio correcto es `tarragasoleasociados.com`, cambia también:

- `CNAME`
- `robots.txt`
- `sitemap.xml`
- las etiquetas `og:url` de `index.html`
- el correo de contacto si se quiere usar el dominio corregido

## Pendiente antes de publicar

- Revisar si el dominio elegido está escrito correctamente.
- Añadir correo real, teléfono y dirección del despacho.
- Completar las descripciones de Rosa Maria Sole Molina y Alberto Tarraga Carmen.
- Revisar aviso legal y privacidad con los datos reales del titular.
- Sustituir el correo `contacto@tarragasoleasocidos.com` cuando exista el buzón definitivo.
