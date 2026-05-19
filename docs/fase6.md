
# Fase 6: Protootipo Visual

## 📌 Resumen de la Fase

En esta fase se elabora el **prototipo visual de alta fidelidad** de la aplicación **"Agéndame Esta"**. Partiendo de los wireframes de baja fidelidad definidos en la Fase 5, se aplica una capa de diseño visual completa (colores, tipografías, iconos y estilos) para representar fielmente cómo será la aplicación antes de iniciar la programación.

!!! success "Estado"
    **Completada**

!!! info "Responsable"
    Esta fase ha sido desarrollada por **Anna Pérez Company**, quien ha liderado el diseño visual y la creación del prototipo de alta fidelidad.

---

## 1. 🎨 Herramienta de Prototipado

### Selección: Canva

Se ha elegido **Canva** como herramienta principal para la creación del prototipo visual por las siguientes razones:

| Criterio | Canva | Justificación |
|----------|-------|---------------|
| **Facilidad de uso** | ✅ Intuitivo | Interfaz amigable que permite crear diseños profesionales sin experiencia previa en diseño de interfaces |
| **Nube** | ✅ 100 % online | Sin necesidad de instalación; acceso desde el IES y desde casa con cualquier navegador |
| **Plantillas** | ✅ Extensa biblioteca | Amplia variedad de plantillas de interfaces y prototipos de apps que aceleran el trabajo inicial |
| **Exportación** | ✅ PNG, JPG, PDF | Facilita la inserción de capturas en la documentación MkDocs y la presentación final |
| **Elementos visuales** | ✅ Iconos, formas, fotos | Biblioteca integrada de recursos gráficos para enriquecer el prototipo sin buscar externos |
| **Gratuito** | ✅ Plan educativo | Accesible para uso académico sin coste; cuenta Edu para estudiantes disponible |
| **Colaboración** | ✅ Compartir y comentar | Permite compartir el diseño con Ramón para revisión y feedback directo en la plataforma |

### Alternativas descartadas

| Herramienta | Motivo del descarte |
|-------------|---------------------|
| Figma | Curva de aprendizaje más pronunciada; requiere conocimientos avanzados de prototipado que no aportan valor añadido para el alcance de este proyecto académico |
| PowerPoint | Limitado para diseño de interfaces; no permite trabajar con píxeles reales ni exportar assets de calidad |
| Papel escaneado | Útil para wireframes rápidos, pero insuficiente para alta fidelidad y presentación profesional |

---

## 2. 🧩 Sistema de Diseño

Antes de construir las pantallas, se ha definido un **sistema de diseño mínimo** que garantiza la coherencia visual en toda la aplicación.

### 2.1 Paleta de Colores

| Token | Hex | Uso |
|-------|-----|-----|
| **Primario** | `#2563EB` | Botones principales, títulos, enlaces activos |
| **Primario Hover** | `#1D4ED8` | Estado hover de botones |
| **Secundario** | `#10B981` | Acciones positivas (Añadir, Guardar, Confirmar) |
| **Peligro** | `#EF4444` | Acciones destructivas (Eliminar, Borrar) |
| **Advertencia** | `#F59E0B` | Alertas y campos con errores de validación |
| **Fondo** | `#F8FAFC` | Color de fondo general de la app |
| **Superficie** | `#FFFFFF` | Tarjetas, formularios, áreas de contenido |
| **Texto Principal** | `#1E293B` | Títulos y etiquetas |
| **Texto Secundario** | `#64748B` | Placeholders, descripciones, hints |
| **Borde** | `#E2E8F0` | Bordes de inputs, separadores sutiles |

### 2.2 Tipografía

| Elemento | Fuente | Tamaño | Peso | Color |
|----------|--------|--------|------|-------|
| Título App | Inter | 24 px | 700 (Bold) | Primario |
| Subtítulo | Inter | 18 px | 600 (Semibold) | Texto Principal |
| Botón Principal | Inter | 16 px | 600 | Blanco sobre Primario |
| Campo Etiqueta | Inter | 14 px | 500 (Medium) | Texto Principal |
| Input Texto | Inter | 14 px | 400 (Regular) | Texto Principal |
| Placeholder | Inter | 14 px | 400 | Texto Secundario |
| Texto Informativo | Inter | 14 px | 400 | Texto Secundario |


