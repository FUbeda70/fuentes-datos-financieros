# Tema 4 · Determinantes de la rentabilidad de las acciones

## Archivos necesarios

Para la replicación y análisis descritos en el notebook se utilizan:

- `04_Efectos_Macro_Contable_Rentabilidad.ipynb`: cuaderno docente **original**, sin cambios.
- `04_Efectos_Macro_Contable_Rentabilidad_colab.ipynb`: el mismo cuaderno con **una sola celda inicial adicional** para descargar los archivos auxiliares desde GitHub si faltan en la sesión.
- `helper.py`: módulo de funciones de cálculo de estadísticas.
- `GW05_original_annual.csv`: serie anual.
- `GW05_original_monthly.csv`: serie mensual.
- `Welch.pdf`: documento de apoyo.

### Ejecución con Google Colab

Abre la versión que termina en `_colab.ipynb` y ejecuta las celdas en orden. La primera celda de código añadida comprueba la presencia de los tres archivos y, cuando faltan, los descarga de la rama `main` del repositorio. Es necesario tener conexión a Internet y que el repositorio esté publicado.

### Ejecución en Jupyter local

Inicia Jupyter desde **esta carpeta** (no desde el directorio padre); de este modo, las rutas relativas `helper.py` y `GW05_original_*.csv` que aparecen en el notebook se resuelven correctamente. Con un entorno virtual de Python 3 preparado, instala las librerías de `../requirements.txt`.

### Procedencia del código y cita del repositorio utilizado

El cuaderno de este tema ha sido desarrollado tomando como base el notebook **`GW08_replication.ipynb`** de **Julius Doebelt** (`juliusd01`) en el repositorio [**ReplicationGoyalWelch2008**](https://github.com/juliusd01/ReplicationGoyalWelch2008), que replica el trabajo de Welch y Goyal (2008).

**Referencia al código utilizado:** Doebelt, Julius (2025). *ReplicationGoyalWelch2008*, notebook `GW08_replication.ipynb`. GitHub. [Enlace permanente a la revisión `f773c60197a7daf8c20769716069264894684ad2`](https://github.com/juliusd01/ReplicationGoyalWelch2008/blob/f773c60197a7daf8c20769716069264894684ad2/GW08_replication.ipynb).

El archivo `helper.py` de esta carpeta es idéntico al que figura en el repositorio original. Su código se distribuye con licencia MIT; se conserva aquí el [aviso de copyright y el texto íntegro de la licencia](LICENSE-JULIUS-DOEBELT-MIT.txt) ([fuente](https://github.com/juliusd01/ReplicationGoyalWelch2008/blob/f773c60197a7daf8c20769716069264894684ad2/LICENSE)). Esta atribución no sustituye la referencia al artículo académico de **Welch y Goyal (2008)**, *A Comprehensive Look at the Empirical Performance of Equity Premium Prediction*, *The Review of Financial Studies*, 21(4), 1455–1508.

**Alcance:** el reconocimiento a Julius Doebelt corresponde al código base de replicación; el curso y los desarrollos docentes asociados siguen atribuidos a Fernando Úbeda y Alfonso Santos.

**Nota:** no se ha realizado una ejecución integral de los cuadernos que dependen de proveedores externos; la disponibilidad de esas fuentes puede variar.
