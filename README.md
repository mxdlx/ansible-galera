# MariaDB Galera
Estoy testeando como armar un cluster galera y los roles que encontré resultaron demasiado complejos. Este rol es extremadamente simple y está basado en el trabajo de [Adfinis SyGroup AG](https://github.com/adfinis-sygroup) que pueden encontrar [aquí](https://github.com/adfinis-sygroup/mariadb-ansible-galera-cluster). Por el momento solo ejecuté y probé este rol sobre Centos 7.

## Requerimientos
Este rol asume que existe un grupo de hosts en el inventario de Ansible llamado "galera".

## Variables
Es necesario definir la variable galera\_sst\_pass en el playbook a utilizar.

## TODO
Este deploy asume que el servicio escucha en una única y principal interfaz de red. Esto podría no ser así para algunos usuarios.
