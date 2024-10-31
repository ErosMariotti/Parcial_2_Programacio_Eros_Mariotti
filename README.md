# Parcial 2 Programación | Proyecto Integrador

# ¿En qué consiste el proyecto?

Este proyecto es una aplicación web de gestión de productos que permite a los usuarios agregar, modificar, buscar y eliminar productos. Su interfaz intuitiva permite organizar productos en diferentes categorías y almacenar estos datos de manera local usando LocalStorage. Esta aplicación es ideal para pequeños negocios o tiendas online que necesiten un sistema simple y efectivo para administrar su inventario.

# Estructura

- HTML: Estructura de la página principal y modal emergente para agregar o modificar productos.
- CSS: Estilos que definen la apariencia de los elementos de la página.
- JavaScript: Lógica de la aplicación dividida en módulos:
      main.js: Controlador principal, configura eventos y estados globales.
      store.js: Gestiona el listado de productos y la interfaz de categorías.
      modal.js: Controla la apertura y cierre de modales para agregar o modificar productos.
      product.js: Lógica de almacenamiento y manejo de productos en LocalStorage.
      searchBar.js: Función para filtrar productos por nombre.

# Lógica de la página y explicación de funcionalidades principales

1. Búsqueda de Productos: Al ingresar el nombre en la barra de búsqueda, se filtran los productos que coinciden.
2. Agregar Producto: El botón "Agregar Elemento" abre un modal en el que se puede agregar el nombre, imagen, precio y categoría del producto. Estos datos se almacenan en LocalStorage.
3. Modificar Producto: Al hacer clic en un producto existente, el modal se llena con sus datos actuales, permitiendo modificaciones.
4. Eliminar Producto: Dentro del modal, el botón "Eliminar" permite eliminar el producto seleccionado tras una confirmación.

# Tecnologías implementadas

- HTML5 y CSS3 para la estructura y estilo de la aplicación.
- JavaScript ES6+ para la lógica de la aplicación y el almacenamiento de datos en LocalStorage.
- LocalStorage para persistir datos localmente.
- SweetAlert2 para mostrar alertas y confirmaciones de manera atractiva.

# Aspectos y detalles importantes

La aplicación persiste los datos en LocalStorage, lo que significa que estos permanecerán hasta que el almacenamiento sea borrado.
Las categorías están predeterminadas en el código (Gaseosas, Hamburguesas, Papas).
El código organiza las funciones en módulos, lo que facilita la escalabilidad y mantenimiento.

# Paso a paso de cómo ejecutar el código

Clonar el repositorio en el entorno local.

```
bash
git clone <URL-del-repositorio>
```

Navegar al directorio del proyecto.

```
bash
cd nombre-del-proyecto
```

Abrir el archivo index.html en un navegador.

Colocar en la terminal:

```
npm install

npm run dev
```

La aplicación está lista para su uso.
