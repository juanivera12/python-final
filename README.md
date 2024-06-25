

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. Creamos una carpeta o directorio: mkdir python-final
3. Entramos en ella:
4. cd python-final
5. Iniciamos el repositorio:
git init
6. Creamos un archivo:
touch finales.py
7. Abrimos VSC:
code .
8. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
python -V
python3 -V

VERSION PYTHON 3.12.4

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

El pip es el sistema oficial de gestión de paquetes para Python. Te permite instalar, actualizar y desinstalar paquetes de software, que son colecciones de módulos o bibliotecas de código para el lenguaje de programación Python
Nuevas Funcionalidades: Cada nueva versión de pip puede incluir características y mejoras que facilitan la gestión de paquetes y hacen que trabajar con efectividad.
Corrección de Errores: Las actualizaciones de pip suelen incluir correcciones de errores que afectan la instalación, actualización o desinstalación de paquetes.
Mejoras de Seguridad: Las nuevas versiones de pip pueden abordar vulnerabilidades mediante parches de seguridad. Usar una versión desactualizada podría exponerte a riesgos de seguridad.
Compatibilidad: Actualizar pip asegura que sea compatible con las últimas versiones de Python y otros sistemas. Las versiones antiguas pueden no funcionar correctamente con las nuevas versiones de Python o de los paquetes.
Mejoras de Rendimiento: Las actualizaciones pueden incluir optimizaciones que hacen que la instalación y actualización de paquetes sea más rápida y eficiente.

13. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

14. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
