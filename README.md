<h1>Vagrant LAMP</h1>

<p>Mi entorno de desarrollo LAMP (Linux, Apache, MySQL, PHP) para Vagrant.</p> 

<p>Se trata de una máquina vagrant basada en <a href="https://github.com/luiscavero92/myMini">myMini</a> de luiscavero92, que a su vez, está basada sobre el proyecto PHP <a href="https://github.com/panique/mini">Mini</a>. Se trata de un servidor web, que incluye una plantilla llamada "Debut" la cual sigue el patrón MVC en PHP.</p>
<h2>Requerimientos</h2>
<ul>
  <li><a href="https://www.virtualbox.org">Virtualbox</a></li>
  <li><a href="https://www.vagrantup.com">Vagrant</a></li>
</ul>

<h2>Instalación</h2>
<ol>
  <li>Descargar los archivos del directorio "_vagrant" a la carpeta de trabajo.</li>
  <li>Nos situamos con el intérprete de comandos en la carpeta.</li>
  <li>Escribimos  <code>vagrant up</code></li>
</ol>
<p> Y no hay más! </p>

<h2>Características</h2>
<p><b> Incluye las actualizaciones más recientes! </b></p>
<ul>
  <li>Box Ubuntu 14.04 trusty 64</li>
  <li>Apache 2.4</li>
  <li>PHP 7</li>
  <li>MySQL 5.7</li>
  <li>Composer con
    <ul>
      <li>Plates</li>
      <li>Dice</li>
      <li>Kint</li>
      <li>Phpmailer</li>
    </ul>
  </li>
  <li>Última versión de Adminer</li>
</ul>

<h2>Configuración y uso</h2>
<ul>
  <li>IP: <code>192.168.33.10</code></li>
  <li>Adminer: <code>IP/adminer</code></li>
  <li>Usuario MySQL: <code>root</code></li>
  <li>Contraseña MySQL: <code>123</code></li>
</ul>
<p> La configuración es susceptible de cambio en los ficheros "vagrantfile" y "config.sh". También aclarar que las carpetas que comienzan por "_" pueden ser borradas una vez haya sido instalada la aplicación. Enjoy!</p>
