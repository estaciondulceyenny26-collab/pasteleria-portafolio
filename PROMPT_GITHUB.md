# Brief listo para pegar en GitHub Copilot

## Objetivo

Crea una página web responsive para **Estación Dulce Yenny**, una pastelería artesanal ubicada en **Villa El Salvador, Lima, Perú**. La página debe funcionar como un catálogo visual y permitir que los clientes consulten o hagan pedidos por WhatsApp.

Usa HTML, CSS y JavaScript sin frameworks ni dependencias de backend. El resultado debe poder publicarse directamente en **GitHub Pages**. Conserva una estética editorial, artesanal, cálida y elegante, inspirada en una revista de pastelería contemporánea.

## Dirección visual

La página debe utilizar una paleta suave y natural:

| Uso | Color |
|---|---|
| Verde principal | `#55BE87` |
| Verde profundo | `#1F4B3D` |
| Fondo crema | `#FBF8F3` |
| Verde muy claro | `#E7F6ED` |
| Texto oscuro | `#33352F` |
| Acento durazno | `#E8A96B` |
| Texto secundario | `#748076` |
| Líneas y bordes | `#DDE7E0` |

Usa las siguientes fuentes de Google Fonts: **Fraunces** para títulos, **Work Sans** para textos y botones, y **Caveat** para palabras manuscritas decorativas. Los títulos deben sentirse elegantes, orgánicos y artesanales. Las palabras como “compartir”, “creaciones”, “favoritos”, “antojo”, “amamos” y “dulce” deben aparecer con estilo manuscrito en color durazno o verde.

El diseño debe tener fondos crema, tarjetas con bordes redondeados, sombras muy suaves, espacios amplios, bloques verdes oscuros, botones tipo píldora y detalles orgánicos como ondas, círculos y formas decorativas. No uses colores neón, diseños genéricos de tienda, gradientes excesivos ni una interfaz fría de marketplace.

## Estructura de la página

### 1. Barra superior promocional

Incluye una franja verde profunda con el texto:

> Programa tu pedido con nosotros →

Debajo, agrega una nota de temporada:

> Especial de temporada · Turrón artesanal · 1/2 kilo S/ 17.00 · Ver producto

### 2. Encabezado

Incluye el nombre de marca **Estación Dulce Yenny**, navegación hacia las secciones “Catálogo”, “Nuestra historia”, “Visítanos” y “Contacto”, además de un botón visible de WhatsApp.

Usa este número de WhatsApp para todos los enlaces de pedido:

`+51 954 525 535`

El enlace base debe ser:

`https://wa.me/51954525535`

### 3. Portada principal

Crea un hero amplio con fondo verde profundo o una fotografía de cheesecake. Incluye:

- Texto pequeño: `Villa El Salvador, Lima`
- Título: `Dulces para compartir.`
- Descripción: `Alfajores, tartas, queques, gelatinas y antojos caseros preparados para acompañar tus momentos más especiales.`
- Botón principal: `Agenda tu pedido →`
- Botón secundario: `Visítanos ↗`
- Etiqueta superior: `Recomendado para portada: cheesecake`

El botón principal debe abrir WhatsApp con el mensaje:

`Hola, quiero hacer un pedido`

### 4. Sección “Nuestras creaciones”

Presenta cuatro tarjetas visuales con fotografía o imagen de respaldo:

| Categoría | Acción |
|---|---|
| Dulces | Ver más → |
| Tortas & postres | Ver más → |
| Salados | Ver más → |
| Temporada | Ver más → |

Cada tarjeta debe llevar una imagen, un degradado oscuro suave en la parte inferior y el nombre de la categoría con tipografía elegante.

### 4. Sección especial de cacao puro

Agrega una sección independiente, visualmente diferenciada del catálogo de postres, para presentar **cacao puro en taperitos**. No lo mezcles con los dulces si se trata de una línea de producto aparte. Usa un bloque verde profundo con una ilustración CSS elegante de un taper o frasco, etiqueta crema y detalles en marrón cacao. No dependas de una fotografía.

Contenido sugerido:

