# QuieroEseFichero

**QuieroEseFichero** es una herramienta de línea de comandos diseñada para rastrear sitios web en busca de documentos de interés como PDFs, archivos de Word, y hojas de cálculo de Excel. El programa no solo descarga estos archivos, sino que también extrae y analiza los metadatos asociados, proporcionando información valiosa sobre su contenido. Está especialmente diseñado para ser fácil de usar, con un menú interactivo que guía al usuario a través de las diferentes opciones disponibles.

## Características Principales

- **Rastreo de Sitios Web**: Explora un sitio web y sus subdominios en busca de documentos específicos.
- **Descarga de Documentos**: Permite descargar documentos directamente desde la interfaz.
- **Extracción de Metadatos**: Analiza y extrae metadatos de archivos PDF, Word (`.docx`), y Excel (`.xls`, `.xlsx`).
- **Generación de Reportes**: Genera un reporte detallado con la lista de archivos encontrados y los metadatos extraídos.
- **Interfaz Retro**: Presenta un menú interactivo con un estilo retro que es fácil de navegar.

## Requisitos

Para ejecutar **QuieroEseFichero**, necesitas tener instalado Python 3.x y las siguientes bibliotecas:

- `requests`
- `beautifulsoup4`
- `PyPDF2`
- `python-docx`
- `openpyxl`
- `xlrd`

Puedes instalar todas las dependencias ejecutando:
```bash
pip install -r requirements.txt
```

## Instalación

1. **Clona este repositorio** en tu máquina local:
   ```bash
   git clone https://github.com/tu_usuario/QuieroEseFichero.git
   cd QuieroEseFichero
   ```

2. **Instala las dependencias** requeridas utilizando `pip`:
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecuta el programa**:
   ```bash
   python quieroEseFichero.py
   ```

## Uso

Una vez que ejecutes el programa, se te presentará un menú interactivo con las siguientes opciones:

1. **Explorar Sitio Web para Documentos**: Introduce la URL del sitio web que deseas analizar.
2. **Mostrar Lista de Archivos Encontrados**: Muestra todos los archivos que han sido encontrados en el sitio web.
3. **Descargar y Analizar un Archivo Seleccionado**: Selecciona un archivo de la lista para descargarlo y extraer sus metadatos.
4. **Generar Reporte**: Genera un reporte con la información de los archivos y sus metadatos.
5. **Salir**: Salir del programa.

### Ejemplo de Uso

```bash
python quieroEseFichero.py
```

```plaintext
+----------------------------------+
|         QUIERO ESE FICHERO       |
|       Author: Oscar Martínez     |
+----------------------------------+

E) xplore Website for Documents
L) ist Found Files
D) ownload and Analyze a Selected File
R) eport Generation
Q) uit

Command : 
```


## Licencia

Este proyecto está bajo la Licencia MIT. Ver [LICENSE](LICENSE.txt) para más detalles.
