# Ansible-Varios y despliegue-total
## En este reposito estan las practicas con Ansible y el despligue total con:
1. Aprovisionamiento con Ansible 
   - Creación-Configuracion de usuario
   - Aprovisionamiento de las carpetas y ficheros necesarios
   - Configuracion de los ficheros necesarios para el posterior despliegue con Jenkins
2. Despliegue con Jenkins mediante las etapas de: 
   - Recogida del Código y Aplicativo desde Repositorio Git
   - Realización de pruebas con JaCoCo, test y Pitest de Gradle
   - Prueba de analisis con Sonarqube
   - Contrucción de la App y empaquetado de imagen dinde se despleguará además de subirla a nuestro Registry inseguro de Gitlab
   - Test de Seguridad de imagen con Trivy 
   - Despligue final de la App contenida en la imagen archivada anteriormente en el host remoto utilizando ssh y llave cifrada
