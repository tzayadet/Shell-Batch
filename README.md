# Python to EXE Converter

Script interactivo de Windows Batch para localizar archivos Python y empaquetarlos como ejecutables mediante PyInstaller.

## Funcionalidades

- Comprueba la disponibilidad de Python.
- Comprueba e instala PyInstaller cuando es necesario.
- Permite buscar scripts en Desktop, Documents y Downloads.
- Permite indicar una ruta personalizada o seleccionar un archivo.
- Incluye opciones de configuración antes de compilar.
- Organiza los resultados en una carpeta de salida.
- Evita sobrescribir ejecutables existentes mediante nombres incrementales.
- Mantiene los directorios de trabajo y archivos temporales dentro de la carpeta de salida; no elimina carpetas `build` ni archivos `.spec` del directorio de origen.

## Requisitos

- Windows.
- Python instalado y disponible en PATH.
- Conexión a Internet durante la instalación de PyInstaller, si no está instalado.
- Dependencia fijada en `requirements.txt` (PyInstaller 6.x).
- Permisos suficientes para instalar paquetes y escribir en la carpeta de salida.

## Uso

Ejecuta `Python2Exe_Converter.bat` desde el Explorador de archivos o desde CMD y sigue el menú.

## Tecnologías

- Windows Batch
- Python
- pip
- PyInstaller

## Seguridad

Compila únicamente scripts propios o código cuya procedencia hayas verificado. Un ejecutable empaquetado no queda automáticamente firmado ni libre de detecciones antivirus.
