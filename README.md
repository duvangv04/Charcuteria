<h1>Sistema para charcuteria 🥩</h1>

Sistema de información para una microempresa dedicada a la producción y comercialización de productos cárnicos, enfocado en la gestión de producción, recetas, materias primas, inventario, clientes, ventas y facturación, permitiendo centralizar la información y optimizar los procesos operativos y administrativos.

---

<details>
<summary><h2>📌 1. Justificación </h2></summary>

Actualmente, la microempresa no dispone de una herramienta tecnológica que integre la gestión de sus procesos productivos, comerciales y administrativos. La empresa se dedica tanto a la producción como a la comercialización de productos; sin embargo, la información relacionada con clientes, productos, inventario, ventas, producción y recetas se administra mediante facturas físicas y registros manuales, generando una alta dependencia de procesos no automatizados. Esta situación dificulta la centralización de la información, el acceso oportuno a los datos y la trazabilidad de las operaciones realizadas en las diferentes áreas del negocio.

Debido a la ausencia de una solución tecnológica, se dificulta el control del inventario de materias primas y productos terminados, así como la administración de ingresos y gastos. Además, la empresa no cuenta con mecanismos para gestionar las recetas de producción, controlar el consumo de materias primas ni realizar un seguimiento de los procesos productivos. Como consecuencia, se presentan ineficiencias operativas, inconsistencias en la información, mayor probabilidad de errores y una capacidad limitada para generar reportes confiables que apoyen la toma de decisiones estratégicas. En este contexto surge la siguiente pregunta de investigación: ¿Cómo optimizar la gestión de los procesos productivos, comerciales y administrativos de una microempresa dedicada a la producción y comercialización de productos mediante la automatización y centralización de la información?

Como respuesta a esta problemática, se propone desarrollar un sistema de información que centralice y automatice la gestión de clientes, productos, recetas de producción, materias primas, inventario, listas de precios, producción, ventas y facturación, mediante una base de datos que garantice la integridad, disponibilidad y trazabilidad de la información en todas las áreas del negocio. La implementación de esta solución permitirá mejorar el control de los procesos, reducir errores asociados a la gestión manual, optimizar el manejo del inventario y facilitar la generación de reportes e indicadores que apoyen la toma de decisiones de manera oportuna y confiable.
</details>

---

<details>
<summary><h2>🎯 2. Objetivo general</h2></summary>

Desarrollar un sistema de información para la gestión de los procesos productivos, comerciales y administrativos de una microempresa, mediante la automatización y centralización de la información

</details>

---

<details>
<summary><h2>✅ 4. Objetivos específicos</h2></summary>

1. **Analizar** los procesos productivos, comerciales y administrativos de la microempresa para identificar el flujo de trabajo actual, comprender su funcionamiento y establecer los requerimientos del sistema.
2. **Diseñar** el modelo de datos y la interfaz del sistema de acuerdo con los requerimientos identificados durante la etapa de análisis.
3. **Construir** el sistema de información con base en el diseño propuesto, integrando los módulos de producción, recetas, inventario, clientes, ventas y facturación.
4. **Desplegar** el sistema de información en el entorno de la microempresa para su puesta en funcionamiento y validación.

</details>

---

<details>
<summary> <h2>🔎 6. Análisis</h2></summary>

<h3>👥 Actores del Sistema</h3>

<table>
<tr>

<td align="center" width="50%">

<details>

<summary>

<h3>👨‍💼 Administrador</h3>

</summary>

<br>

**Permisos**

- 👥 Gestión de usuarios
- 🏭 Gestión de producción
- 🧾 Gestión de recetas
- 📦 Gestión de inventario
- 🥩 Gestión de productos
- 🚚 Gestión de proveedores
- 💲 Gestión de precios
- 🛒 Gestión de ventas
- 🧾 Facturación
- 📊 Reportes
- ⚙️ Configuración

</details>

</td>

<td align="center" width="50%">

<details>

<summary>

<h3>🛒 Vendedor</h3>

</summary>

<br>

**Permisos**

- 👥 Gestión de clientes
- 🛒 Registrar ventas
- 🧾 Generar facturas
- 📦 Consultar inventario
- 🥩 Consultar productos
- 📋 Historial de ventas

</details>

</td>

</tr>
</table>

<h3>📝 Requerimientos Funcionales</h3>

### Gestión de usuarios

- Inicio de sesión.
- Administración de usuarios.
- Asignación de roles.

### Gestión de clientes

- Registrar clientes.
- Editar clientes.
- Eliminar clientes.
- Consultar clientes.
- Asignar precios personalizados.

### Gestión de productos

- Registrar productos.
- Registrar categorías.
- Registrar múltiples presentaciones.
- Actualizar precios.
- Consultar productos.

### Gestión de inventario

- Registrar entradas.
- Registrar salidas.
- Ajustes de inventario.
- Consultar existencias.
- Historial de movimientos.

### Gestión de ventas

- Crear ventas.
- Buscar clientes.
- Aplicar precios correspondientes.
- Imprimir factura.
- Consultar historial.

### Reportes

- Ventas por fecha.
- Ventas por cliente.
- Inventario actual.
- Productos más vendidos.
- Productos con bajo stock.

<h3>📝 Requerimientos NO Funcionales</h3>

- Interfaz sencilla e intuitiva.
- Respuesta rápida.
- Escalabilidad.

</details>
