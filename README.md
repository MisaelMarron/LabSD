# 🛒 Proyecto SOAP 

# 🛒 Proyecto SOAP - RESUELTO:
# SOAPClient - Cliente Java para consumir un servicio SOAP

Este proyecto es un cliente Java que consume un servicio SOAP de una tienda en línea, generado usando `wsimport` y compatible con **JDK 8**.

---

---

## ✅ Requisitos

- JDK 8 instalado y configurado en el `PATH`
- Eclipse (opcional, para desarrollo)
- Servicio SOAP en ejecución (por ejemplo, en `http://localhost:8080/StoreService?wsdl`)

---

## ⚙️ Instalación

1. Clona o copia el proyecto en tu máquina local:

```bash
git clone https://github.com/MisaelMarron/LabSD

Tenemos que ejecutar PublishServices.java

para que el servidor se aloje en http://localhost:1516/WS/Users?wsdl
luego ejecutamos en SOAPClient el archivo : UserClient

VEMOS COMO SE HACE LA CONECCION Y SE CREAN USERS
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