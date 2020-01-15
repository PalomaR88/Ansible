# Ansible
Herramienta que permite automatizar la creación de máquinas.

### Introducción
#### Programando infraestructura en la nube
Ansible está muy relacionado con la nube.

Conflicto entre desarrollo y sistemas. Contra ello **DEVOPS**, una metodología dónde se llega un solución. Esta forma de trabajar, uno de esos puntos es tener **escenarios replicables**. Porque los escenarios donde tienen que trabajar los desarrolladores tiene que ser lo más parecido al escenario de producción. Además, con determinadas herramientas no solo se crean escenarios replicables sino que también se **automatiza la configuración**.

Software de automatización que permite:
- Creacion de infraestructura. MV, redes o almacenamiesto sore un gestor de infraestructuras: openStac, Amazon...
- Configuración de la infraestructura. 

Realmente no hay diferencia entre la creación de infraestructura y la configuración de esta.

**Herramientas**
- Lenguajes de programación.
- Software de orquestación.
- Software de gestión de la configuración.

**Orquestación**:
- Vagrant (escenarios simples). Vagrant puede crear máquinas en VirtualBox, lirvirt y openStack o Amazon. Pero no es lo recomendable para escenarios complejos.
- Cloudformation (AWS) "el Heat de Amazon". 
- Heat (OpenStack) Herramienta de orquestación particular para openStack, la nativa. Toda la funcionalidad de openStack está aquí. El drive que Terraform tiene para openStack puede ser que no pueda utilizar todas las herramientas que tiene OpenStack, con Heat si.
- Terraform. Herramienta de los desarrolladores de Vagrant pero con escenarios complejos. 
- Juju. De Ubuntu, no tiene éxito.

**Gestión de la configuración**
- Puppet. Esta y la posterior son las que más se han utilizado. Esta es capaz de lanzar una máquina y guarda la configuración de esa máquina para que se puedan crear todas las máquinas que quieras con esa receta para que sean todas iguales. Pero además, algo que realizas en una máquina puedes hacerlo en todas las máquinas que se quiera.
- Chef
- Ansible. Desde un ordenador te puedes conectar a otras máquinas, por ssh, y desde ahí lanzar código. De la forma que se haría manualmente, lo hace manualmente. En Ansible lo que se hace es escribir el resultado y ese mismo script se puede ejecutar varias veces. Es capaz de ver el estado de la máquina y hacer las cosas necesarias y las que no, no lo hace. 
- Salt (saltStack). Como ansible.


#### Presentación de ansible

#### Introducción a ansible

### Recurso útiles

#### YAML Syntax
#### Ansible examples

### Demo

#### Instalación de apache2+mariadb+wordpress

### Ejercicios

