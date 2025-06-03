# 🛒 Proyecto SOAP 
# GITHUB : https://github.com/MisaelMarron/LabSD

# 🛒 Proyecto SOAP - RESUELTO:

# 🛒 Proyecto SOAP - Tienda Online

Este proyecto implementa una aplicación Java basada en servicios web **SOAP**, desarrollada con **JDK 1.8** en **Eclipse IDE**. Está compuesta por dos módulos:

- **`TiendaOnline`**: Servidor SOAP que expone operaciones para listar, agregar y comprar productos.
- **`TiendaClient`**: Cliente SOAP que consume los servicios ofrecidos por el servidor.

---

## 📦 Descarga del Proyecto

Puedes importar los siguientes archivos `.zip` directamente en Eclipse:

- [📁 Descargar TiendaOnline](Propuesto/TiendaOnline.zip)
- [📁 Descargar TiendaClient](Propuesto/TiendaClient.zip)

---

## ▶️ Ejecución del Proyecto

### 1. Iniciar el Servidor

En el proyecto `TiendaOnline`, ejecuta la clase:

```java
es.sistemasdistribuidos.PublishStoreService
En el proyecto TiendaClient, ejecuta la clase:
tienda.client.TiendaClient
 ¿Qué hace el cliente?
Muestra los productos disponibles.

Solicita al usuario que seleccione un producto por ID.

Realiza la compra (el producto se elimina del servidor).

Vuelve a mostrar los productos restantes.