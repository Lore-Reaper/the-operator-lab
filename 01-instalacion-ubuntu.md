
Antes de empezar

He decidido utilizar Ubuntu Server 24.04 LTS porque es una distribución muy extendida en empresas, tiene soporte durante varios años y prácticamente toda la documentación que encuentro en Internet está orientada a Ubuntu o Debian.

La idea es montar un servidor sencillo pero que pueda ir creciendo poco a poco.

No voy a instalar veinte servicios el primer día. Prefiero entender cada paso antes de pasar al siguiente.

Hardware

En mi caso utilizaré una máquina virtual.

La configuración es la siguiente.

Recurso	Valor
CPU	2 núcleos
RAM	4 GB
Disco	40 GB
Red	Adaptador puente
Instalación

Durante la instalación prácticamente dejo todas las opciones por defecto.

La única diferencia es que marco la instalación de OpenSSH.

Prefiero poder administrar el servidor desde otro equipo en lugar de estar siempre delante de la máquina virtual.

