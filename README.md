# Patymar — Web y toma-pedidos

Proyecto tech de **Patymar** (ensaladas frescas y cócteles de mar, Santa Ana, El Salvador).

## Contenido
- `index.html` — Form de toma-pedidos (mobile-first). Flujo: antojo → menú con beneficios → personalizar (aderezo/extras) → carrito → entrega (delivery $2 / recoger, ubicación GPS) → confirmar → pedido pre-escrito a WhatsApp de Patymar.

## Stack
- HTML/CSS/JS puro, sin dependencias. Se hospeda gratis en **Cloudflare Pages**.
- Dominio: `patymar.com`.
- Pedidos entran por **WhatsApp** (wa.me). Fase 2: guardar cada pedido en **Airtable** vía webhook (n8n / Cloudflare Function).

## Pendiente (siguiente sprint)
- Listado real de aderezos (desde Airtable) y cuál lleva cada ensalada.
- Extras y precios (ensaladas y cócteles).
- Beneficios exactos por plato.
- Zonas de delivery con precio (suburbios > $2).
- Fotos de los platos.
- Webhook → Airtable (Leads + Pedidos).

## Datos ya confirmados
- WhatsApp Patymar: +503 6086 3089
- Delivery: $2 en Santa Ana ciudad; afueras se confirma por zona. Pickup gratis.
- Ensaladas Lun–Vie. Cócteles Sáb–Dom (entre semana con 2h de aviso).
