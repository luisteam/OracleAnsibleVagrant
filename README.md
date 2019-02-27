# OracleAnsibleVagrant
Instala cualquier version de Oracle que quieras, nesecitas:

los .zip de Oracledatabase y guardarlos en: OracleDatabase/version


vagrant up <- y dejar ocurrir la magia

El repositorio trae un archivo de variables para configurar el usuario.

scripts/setPassword.sh 

ORACLE_PWD="oracle"

Info: https://dzone.com/articles/creating-an-oracle-database-vagrant-box

Es necesario tener FLASH PLAYER en el navegador para usar EM.

Cuando termina la instalacion:

    oracle-12102-vagrant: ORACLE PASSWORD FOR SYS, SYSTEM AND PDBADMIN: 4wD27RfXDMs=1
    oracle-12102-vagrant: INSTALLER: Installation complete, database ready to use!

Nos da la contraseña temporal para los usuarios si no cambias la variable.
