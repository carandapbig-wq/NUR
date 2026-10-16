# Nur para Android

Aplicación Android instalable. La interfaz, las guías, las ilustraciones y el texto árabe y español del Corán se incluyen en la app. El lector del Corán y el cálculo de horarios funcionan sin conexión. Qibla utiliza ubicación/GPS y sensores del teléfono. Los horarios de oración usan la zona horaria de la ciudad elegida cuando se busca por ciudad; al usar el GPS se usa la zona horaria configurada en el teléfono.

Los audios se descargan bajo demanda con conexión y se guardan dentro del almacenamiento de la app: cada sura del Corán o audio de súplica que se guarde podrá reproducirse sin conexión en adelante. No se incluye toda la recitación en el APK para mantener su tamaño razonable. Si se borran los datos de la app, habrá que volver a guardar esos audios.

## Atribuciones

Consulta `app/src/main/assets/www/ATRIBUTOS.txt` para fuentes y licencias del texto y la traducción del Corán y la recitación.

## Compilar en Android Studio

Abre la carpeta del proyecto, espera a que Gradle sincronice y selecciona **Build > Build APK(s)**. Para instalar esta actualización sobre una versión existente sin perder sus datos, firma el APK con **la misma clave** usada para esa versión. Una clave nueva, aunque sea de depuración, causará un conflicto de firma; no desinstales la versión anterior para evitarlo.

La pantalla de rezos permite elegir y probar tres llamadas a la oración (adhan) incluidas en el paquete. La recitación seleccionada se reproduce para cada oración que el usuario active, salvo que marque «Silenciar el adhan».

Cuando suena una alarma, tocar cualquier punto de la pantalla de alarma la detiene. Tocar el aviso de NUR o su acción «Detener» también la detiene. Si NUR ya está abierta, tocar su pantalla detiene la alarma. En Android 14 o posterior, permite la pantalla de alarma completa cuando el sistema lo solicite; si está desactivada, el aviso sigue ofreciendo «Detener».

## Versión 1.9

Los horarios aparecen al principio de Rezos. Al entrar se recuperan las coordenadas y la zona horaria de la última ubicación guardada, y se calculan los horarios sin conexión. Si todavía no hay una ubicación, aparecen las cinco oraciones y la indicación para usar el GPS o buscar una ciudad. Cambiar la fecha o el método actualiza las horas. La atribución Open-Meteo / GeoNames se mantiene como texto sin enlace.
