# Definición de RQF – RQNF
PC → Pedidos cliente

PA-> Pedidos del Micro aliado hacia Alquería

IC-> Información corporativa

<img width="681" height="421" alt="Image" src="https://github.com/user-attachments/assets/dd0f6dbb-9d6c-45d6-b4a0-b42af95fad56" />

<img width="704" height="754" alt="Image" src="https://github.com/user-attachments/assets/5374a576-d97d-4718-9a3b-9bf793fcc74c" />
<img width="689" height="768" alt="Image" src="https://github.com/user-attachments/assets/6693addc-3e5e-4abb-ac91-86331d7cf8a6" />
<img width="706" height="661" alt="Image" src="https://github.com/user-attachments/assets/aa3d06ce-2e2e-4f4e-b13c-e03ab6ac688c" />
<img width="708" height="265" alt="Image" src="https://github.com/user-attachments/assets/c9b85d47-aa7d-45cb-a517-1d03773daf99" /> 

<img width="706" height="642" alt="Image" src="https://github.com/user-attachments/assets/04104a04-d7d9-4233-b425-1934ed90ef25" />
<img width="675" height="656" alt="Image" src="https://github.com/user-attachments/assets/57fcd226-abf4-4517-bb37-a0bdc2ae0bb4" />
<img width="694" height="222" alt="Image" src="https://github.com/user-attachments/assets/e448afcb-2dd3-4b9b-bf83-878b64aa3aea" />






# 📌 Requisitos Funcionales – Información Corporativa (IC)

| ID        | Tipo       | Descripción                                                                 | Prioridad | Criterio de aceptación                                                 |
|-----------|------------|-----------------------------------------------------------------------------|-----------|------------------------------------------------------------------------|
| RQF-IC-01 | Funcional  | El sistema debe mostrar la misión, visión y valores de la empresa en una sección dedicada. | Alta      | La sección despliega texto validado por el administrador.              |
| RQF-IC-02 | Funcional  | El sistema debe permitir visualizar reseñas de clientes sobre la empresa.   | Media     | La sección muestra reseñas cargadas previamente en el sistema.         |
| RQF-IC-03 | Funcional  | El sistema debe permitir consultar información sobre clientes/aliados de la empresa. | Baja      | La sección lista clientes o empresas aliadas con nombre y breve descripción. |
| RQF-IC-04 | Funcional  | El sistema debe mostrar el valor agregado de la empresa para fortalecer la confianza de los clientes. | Alta      | El valor agregado aparece en un bloque de información destacado.       |

---

# 📌 Requisitos Funcionales – Pedidos del Microaliado (PA)

| ID        | Tipo       | Descripción                                                                 | Prioridad | Criterio de aceptación                                                 |
|-----------|------------|-----------------------------------------------------------------------------|-----------|------------------------------------------------------------------------|
| RQF-PA-01 | Funcional  | El sistema debe permitir al microaliado realizar pedidos de productos a Alquería desde un módulo específico. | Alta      | El microaliado selecciona productos, cantidades y genera un pedido.    |
| RQF-PA-02 | Funcional  | El sistema debe mostrar el catálogo de productos de Alquería disponibles para pedido interno. | Alta      | El microaliado puede visualizar productos con nombre, precio y disponibilidad. |
| RQF-PA-03 | Funcional  | El sistema debe generar un comprobante digital de cada pedido realizado a Alquería. | Alta      | Tras confirmar el pedido, se genera un comprobante descargable/consultable. |
| RQF-PA-04 | Funcional  | El sistema debe permitir al microaliado consultar el historial de pedidos realizados a Alquería. | Media     | El módulo muestra la lista de pedidos previos con fecha, estado y total. |

---

# 📌 Requisitos Funcionales – Plataforma Central (PC)

| ID        | Tipo       | Descripción                                                                 | Prioridad | Criterio de aceptación                                                 |
|-----------|------------|-----------------------------------------------------------------------------|-----------|------------------------------------------------------------------------|
| RQF-PC-01 | Funcional  | El sistema debe permitir a los usuarios registrados acceder mediante inicio de sesión con correo electrónico y contraseña. | Alta      | El usuario accede al sistema solo si sus credenciales son correctas; de lo contrario, recibe un mensaje de error. |
| RQF-PC-02 | Funcional  | El sistema debe permitir a los administradores consultar información básica sobre accesos de usuarios (fechas y horas de inicio de sesión). | Media     | El administrador puede visualizar un listado con la fecha y hora de cada acceso realizado por los usuarios registrados. |
| RQF-PC-03 | Funcional  | El sistema debe permitir a los usuarios cerrar su sesión de forma segura, garantizando la privacidad de su cuenta. | Alta      | El sistema invalida la sesión del usuario y lo redirige a la pantalla de inicio. |
| RQF-PC-04 | Funcional  | El sistema debe mostrar un catálogo de productos con imágenes, descripciones, precios y disponibilidad. | Alta      | El usuario puede visualizar productos con foto, nombre, descripción, precio y disponibilidad actualizada. |
| RQF-PC-05 | Funcional  | El sistema debe permitir la selección de productos y la generación de cotizaciones personalizadas. | Alta      | El usuario puede generar una cotización seleccionando productos y cantidades; el sistema muestra el total y permite exportar/guardar. |
| RQF-PC-06 | Funcional  | El sistema debe ofrecer un flujo de compra en línea para que los clientes realicen pedidos de manera rápida y sencilla. | Alta      | El usuario puede añadir productos al carrito, confirmar la compra y obtener un comprobante digital. |
| RQF-PC-07 | Funcional  | El sistema debe contar con un panel de gestión para que cada cliente administre su perfil y consulte su historial de cotizaciones y pedidos. | Media     | El usuario puede actualizar su información personal y visualizar su historial completo de cotizaciones y pedidos previos. |

---

# 📌 Requisitos No Funcionales

| ID         | Tipo        | Descripción                                                                 | Prioridad | Criterio de aceptación                                                 |
|------------|-------------|-----------------------------------------------------------------------------|-----------|------------------------------------------------------------------------|
| RQNF-IC-01 | No Funcional| La sección de información corporativa debe ser accesible desde cualquier dispositivo (responsive). | Alta      | El contenido se visualiza correctamente en móvil, tablet y escritorio. |
| RQNF-IC-02 | No Funcional| El contenido corporativo debe cargarse en menos de 3 segundos.              | Media     | El tiempo de carga medido no supera los 3 segundos en pruebas estándar. |
| RQNF-PA-01 | No Funcional| El módulo de pedidos internos debe garantizar la seguridad en la transmisión de datos hacia Alquería. | Alta      | La comunicación se realiza bajo HTTPS y con autenticación válida.      |
| RQNF-PA-02 | No Funcional| El sistema debe permitir al microaliado consultar pedidos anteriores en menos de 2 segundos de respuesta. | Media     | La consulta de historial devuelve resultados rápidamente en pruebas.   |
| RQNF-PA-03 | No Funcional| El módulo de pedidos debe estar disponible al menos el 95% del tiempo para evitar interrupciones en la cadena de suministro. | Alta      | El uptime del módulo es ≥ 95% medido mensualmente.                     |
| RQNF-PA-04 | No Funcional| El sistema debe ser intuitivo para el microaliado, reduciendo la necesidad de capacitación adicional. | Media     | Usuarios nuevos pueden realizar pedidos sin documentación extensa.     |
| RQNF-01    | No Funcional| La aplicación debe ser responsiva, adaptándose automáticamente a dispositivos móviles, tablets y computadores. | Alta      | Al acceder desde distintos dispositivos, la interfaz se ajusta correctamente sin pérdida de funcionalidad. |
