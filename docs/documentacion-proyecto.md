# Documentación del proyecto — Web Radio La Mina

## Objetivo

Crear una nueva web para Radio La Mina con WordPress, manteniendo la web antigua activa hasta el momento de la migración final.

## Situación inicial

La web principal redirigía hacia Blogger. Se quería crear una web más moderna, visual y multimedia, con emisión en directo, formulario de contacto y estructura de contenidos propia.

## Entorno de pruebas

Se creó el subdominio:

dev.radiolamina.com

Este entorno permitió trabajar sin afectar la web pública.

## Estructura de páginas

- Inicio
- Escucha en directo
- Programación
- Programas

- Noticias
- Sobre la radio
- Contacto
- Aviso legal
- Política de privacidad

## Configuración técnica

Se configuró WordPress con el tema Twenty Twenty-Four, personalización de bloques, formulario de contacto, SMTP, copias de seguridad y migración final al dominio principal.

## Emisión en directo

Se integró un reproductor de streaming con la URL proporcionada por la radio.

## Formulario de contacto

Se configuró WPForms junto con WP Mail SMTP para que los mensajes llegaran correctamente al correo oficial.

## Migración

La web se desarrolló en un entorno de pruebas y después se migró a radiolamina.com, actualizando URLs internas, redirecciones y configuración HTTPS.

## Problemas encontrados

- Redirección inicial hacia Blogger.
- Certificado SSL pendiente.
- Formulario sin envío correcto hasta configurar SMTP.
- Problemas de permisos en carpetas del hosting.
- Stream HTTP dentro de una web con HTTPS.

## Soluciones aplicadas

- Desarrollo en subdominio.
- Configuración de SMTP.
- Revisión y corrección de permisos.
- Migración controlada.
- Activación HTTPS.
- Revisión final en producción.
