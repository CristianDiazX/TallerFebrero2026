<h1 align="left">Taller Febrero 2026</h1>

###

<p align="left">Cristian Diaz y Mattias Sánchez</p>

###

<h2 align="left">Topología</h2>

###

<p align="left">Centos01 = 192.168.10.11<br>Centos02 = 192.168.10.12<br><br>Ubuntu01 = 192.168.10.21<br>Ubuntu02 = 192.168.10.22<br><br>Bastion = 192.168.10.1</p>

###

<h2 align="left">Requisitos Previos</h2>

###

<p align="left">Tener ansible descargado e instalado en los equipos.<br>Configurar la ip de todos los equipos correctamente en el inventario y maquinas virtuales<br>Tener una copia del repositorio<br>Descargar una copia del repositorio al bastión</p>

###

<h2 align="left">Como Ejecutar</h2>

###

<p align="left">Desde el Bastion:<br><br>Ejectuar el comando:<br><br>ansible-galaxy install -r .collections/requirements.yml<br><br>ansible-playbook -i inventory/hosts.ini site.yml</p>

###

<img align="left" height="200" src="https://i.imgflip.com/65efzo.gif"  />

###
