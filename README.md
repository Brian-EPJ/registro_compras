# 🛒 Mis Compras

**Proyecto interactivo de registro de compras** desarrollado con **HTML, CSS y JavaScript puro**.  
Permite llevar un control de compras personales, incluyendo opción de cuotas, visualización de progreso y almacenamiento en el navegador mediante **Local Storage**.

---

## 🌐 Enlace al proyecto

Puedes acceder al proyecto en línea a través de GitHub Pages:  
[https://brian-epj.github.io/registro_compras/](https://brian-epj.github.io/registro_compras/)

---

## 🧰 Tecnologías utilizadas

- **Lenguajes:** HTML, CSS, JavaScript  
- **Almacenamiento:** Local Storage del navegador  
- **Herramientas:** Git, GitHub, Visual Studio Code  

---

## 🚀 Funcionalidades principales

- Agregar compras con:
  - **Descripción**  
  - **Precio**  
  - **Opción de usar cuotas** y cantidad total de cuotas  
- Visualizar lista de compras en tarjetas con:
  - Total de cuotas pagadas  
  - Barra de progreso del pago  
- Editar y eliminar compras existentes  
- Calcular **total a pagar a fin de mes** considerando cuotas  
- Almacenar automáticamente los datos en **Local Storage**, manteniéndolos aunque cierres o recargues el navegador  
- Botón para **limpiar todas las compras**  
🔧 Retos y soluciones

Persistencia de datos: Inicialmente los datos se perdían al recargar la página.

Solución: Implementé Local Storage, lo que permite que los datos permanezcan incluso después de cerrar el navegador.

Gestión de cuotas: Calcular el progreso de pagos de manera dinámica fue un reto.

Solución: Se implementó una barra de progreso que se actualiza automáticamente con cada pago de cuota.

Diseño y responsividad: Ajustar el CSS para que el proyecto se vea bien en diferentes tamaños de pantalla.

Solución: Uso de estilos modernos, colores pastel y flexbox para la disposición de elementos.

