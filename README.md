# Practicas - Sistemas Gestion Empresarial

### Autor
- <b>Nombre:</b> Daniel Mayor Sánchez
- <b>Ciclo:</b> DAM 
- <b>Curso:</b> 2.º A

# Estructura
- Ejercicio 01 - Creación de Productos
- Ejercicio 02 - Administración del Almacen
- Practica 01 - Exportar e Importar Datos
- Practica 02 - Rutas de Abastecimiento
- Practica 03 - Modulos de Inventario
- Ejercicio 03 - Modulos de RRHH
- Practica 04 - Sitio Web
- Practica 05 - Comercio Electronico
- Ejercicio 04 - PoS Restaurante

## Ejercicio 01 - Creación de Productos
### Creación del inventario
- Debes crear una nueva base de datos para esta práctica.
- Crea 3 usuarios nuevos
- Realiza la instalación de los módulos necesarios para la gestión de clientes, compras, ventas, facturación e inventario.
- La empresa tiene un almacén central en Alquerías y dos almacenes a los que distribuye material desde el almacén central, uno en Moratalla y otro en Águilas.
- Crea al menos 5 categorías de productos y varios productos en cada una de ellas. Asigna un proveedor a cada producto.

### Entrega
- Debes entregar un documento dónde se pruebe que has realizado el ejercicio.
- Para el listado de los productos, tendrás que entregar un listado de un informe en pdf.

## Ejercicio 02 - Administración del Almacen
Después de haber creado los almacenes y productos en el ejercicio anterior, visualiza el vídeo 05 de los contenidos y repasa tu configuración. Ve realizando las siguientes tareas:

1. Configura la vista de inventario, ordenada por almacenes.
2. Activa el seguimiento por lotes y las variantes de producto.
3. Instala los módulos de mantenimiento y fabricación
4. Introduce al menos 3 proveedores
5. Crea órdenes de compra para abastecer tu almacén principal de productos
6. Sigue el flujo de compra que se muestra en el vídeo (deberás documentar y entregar dicho flujo)
7. Crea un producto que sea un ordenador montado y que esté compuesto por varios componentes.
8. Crea una caja para ordenador que tenga varias variantes de color
9. Crea órdenes de compra para el abastecimiento.
10. Crea notas y planifica la llamada al proveedor en 3 días.
11. Genera varias ventas, siguiendo el flujo mostrado en el vídeo.
12. Muestra cómo varía el stock de productos.

- Puedes necesitar crear más usuarios, clientes o proveedores. Crea los que consideres necesarios para realizar una práctica lo más real posible.
- Debes documentar cada uno de los apartados anteriores. Para las órdenes de compra, presupuestos, albaranes, facturas y demás documentos, debes realizar la impresión en pdf y añadirlo a la documentación que deberás entregar.
- Documenta cualquier otra cuestión que consideres interesante, o los problemas con los que te hayas encontrado durante la realización de este ejercicio.

## Practica 01 - Exportar e Importar Datos
Esta práctica consiste en realizar la exportación e importación de datos en Odoo. Debes realizar las siguientes tareas:

1. Crea una estructura de categorías y subcategorías de producto.
2. Realiza la exportación de los datos en un fichero csv.
3. En otra base de datos, importa los datos.
4. Crea al menos 5 productos (de la categoría escogida en clase) en el fichero product_template.csv adjunto.
5. Puedes hacerlo directamente en el fichero csv o exportando los datos desde Odoo. Debe tener las mismas columnas que el fichero adjunto

Debes entregar el fichero csv relleno y un documento dónde expliques los pasos 1, 2 y 3. Se adjunta el fichero de las categorías planteadas en clase, directamente para importar (product_category.csv) IMPORTANTE la categoría escogida se escribirá en el foro general de #slack.

## Practica 02 - Rutas de Abastecimiento
Configurar las rutas de abastecimiento para que funcionen con las rutas creadas anteriormente, Abastecimiento Alquerías, Requerimientos Alquerías:

