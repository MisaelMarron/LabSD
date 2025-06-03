# 🛒 Proyecto SOAP

## 📋 Descripción

Este proyecto es un cliente Java que consume un servicio SOAP de una tienda en línea, generado usando `wsimport` y compatible con **JDK 8**.

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
```

---

## ▶️ Ejecución

### Paso 1: Iniciar el Servidor de Usuarios

1. Ejecutar `PublishServices.java` para que el servidor se aloje en:
   ```
   http://localhost:1516/WS/Users?wsdl
   ```

### Paso 2: Ejecutar el Cliente

1. En SOAPClient, ejecutar el archivo `UserClient`
2. Observar cómo se hace la conexión y se crean los usuarios

---

## 🛒 Tienda Online - Componentes del Proyecto

Este proyecto implementa una aplicación Java basada en servicios web **SOAP**, desarrollada con **JDK 1.8** en **Eclipse IDE**. Está compuesta por dos módulos:

- **`TiendaOnline`**: Servidor SOAP que expone operaciones para listar, agregar y comprar productos
- **`TiendaClient`**: Cliente SOAP que consume los servicios ofrecidos por el servidor

---

## 📦 Archivos del Proyecto

Puedes importar los siguientes archivos `.zip` directamente en Eclipse:

- [📁 Descargar TiendaOnline](Propuesto/TiendaOnline.zip)
- [📁 Descargar TiendaClient](Propuesto/TiendaClient.zip)

---

## 🚀 Ejecución del Proyecto Completo

### 1. Iniciar el Servidor

En el proyecto `TiendaOnline`, ejecuta la clase:

```java
es.sistemasdistribuidos.PublishStoreService
```

### 2. Ejecutar el Cliente

En el proyecto `TiendaClient`, ejecuta la clase:

```java
tienda.client.TiendaClient
```

---

## 🔄 ¿Qué hace el cliente?

El cliente realiza las siguientes operaciones:

1. **Muestra los productos disponibles**
2. **Solicita al usuario que seleccione un producto por ID**
3. **Realiza la compra** (el producto se elimina del servidor)
4. **Vuelve a mostrar los productos restantes**