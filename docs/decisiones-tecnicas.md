# Decisiones técnicas del proyecto

## Uso de WordPress

Se eligió WordPress porque permite gestionar contenidos de forma sencilla para una entidad local, facilita la creación de páginas, entradas, formularios y futuras actualizaciones sin depender siempre de conocimientos avanzados de desarrollo.

## Uso de Twenty Twenty-Four

Se utilizó el tema Twenty Twenty-Four por ser un tema oficial, moderno, compatible con el editor de bloques y suficientemente flexible para crear una web visual sin añadir constructores pesados.

## Entorno de desarrollo

Antes de modificar la web pública, se trabajó en un subdominio de pruebas:

dev.radiolamina.com

Esto permitió diseñar, probar y corregir la web sin afectar a la versión antigua.

## Estructura de contenidos

La web se organizó en páginas principales:

- Inicio
- Escucha en directo
- Programación
- Programas

- Noticias
- Sobre la radio
- Contacto

Esta estructura permite separar contenido fijo, información de la radio, emisión en directo y noticias.

## Formulario de contacto

Se configuró un formulario mediante WPForms y el envío de correos mediante SMTP para mejorar la fiabilidad del envío.

## SMTP

El envío de correos desde WordPress no se dejó con la configuración por defecto. Se configuró SMTP para evitar problemas de entrega y asegurar que los mensajes del formulario llegaran correctamente.

## Emisión en directo

Se integró un reproductor para la emisión en directo de la radio usando la URL de streaming proporcionada por la entidad.

## HTTPS

Se activó HTTPS para publicar la web de forma segura en el dominio principal.

## Migración

La web se desarrolló primero en un entorno de pruebas y después se migró al dominio principal, actualizando URLs internas y revisando enlaces, formularios y contenido.

## Seguridad básica

Se tuvieron en cuenta copias de seguridad, usuarios, plugins necesarios, permisos del hosting, HTTPS y revisión de formularios antes de publicar.
