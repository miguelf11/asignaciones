Symfony 2.7

## How to execute local in UNIX

Requisitos
- PHP >5.5
- Composer - https://getcomposer.org/
- MySQL
- Instalar ElasticSearch (recomendada versión 1.75 ya que el bundle que se usa tiene problemas con versiones > 2)..

Steps: 

- 1. Clone the project
- 2. Open the terminal and go to the path of the project and execute
- ```composer install```




Gestionar los permisos de app/cache y app/log:
http://symfony.es/documentacion/como-solucionar-el-problema-de-los-permisos-de-symfony2/

# Reiniciar elasticsearch
sudo /etc/init.d/elasticsearch restart