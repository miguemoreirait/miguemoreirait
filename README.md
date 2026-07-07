# MigueMoreiraIT — Enlaces

Página de enlaces ("link in bio") de la marca personal MigueMoreiraIT, compartida desde Instagram (@miguemoreirait).

## Sobre este proyecto

Landing estática de un solo archivo (`index.html`), sin dependencias ni build. Centraliza el acceso a:

- Revisión de Perfil Técnico (servicio destacado)
- Charla de Concientización en Ciberseguridad
- Instagram
- LinkedIn
- WhatsApp
- Formulario de contacto ("Empecemos por acá:")

## Stack

- HTML + CSS + JS vanilla (sin frameworks, sin backend)
- Tipografías vía Google Fonts CDN: Instrument Serif, Geist, JetBrains Mono
- Formulario: [Web3Forms](https://web3forms.com) (envío directo por email, sin backend propio)
- Deploy: [Vercel](https://vercel.com)

## Formulario de contacto

Envía por `fetch` a la API de Web3Forms sin recargar la página. Campos: nombre, email (validado por formato y con máximo 60 caracteres), servicio de interés (Revisión de Perfil Técnico / Asesoría 1:1 / Charla de Concientización) y mensaje opcional (máximo 500 caracteres). Al enviarse con éxito muestra un mensaje de confirmación en la misma página.

## Estructura

```
index.html   # página completa (markup, estilos, formulario y animaciones inline)
```

## Marca

Sistema visual definido en el brand book de MigueMoreiraIT — paleta navy/cyan, monograma `[MM]`, wordmark `MigueMoreiraIT` con "IT" en Instrument Serif italic. Esta página usa el modo oscuro de la marca (hex directos, sin `tokens.css`); el modo claro se reserva para Brandbook.html y concientizacion.vercel.app.

## Contacto

- Instagram: [@miguemoreirait](https://instagram.com/miguemoreirait)
- LinkedIn: [linkedin.com/in/miguemoreira](https://linkedin.com/in/miguemoreira)
- Email: miguemoreirait@gmail.com
