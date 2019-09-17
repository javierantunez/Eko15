Datos generales
---------------

El lab entregado cuenta con 2 equipos:
- Windows 10 Enterprise edition
- Kali linux 2019.2 recientemente upgradeado y con algunas herramientas pre instaladas

Instalación
-----------
Las maquinas se encuentran comprimidas en formato zip.
Una vez extraidas, se pueden activar abriendo cada carpeta y abriendo el archivo con extension .vmx.

Las maquinas se generaron con VMWare Workstation Pro 15 y se pueden utilizar con:

	- VMWare workstation pro 15.1.0 o superior (se puede descargar el trial de https://www.vmware.com/products/workstation/workstation-evaluation.html)
	- VMWare fusion 11 o superior (https://www.vmware.com/products/fusion/fusion-evaluation.html)
	- VMWare player free 15.1.0 o superior (se puede descargar de https://my.vmware.com/en/web/vmware/free#desktop_end_user_computing/vmware_workstation_player/15_0)

Recomendamos usar workstation pro/ fusion, dado que si quieren ajustar alguna configuracion del hardware virtual solo puede hacerse con esas versiones.

Una vez instalado VMware e importadas las maquinas se pueden customizar su hardware virtual de acuerdo a la disponibilidad de memoria que tengan.

Si se recibe un mensaje preguntando si la VM fue movida o copiada seleccionar la opción copiado.


Configuraciones de las VM
--------------------------
1- RAM

Por favor cuando importen las VM verifiquen el tamaño de RAM asignado, siempre tratamos de que las VMs esten configuradas con el minimo posible de RAM, tratando de bajar la barrera de entrada para ejecutarlas al mismo tiempo. 

Con la configuracion actual de recursos debería funcionar con 8 GB de RAM.

Es por eso que la performance de alguna puede llegar a ser un poco pobre en algun momento. Si tu equipo cuenta con suficiente RAM, podes probar ampliar los recursos de memoria de las VMs, en lineas generales con 2 GB por VM para clientes/kalis es suficiente.

2- Cores

Todas las maquinas cliente estan configuradas con 1 micro dual core (1x2). 
Todas las maquinas kali estan configuradas con 2 micro dual core (2x2).

Si tu equipo no es al minimo dual core es probable que debas reducir las virtual CPUs a algo acorde a tu hardware.


Networking
----------
Las VMs que se otorgan deben encontrarse en la VMNET 5 para que puedan verse si (esto esta pre configurado en las VMs de esa forma).
El rango de direccionamiento utilizado es IP 192.168.2.0/24 (mascara 255.255.255.0/GW 192.168.2.1)


Informacion de las VM
----------------------

VM Windows 10 Pro 64 Bits
IP: 192.168.2.16 / / DNS: 192.168.2.12
User: User1 – Password: P@ssw0rd 

VM Kali linux 64 Bits
IP: 192.168.2.100 / / DNS: 192.168.2.12
User: root – Password: toor (password que viene por defecto).
