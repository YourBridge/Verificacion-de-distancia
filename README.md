# Kleto Geo Delivery

## Flujo del sistema

Este proyecto implementa un sistema de verificación geoespacial basado en navegador que permite a un negocio validar si un cliente se encuentra dentro de un perímetro definido para acceder a beneficios como delivery gratuito.

1. El usuario abre la página web
2. El navegador solicita permiso de ubicación
3. El sistema obtiene las coordenadas GPS
4. Se calcula la distancia al negocio usando la fórmula de Haversine
5. Se determina si el usuario está dentro o fuera del radio configurado
6. Se muestra el resultado visual en pantalla
7. Se genera un enlace automático a WhatsApp (click-to-chat) para contacto o pedido
8. Permite contactar automáticamente al negocio vía WhatsApp Business
9. Registra cada verificación en Google Sheets mediante Google Apps Script como sistema analítico sin servidor


<u>**🔹 Tecnologías usadas**</u>

HTML5

CSS3

JavaScript (Geolocation API)

Google Apps Script

Google Sheets (Analytics Backend)

WhatsApp Click-to-Chat API

GitHub Pages (Hosting)


<u>**🔹 Flujo del sistema**</u>

El usuario abre la página web

El navegador solicita permiso de ubicación

El sistema obtiene coordenadas GPS

Se calcula la distancia al negocio

Se muestra el resultado visual

Se genera enlace a WhatsApp con mensaje automático

Se guarda el evento en Google Sheets


<u>**🔹 Cumplimiento legal y privacidad**</u>

Este sistema solicita consentimiento explícito del usuario antes de acceder a su ubicación.
Los datos recolectados se usan únicamente con fines analíticos y operativos internos del negocio y no se comparten con terceros.
