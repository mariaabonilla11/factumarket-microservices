# Microservicios de Facturas - FactuMarket

Microservicios para la gestión y registro de facturas en el sistema de facturación electrónica, implementado con Ruby on Rails 7 siguiendo principios de Clean Architecture.

## 🏗️ Arquitectura

Este microservicio implementa **Clean Architecture** con las siguientes capas:

```
┌─────────────────────────────────────┐
│   Presentación (Controllers)        │  ← API REST con MVC
├─────────────────────────────────────┤
│   Aplicación (Use Cases)            │  ← Lógica de aplicación
├─────────────────────────────────────┤
│   Dominio (Entities, Validators)    │  ← Lógica de negocio
├─────────────────────────────────────┤
│   Infraestructura (Repositories)    │  ← Acceso a datos
└─────────────────────────────────────┘
```

![Diagrama de la arquitectura](diagrama.png)

## 📁 Microservicios

Gestión de clientes: https://github.com/mariaabonilla11/clients-service-app
Gestión de facturas: https://github.com/mariaabonilla11/invoices-service-app
Gestión de audits: https://github.com/mariaabonilla11/audits-service-app

## 👥 Autor

Maria Bonilla
