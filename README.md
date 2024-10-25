# Tienda_Ropa_POOBootcamp.

## Clases Implementadas

### 1. Producto
- Clase base que representa un producto general.
- Contiene atributos como nombre, precio y categoría.
- Métodos para mostrar información del producto.

### 2. Camisa
- Hereda de la clase `Producto`.
- Añade el atributo específico de talla.
- Sobrescribe el método `mostrar_info` para incluir información de la talla.

### 3. Pantalon
- Hereda de la clase `Producto`.
- Añade el atributo específico de talla.
- Sobrescribe el método `mostrar_info`.

### 4. Zapato
- Hereda de la clase `Producto`.
- Añade el atributo específico de talla.
- Sobrescribe el método `mostrar_info`.

### 5. Carrito
- Clase que gestiona los productos seleccionados para la compra.
- Métodos para agregar productos al carrito y calcular el total.

### 6. Tienda
- Clase que maneja los productos disponibles y las compras.
- Métodos para agregar productos y mostrar la lista de productos disponibles.

### 7. SistemaCompras
- Clase principal que inicia el programa y gestiona la interacción con el usuario.
- Permite a los usuarios seleccionar productos y muestra el resumen final de la compra.

## Pilares de POO Implementados

- **Encapsulamiento**: Los atributos de las clases están encapsulados y se accede a ellos a través de métodos getters.
- **Herencia**: Las clases `Camisa`, `Pantalon` y `Zapato` heredan de `Producto`, lo que permite reutilizar código.
- **Polimorfismo**: Se utiliza el método `mostrar_info` en cada clase hija para mostrar información específica de cada producto.
- **Abstracción**: Se ocultan los detalles internos del proceso de compra, permitiendo al usuario enfocarse en la selección de productos.

## Interacción con el Usuario

1. Al ejecutar el programa, se mostrarán los productos disponibles.
2. El usuario puede seleccionar uno o más productos para agregar al carrito.
3. Al finalizar la selección, se mostrará un resumen de los productos seleccionados y el total a pagar.

## Cómo Ejecutar el Programa

Para ejecutar el programa, sigue estos pasos:

1. **Clona este repositorio** en tu máquina local utilizando el siguiente comando:
   ```bash
   git clone https://github.com/Oscar818ss/Tienda_Ropa_POOBootcamp.git

