
# DonGalleto

## Contexto

La empresa DonGalleto se dedica a la producción y venta de galletas, y es operada únicamente por el dueño y su esposa.

La empresa elabora 10 tipos de galletas diferentes utilizando insumos para cada tipo de galleta y cuenta con un proceso de venta a granel o paquetes ya sea por cantidad o peso.

## Problemática

La producción enfrenta desafíos debido a la falta de un sistema de gestión adecuado, lo que complica el manejo de inventarios y las solicitudes de materias primas. Esto afecta directamente su eficiencia, control financiero y capacidad para satisfacer la demanda del mercado.

## Justificación

La implementación de un sistema de gestión resolverá las siguientes problemáticas:

- Gestión deficiente de la producción y ventas
- Falta de control de inventarios
- control de insumos y pedidos con proveedores
- Pérdidas por caducidad y merma para productos
- Pérdidas por caducidad y merma para insumos
- Faltante de ganancias

## Módulos

### 1. Modulo ventas
- Generar ventas
- Generar Descuentos
- Generar tickets

### 2. Modulo de Inventario
- creación de lotes de galletas
- creación de paquetes de galletas
- merma de galletas
- merma de paquetes de galletas
- visualización de productos

### 3. Producción
- Visualización de Producción de galletas por hacer

### 4. Recetas
- Visualización de recetas de galletas

### 5. Modulo de Insumos
- Registro de insumos
  - merma/eliminación de insumos
- visualización de productos
- solicitud a proveedores

### 6. Modulo de reportes
- Visualizar reportes de ventas
- Crear reportes de ventas
- Crear Reportes de ganancias totales (Incluyendo gastos regulares)
- Crear reportes de gastos en insumos

## Actualizaciones necesarias
- Es recomendable cambiar el sistema de ventas por un modelo de 2 tablas, una tabla izquierda que muestre el ticket de venta, todo lo que se va a vender, y una tabla derecha que muestre la disponibilidad de productos que hay para vender, para de esta forma no seleccionar un producto que no hay
- corregir el modulo de inventario, agregar la merma global, que permita mermar tanto paquetes como galletas a granel en una unica funcion para mayor practicidad
- implementar la adaptabilidad del inventario dependiendo la temporada del año
- **unificar la base de datos**
  
  
  
⢸⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⡷  
⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀ ⠀⠢⣀  
⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇ Are you programming son?  
⢸⠀⠀⠀⠀ ⠖⠒⠒⠒⢤⠀⠀⠀⠀⠀⡇  
⢸⠀⠀⣀⢤⣼⣀⡠⠤⠤⠼⠤⡄⠀⠀⡇  
⢸⠀⠀⠑⡤⠤⡒⠒⠒⡊⠙⡏⠀⢀⠀⡇  
⢸⠀⠀⠀⠇⠀⣀⣀⣀⣀⢀⠧⠟⠁⠀⡇  
⢸⠀⠀⠀⠸⣀⠀⠀⠈⢉⠟⠓  
⢸⠀⠀⠀⠀⠈⢱⡖⠋⠁⠀⠀⠀⠀⠀⠀⡇  
⢸⠀⠀⠀⠀⣠⢺⠧⢄⣀⠀⠀⣀⣀⠀⠀⡇  
⢸⠀⠀⠀⣠⠃⢸⠀⠀⠈⠉⡽⠿⠯⡆  
⢸⠀⠀⣰⠁⠀⢸⠀⠀⠀⠀⠉⠉⠉⠀⠀⡇  
⢸⠀⠀⠣⠀⠀⢸⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇  
⢸⠀⠀⠀⠀⠀⢸⠀⢇⠀⠀⠀⠀⠀⠀⠀⠀⡇  

