<img width="2486" height="516" alt="imagen" src="https://github.com/user-attachments/assets/3cca2fbd-58b0-459d-9add-d3203987565b" />

<h2 style="font-size: 2em;"><b>Filebrowser</b></h2>

<p><b>Filebrowser</b> es un administrador de archivos ligero basado en web que proporciona una interfaz limpia para navegar, subir, descargar, editar y gestionar archivos e instancias de tu servidor desde cualquier navegador web.</p>

<h3>📌 ¿Para qué sirve?</h3>
<ul>
  <li><b>Explorador de archivos remoto:</b> Transforma cualquier directorio de tu servidor en una interfaz gráfica accesible desde el navegador.</li>
  <li><b>Gestión completa de archivos:</b> Permite subir, descargar, renombrar, mover, eliminar y editar archivos de texto o código directamente desde la web.</li>
  <li><b>Editor de código integrado:</b> Incluye un editor de texto con resaltado de sintaxis ideal para modificar scripts, archivos de configuración o notas rápidamente.</li>
  <li><b>Gestión de usuarios y permisos:</b> Permite crear múltiples usuarios con permisos específicos (solo lectura, administración o acceso limitado a ciertas carpetas).</li>
  <li><b>Enlaces públicos de descarga:</b> Permite compartir archivos o carpetas con otras personas mediante enlaces temporales con o sin contraseña.</li>
</ul>

<h3>🚀 Uso e información básica del despliegue</h3>
<ul>
  <li><b>Puerto de acceso HTTP:</b> <code>8080</code> (mapeado al puerto interno <code>80</code>)</li>
  <li><b>Acceso Web:</b> <code>http://localhost:8080</code> (o la IP de tu servidor).</li>
  <li><b>Credenciales por defecto:</b>
    <ul>
      <li><b>Usuario:</b> <code>admin</code></li>
      <li><b>Contraseña:</b> <code>admin</code> <i>(Se recomienda cambiarla inmediatamente tras el primer inicio de sesión)</i>.</li>
    </ul>
  </li>
  <li><b>Volúmenes de datos:</b>
    <ul>
      <li><code>./srv:/srv</code> — Carpeta del servidor donde se gestionarán tus archivos.</li>
      <li><code>./filebrowser.db:/database/filebrowser.db</code> — Base de datos SQLite donde se guardan usuarios y configuraciones.</li>
      <li><code>./settings.json:/config/settings.json</code> — Archivo de configuración inicial de la aplicación.</li>
    </ul>
  </li>
</ul>

<hr>
<img width="1792" height="1024" alt="imagen" src="https://github.com/user-attachments/assets/2fe283e0-c059-4aeb-bce9-d11de584fc00" />

<img width="1024" height="559" alt="imagen" src="https://github.com/user-attachments/assets/051bd9c1-c246-42bf-aa75-5fa773c16bfa" />



