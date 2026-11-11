<h2 style="font-size: 2em;"><b>Portainer</b></h2>

<p><b>Portainer</b> es una plataforma ligera de gestión visual con interfaz web que permite administrar, monitorear y desplegar contenedores, imágenes, volúmenes y redes de Docker de forma sencilla sin necesidad de usar únicamente la terminal.</p>

<h3>📌 ¿Para qué sirve?</h3>
<ul>
  <li><b>Gestión gráfica:</b> Permite iniciar, detener, reiniciar y eliminar contenedores con un par de clics.</li>
  <li><b>Monitoreo en tiempo real:</b> Facilita la consulta de registros (logs), estadísticas de consumo de CPU/RAM y la consola interna de cada contenedor.</li>
  <li><b>Despliegue de Stacks:</b> Soporta la creación y ejecución de archivos <code>docker-compose</code> directamente desde su panel web.</li>
  <li><b>Control de recursos:</b> Simplifica la administración de volúmenes de almacenamiento y redes virtuales de Docker.</li>
</ul>

<h3>🚀 Uso e información básica del despliegue</h3>
<ul>
  <li><b>Puerto de acceso seguro (HTTPS):</b> <code>9443</code></li>
  <li><b>Acceso Web:</b> <code>https://localhost:9443</code> (o la IP de tu servidor).</li>
  <li><b>Volumen de datos:</b> Asigna un volumen persistente (<code>portainer_data</code>) para conservar la configuración y los usuarios creados.</li>
  <li><b>Socket de Docker:</b> Requiere acceso a <code>/var/run/docker.sock</code> para interactuar directamente con el motor de Docker del sistema.</li>
</ul>

<hr>

<img width="1024" height="559" alt="imagen" src="https://github.com/user-attachments/assets/3083215f-3e65-4d50-81c0-4b2c8f831a8f" />
