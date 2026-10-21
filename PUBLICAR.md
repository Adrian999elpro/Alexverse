# Publicar versiones de AlexVerse

Repositorio conectado: https://github.com/Adrian999elpro/Alexverse

Catálogo que leen los launchers:
https://raw.githubusercontent.com/Adrian999elpro/Alexverse/main/catalog.json

## Estado inicial
El catálogo contiene las versiones que estaban configuradas en el equipo del creador al conectar GitHub. Las entradas marcadas como plantilla todavía necesitan sus mods. No se publican cuentas, sesiones ni archivos personales.

## Publicar un cambio
1. Crea o actualiza la versión en Modo creador. Conserva su identificador cuando sea una actualización.
2. Exporta el catálogo con esta URL de archivos:
   https://github.com/Adrian999elpro/Alexverse/releases/download/catalogo/
3. Crea una release con la etiqueta catalogo cuando necesites alojar los primeros archivos. En futuras publicaciones edita esa misma release.
4. Adjunta los archivos con nombres hash de la exportación. Conserva los que todavía usa algún pack publicado. El archivo LEEME.txt no es necesario.
5. Cuando los archivos estén disponibles, sube el catalog.json exportado a la raíz de la rama main de este repositorio, reemplazando el anterior. Este paso anuncia la actualización.
6. Los launchers consultan el catálogo al abrir y cada cinco minutos. Puede haber unos minutos de caché de GitHub. Las instalaciones se actualizan con Minecraft cerrado si está activada esa opción.

La publicación sigue siendo manual: editar una versión en el PC no la sube automáticamente. Desde AlexVerse 0.3.1, la sincronización conserva los cambios locales pendientes hasta que se publique el mismo contenido.

## Distribuir el launcher
Comparte AlexVerse-Launcher-0.3.1.exe. Lleva incorporada la URL del catálogo. Puedes adjuntarlo a otra release para que tus usuarios lo descarguen.