1. Configurar las reglas de ambos almacenes (Águilas y Moratalla) para que se comporten como el almacén de Águilas.<br>Almacén Principal ---- PULL --> Águilas Abasteciemiento         Águilas Abastecimiento --- PULL --> Stock Águilas
2. Establecer reglas de abastecimiento para un producto en el almacén principal. Con la ruta de compras.
3.Establecer reglas de abastecimiento para el mismo producto en el almacén de Águilas, usando la ruta Abastecimiento Águilas
4. Establecer reglas de abastecimiento para el mismo producto en el almacén de Moratalla, usando la ruta Abastecimiento Moratalla
5. Establecer las cantidades de stock del producto seleccionado, por debajo de las reglas de abastecimiento.
6. Ejecutar el planificador.
7. Comprobar que se han creado los documentos necesarios para satisfacer todas las rutas de abastecimiento.
8. Realizar el flujo de abastecimiento. Aceptar el pedido de compra y realizar ambas transacciones a los almacenes.

Entregar documentación dónde se observe todo el procedimiento seguido.

## Practica 03 - Modulos Inventario
Debes buscar y evaluar dos módulos para Inventario que añadan alguna funcionalidad interesante.

1. Realiza una copia de seguridad de la base de datos de Odoo
2. Busca dos módulos para inventario, instálalos y prueba su funcionamiento.
3. Realiza una documentación y una breve exposición para realizarla en clase. 10 minutos máximo.

## Ejercicio 03 - Modulos de RRHH
Realiza una presentación sobre el módulo de RRHH asignado:

- Procesos Selección
- Flota
- Gastos
- Habilidades
- Comidas

## Practica 04 - Sitio Web
Explora la funcionalidad del módulo Sitio Web:

- Interesa la funcionalidad, no el diseño de logotipos ni páginas.
- Explorar los componentes disponibles para crear las distintas páginas WEB.
- Tenéis que mostrar las funcionalidades que ofrece el módulo desde el punto de vista de los clientes de vuestra empresa.
- Crear un documento con vuestros nombres, en el que relatéis de forma breve cada funcionalidad explorada y la bibliografía utilizada.
- Se realizará una presentación entre el Lunes 31 y martes 1 dónde se mostrarán las distintas funcionalidades.

## Practica 05 - Comercio Electronico
Tomando como referencia la documentación del siguiente enlace: https://www.odoo.com/documentation/14.0/es/applications/websites/ecommerce.html crea la parte de comercio electrónico para la página que habéis creado en la práctica 04.

Deben tratarse al menos los siguientes apartados (8 puntos):

- Creación de una página de producto
- Customización de la página de catálogo
- Mostrar varias imágenes de producto
- Administrar las variantes de producto
- Cómo importar productos con categorías y variantes
- Impuestos predeterminados
- Cómo acceden los clientes a sus cuentas
- Cómo vender productos alternativos más caros
- Venta cruzada
- Habilitar comentarios y calificación
- Adaptar los precios a los visitantes de la web
- Crear y compartir códigos promocionales

Cualquier detalle adicional, módulo complementario o mejora a esta documentación será tenido en cuenta. (2 puntos)

- Si no se trata alguno de los apartados, la calificación será negativa.

Entrega:
- Consistirá en la documentación y una presentación que no supere los 15 minutos por grupo.

## Ejercicio 04 - PoS Restaurante
Estudiar las configuración del punto de venta para un restaurante.
Crear una presentación (que debéis entregar aquí) para explicar las opciones de configuración y el funcionamiento.

Se deberá incluir como mínimo: (8 puntos)
- Mesas ( 2 puntos )
- Dividir cuentas (1 punto)
- Imprimir el ticket (1 punto)
- Imprimir órdenes en cocina o bar (2 puntos)
- Propinas (2 puntos)
- Mejoras u otras características (2 puntos)
