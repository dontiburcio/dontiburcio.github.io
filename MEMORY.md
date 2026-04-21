# Pizzería El Romano — Memory

## Cliente
- **Negocio:** Pizzería El Romano
- **Demo ficticia** — sin cliente real todavía (prospecto: Mariano)

## Hosting
- **Org GitHub:** `dontiburcio`
- **Repo:** `dontiburcio.github.io`
- **URL:** dontiburcio.github.io
- **Carpeta local:** `EMPRENDEDORES/dontiburcio-deploy/`

## Archivos
- `index.html` — página completa

## Diseño
- **Paleta:** azul `#1B4F8A`, celeste `#5BA4D4`, crema `#FAF8F4`
- **Fuentes:** Playfair Display (títulos) + Inter (cuerpo)
- **Estilo:** menú de pizzería, mobile-first, carrito flotante

## Funcionalidades
- Catálogo de pizzas con precios
- Carrito flotante con contador
- Modal detalle de producto
- Formulario pedido → WhatsApp formateado
- Botón WhatsApp directo

## Flujo para actualizar
```bash
cd dontiburcio-deploy
# editar index.html
git add .
git commit -m "descripcion del cambio"
git push
# live en 1-2 min en dontiburcio.github.io
```

## Pendiente
- [ ] Conseguir cliente real (Mariano u otro pizzero)
- [ ] Reemplazar productos de ejemplo con menú real
- [ ] Agregar fotos reales de pizzas
- [ ] Definir número de WhatsApp del cliente