---

## 3. 🖥️ Prototipo de Alta Fidelidad por Pantallas

A continuación se muestra el aspecto visual final de cada pantalla, aplicando el sistema de diseño definido.

### 3.1 Menú Principal

<img src="../docs/assets/images/Menu Principal Canva.png" width="300" alt="Menu Principal">


**Estructura:**
- Logo superior + título MENÚ PRINCIPAL + 4 botones grandes verticales + botón Salida alineado a la derecha inferior.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: MENÚ PRINCIPAL en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Botones principales: pill-shape grandes con fondo degradado (`#A5F3FC` a `#C4B5FD`), borde blanco sutil, texto azul oscuro (`#1E3A8A`) en Georgia subrayado, sombra suave (`0 4px 6px rgba(0,0,0,0.05)`)
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Textos: Listado, Buscador, Opciones, Acerca de
- Botón Salida: pill degradado reducido (~50 % ancho), alineado a la derecha inferior

---

### 3.2 Listado de Contactos

<img src="../docs/assets/images/Listado Canva.png" width="300" alt="Listado">


**Estructura:**
- Logo superior + título LISTADO + caja central grande scrollable + flechas de navegación (arriba/abajo) a la derecha + botón Atrás a la derecha inferior.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: LISTADO en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Caja central: rectángulo grande con fondo `#C084B5`, borde morado (`#7C3AED`), border-radius amplio (`30px`), padding amplio
- Texto interior: LISTADO DE CONTACTOS centrado en mayúsculas monoespaciada negro
- Área scrollable con items de contacto (fondo semitransparente blanco, bordes redondeados)
- Flechas de navegación: triángulos azules (`#1E3A8A`) puros posicionados a la derecha de la caja, uno apuntando arriba y otro abajo, separación vertical amplia
- Botón Atrás: pill degradado reducido, alineado a la derecha inferior
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)

---

### 3.3 Búsqueda

<img src="../docs/assets/images/Busqueda Canva.png" width="300" alt="Busqueda">


**Estructura:**
- Logo superior + título BÚSQUEDA + selector DESPLEGAR TIPOS + caja de búsqueda + botón Buscar + caja de resultado RESULTADO BÚSQUEDA + botón Atrás a la derecha inferior.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: BÚSQUEDA en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Selector DESPLEGAR TIPOS: rectángulo con fondo `#C084B5`, borde negro (`3px solid #000`), border-radius asimétrico (`30px 0 30px 0`), texto centrado mayúsculas monoespaciado
- Caja de búsqueda: contenedor con fondo `#C084B5`, borde negro (`3px solid #000`), border-radius asimétrico (`30px 0 30px 0`)
- Input interno pill-shape: borde negro, icono lupa a la izquierda, separador vertical, placeholder TEXTO A BUSCAR en mayúsculas
- Botón Buscar: pill degradado reducido, alineado a la derecha
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Caja de resultado: rectángulo grande con fondo `#C084B5`, borde morado (`#7C3AED`), border-radius amplio (`30px`), texto centrado RESULTADO BÚSQUEDA en mayúsculas monoespaciado negro
- Botón Atrás: pill degradado reducido, alineado a la derecha inferior
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
---

### 3.4 Opciones (Submenú)

<img src="../docs/assets/images/Opciones Canva.png" width="300" alt="Opciones">

**Estructura:**
- Logo superior + título OPCIONES + 3 botones grandes verticales + botón Atrás alineado a la derecha inferior.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: OPCIONES en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Botones principales: pill-shape grandes con fondo degradado (`#A5F3FC` a `#C4B5FD`), borde blanco sutil, texto azul oscuro (`#1E3A8A`) en Georgia subrayado, sombra suave (`0 4px 6px rgba(0,0,0,0.05)`)
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Textos: Añadir, Editar, Eliminar
- Botón Atrás: pill degradado reducido, alineado a la derecha inferior

