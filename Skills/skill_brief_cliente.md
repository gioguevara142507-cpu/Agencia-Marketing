# SKILL: PROCESAMIENTO Y VALIDACIÓN DE BRIEFS DE CLIENTE

## OBJETIVO
Estandarizar la recepción de datos de cada nuevo cliente de la agencia, asegurando que Claude y Gemini cuenten con toda la información necesaria antes de ejecutar el diseño web o la estrategia de redes sociales.

## ESTRUCTURA OBLIGATORIA DEL BRIEF (.JSON)
Cada cliente en la carpeta `/clientes/` debe contar con un archivo `brief.json` estructurado con los siguientes campos:

1. **Datos de Empresa:** Nombre comercial, giro (restaurante, tienda, boutique, servicio), dirección exacta o zona de Querétaro (Juriquilla, Centro Histórico, Zibatá, etc.).
2. **Paquete Contratado:** Económico, Pro o Ultra.
3. **Identidad de Marca:** Paleta de colores en códigos HEX (ej. `#FF5733`), estilo visual (minimalista, rústico, moderno) y enlaces a redes sociales existentes.
4. **Catálogo / Productos Estrella:** Lista de productos/platillos con precios, imágenes o descripciones.
5. **Objetivo Principal:** Incrementar ventas en tienda, compras en e-commerce o reservas por WhatsApp.

## REGLA DE VALIDACIÓN
Si algún dato clave falta en el `brief.json` (por ejemplo, si no proporcionaron códigos HEX), el agente debe proponer automáticamente una paleta de colores coherente con el giro del negocio y la zona de Querétaro sin detener la ejecución del proyecto.
