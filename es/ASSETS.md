# Assets de la versión en español latinoamericano

Estas imágenes son exclusivas de `/es/`. La página en portugués y la carpeta
`/assets/` original no se modificaron. Las 18 fotos sin texto se copiaron sin
cambios; las nueve piezas que contenían texto se localizaron con la herramienta
integrada `image_gen` (edición `text-localization`, sin API/CLI externo).

## Instrucción común de los prompts

Editar la imagen original para español latinoamericano. Conservar composición,
proporción, perspectiva de los libros, ubicación de los objetos, fotografías de
comida, iluminación, colores y estilo tipográfico. Traducir TODO el texto en
portugués, incluidos lomos, pantallas, sellos y leyendas pequeñas. Usar español
natural y legible. No añadir productos ni promesas. Entregar una sola imagen
completa, sin comparaciones ni márgenes nuevos. Conservar la transparencia del
sello de garantía. La codificación a WebP es solo para reducir el peso de las
imágenes generadas, sin cambiar su contenido.

## Prompts de cada pieza

- `assets/banner-airfryer-v3-es.webp`: "+200 RECETAS en AIR FRYER";
  "¡PRÁCTICAS, SALUDABLES E IRRESISTIBLES!"; "¡PARA TODA LA FAMILIA!";
  "Más de 200 recetas fáciles, rápidas y sabrosas para todos los días".
  Pantalla: "Recetas en Air Fryer", "Carnes", "Pollo", "Pescados", "Verduras",
  "Pastas", "Postres", "DESTACADAS", "MÁS VISTAS", "Pollo crocante con hierbas",
  "Croquetas de papa rellenas", "Verduras asadas al romero", "Albóndigas con queso".
  Iconos: "PRÁCTICAS Y RÁPIDAS", "SALUDABLES Y NUTRITIVAS",
  "MENOS TIEMPO, MÁS SABOR", "PARA TODA LA FAMILIA". Conservar la identidad de la chef.
- `assets/bonus-lista-compras-es.webp`: "Lista de Compras Inteligente";
  "¡4 SEMANAS ORGANIZADAS PARA AHORRAR TIEMPO Y DINERO!";
  "PLAN SEMANAL", "DESAYUNO", "ALMUERZO", "CENA", "MERIENDA", "HIGIENE Y LIMPIEZA";
  "¡COMPRA SOLO LO NECESARIO Y EVITA DESPERDICIOS!";
  "¡PRÁCTICO, COMPLETO Y FÁCIL DE USAR!". Mismo título en el lomo.
- `assets/bonus-cardapio-30-es.webp`: "Menú Listo de 30 Días EN AIR FRYER";
  "¡PLANIFICA TUS COMIDAS Y OLVÍDATE DE LA DUDA DE QUÉ COCINAR!";
  "PLAN COMPLETO", "ALMUERZOS", "CENAS", "MERIENDAS", "POSTRES";
  "¡30 DÍAS DE PRACTICIDAD, SABOR Y VARIEDAD!". Mismo título en el lomo.
- `assets/bonus-congelamento-es.webp`: "Guía de Congelación y Recalentado";
  "¡CÓMO CONGELAR Y RECALENTAR CORRECTAMENTE PARA CONSERVAR SABOR, TEXTURA Y PRACTICIDAD!";
  "¡CONGELA HOY, DISFRUTA MAÑANA!"; "CONSEJOS PARA CONGELAR CORRECTAMENTE";
  "CÓMO RECALENTAR SIN RESECAR"; "ORGANIZA TUS COMIDAS CON FACILIDAD";
  "MENOS DESPERDICIO, MÁS AHORRO Y TIEMPO PARA TI". Mismo título en el lomo.
- `assets/bonus-temperos-es.webp`: "30 Condimentos y Salsas";
  "PARA VARIAR LOS SABORES";
  "¡COMBINACIONES PRÁCTICAS PARA TRANSFORMAR TUS RECETAS EN AIR FRYER!";
  "¡MÁS SABOR, MÁS CREATIVIDAD TODOS LOS DÍAS!";
  "PRÁCTICOS Y RÁPIDOS", "INGREDIENTES SENCILLOS", "COMBINAN CON TODO",
  "MÁS SABOR SIN COMPLICACIONES", "PARA TODA LA FAMILIA". Mismo título en el lomo.
- `assets/bonus-15min-es.webp`: "50 Recetas Listas en Hasta 15 Minutos EN AIR FRYER";
  "¡PRACTICIDAD Y SABOR PARA TUS DÍAS MÁS OCUPADOS!";
  "¡RECETAS RÁPIDAS, SABROSAS Y FÁCILES PARA SIMPLIFICAR TU RUTINA!";
  "LISTO EN HASTA 15 MINUTOS", "HECHO 100% EN AIR FRYER", "INGREDIENTES SENCILLOS",
  "MÁS TIEMPO PARA TI", "PERFECTO PARA CUALQUIER COMIDA". Mismo título en el lomo.
- `assets/bonus-romanticos-es.webp`: "+40 Cenas Románticas PARA PAREJAS EN AIR FRYER";
  "¡Momentos inolvidables con recetas que enamoran por su sabor y cariño!";
  "¡RECETAS SOFISTICADAS Y FÁCILES PARA SORPRENDER A QUIEN AMAS!";
  "IDEAS PARA TODAS LAS OCASIONES", "PLATOS COMPLETOS Y EQUILIBRADOS",
  "HECHO EN AIR FRYER", "MÁS SABOR, ROMANCE Y CONEXIÓN". Mismo título en el lomo.
- `assets/recipes-showcase-airfryer-v2-es.webp`: usar los mismos títulos y textos
  anteriores en todos los libros. Título principal "+200 Recetas en AIR FRYER";
  "¡PRÁCTICAS, SALUDABLES E IRRESISTIBLES!";
  "¡Más de 200 recetas fáciles, rápidas y sabrosas para todos los días!";
  "¡ACCESO INMEDIATO EN LA APP Y EN EL SITIO!"; "PARA TODA LA FAMILIA".
  Laptop: "Hola, Chef Luana", "¡Bienvenida a tu libro de recetas!", "Inicio",
  "Recetas", "Favoritos", "Categorías", "Lista de compras", "Más recientes",
  "Mis favoritas", "Recetas destacadas", "Pollo crocante", "Salmón con verduras",
  "Albóndigas", "Pan de queso". Celular: "Salmón con verduras en Air Fryer",
  "20 min", "Fácil", "2 porciones", "Ingredientes", "Preparación",
  "Sazona el salmón al gusto.", "Precalienta a 200 °C por 3 minutos.",
  "Coloca el salmón y las verduras en la canasta.", "Cocina de 15 a 18 minutos.",
  "¡Sirve y disfruta!", "Favorito", "Compartir". Otros títulos del mosaico:
  "GUÍA DE TEMPERATURAS", "GUÍA DE LIMPIEZA Y CUIDADOS".
- `assets/JkRnpY1-es.png`: texto exacto "GARANTÍA", "15 DÍAS", "INCONDICIONAL";
  conservar las tildes, hojas de laurel doradas, estrellas, anillos y fondo transparente.

La versión `/es/index.html` carga sus 27 imágenes desde `assets/` relativo a su
propia carpeta. No volver a enlazar estos archivos a `../assets/` al regenerar HTML.
