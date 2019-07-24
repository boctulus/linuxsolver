# linuxsolver
Linux Solver - Herramienta de diagnóstico para Linux

El programa de diagnóstico y solucionador de problemas de (configuración de) hardware es un script en Bash e intenta ser una solución para todas las distribuciones de Linux. 

"solver" está conformado por un conjunto de módulos que intentan responder preguntas (hipótesis) acerca de porque no funciona una pieza de hardware y en muchos casos se intenta solucionarlos.

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
	cd linuxsolver
	chmod +x solver

Ejecución:

	./solver
	

Se aceptan "pull requests" 