- Etiqueta: `Una propuesta especial`
- Título: `Cacao puro.`
- Descripción: `Además de nuestros postres artesanales, también ofrecemos cacao puro en prácticos taperitos. Es una opción especial para tener en casa, preparar bebidas, acompañar recetas o regalar.`
- Indicadores: `Producto independiente`, `Presentación en taper`, `Consulta disponibilidad`
- Botón: `Consultar cacao →`
- Mensaje de WhatsApp: `Hola, quiero consultar por el cacao puro`

Como el precio todavía no está confirmado, no muestres un monto inventado. Usa `Consultar precio y disponibilidad` o enlaza directamente a WhatsApp. Deja el precio preparado como una variable fácil de editar cuando se confirme.

### 5. Accesos rápidos

Agrega cuatro accesos horizontales:

1. Recojo en local.
2. Delivery.
3. Visítanos.
4. Ver catálogo.

### 6. Historia de la marca

Crea una sección de dos columnas con fondo verde profundo. En un lado debe aparecer una fotografía de Yenny. En el otro, usa:

- Etiqueta: `Nuestra historia`
- Título: `Volver a lo que amamos.`
- Frase destacada: `Empezamos con más sueños que recursos, y aun así, cada postre que salía nos llenaba de felicidad.`

Texto de historia:

> Estación Dulce Yenny nació de un reencuentro con lo que siempre nos apasionó. Durante mucho tiempo, por necesidad, dejamos la pastelería de lado. Pero esas ganas de volver a hacer postres nunca se fueron, así que decidimos arriesgarnos y dedicarnos a esto al cien por ciento.
>
> Empezamos en un pequeño espacio dentro de un mercado. Después nos mudamos a otro espacio un poco más grande, donde por fin pudimos instalar nuestro horno de siempre, ese que tiene años de historia y de sentimiento con nosotros. Ahí seguimos hoy, preparando cada día alfajores, pays, queques y nuestras tartas de fresa, con el mismo entusiasmo del primer día.
>
> Sabemos que todavía nos falta crecer y que el camino recién empieza. Pero vamos paso a paso, y ahora también estamos dando un paso nuevo: darnos a conocer por acá, en línea. Gracias a cada persona que nos acompaña y disfruta de nuestros postres.

Cierra la sección con:

> Cada postre, una parada dulce en tu día.

### 7. Productos favoritos

Crea tarjetas destacadas para:

| Producto | Categoría | Precio inicial |
|---|---|---:|
| Alfajores | Dulces | Desde S/ 6.00 |
| Tarta de fresa | Tartas | Desde S/ 50.00 |
| Cheesecake | Postres | Desde S/ 60.00 |
| Turrón artesanal | Temporada | Desde S/ 17.00 |

Cada tarjeta debe enlazar a WhatsApp con un mensaje personalizado que mencione el nombre del producto.

### 8. Catálogo completo

Crea filtros funcionales para “Todo”, “Dulces”, “Tortas & postres”, “Salados” y “Temporada”. Cada producto debe mostrarse en una tarjeta con categoría, nombre, descripción, presentaciones, precio y botón “+ Pedir por WhatsApp”.

Usa este catálogo:

