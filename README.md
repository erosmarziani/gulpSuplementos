# gulpSuplementos


GULP. - Catálogo digital gratuito
===================================

ARCHIVOS
- index.html: página del catálogo.
- productos.csv: plantilla para organizar los productos.

CÓMO SE ADMINISTRARÁ SIN PROGRAMAR
1. Crear una hoja de cálculo en Google Sheets con estas columnas, respetando los nombres:
   nombre | categoria | descripcion | precio | stock | imagen
2. Cargar los productos en filas. Categorías sugeridas:
   Creatinas, Proteínas, Magnesio, Colágeno, Pre-entrenos, Otros.
3. En Google Sheets: Archivo > Compartir > Publicar en la web.
   Elegir la hoja correcta y formato CSV. Copiar el enlace publicado.
4. En index.html, reemplazar el valor vacío de SHEET_CSV_URL por ese enlace.
5. Completar WHATSAPP_NUMBER con el número de WhatsApp de Gulp en formato internacional,
   sin +, espacios ni guiones. Ejemplo de formato argentino: 5492911234567.
6. Subir index.html a un repositorio público de GitHub y activar Settings > Pages
   (Deploy from a branch, rama main, carpeta /root). GitHub mostrará la URL pública.
7. Crear el QR apuntando a esa URL. El QR no cambia cuando se actualizan productos/precios.

NOTAS
- GitHub Pages ofrece hosting estático gratuito. Google Sheets también tiene opción gratuita.
- Para que la web lea la planilla sin iniciar sesión, la hoja debe estar publicada en la web.
- No cargues datos privados. La planilla publicada será accesible públicamente.
- Los productos de ejemplo son ilustrativos: reemplazalos por tu stock real.
- La información sobre suplementos es general; verificar etiquetas, ingredientes y dosis de cada producto.
