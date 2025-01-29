## Descripción

El plugin **Mercado Pago para WordPress** permite integrar el sistema de pagos de **Mercado Pago** en tu tienda en línea desarrollada con **WordPress**. Con este plugin, podrás ofrecer a tus clientes una experiencia de compra fluida y segura, permitiendo pagos con tarjeta de crédito, débito, transferencias bancarias y otros métodos de pago disponibles en Mercado Pago.

### Características:
- **Integración fácil y rápida**: Solo necesitas instalar y activar el plugin para comenzar a aceptar pagos con Mercado Pago.
- **Métodos de pago variados**: Soporta pagos con tarjetas de crédito, débito, transferencias y más.
- **Monedas locales**: Compatible con múltiples monedas dependiendo de tu país de configuración.
- **Configuración flexible**: Personaliza los métodos de pago y la apariencia del proceso de pago para ajustarlos a las necesidades de tu tienda.
- **Seguridad**: Mercado Pago cumple con los estándares más altos de seguridad en pagos en línea, asegurando la protección de los datos de tus clientes.

### Detalles Técnicos:
Este plugin está desarrollado utilizando el SDK oficial de **Mercado Pago** para PHP: `mercadopago/dx-php:2.6.2`. La integración está completamente orientada a la **interacción del servidor** y no requiere ningún componente de JavaScript en el frontend.

Cuando el usuario presiona el botón de **"Finalizar compra"**, el plugin redirige automáticamente al cliente a la página de **Mercado Pago** para completar el proceso de pago. Este flujo es completamente seguro, ya que el plugin utiliza las credenciales de la cuenta de Mercado Pago para generar la preferencia de pago y asegurar la correcta gestión de la transacción.

### Requisitos:
- **WordPress 5.0 o superior**
- **PHP 7.0 o superior**
- **Cuenta activa en Mercado Pago**

### Instalación:
1. Descarga el plugin desde este repositorio.
2. Sube el archivo ZIP a tu instalación de WordPress en `wp-content/plugins`.
3. Activa el plugin desde el panel de administración de WordPress.
4. Configura tu cuenta de Mercado Pago en la sección de configuración del plugin.

### Contribuciones:
¡Las contribuciones son bienvenidas! Si deseas mejorar el plugin o agregar nuevas funcionalidades, haz un fork del repositorio y envía un pull request.
