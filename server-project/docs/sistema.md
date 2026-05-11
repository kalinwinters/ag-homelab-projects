# 💿Sistema operativo

Cuando se habla de servidores y ecosistemas de servidores, lo que se nos viene a la mente de inemediato, LINUX, sin embargo 
existen distribuciones espcializadas para ciertos casos y para ciertos requerimientos de hardaware.

Siendo esta la eleccion mas importante dentro de todas las que se tomaran. Se barajan varias opciones para este fin:
<li>Fedora</li>
<li>Ubuntu server</li>
<li>Red Hat</li>
<li>RockyLinux</li>
<li>AlmaLinux</li>
<li>CentOS</li>
<li>Debian</li>
<br>
Sin embargo y debido a que estamos en un contexto de un PC viejo, muchas de estas opciones se descartan, por lo que, la opcion que nos da mas ventajas a largo plazo es (en especial para el editor):

### Debian

Usar Debian, tanto para un servidor personal, serio o empresarial, nos da una amplia gama de ventajas y beneficios:

<li>Estabilidad extrema: Debian prioriza paquetes muy probados</li>
<li>Bajo consumo de recursos: usa menos RAM, menos procesos en segundo plano, mejor rendimiento en hardware antiguo</li>
<li>Seguridad sólida: actualizaciones de seguridad constantes, repositorios muy controlados, pocos servicios activos por defecto</li>
<li>Instalación minimalista: sin entorno gráfico, sin servicios innecesarios</li>
<li>Actualizaciones conservadoras: no cambia todo constantemente, mantiene versiones estables</li>

---
## Tipo de instalacion

Tanto si se ha usado o no un servidor de linux, la filosofia es "Lo minimo indispensable", por lo que lo ideal seria instalar Debian sin escritorio/entorno grafico y dejarlo solo como una shell para la cual realizar los comandos de instalacion, monitoreo y pruebas con herramientas.

Sin embargo, para que esto sea una experiencia mas amigable para aquellos no tan iniciados con servidores linux 
(como el editor), cambiaremos un poco los parametros. Debian Linux viene por defecto con la instalacion del entorno
grafico GNOME, el cual es popular en la comunidad al igual KDE plasma, no obstante, es muy pesado y
debido a la naturaleza de los componentes que tenemos a nuestra disposicion, no nos es muy util, para eso usaremos XFCE, un entorno ultra ligero que se destaca por:

* Liviano
* Estable
* Fácil de usar
* Apariencia “clásica”