| Categoría | Producto | Descripción | Presentaciones y precios |
|---|---|---|---|
| Dulces | Alfajores | Bocados suaves con relleno dulce, ideales para compartir o regalar. | 1/4 de docena S/ 6.00; 1/2 docena S/ 11.00; 1 docena S/ 20.00 |
| Tortas & postres | Crema volteada | Postre casero, suave y cremoso, con el toque caramelizado de siempre. | Tamaño S/ 40.00 |
| Tortas & postres | Tarta de fresa | Base delicada y una cubierta fresca de fresa para una mesa especial. | Tarta S/ 50.00 |
| Dulces | Empanadas de boda | Pequeñas, doraditas y perfectas para acompañar una celebración. | 1/4 de docena S/ 6.00; 1/2 docena S/ 11.00; 1 docena S/ 20.00 |
| Salados | Empanadas mixtas o de carne | Una opción salada para compartir en reuniones, loncheras o celebraciones. | 1/4 de docena S/ 15.00; 1/2 docena S/ 25.00; 1 docena S/ 48.00 |
| Tortas & postres | Cheesecake | Cremoso, delicado y listo para convertirse en el centro de la mesa. | Molde pequeño S/ 60.00; molde grande S/ 80.00 |
| Tortas & postres | Pay de manzana | Un clásico de sabor casero, con manzana y masa doradita. | Molde pequeño S/ 25.00; molde mediano S/ 35.00 |
| Dulces | Queques | Vainilla, naranja y marmoleado; también queque de zanahoria con frutos secos. | Rectangular S/ 15.00; molde de zanahoria S/ 20.00 |
| Dulces | Galletas de Nida | Galletas caseras para compartir, con presentaciones para cada ocasión. | 1/4 de docena S/ 7.00; 1/2 docena S/ 13.00; 1 docena S/ 25.00 |
| Dulces | Muffins | Sabores de chocolate y zanahoria, suaves y perfectos para la merienda. | Unidad S/ 2.50 |
| Tortas & postres | Gelatina de mosaico | Colorida, fresca y cremosa; un postre que alegra cualquier mesa. | Tamaño mediano S/ 35.00 |
| Tortas & postres | Gelatinas florales | Diseños florales hechos con cuidado, para regalar o celebrar. | Vaso chico S/ 5.00; torta S/ 45.00 |
| Temporada | Turrón artesanal | Especial de temporada para compartir durante el mes del Señor de los Milagros. | 1/2 kilo S/ 17.00 |

Aclara que los precios corresponden a las presentaciones indicadas y que las decoraciones especiales, pedidos grandes o fechas específicas deben consultarse por WhatsApp.

### 9. Cómo pedir

Incluye tres pasos:

| Paso | Título | Texto |
|---:|---|---|
| 01 | Elige | Revisa el catálogo y decide el postre y la presentación que quieres. |
| 02 | Escríbenos | Pulsa “Pedir por WhatsApp” y recibirás un mensaje listo con tu elección. |
| 03 | Confirma | Coordinamos contigo los detalles finales de disponibilidad y entrega. |

### 10. Visítanos

Incluye tres tarjetas:

- **Recojo en local:** Villa El Salvador. Escribir por WhatsApp para coordinar el horario.
- **Delivery cercano:** Villa El Salvador y distritos cercanos. El costo se confirma según la zona.
- **Horarios:** Lunes a domingo, de 7:00 a. m. a 6:00 p. m. Los pedidos pequeños requieren al menos 2 días de anticipación.

### 11. Contacto

Crea un bloque verde claro con el título:

> Hagamos algo dulce.

Incluye el número `+51 954 525 535` y un botón `Abrir WhatsApp ↗`.

### 12. Pie de página

Incluye la frase:

> Postres artesanales hechos con cariño en Villa El Salvador, Lima.

Agrega estos enlaces:

- Instagram: `https://www.instagram.com/estaciondulceyenny/`
- Facebook: `https://www.facebook.com/profile.php?id=61584760162220`
- WhatsApp: `https://wa.me/51954525535`

## Requisitos técnicos

La página debe ser completamente responsive para celular, tablet y computadora. Debe tener navegación con anclas, filtros funcionales del catálogo, botones de WhatsApp con mensajes personalizados, estados hover suaves, texto alternativo en imágenes y soporte para `prefers-reduced-motion`.

Organiza el repositorio de esta forma:

```text
estacion-dulce-yenny/
├── index.html
├── README.md
└── img/
    ├── logo.png
    ├── portada-cheesecake.jpg
    ├── alfajores.jpg
    ├── cheesecake.jpg
    ├── empanadas-carne.jpg
    ├── turron.jpg
    ├── yenny.jpg
    └── demás-imágenes-del-catálogo
```

Si una imagen todavía no existe, muestra un respaldo visual elegante con degradados, formas decorativas y el nombre del producto. Para la sección de cacao, usa una ilustración CSS de un taper o frasco en lugar de dejar un espacio vacío. No inventes una dirección exacta, precio, gramaje ni información que no haya sido proporcionada.

## Resultado esperado

Entrega un `index.html` completo, limpio y funcional. Incluye todo el CSS y JavaScript necesario para que el proyecto pueda abrirse localmente haciendo doble clic en `index.html` y pueda publicarse en GitHub Pages sin configuración adicional.
