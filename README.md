# Guitafy

Guitafy es una aplicación web multifuncional para la gestión financiera, diseñada tanto para **uso personal** como para **pequeños negocios** (kioscos, comercios de barrio, emprendimientos). Permite registrar gastos, ingresos, gestionar categorías y analizar movimientos financieros de forma clara y estructurada.

El sistema se basa en el uso de **categorías únicas y permanentes**, asociadas a cada movimiento, permitiendo un mejor análisis de hábitos financieros y una base sólida para la toma de decisiones económicas.

---

## Problema que resuelve

Muchas herramientas de finanzas personales carecen de consistencia en la categorización de datos y de una estructura pensada para el análisis a largo plazo. A su vez, los pequeños negocios no siempre tienen acceso a herramientas simples que les permitan llevar un control básico de sus operaciones sin complejidad innecesaria.

Guitafy apunta a resolver este problema mediante:

- Categorías persistentes y bien definidas
- Separación clara entre ingresos y gastos
- Organización simple pero escalable
- Enfoque en usabilidad y claridad de la información
- Adaptabilidad a distintos contextos de uso (personal y negocio)

---

## Modos de uso

Guitafy está pensado para funcionar en dos contextos distintos desde una misma plataforma:

### 💼 Software de negocio
Orientado a pequeños comercios y emprendimientos que necesitan llevar un control básico de sus operaciones financieras.

| Funcionalidad | Disponible |
|---|---|
| Categorías | ✅ |
| Gastos / Ingresos | ✅ |
| Inventario / Stock | ✅ |
| Dashboard | ✅ |
| Historial de transacciones | ✅ |
| Fiados | 🔜 Próximamente |

### 👤 Software personal
Orientado a usuarios que quieren gestionar sus finanzas personales de forma simple y ordenada.

| Funcionalidad | Disponible |
|---|---|
| Categorías | ✅ |
| Gastos / Ingresos | ✅ |
| Dashboard | ✅ |
| Historial de transacciones | ✅ |

---

## Funcionalidades principales

- Registro de gastos e ingresos
- Categorías únicas y permanentes
- Asociación de categorías a cada transacción
- Historial de movimientos financieros
- Dashboard con métricas y gráficos
- Base preparada para reportes y estadísticas
- Arquitectura preparada para escalar a múltiples usuarios

---

## Arquitectura del proyecto

Guitafy está desarrollado con una arquitectura **frontend / backend desacoplada**, organizada en repositorios independientes:

- **Frontend**  
  Aplicación web responsable de la interfaz de usuario y la experiencia visual.

- **Backend**  
  API REST encargada de la lógica de negocio, validaciones y persistencia de datos.

Esta arquitectura permite:

- Escalabilidad horizontal
- Mantenimiento independiente
- Evolución hacia un modelo SaaS
- Posibles integraciones futuras (mobile, servicios externos, etc.)

---

## Tecnologías utilizadas

### Frontend

- Next.js / React
- Tailwind CSS
- Axios
- TanStack Query
- TypeScript

### Backend

- Node.js
- Express
- Prisma ORM
- TypeScript
- PostgreSQL

---

## Repositorios

Los repositorios de frontend y backend son **privados**, ya que el proyecto se encuentra en desarrollo activo.

Este repositorio público funciona como:

- Presentación del producto
- Visión general del sistema
- Descripción de la arquitectura
- Punto de referencia del proyecto

---

## Estado del proyecto

**En desarrollo activo**

Actualmente enfocado en:

- Consolidación del modelo de datos
- Experiencia de usuario
- Validaciones y consistencia de información
- Preparación para funcionalidades avanzadas

---

## Roadmap

- [x] Autenticación y gestión de usuarios (JWT + Refresh Tokens)
- [x] Creación de categorías permanentes
- [x] Módulo de Transacciones (gastos e ingresos)
- [x] Dashboard con métricas y gráficos
- [ ] Historial con filtros avanzados
- [ ] Reportes mensuales y anuales
- [ ] Exportación de datos (CSV)
- [ ] Módulo de Inventario / Stock
- [ ] Fiados (para modo negocio)
- [ ] Preparación para modelo SaaS (planes / límites / escalabilidad)

---

## Modelo Freemium

Guitafy está pensado para operar bajo un **modelo Freemium**, ofreciendo funcionalidades básicas de forma gratuita y funcionalidades avanzadas mediante planes pagos.

### Funcionalidades básicas (Free)

- Registro de gastos e ingresos
- Gestión de categorías
- Historial de movimientos
- Dashboard básico
- Uso individual de la aplicación

### Funcionalidades avanzadas (Premium – planeado)

- Reportes avanzados y análisis detallado
- Gráficos y visualizaciones personalizadas
- Filtros avanzados
- Exportación de datos
- Módulo de inventario (modo negocio)
- Fiados y cuentas por cobrar

---

## Visión del proyecto

Guitafy está pensado como un **producto real**, orientado a usuarios finales, con una arquitectura y diseño que permiten su evolución hacia un **modelo SaaS Freemium**.

El objetivo es ofrecer una solución accesible tanto para la gestión financiera personal como para pequeños negocios, combinando simplicidad en el uso gratuito con funcionalidades avanzadas para quienes requieran un mayor nivel de control y análisis.

Forma parte de mi portfolio como desarrollador web y representa mi enfoque en:

- Construcción de productos escalables
- Arquitectura bien definida
- Buenas prácticas de desarrollo
- Pensamiento orientado a negocio y producto

---

## Licencia

Licencia pendiente de definición.
