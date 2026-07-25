# 📱 Agéndame Esta
### Aplicación Móvil de Gestión de Contactos

**Proyecto Intermodular — Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)**  
**IES L'Estació — Ontinyent (Valencia) | Curso 2025/2026**

---

## 📋 1. Introducción

**Agéndame Esta** es una aplicación móvil nativa para Android diseñada como una agenda digital integral. Permite almacenar, organizar, consultar, editar y eliminar información de contactos de forma local, sin dependencia de conexión a internet.

El proyecto nace como entrega final de la asignatura Intermodular del CFGS en DAM, con el objetivo de aplicar conocimientos de desarrollo móvil estructurado mediante **MIT App Inventor 2**, simulando un ciclo de vida real de software con planificación, diseño UX/UI y documentación rigurosa.

---

## 🎯 2. Objetivos

- **Funcional:** Crear una agenda digital moderna con operaciones CRUD completas y navegación fluida.
- **Técnico:** Integrar conocimientos de desarrollo móvil visual estructurado con MIT App Inventor 2.
- **Metodológico:** Simular el ciclo de vida de un desarrollo de software real, incluyendo planificación, diseño y documentación.
- **Formativo:** Consolidar el trabajo en equipo bajo control de versiones estricto y metodologías ágiles.

---

## 🛠️ 3. Problema que resuelve

La aplicación unifica la información de contactos que suele estar fragmentada en libretas, correos o dispositivos antiguos. Evita duplicidades, previene la pérdida de datos y permite el acceso inmediato y continuo desde el smartphone, integrando además llamadas y envío de correos directos.

---

## 👥 4. Equipo de desarrollo y contexto

- **Desarrolladores:** Ramón Vicente Picazo Cayuela & Anna Pérez Company
- **Docente evaluador:** Tamara Climent Fuentes
- **Centro educativo:** IES L'Estació (Ontinyent, Valencia)
- **Fecha de entrega:** 05/06/2026

---

## ✨ 5. Características principales

- 📇 **Gestión CRUD completa:** añadir, listar, editar y eliminar contactos.
- 🔍 **Búsqueda dinámica:** filtrado avanzado por múltiples campos.
- 📞 **Integración nativa:** llamadas telefónicas y envío de correos desde la ficha del contacto.
- 💾 **Funcionamiento offline:** almacenamiento local instantáneo sin necesidad de red.
- 📤 **Compartir contactos:** opción para compartir fichas de contactos.
- 📱 **UI responsive:** diseñada para usarse cómodamente con una sola mano en terminales Android.

---

## 🛠️ 6. Tecnologías y herramientas utilizadas

| Área | Herramienta / Tecnología |
|---|---|
| Entorno de desarrollo | MIT App Inventor 2 (UI y lógica de bloques) |
| Base de datos | TinyDB (NoSQL embebida local clave-valor) |
| Diseño y prototipado UX | Canva (alta fidelidad) |
| Planificación | Trello y Microsoft Project |
| Documentación | Markdown, MkDocs y Material for MkDocs |
| Control de versiones | Git y GitHub (repositorio privado) |
| Comunicación | Microsoft Teams |

---

## 🗺️ 7. Arquitectura y navegación

La app cuenta con una arquitectura lineal de **9 pantallas** distribuidas en árbol, evitando callejones sin salida o bucles infinitos. Todas las pantallas subordinadas incluyen un botón unificado **"Atrás"**.

- **Menú principal:** hub centralizador.
- **Listado de contactos:** visualización masiva local.
- **Búsqueda:** filtrado dinámico.
- **Opciones:** submenú de enrutamiento CRUD.
- **Añadir contacto:** formulario de inserción.
- **Editar contacto:** pasarela de selección de registro.
- **Editar campos:** formulario de modificación con precarga.
- **Eliminar contacto:** interfaz de remoción con diálogo de confirmación.
- **Acerca de:** créditos e información de la build.

---

## 🎨 8. Guía de estilos

- **Colores identitarios:** azules profundos para botones principales y títulos.
- **Acciones positivas:** tonos verdes para guardado y confirmación.
- **Acciones de peligro:** tonos rojos para eliminar registros.
- **Fondos:** gris azulado `#8FA8C8` con áreas de contenido en lila degradado `#C084B5`.
- **Tipografía:** Inter, con `24px Bold` para rótulos y `14px Medium/Regular` para datos.

---

## 📂 9. Estructura del repositorio

```plaintext
Projecto-Intermodular-Final-Dam1/
├── mkdocs.yml                 # Configuración de la documentación MkDocs
├── docs/                      # Portal web formativo
│   ├── index.md
│   ├── fase1.md
│   ├── ...
│   └── assets/
│       └── imagenes/
├── planificacion/             # Gestión del proyecto
│   ├── cronograma.mpp
│   └── capturas_trello/
├── diseno/                    # UX y estructuras visuales
│   └── mapa_estructural.pdf
└── src/                       # Código fuente de la aplicación
    ├── AgendameEsta.aia       # Proyecto editable en App Inventor
    └── AgendameEsta.apk       # Ejecutable instalable en Android
```

---

## ⚙️ 10. Metodología de trabajo

Se adoptó un modelo híbrido ágil (**Scrum + Kanban**) adaptado a un equipo de dos personas, evitando la sobrecarga burocrática pero manteniendo iteraciones cerradas.

- **Ceremonias:** Daily Standup (10–15 min diarios), Sprint Planning (lunes), Sprint Review y retrospectiva (viernes).
- **Control de versiones:** flujo Git con rama `main` para producción, `develop` para integración y ramas `feature/nombre-tarea`.
- **Buenas prácticas:** commits descriptivos en español y Pull Requests obligatorios con revisión cruzada.

---

## 🚀 11. Ejecución y despliegue

Para probar la aplicación en un entorno local:

1. **Instalar el APK:** descarga el archivo `AgendameEsta.apk` desde la carpeta `/src` e instálalo en cualquier dispositivo Android físico.
2. **Modificar el código:** importa el archivo `AgendameEsta.aia` en el entorno web de [MIT App Inventor 2](https://ai2.appinventor.mit.edu/) para inspeccionar o modificar la lógica de bloques y la interfaz visual.

---

## 🔮 12. Futuras líneas de trabajo

- **Migración a la nube:** implementar Firebase para sincronización de contactos en la nube y multiplataforma.
- **Importación masiva:** desarrollar módulos para importar contactos desde archivos estructurados CSV.

---

## 🙏 13. Agradecimientos

El equipo de desarrollo desea expresar su gratitud a:

- IES L'Estació de Ontinyent por proveer las instalaciones y el entorno de aprendizaje.
- Tamara Climent Fuentes, profesora de Intermodular, por su guía, directrices y seguimiento constante.
- Compañeros de la clase de DAM por actuar como entorno de pruebas y aportar feedback técnico.