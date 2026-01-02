[readme_file.txt](https://github.com/user-attachments/files/24412602/readme_file.txt)
==============================================
SISTEMA DE SORTEO DÍA DE REYES v1.1
#AlquimiaAlHorno
==============================================

ARCHIVOS INCLUIDOS:
-------------------
1. index.html - Sistema de sorteo con registro de participantes
2. test-empanadas.html - Test de personalidad para saber qué empanada eres
3. README.txt - Este archivo de instrucciones

CREDENCIALES DE ADMINISTRADOR:
----------------------------
Usuario: alquimia
Contraseña: six10stone

CÓMO SUBIR A TU SERVIDOR:
-----------------------
1. Conecta por FTP a tu servidor (FileZilla, Cyberduck, cPanel)
2. Sube ambos archivos HTML a la carpeta public_html (o www)
3. Accede desde tu dominio:
   - https://tudominio.com/index.html (Sorteo)
   - https://tudominio.com/test-empanadas.html (Test)

REQUISITOS DEL SERVIDOR:
-----------------------
- Servidor web (Apache, Nginx, o cualquier hosting)
- Soporte para HTML5
- NO requiere PHP, MySQL ni bases de datos
- NO requiere certificado SSL (pero es recomendado)
- NO requiere Node.js ni instalaciones adicionales

FUNCIONAMIENTO:
--------------
- Los datos se almacenan usando la API de Storage del navegador
- Los datos son compartidos entre todos los usuarios
- Funciona 100% en el navegador, sin backend
- Sistema completamente estático

CARACTERÍSTICAS DEL SORTEO:
--------------------------
✅ Registro de participantes (Nombre, Email, Teléfono, Tipo de Empanada)
✅ Selección de números del 1-500
✅ Solo muestra números disponibles
✅ Validación de usuarios únicos (no permite duplicados)
✅ Panel administrativo protegido
✅ Exportación a CSV
✅ Eliminación individual y masiva de registros
✅ 4 premios (uno por cada tipo de empanada)
✅ Confirmación por WhatsApp automática

CARACTERÍSTICAS DEL TEST:
------------------------
✅ 6 preguntas divertidas e irónicas
✅ 4 resultados tipo empanada (Pollo, Cajeta, Nutella, Champiñones)
✅ Personalización con nombre del participante
✅ Resultados compartibles
✅ Diseño instagrameable
✅ Botón de reinicio

CONFIGURACIÓN:
-------------
📱 Para cambiar el número de WhatsApp:
   - Busca "527201860659" en ambos archivos HTML
   - Reemplaza por tu número (formato: código país + número sin espacios)
   - Ejemplo: 521234567890 (para México)

🎨 Para cambiar colores:
   - Busca en la sección <style> de cada archivo
   - Colores principales:
     * #667eea (morado principal)
     * #764ba2 (morado oscuro)
     * #ffd700 (dorado)
     * #f093fb (rosa)

ACCESO AL PANEL ADMIN:
---------------------
1. Abre index.html en tu navegador
2. Haz clic en el botón "🔐 Admin" (esquina superior derecha)
3. Ingresa credenciales:
   - Usuario: alquimia
   - Contraseña: six10stone
4. Tendrás acceso a:
   - Tabla completa de participantes
   - Estadísticas en tiempo real
   - Búsqueda y filtros
   - Exportación a CSV
   - Eliminación de registros
   - Restablecer todo a cero

FLUJO DEL USUARIO:
-----------------
1. Usuario hace el TEST (test-empanadas.html)
2. Descubre qué tipo de empanada es
3. Hace clic en WhatsApp y obtiene link al SORTEO
4. Entra al SORTEO (index.html)
5. Registra sus datos + tipo de empanada
6. Selecciona un número del 1-500
7. Confirma por WhatsApp
8. ¡Listo! Ya está participando

PREMIOS:
--------
Habrá 4 ganadores, uno por cada tipo de empanada:
🍗 Empanada de Pollo
🍯 Empanada de Cajeta
🍫 Empanada de Nutella
🍄 Empanada de Champiñones

IMPORTANTE - SEGURIDAD:
---------------------
⚠️ Haz backup antes de eliminar registros
⚠️ El botón "Restablecer a cero" es IRREVERSIBLE
⚠️ Guarda la contraseña de admin en un lugar seguro
⚠️ Los datos persisten entre sesiones
⚠️ Cada participante puede registrarse solo UNA vez

SOLUCIÓN DE PROBLEMAS:
--------------------
❌ Si no guarda los registros:
   - Verifica que el navegador permita cookies/storage
   - Abre la consola (F12) y busca errores
   - Asegúrate de que el sitio sea HTTPS (recomendado)

❌ Si no aparece el botón Admin:
   - Verifica que el archivo esté completo
   - Recarga la página (Ctrl + F5)
   - Limpia caché del navegador

❌ Si no funciona en móvil:
   - Asegúrate de que sea HTTPS (no HTTP)
   - Verifica que el navegador sea moderno (Chrome, Safari, Firefox)

❌ Si no se elimina un registro:
   - Abre la consola del navegador (F12)
   - Intenta eliminar de nuevo
   - Verás logs detallados del proceso
   - Si persiste, contacta soporte

HOSTING RECOMENDADOS (GRATIS):
----------------------------
1. GitHub Pages - github.com/pages
2. Netlify - netlify.com (RECOMENDADO ⭐)
3. Vercel - vercel.com
4. Cloudflare Pages - pages.cloudflare.com

ESTRUCTURA DE ARCHIVOS EN SERVIDOR:
---------------------------------
public_html/
│
├── index.html          (Sorteo - Página principal)
├── test-empanadas.html (Test de personalidad)
└── README.txt          (Este archivo - opcional)

URLs DE ACCESO:
--------------
https://tudominio.com/index.html          → Sorteo
https://tudominio.com/test-empanadas.html → Test

Para hacer index.html la página principal:
- Renombra index.html como el nombre que use tu servidor
- Usualmente: index.html, index.php, default.html

VERSIÓN: 1.1
FECHA: Enero 2026
DESARROLLADO PARA: #AlquimiaAlHorno

SOPORTE:
--------
Para dudas o problemas:
1. Revisa la consola del navegador (F12)
2. Verifica que los archivos estén completos
3. Asegúrate de tener las credenciales correctas

¡Éxito con tu sorteo de Día de Reyes! 👑🎁✨
