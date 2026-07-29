# Tu PC

Landing de **Tu PC** — reparación de computadoras, consultoría/asesoría e insumos informáticos.

Producción: https://tupc.com.ar

## Stack

HTML estático en un solo archivo. Sin build, sin dependencias.
Vercel lo sirve directo desde la raíz del repo.

## Editar

Todo está en `index.html`: estilos en el `<style>` del head, la animación
del hero en el `<script>` del final.

Datos de contacto (WhatsApp, mail, zona) están hardcodeados en el HTML:
- botones de WhatsApp → `wa.me/5491165129359`
- mail → `hola@tupc.com.ar`

## Deploy

Push a `main` → Vercel despliega automático.
