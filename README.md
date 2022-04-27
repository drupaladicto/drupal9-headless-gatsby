Repositorio Drupal 9 Headless con Gatsby
========================================

# Contenido:
1. Proyecto Gatsby con lando listo para utilizar
2. Proyecto Drupal 9 con BD Umami Magazine con lando listo para utilizar

INSTRUCCIONES
=============
1.-Instalar lando en tu SO
  Ver video: https://bit.ly/3xUGtbO

2-.Clonar el repositorio 
  git clone https://github.com/drupaladicto/drupal9-gatsby-lando.git

3.-Arrancar cada proyecto por separado
  cd PROYECTO
  lando start 

4.-En el proyecto drupal, completar instalación:
  - Copia de base de datos lista y Settings.php en la carpeta Extras
  - Para descargar las dependencias de Drupal ejecutar:
      lando composer update
  - Para importar la base de datos, colocarte en la carpeta extras y ejecutar:
      lando db-import NOMBRE-DEL-sql
  - Para asegurarte de que todo funcione, ejecutar:
      lando rebuild

CURSO DRUPAL 9 HEADLESS CON GATSBY Y LANDO
  Ver video https://bit.ly/3OGh3Vc
  
Corrección de posible error con Lando:
  Ver video: https://bit.ly/3OzCxmZ  

NOTA:
  Ambos proyectos Gatsby y Drupal funcionan independientemente,
  para facilitar su adaptación con otras versiones de Drupal.