---

### 3.5 Añadir Contacto

<img src="../docs/assets/images/Añadir Canva.png" width="300" alt="Añadir">

**Estructura:**
- Logo superior + título AÑADIR + 5 filas de formulario (label + input) + botones Añadir y Atrás en la parte inferior, uno a cada lado.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: AÑADIR en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Filas de formulario: label en mayúsculas monoespaciada negra a la izquierda + input pill-shape a la derecha
- Inputs: fondo `#C084B5`, borde negro (`2px solid #000`), sombra desplazada (`6px 6px 0px rgba(0,0,0,0.9)`), bordes redondeados completos
- Campos: NOMBRE, APELLIDO, DIRECCIÓN, TELÉFONO, @EMAIL
- Botones inferiores: pill-shape pequeños con fondo degradado (`#A5F3FC` a `#C4B5FD`), borde blanco sutil, texto azul oscuro (`#1E3A8A`) en Georgia subrayado, sombra suave (`0 4px 6px rgba(0,0,0,0.05)`)
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Izquierda: Añadir — Derecha: Atrás

---

### 3.6 Editar (Búsqueda)

<img src="../docs/assets/images/Editar Canva.png" width="300" alt="Editar">

**Estructura:**
- Logo superior + título EDITAR + selector DESPLEGAR TIPOS + caja de búsqueda con lupa + botón Buscar a la derecha + botón Atrás a la derecha inferior.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: EDITAR en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Selector DESPLEGAR TIPOS: rectángulo con fondo `#C084B5`, borde negro (`3px solid #000`), border-radius asimétrico (`30px 0 30px 0`), texto centrado mayúsculas monoespaciado
- Caja de búsqueda: contenedor con fondo `#C084B5`, borde negro (`3px solid #000`), border-radius asimétrico (`30px 0 30px 0`), padding interno
- Input interno pill-shape: borde negro, icono lupa a la izquierda, separador vertical, placeholder TEXTO A BUSCAR en mayúsculas
- Botón Buscar: pill degradado reducido, alineado a la derecha debajo de la caja
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Botón Atrás: pill degradado reducido, alineado a la derecha inferior

---

### 3.7 Editar Campos

<img src="../docs/assets/images/EditarCampos Canva.png" width="300" alt="Editar_Campos">

**Estructura:**
- Logo superior + título EDITAR CAMPOS + 5 filas de formulario pre-rellenadas + botones Editar y Atrás en la parte inferior, uno a cada lado.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: EDITAR CAMPOS en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Filas de formulario: label en mayúsculas monoespaciada negra a la izquierda + input pill-shape a la derecha
- Inputs: fondo `#C084B5`, borde negro (`2px solid #000`), sombra desplazada (`6px 6px 0px rgba(0,0,0,0.9)`), bordes redondeados completos, valores pre-cargados
- Campos: NOMBRE, APELLIDO, DIRECCIÓN, TELÉFONO, @EMAIL
- Botones inferiores: pill-shape pequeños con fondo degradado (`#A5F3FC` a `#C4B5FD`), borde blanco sutil, texto azul oscuro (`#1E3A8A`) en Georgia subrayado, sombra suave (`0 4px 6px rgba(0,0,0,0.05)`)
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Izquierda: Editar — Derecha: Atrás

---

### 3.8 Eliminar Contacto

<img src="../docs/assets/images/Eliminar Canva.png" width="300" alt="Eliminar">


