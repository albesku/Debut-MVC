<h1>Debut MVC</h1>

<p><b>Debut MVC</b> es una aplicación PHP simple basada en el patrón arquitectónico MVC. <b>Debut MVC</b> ofrece una base para desarrollar blogs sin mucha complejidad, siendo muy fácil de instalar y configurar.</p> 

<p><b>Debut MVC</b> está basado sobre el proyecto PHP original <a href="https://github.com/panique/mini">Mini</a> con algunas modificaciones añadidas.</p>

<h2>Características</h2>
<ul>
  <li>Usa sólo código PHP nativo.</li>
  <li>Bien comentado para su entendimiento, siguiendo el estilo estandar PSR4.</li>
  <li>Utiliza la nomenclatura StudlyCaps en los nombres de los archivos de clases.</li> 
  <li>Utiliza la nomenclatura camealCase en los nombres de los métodos.</li>
  <li>Composer configurado con:
    <ul>
      <li>El motor de plantillas <a href="http://platesphp.com/">Plates</a>.</li>
      <li>El inyector de dependencias <a href="https://github.com/Level-2/Dice">Dice</a>.</li>
      <li>El depurador de código <a href="https://github.com/raveren/kint">Kint</a>.</li>
      <li>La clase <a href="https://github.com/PHPMailer/PHPMailer">PHPMailer</a>.</li>
    </ul>
  </li>
  <li>Última versión del administrador de base de datos <a href="https://www.adminer.org">Adminer</a></li>
</ul>

<h2>Requerimientos</h2>
<ul>
  <li>PHP 5.3.0+</li>
  <li>MySQL</li>
</ul>

<h2>Instalación</h2>
<p>La instalación es 100% automática si usamos <b>Vagrant</b>!</p>
<ol>
  <li>Descargar los archivos del directorio "_vagrant" a la carpeta de trabajo.</li>
  <li>Nos situamos con el intérprete de comandos en la carpeta.</li>
  <li>Escribimos  <code>vagrant up</code></li>
</ol>
<p> Y no hay más! </p>

<h2>Configuración y uso</h2>
<ul>
  <li>IP: <code>192.168.33.10</code></li>
  <li>Adminer: <code>IP/adminer</code></li>
  <li>Usuario MySQL: <code>root</code></li>
  <li>Contraseña MySQL: <code>123</code></li>
</ul>
<p> La configuración es susceptible de cambio en los ficheros "vagrantfile" y "config.sh". También aclarar que las carpetas que comienzan por "_" pueden ser borradas una vez haya sido instalada la aplicación. Enjoy!</p>
