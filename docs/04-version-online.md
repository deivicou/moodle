# Versión online (Hosting)

## Versión probada

**Versión:** `4.5.3+`

## Hosting

Se utilizó **InfinityFree** ([Hosting Accounts - InfinityFree](https://infinityfree.net/)) como proveedor de hosting gratuito para alojar la instancia online de Moodle.

## Instalación

La instalación a través del panel de hosting **no funcionó correctamente** de forma automática: la plataforma no tenía bien configurado el script de instalación de Moodle.

### Solución aplicada

Fue necesario instalar Moodle **manualmente**:

1. Subir los ficheros de Moodle a través del **File Manager** del panel de hosting.
2. Crear la **base de datos** MySQL desde el panel de hosting.
3. Ejecutar el instalador de Moodle apuntando a la base de datos creada manualmente.
4. Completar la configuración del sitio (`config.php`, rutas, datos de conexión a la BD).

## Notas

El acceso al área personal de Moodle online se realiza desde la URL proporcionada por el hosting tras completar la instalación.
