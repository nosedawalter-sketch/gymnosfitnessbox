GYMNOS FITNESS BOX - PANEL EDITABLE

Se agregó:
- /admin.html para editar portada, contacto, actividades, horarios y fotos.
- /api/content para guardar/publicar el contenido.
- /api/upload para subir fotos.
- La página pública carga automáticamente los cambios guardados.

Para activarlo en Vercel hacen falta dos variables del proyecto:
1) BLOB_READ_WRITE_TOKEN: se crea al conectar un Vercel Blob Store.
2) ADMIN_PASSWORD: la clave privada que usará Gymnos para entrar al panel.

Las imágenes originales siguen referenciadas en /assets; hay que conservar la carpeta assets del sitio actual al publicar esta versión.
