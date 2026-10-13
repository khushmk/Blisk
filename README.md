# Prototipos de gestión: colegio, clínica, veterinaria y taller

Cuatro prototipos web funcionales (frontend) hechos con **HTML5, CSS3 (Tailwind CSS vía CDN) y JavaScript puro**. No necesitan servidor ni base de datos: se abren en el navegador y guardan sus datos en el mismo dispositivo con `localStorage`.

## Ver en vivo

Cuando GitHub Pages esté activo, los enlaces serán (reemplaza `TU-USUARIO`):

| Sistema | Enlace |
|---|---|
| Portada con los 4 sistemas | `https://TU-USUARIO.github.io/prototipos-gestion/` |
| Aula Virtual · Colegio San Andrés | `https://TU-USUARIO.github.io/prototipos-gestion/colegio/` |
| Clínica médica y dental | `https://TU-USUARIO.github.io/prototipos-gestion/clinica/` |
| Veterinaria Patitas del Sur | `https://TU-USUARIO.github.io/prototipos-gestion/veterinaria/` |
| Taller mecánico Torque Sur | `https://TU-USUARIO.github.io/prototipos-gestion/taller/` |

## Estructura

```
prototipos-gestion/
├── index.html        Portada con enlaces a los 4 sistemas
├── capturas/         Imágenes de la portada
├── colegio/          Sistema 1: notas, tareas, asistencia, anotaciones, mensajería, anuncios
├── clinica/          Sistema 2: agenda, ficha dinámica, odontograma, exámenes, inventario, presupuestos, finanzas
├── veterinaria/      Sistema 3: mascotas y tutores, carnet de vacunas, agenda, inventario, finanzas
└── taller/           Sistema 4: órdenes de trabajo, agenda por bahías, boletas/facturas, compras, newsletter
```

Cada sistema tiene la misma organización interna:

```
sistema/
├── index.html        Esqueleto de la página
├── css/styles.css    Identidad visual propia
└── js/
    ├── tema.js       Paleta de colores para Tailwind
    ├── config.js / datos.js   Datos del negocio y datos de ejemplo
    └── app.js        Lógica: vistas, acciones y eventos
```

## Probar en tu computador

Abre cualquier `index.html` con doble clic. Para volver a los datos de ejemplo, usa el botón de restablecer (colegio) o borra los datos del sitio desde el navegador.

## Aviso

Son prototipos de demostración: las boletas y facturas no tienen validez tributaria (la emisión real se hace en el SII o con un proveedor autorizado) y el newsletter simula el envío de correos.
