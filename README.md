# Estación Dulce Yenny

Catálogo web de **Estación Dulce Yenny**, pastelería artesanal de Villa El Salvador, Lima. La página presenta productos, precios, historia de la marca, formas de pedido y contacto directo por WhatsApp.

> **Dulces para compartir.** Alfajores, tartas, queques, gelatinas y antojos caseros preparados para acompañar tus momentos más especiales.

## Vista general

El diseño utiliza una identidad editorial y artesanal basada en verde profundo, verde menta, crema y acentos durazno. Las tipografías son Fraunces, Work Sans y Caveat, con tarjetas redondeadas, espacios amplios y botones tipo píldora.

| Información | Detalle |
|---|---|
| Ubicación | Villa El Salvador, Lima, Perú |
| WhatsApp | [+51 954 525 535](https://wa.me/51954525535) |
| Instagram | [@estaciondulceyenny](https://www.instagram.com/estaciondulceyenny/) |
| Facebook | [Estación Dulce Yenny](https://www.facebook.com/profile.php?id=61584760162220) |
| Horario | Lunes a domingo, 7:00 a. m. – 6:00 p. m. |
| Nueva sección | Cacao puro en taperitos, con precio por confirmar |

## Contenido del catálogo

La página incluye alfajores, crema volteada, tarta de fresa, empanadas de boda, empanadas mixtas o de carne, cheesecake, pay de manzana, queques, galletas de Nida, muffins, gelatina de mosaico, gelatinas florales y turrón artesanal.

Los pedidos se coordinan por WhatsApp. El costo de delivery depende de la zona y los pedidos personalizados o grandes deben consultarse previamente. También se agregó una sección independiente para el **cacao puro en taperitos**. Como todavía no se ha confirmado su precio, la página invita a consultar por WhatsApp en lugar de mostrar un monto incorrecto.

## Estructura recomendada

```text
.
├── index.html
├── README.md
├── PROMPT_GITHUB.md
└── img/
    ├── logo.png
    ├── portada-cheesecake.jpg
    ├── alfajores.jpg
    ├── cheesecake.jpg
    ├── crema-volteada.jpg
    ├── tarta-fresa.jpg
    ├── empanadas-boda.jpg
    ├── empanadas-carne.jpg
    ├── pay-manzana.jpg
    ├── queques.jpg
    ├── galletas-nida.jpg
    ├── muffins.jpg
    ├── gelatina-mosaico.jpg
    ├── gelatinas-florales.jpg
    ├── turron.jpg
    └── yenny.jpg
```

Si todavía no tienes fotografías, el HTML ahora utiliza respaldos visuales con degradados, letras manuscritas y una ilustración CSS de un taper de cacao. Así la página no se ve vacía ni rota. Cuando tengas fotos, puedes agregarlas dentro de `img/` conservando los nombres de archivo correspondientes; las imágenes reemplazarán automáticamente los respaldos.

## Recomendaciones para completar la información

Cuando tengas el dato, conviene agregar el **precio y gramaje del cacao puro**, por ejemplo 100 g, 250 g o 500 g. También puede ser útil indicar si es cacao en polvo, pasta de cacao o nibs, el modo de entrega, los medios de pago y si existen presentaciones para regalo. Mientras esa información no esté confirmada, es mejor mostrar “Consultar precio y disponibilidad” que inventar un valor.

## Publicar en GitHub Pages

Crea un repositorio nuevo, sube `index.html`, `README.md`, `PROMPT_GITHUB.md` y la carpeta `img`. Después entra en **Settings → Pages**, selecciona la rama principal y la carpeta raíz `/root`. Guarda los cambios y espera a que GitHub genere el enlace público.

La página no necesita servidor, base de datos ni instalación de dependencias. Puede abrirse localmente haciendo doble clic en `index.html`.

## Nota importante

GitHub Markdown no puede reproducir por sí solo el diseño visual completo del catálogo. Para que la página se vea como el ejemplo del PDF, el archivo principal debe ser `index.html` y debe publicarse como sitio estático mediante GitHub Pages. El archivo `PROMPT_GITHUB.md` contiene el brief listo para usar con GitHub Copilot u otra herramienta de generación de código.
