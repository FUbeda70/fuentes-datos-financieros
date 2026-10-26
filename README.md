# Fuentes y análisis de datos económico-financieros

Materiales docentes de **Fernando Úbeda y Alfonso Santos** · **Universidad Autónoma de Madrid**.

[**Ver la página web del curso**](https://fubeda70.github.io/fuentes-datos-financieros/) · [Curso anterior: Introducción a Python para Finanzas](https://fubeda70.github.io/introduccion-python-finanzas/)

## Presentación

Este curso trabaja la identificación de fuentes económico-financieras, la extracción y el análisis de datos macroeconómicos y contables, el estudio de los determinantes de la rentabilidad bursátil y la interpretación de datos de sostenibilidad.

Los materiales están organizados en cinco temas. **Los temas 1–4 contienen cuadernos de Python; el tema 5 contiene una presentación y no tiene notebook.** La presentación del tema 5 se incluye en PDF (18 diapositivas, 2,8 MB). La versión editable en PowerPoint permanece en Google Drive.

## Contenido

| Tema | Contenido y recursos |
|---|---|
| **01 · Fuentes de datos económico-financieras** | [Notebook](01-fuentes-de-datos/01_Fuentes_Datos_Econ-Financieros.ipynb) · [PDF](01-fuentes-de-datos/Fuentes_Economicas.pdf) · [Bibliografía y original](01-fuentes-de-datos/README.md) |
| **02 · Análisis de datos macroeconómicos** | [Notebook](02-analisis-macroeconomico/02_Analisis_datos_macro.ipynb) · [Econ_Espa (PDF)](02-analisis-macroeconomico/Econ_Espa.pdf) |
| **03 · Análisis de datos contables** | [Notebook](03-analisis-contable/03_Analisis_Datos_Contables_MIAX.ipynb) |
| **04 · Determinantes de la rentabilidad de las acciones** | [Notebook original](04-rentabilidad-acciones/04_Efectos_Macro_Contable_Rentabilidad.ipynb) · [Versión lista para Colab](04-rentabilidad-acciones/04_Efectos_Macro_Contable_Rentabilidad_colab.ipynb) · [Welch (PDF)](04-rentabilidad-acciones/Welch.pdf) |
| **05 · Decodificando los datos de sostenibilidad** | [Presentación en PDF](05-datos-sostenibilidad/Decodificando_el_Valor_Sostenible.pdf) · [PowerPoint original (Drive)](https://drive.google.com/file/d/1JYDU16hCsYUT-lRJ7m-Cb8_UNZpSKVkq/view) · *Sin notebook* |

### Acceso directo a Google Colab

- [Tema 1: Fuentes de datos económico-financieras](https://colab.research.google.com/github/FUbeda70/fuentes-datos-financieros/blob/main/01-fuentes-de-datos/01_Fuentes_Datos_Econ-Financieros.ipynb)
- [Tema 2: Análisis de datos macroeconómicos](https://colab.research.google.com/github/FUbeda70/fuentes-datos-financieros/blob/main/02-analisis-macroeconomico/02_Analisis_datos_macro.ipynb)
- [Tema 3: Análisis de datos contables](https://colab.research.google.com/github/FUbeda70/fuentes-datos-financieros/blob/main/03-analisis-contable/03_Analisis_Datos_Contables_MIAX.ipynb)
- [Tema 4: Determinantes de la rentabilidad (versión preparada)](https://colab.research.google.com/github/FUbeda70/fuentes-datos-financieros/blob/main/04-rentabilidad-acciones/04_Efectos_Macro_Contable_Rentabilidad_colab.ipynb)

Para utilizar un notebook en Colab, abre el enlace y selecciona **Archivo → Guardar una copia en Drive** si quieres conservar tus cambios. Es necesario disponer de acceso a Internet para las fuentes externas.

## Cómo ejecutar el tema 4

El cuaderno del tema 4 utiliza tres archivos auxiliares disponibles **en la misma carpeta** que el notebook:

1. [`helper.py`](04-rentabilidad-acciones/helper.py): funciones para los cálculos estadísticos.
2. [`GW05_original_monthly.csv`](04-rentabilidad-acciones/GW05_original_monthly.csv): datos de frecuencia mensual.
3. [`GW05_original_annual.csv`](04-rentabilidad-acciones/GW05_original_annual.csv): datos de frecuencia anual.

**En Google Colab:** utiliza [esta versión preparada del cuaderno](https://colab.research.google.com/github/FUbeda70/fuentes-datos-financieros/blob/main/04-rentabilidad-acciones/04_Efectos_Macro_Contable_Rentabilidad_colab.ipynb). Incluye una celda adicional que descarga los tres archivos automáticamente desde el presente repositorio (en su rama `main`) cuando no estén en el entorno. No se han modificado las celdas de análisis del cuaderno original.

**En Jupyter local:** abre una terminal dentro de `04-rentabilidad-acciones/`, instala las dependencias necesarias y abre [`04_Efectos_Macro_Contable_Rentabilidad.ipynb`](04-rentabilidad-acciones/04_Efectos_Macro_Contable_Rentabilidad.ipynb). Los tres archivos ya están en esa misma carpeta.

Consulta también [las instrucciones específicas del tema 4](04-rentabilidad-acciones/README.md).

## Requisitos

- **Google Colab**: navegador, cuenta de Google y acceso a Internet. Algunas celdas instalan sus propias dependencias.
- **Jupyter local**: Python 3 y los paquetes indicados en [`requirements.txt`](requirements.txt). Instalación orientativa: `pip install -r requirements.txt`.
- Los ejemplos obtienen información de proveedores y APIs externos. Su disponibilidad, estructura y condiciones de acceso pueden cambiar con el tiempo.

## Procedencia y atribución

Los archivos docentes proceden de la [carpeta original de Drive](https://drive.google.com/drive/folders/1LFv_kFDRgYVlx-UwU-r6xLpbkRjdCTL7). La correspondencia entre los nombres originales y los archivos del repositorio figura en [`fuentes.json`](fuentes.json).

**Tema 1 · Bibliografía de referencia.** Scheuch, C., Voigt, S., Weiss, P. y Frey, C. (2024). *Tidy Finance with Python* (1.ª ed.). Chapman & Hall/CRC, Taylor & Francis. [DOI: 10.1201/9781032684307](https://doi.org/10.1201/9781032684307). Disponible también en VitalSource Bookshelf y en los [recursos en línea del proyecto](https://www.tidy-finance.org/chapters/index.html). Se incluye esta atribución en el notebook del tema 1, conservando el [cuaderno original sin modificaciones](01-fuentes-de-datos/01_Fuentes_Datos_Econ-Financieros_original.ipynb) y las [instrucciones y bibliografía del tema](01-fuentes-de-datos/README.md).

**Tema 4 · Código de replicación y reconocimiento de autoría.** El notebook docente se ha elaborado tomando como referencia el trabajo de **Julius Doebelt** (`juliusd01`), [*ReplicationGoyalWelch2008*](https://github.com/juliusd01/ReplicationGoyalWelch2008), en concreto el cuaderno [**`GW08_replication.ipynb`**](https://github.com/juliusd01/ReplicationGoyalWelch2008/blob/f773c60197a7daf8c20769716069264894684ad2/GW08_replication.ipynb) (revisión Git `f773c60197a7daf8c20769716069264894684ad2`). Se mantiene explícitamente el reconocimiento al repositorio de origen, tanto en el material del tema 4 como en la web del curso.

El archivo [`helper.py`](04-rentabilidad-acciones/helper.py) coincide con el módulo publicado en el repositorio citado y se distribuye conservando el aviso de **copyright © 2025 Julius Doebelt** y el texto íntegro de su [**licencia MIT**](04-rentabilidad-acciones/LICENSE-JULIUS-DOEBELT-MIT.txt) ([ver la licencia de origen](https://github.com/juliusd01/ReplicationGoyalWelch2008/blob/f773c60197a7daf8c20769716069264894684ad2/LICENSE)).

El trabajo académico analizado es **Welch y Goyal (2008)**, *A Comprehensive Look at the Empirical Performance of Equity Premium Prediction*, *The Review of Financial Studies*, 21(4), 1455–1508.

**Nota sobre derechos:** la licencia MIT del proyecto citado se aplica al código correspondiente, no automáticamente al resto de las presentaciones, documentos y otros recursos docentes. Consulta los derechos específicos de cada material antes de su reutilización o redistribución.

## Publicación con GitHub Pages

Este paquete está preparado para el repositorio público **`FUbeda70/fuentes-datos-financieros`** y la rama `main`. Para ponerlo en línea:

1. Los archivos del curso están publicados en la rama `main` del repositorio.
2. En **Settings → Pages**, elige **Deploy from a branch → main → /(root)** y guarda.
3. La web estará disponible, tras activar GitHub Pages, en [https://fubeda70.github.io/fuentes-datos-financieros/](https://fubeda70.github.io/fuentes-datos-financieros/).

Los enlaces directos a Colab presuponen el nombre del repositorio y la rama indicados. Si se utilizan otros nombres, habrá que actualizar los enlaces en `index.html`, `README.md` y la celda de preparación del notebook 4.
