# List Combine PDFs

**List Combine PDFs** es una aplicación de escritorio desarrollada en Python con Tkinter que permite combinar archivos PDF de manera interactiva. La aplicación proporciona una interfaz gráfica para seleccionar carpetas de archivos PDF, generar una plantilla de Excel que puede ser editada para especificar los PDFs a combinar y generar archivos PDF combinados basados en esa plantilla.

## Características

- **Listar PDFs**: Selecciona una carpeta y lista automáticamente todos los archivos PDF.
- **Generar plantilla Excel**: Crea una plantilla `.xlsx` que puede ser editada para definir qué PDFs combinar y el nombre del archivo resultante.
- **Combinación de PDFs**: Combina los archivos PDF especificados en la plantilla Excel.
- **Progreso visual**: La barra de progreso muestra el avance del proceso de combinación de archivos.
- **Interfaz amigable**: Se utiliza una interfaz gráfica con botones simples para navegar a través del proceso.
- **Botón de salida**: Salida inmediata de la aplicación.

## Requisitos del sistema

- **Python 3.x**
- **Sistema operativo**: Windows (aunque podría funcionar en otros sistemas operativos con ajustes menores).

## Dependencias

Asegúrate de instalar las siguientes bibliotecas de Python antes de ejecutar el programa:

- **Tkinter** (biblioteca estándar en Python para la interfaz gráfica, no requiere instalación en la mayoría de los sistemas)
- **openpyxl**: Para trabajar con archivos Excel (.xlsx).
- **PyPDF2**: Para manejar y combinar archivos PDF.

### Instalar dependencias

Para instalar las bibliotecas necesarias, ejecuta los siguientes comandos en tu terminal:

```bash
pip install openpyxl PyPDF2
```
## Instrucciones de instalación y ejecución

### 1. Clonar el repositorio:

Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/tu-usuario/list-combine-pdfs.git
```

### 2. Navegar al directorio del proyecto:

```bash
cd list-combine-pdfs
```

### 3. Instalar dependencias:

Asegúrate de tener Python 3.x instalado y ejecuta el siguiente comando para instalar las dependencias necesarias:

```bash
pip install -r requirements.txt
```
Si no tienes un archivo requirements.txt, puedes usar este comando para instalar las dependencias individuales:

```bash
pip install openpyxl PyPDF2
```

### 4. Ejecutar la aplicación:
Para iniciar la aplicación, ejecuta el siguiente comando:

```bash
python list_combine_pdfs.py
```

## Uso de la aplicación

Uso de la aplicación
### 1. Seleccionar carpeta de PDFs:
Haz clic en el botón "Paso 1: Seleccionar carpeta de PDFs" y elige la carpeta que contiene los archivos PDF que quieres combinar.

### 2. Generar plantilla Excel:
Después de seleccionar la carpeta, la aplicación generará un archivo Excel con todos los PDFs listados en la columna PDF-BASE. Este archivo puede ser editado manualmente para especificar los archivos a combinar y los nombres de los resultados.

### 3. Seleccionar archivo Excel y combinar PDFs:
Haz clic en el botón "Paso 2: Seleccionar Excel y Combinar PDFs". Selecciona el archivo Excel modificado para iniciar el proceso de combinación. La barra de progreso indicará el estado del proceso.

## Ejemplo de la plantilla Excel

El archivo Excel generado tendrá las siguientes columnas:

| PDF-BASE | PDF-1     | PDF-2     | RESULTADO            |
|----------|-----------|-----------|----------------------|
| file1.pdf | file1.pdf | file2.pdf | file1_file2_combined.pdf |
| file2.pdf |           |           |                      |

- **PDF-BASE**: Archivos listados automáticamente desde la carpeta seleccionada.
- **PDF-1** y **PDF-2**: Archivos que quieres combinar (puedes editarlos manualmente).
- **RESULTADO**: Nombre del archivo PDF combinado que será generado.

Este archivo Excel es generado automáticamente por la aplicación y permite al usuario especificar los archivos PDF que serán combinados y el nombre del archivo resultante.


### 4. Salir:
Usa el botón "Salir" para cerrar la aplicación cuando hayas terminado.

## Autor
Jorge A Melo

## Licencia
Este proyecto está bajo la licencia MIT. Para más detalles, revisa el archivo LICENSE.
---

### Resumen de la estructura:

1. **Clonar el repositorio**: Proporciona los comandos para clonar el proyecto desde GitHub.
2. **Navegar al directorio**: Instrucción para ingresar al directorio del proyecto.
3. **Instalar dependencias**: Instrucción para instalar las dependencias desde el archivo `requirements.txt` o mediante el comando `pip`.
4. **Ejecutar la aplicación**: Instrucciones sobre cómo ejecutar el programa usando Python.


