Sistema de Fichero ASSOOFS creado e implementado por Julio Machin Ruiz

Estan realizadas las funciones basicas, juntos con los semáforos (MUTEX) y cache.

Al desmontar necesitas hacer dos veces los comandos:
 - rmmod assoofs
 - insmod assoofs.ko 
 - mount -o loop -t assoofs image ~/mnt
