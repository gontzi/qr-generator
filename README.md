# Generador de QR

Escribe un texto o un enlace y descarga tu código QR al momento. Sin registros ni anuncios.

## Qué hace

- Genera el QR en el navegador a partir de cualquier texto o URL. No se envía nada a ningún servidor.
- Opcionalmente, pone una imagen (tu logo, por ejemplo) en el centro del código.
- Lo descargas como `qrcode.png`.
- Interfaz de widgets con estética inspirada en Nothing, con reloj incluido.

## Stack

[Astro](https://astro.build) 5 · Tailwind CSS · [`qrcode`](https://www.npmjs.com/package/qrcode)

## Desarrollo

```bash
npm install
npm run dev     # http://localhost:4321
npm run build   # genera dist/
```
