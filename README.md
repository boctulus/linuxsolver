# linuxsolver
Linux Solver - Herramienta de diagnóstico para Linux

Programa de diagnóstico y solucionador de problemas de (configuración de) hardware escrito en Bash conformado por un conjunto de módulos que intentan responder preguntas (hipótesis) acerca de porque no funciona una pieza de hardware y busca de solucionarlos.


Módulos disponibles:

    performance
    video
    sound
    bluetooth
    wi-fi
    ethernet
    touchpad


Instalación:

	git clone https://github.com/boctulus/linuxsolver.git
    sudo ln -s $(pwd)/solver /usr/bin
	cd linuxsolver


Ejecución:

	./solver
	

Se aceptan "pull requests" 

