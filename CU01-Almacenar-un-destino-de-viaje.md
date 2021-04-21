### Almacenar un destino de viaje
## Identificación

| Campo| Información|
| -----| ---- |
| Autor | Vinni - 20/04/2021 |
| Nombre | Almacenar un destino de viaje. |
| Descripción | Persistir la información de país, fecha de inicio y fecha de fin de viaje. El país se selecciona de una lista de 192 opciones. Las fechas deben ser mayores a hoy. Al guardar debe mostrar el mensaje "Se creo el nuevo viaje"  |
| Datos entrada| nombre de país, fecha inicio y fecha de fin |
| Datos salida| N/A |
| Actor | usuario |
| Requerimiento  base  | RQ01|
| Precondiciones  | Cargar la lista de 192 países . N/A|
| Postcondiciones | Regresar a la pantalla que lo invocó |
| Mockup| Se llega haciendo click en el botón registrar viaje. ![Demo (1)](https://user-images.githubusercontent.com/54365595/115477272-32770b80-a209-11eb-8186-ea46ac5a2655.png)|

## Flujo

| Actor | Sistema|
| -----| ---- |
| 1. Registrar los datos entrada |  |
| 2. Hacer click sobre botón "Guardar"| 3. Validar que los datos no estén vacíos  |
| | 4. Validar que las fechas sean mayores a hoy|
| | 5. Persistir la información, y devolver mensaje de éxito |
| | 6. Mostrar en pantalla el mensaje de éxito |

## Excepciones

| Paso | Solución|
| -----| ---- |
| 3. Los datos no son vacíos | 3.1. No almaceno  |
|  | 3.2. Mensaje en pantalla "Datos vacíos"|
|  | 3.3. Volver a la pantalla de almacenar|