**Estructura:**
- Logo superior + título ELIMINAR + selector DESPLEGAR TIPOS + caja de búsqueda + botón Buscar + caja de resultado RESULTADO BÚSQUEDA + botones Borrar y Atrás en la parte inferior, uno a cada lado.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: ELIMINAR en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Selector DESPLEGAR TIPOS: rectángulo con fondo `#C084B5`, borde negro (`3px solid #000`), border-radius asimétrico (`30px 0 30px 0`), texto centrado mayúsculas monoespaciado
- Caja de búsqueda: contenedor con fondo `#C084B5`, borde negro (`3px solid #000`), border-radius asimétrico (`30px 0 30px 0`)
- Input interno pill-shape: borde negro, icono lupa a la izquierda, separador vertical, placeholder TEXTO A BUSCAR en mayúsculas
- Botón Buscar: pill degradado reducido, alineado a la derecha
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Caja de resultado: rectángulo grande con fondo `#C084B5`, borde morado (`#7C3AED`), border-radius amplio (`30px`), texto centrado RESULTADO BÚSQUEDA en mayúsculas monoespaciado negro
- Botones inferiores: pill-shape pequeños con fondo degradado (`#A5F3FC` a `#C4B5FD`), borde blanco sutil, texto azul oscuro (`#1E3A8A`) en Georgia subrayado, sombra suave (`0 4px 6px rgba(0,0,0,0.05)`)
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Izquierda: Borrar — Derecha: Atrás


---

### 3.9 Acerca De

<img src="../docs/assets/images/AcercaDe Canva.png" width="300" alt="Acerca_De">

**Estructura:**
- Logo superior + título ACERCA DE + caja informativa grande centrada + botón Atrás a la derecha inferior.

**Detalles visuales:**
- Fondo general: `#8FA8C8`
- Logo: *Agendeame* en tipografía cursiva gris oscuro; *ESTA* en negrita itálica gris oscuro escalonado debajo
- Título: ACERCA DE en mayúsculas en mayúsculas, fuente monoespaciada, centrado, tracking amplio
- Caja informativa: rectángulo con fondo #C084B5, borde morado (#7C3AED), border-radius amplio (30px), padding amplio (40px 30px), Texto centrado multilínea en mayúsculas monoespaciado negro, peso bold:
      INFORMACIÓN DE LOS CREADORES Y LA APLICACIÓN
- Hover: oscurecimiento sutil del fondo (`#1D4ED8`)
- Botón Atrás: pill degradado reducido, alineado a la derecha inferior

---

## 4. 🔗 Flujo de Navegación en el Prototipo

El prototipo en Canva se ha estructurado como un **conjunto de páginas enlazadas** que permiten visualizar la experiencia de usuario:

| Origen | Destino | Interacción |
|--------|---------|-------------|
| Menú Principal → Listado | Clic en "LISTADO" | Navegación visual |
| Menú Principal → Búsqueda | Clic en "BÚSQUEDA" | Navegación visual |
| Menú Principal → Opciones | Clic en "OPCIONES" | Navegación visual |
| Menú Principal → Acerca De | Clic en "ACERCADE" | Navegación visual |
| Cualquier pantalla → Menú Principal | Clic en "ATRÁS" | Retorno visual |
| Opciones → Añadir | Clic en "AÑADIR" | Navegación visual |
| Opciones → Editar | Clic en "EDITAR" | Navegación visual |
| Editar → Editar Campos | Selección de resultado | Navegación visual |
| Opciones → Eliminar | Clic en "ELIMINAR" | Navegación visual |
| Eliminar → Confirmación | Clic en "BORRAR" | Overlay visual |

!!! nota "Prototipo estático en Canva"
    Canva permite crear diseños de alta fidelidad y organizarlos en páginas. Aunque no ofrece prototipado interactivo avanzado como Figma, se han diseñado todas las pantallas con la navegación representada mediante flechas y notas explicativas en el propio lienzo de Canva, lo que permite al equipo y a Tamara visualizar el flujo completo de la aplicación.

---

## 5. 📁 Archivos del Prototipo

### Enlace y Recursos

| Recurso | Ubicación / Enlace | Formato |
|---------|-------------------|---------|
| **Prototipo Canva** | [Enlace al proyecto Canva](../docs/assets/documentos/canva.pdf) | PDF |
| **Capturas de pantalla** | `../docs/assets/images/` | PNG |


---

!!! tip "Navegación"
    ← [Fase 5: Diseño Web ](fase5.md) | [Fase 7: Documentación Final ](fase7.md) →


