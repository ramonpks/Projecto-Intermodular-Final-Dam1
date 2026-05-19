# Fase 5: Diseño Web

## 📌 Resumen de la Fase

En esta fase se define la arquitectura visual y la experiencia de usuario de la aplicación **"Agéndame Esta"**. Se elaboran el mapa de páginas, la estructura de navegación, los wireframes de baja fidelidad y el flujo básico de usuario que guiará el desarrollo frontend.

!!! success "Estado"
    **Completada**

---

## 1. 🗺️ Mapa de Páginas

La aplicación está compuesta por **7 pantallas principales** organizadas en una estructura jerárquica sencilla, pensada para facilitar el acceso rápido a todas las funcionalidades desde un menú central.

### Estructura del Mapa

![Mapa Estructural](../docs/assets/images/Mapa%20Estructural.png)


### Pantallas de la Aplicación

| # | Pantalla | Descripción | Tipo |
|---|----------|-------------|------|
| 1 | **Menú Principal** | Pantalla de inicio con acceso a todas las secciones | Navegación |
| 2 | **Listado** | Visualización de todos los contactos almacenados | Visualización |
| 3 | **Búsqueda** | Filtrado y búsqueda de contactos por criterios | Interacción |
| 4 | **Opciones** | Submenú de gestión: Añadir, Editar, Eliminar | Navegación |
| 5 | **Añadir** | Formulario para crear un nuevo contacto | Formulario |
| 6 | **Editar** | Búsqueda del contacto a modificar | Interacción |
| 7 | **Editar Campos** | Formulario con los datos del contacto seleccionado | Formulario |
| 8 | **Eliminar** | Búsqueda y confirmación de borrado de contacto | Interacción |
| 9 | **Acerca de** | Información de los creadores y la aplicación | Informativa |

---

## 2. 🧭 Estructura de Navegación

La navegación sigue un modelo **jerárquico en árbol** con retorno al menú principal. Todas las pantallas secundarias disponen de un botón **"ATRÁS"** que permite volver al nivel anterior.

### Diagrama de Navegación

![WireFrames](../docs/assets/images/WireFrames.png)


### Reglas de Navegación

| Regla | Descripción |
|-------|-------------|
| **Punto único de entrada** | Todas las funciones parten del Menú Principal |
| **Navegación bidireccional** | Cada pantalla permite avanzar y retroceder |
| **Botón ATRÁS universal** | Todas las pantallas secundarias incluyen botón de retorno |
| **Sin bucles cerrados** | No se permite la navegación circular entre pantallas del mismo nivel |
| **Salida controlada** | El botón "SALIDA" en el menú principal cierra la aplicación |

---

## 3. 🖼️ Wireframes de las Páginas Principales

Los wireframes de baja fidelidad definen la disposición de los elementos en cada pantalla, priorizando la claridad y la usabilidad sobre el diseño estético.

### 3.1 Menú Principal

![Menu Principal](../docs/assets/images/Menu%20Principal.png)+


**Elementos:**
- 4 botones principales de navegación.
- 1 botón de salida.
- Título y subtítulo centrados.
- Diseño vertical centrado tipo mobil.

### 3.2 Listado de Contactos

![Listado](../docs/assets/images/Listado.png)


**Elementos:**
- Área de contenido scrollable verticalmente.
- Indicadores de dirección de scroll.
- Botón ATRÁS para retorno al Menú Principal.

### 3.3 Búsqueda

![Busqueda](../docs/assets/images/Busqueda.png)


**Elementos:**
- Selector desplegable.
- Campo de texto para el criterio de búsqueda.
- Botón BUSCAR.
- Área de resultados dinámica.
- Botón ATRÁS para retorno al Menú Principal.

### 3.4 Opciones

![Opciones](../docs/assets/images/Opciones.png)


**Elementos:**
- 3 botones de acción.
- Botón ATRÁS al Menú Principal.


### 3.5 Añadir Contacto

![Añadir](../docs/assets/images/Añadir.png)


**Elementos:**
- 5 campos de formulario etiquetados.
- Botón AÑADIR.
- Botón ATRÁS al Menú Opciones.

### 3.6 Editar

![Editar](../docs/assets/images/Editar.png)

**Elementos:**
- Selector desplegable.
- Campo de texto para el criterio de búsqueda.
- Botón BUSCAR.
- Botón ATRÁS para retorno al Menú Opciones.

### 3.7 Editar Campos

![EditarCampos](../docs/assets/images/EditarCampos.png)

**Elementos:**
- 5 campos de formulario etiquetados.
- Botón Editar.
- Botón ATRÁS a Editar.

### 3.8 Eliminar Contacto

![Eliminar](../docs/assets/images/Eliminar.png)

**Elementos:**
- Selector desplegable.
- Campo de texto para el criterio de búsqueda.
- Botón BUSCAR.
- Área de resultados dinámica Seleccionable.
- Botón ATRÁS para retorno al Menú Opciones.


### 3.9 Acerca De

![Acerca De](../docs/assets/images/AcercaDe.png)

**Elementos:**
- Información de la aplicacion y los desarrolladores.
- Botón ATRÁS para retorno al Menú.

---

## 4. 🔄 Flujo Básico de Usuario

El flujo de usuario describe los pasos que realiza una persona para completar las tareas principales en la aplicación.

### 4.1 Consultar Listado

```text
INICIO APP → MENÚ PRINCIPAL → LISTADO → VISUALIZA DATOS → ATRÁS
```

### 4.2 Buscar

```text
INICIO APP → MENÚ PRINCIPAL → BÚSQUEDA → DESPLEGABLE TIPO → TEXTO A BUSCAR → RESULTADOS BÚSQUEDA → ATRAS
```

### 4.3 Añadir Nuevo Contacto

```text
INICIO APP → MENÚ PRINCIPAL → OPCIONES → AÑADIR → FORMULARIO → AÑADIR → ATRÁS
```

### 4.4 Editar

```text
INICIO APP → MENÚ PRINCIPAL → OPCIONES → EDITAR → DESPLEGABLE TIPO → TEXTO A BUSCAR → BUSCAR → EDITAR CAMPOS → ATRAS 
```

### 4.5 Eliminar Contacto

```text
INICIO APP → MENÚ PRINCIPAL → OPCIONES → ELIMINAR →  DESPLEGABLE TIPO → TEXTO A BUSCAR → RESULTADOS BÚSQUEDA → SELECCIONAR RESULTADO → BORRAR → ATRAS
```

### 4.6 Acerca de

```text
INICIO APP → MENÚ PRINCIPAL → ACERCA DE → ATRAS
```

---

## 5. 📐 Decisiones de Diseño

| Decisión | Justificación |
|----------|---------------|
| **Mobil** | La app está pensada para uso personal y rápido desde cualquier dispositivo |
| **Menú centralizado** | Facilita el acceso a todas las funciones sin navegación profunda |
| **Formularios verticales** | Mejor legibilidad en pantallas estrechas y dispositivos móviles |
| **Botón ATRÁS universal** | Garantiza que el usuario nunca se pierde en la navegación |
| **Búsqueda previa en Editar/Eliminar** | Evita errores al seleccionar contactos de listas largas |
| **Campos unificados** | Todos los contactos comparten la misma estructura |

---

!!! tip "Navegación"
    ← [Fase 4: Metodología](fase4.md) | [Fase 6: Prototipo Visual](fase6.md) →