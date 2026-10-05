
# PETCARE DOMICILIOS

Prototipo académico navegable para representar la propuesta de gestión de atención domiciliaria para mascotas en Manizales.

## Requerimientos representados

| RF | Flujo ilustrado |
|---|---|
| RF-01 · Gestión de planes y servicios | Consulta y organización del catálogo con tarifas ilustrativas. |
| RF-02 · Registro de mascotas | Registro de mascota, responsable y zona de atención. |
| RF-03 · Programación de citas | Selección de un plan, servicio asociado, mascota, fecha, hora, zona y personal de referencia. |
| RF-04 · Registro de tratamientos | Registro de una atención realizada y observaciones de demostración. |
| RF-05 · Responsable del servicio | Consulta del personal y asignación a citas o atenciones. |
| RF-06 · Organización de rutas | Agrupación de visitas pendientes por zonas de Manizales. |

### Planes de demostración

- **Plan Básico:** Consulta veterinaria, Baño y cuidado, Paseo.
- **Plan Integral:** Consulta veterinaria, Vacunación, Baño y cuidado.
- **Plan Preventivo:** Vacunación y Control posoperatorio.

Los planes guardan IDs de servicios, y las citas registran `planId` y `serviceId` junto con el nombre del servicio para mantener compatibilidad con las vistas existentes. Los datos previos de `localStorage` se conservan; las citas antiguas sin `planId` se muestran como “Sin plan”.

El documento del proyecto limita el trabajo al análisis, diseño y mockups. Este prototipo ilustra interacciones para revisión académica; **no es un sistema productivo**. No incluye backend, base de datos remota, autenticación real, GPS, geolocalización, mapas ni tráfico en tiempo real. Los perfiles y operaciones de ejemplo usan información ficticia y `localStorage` en el navegador actual.

## Estructura

```text
petcare-domicilios/
├── index.html
├── css/styles.css
├── js/app.js
├── README.md
└── .gitignore
```

## Uso

Abre `index.html` en un navegador moderno. No requiere instalación de dependencias. Los cambios se guardan únicamente en el almacenamiento local del navegador donde se abre el prototipo. Usa datos ficticios durante las demostraciones.

## Publicación posterior

El repositorio del proyecto está publicado en https://github.com/JulianOrtiz84/petcare-domicilios. Puedes clonar el repositorio para continuar el desarrollo local.


