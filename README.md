# SmartMeal

Aplicación web educativa para registrar compras, consultar gastos, explorar ideas de comidas y visualizar perfiles demostrativos de profesionales de la nutrición.

## Estructura

```text
SmartMeal-GitHub/
├── index.html                 # Estructura y navegación
├── css/
│   └── styles.css             # Diseño adaptable
├── js/
│   └── app.js                 # Compras, pagos, historial y formularios
├── assets/
│   └── img/
│       └── logo-smartmeal.png # Logo y favicon
└── README.md
```

## Abrir en VS Code

1. Descomprimí el ZIP y abrí la carpeta `SmartMeal-GitHub` en VS Code.
2. Abrí `index.html` con Live Server o directamente en el navegador.
3. No requiere instalar paquetes ni ejecutar comandos de compilación.

## Subir a GitHub

En **Control de código fuente** de VS Code, elegí **Inicializar repositorio**, confirmá los archivos con un mensaje y usá **Publicar en GitHub**. También podés subir el contenido de esta carpeta con **Add file > Upload files** desde el sitio de GitHub. Conservá las carpetas `css`, `js` y `assets` con estas rutas.

Si ya tenés un repositorio SmartMeal, abrilo primero y copiá allí estos archivos. Revisá las diferencias antes de confirmar cambios para no reemplazar trabajo anterior que quieras conservar.

## Publicar con GitHub Pages

En tu repositorio abrí **Settings > Pages**. Seleccioná **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`. Guardá y esperá a que GitHub muestre la URL.

## Alcance del prototipo

- **Comprando:** carga productos, cantidades, precios y comercios. El pago se elige para el total antes de guardar.
- **Mis compras:** muestra y permite eliminar compras guardadas.
- **Ideas de comidas:** señala ingredientes que coinciden con la compra en curso.
- **Profesionales:** perfiles ficticios y borrador de consulta que no se envía.
- **Mi perfil profesional:** vista previa guardada localmente.

Los datos se guardan en el `localStorage` de cada navegador. No hay cuentas, servidor ni base de datos, por lo que no se sincronizan entre dispositivos. La información alimentaria es general y no reemplaza una consulta profesional.
