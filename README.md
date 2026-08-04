# OBAH SHOP — Landing

Landing de OBAH SHOP (ropa y accesorios originales, Carúpano).
Publicada en https://samf2022.github.io/obah-shop/

## Datos pendientes de la dueña

Los siguientes campos están en `null` dentro del objeto `DATOS` del componente
(embebido en `index.html`). Mientras estén en null **no se muestran** en la
página; al llenarlos aparecen solos en su sección:

| Campo | Ejemplo | Dónde aparece |
|---|---|---|
| `plazoApartado` | `'15 días'` | Sección Apartado + FAQ "¿Cómo aparto una prenda?" |
| `costoDelivery` | `'$1 en el centro'` | Pagos, envíos y entregas |
| `costoEnvioNacional` | `'desde $3 según agencia'` | Pagos, envíos y entregas |
| `garantia` | política por defectos de fábrica | Políticas de venta |
| `horario` | `'Lun–Sáb, 9:00 a. m. a 6:00 p. m.'` | Showroom (dirección) |
| `rangoTallas` | `'Tallas S a XL en la mayoría de las prendas'` | Catálogo |
| `tiktok` | URL real del perfil | Footer |
| `facebook` | URL real del perfil | Footer |
| `correo` | correo de contacto | Footer |

## Otros pendientes (no son campos)

- **Confirmar el pin del mapa**: la captura (mapa.jpg) está centrada en 10.66255,-63.25052 — la ubicación de "Helados Cali Carupano" en la Av. Carabobo, asumiendo que es el mismo Edificio Cali. Si el local está en otro punto, avisar para regenerar la captura.
- **Confirmar** que el enlace corto `wa.me/message/NFJBRNTZCSK3I1` corresponde
  al número 0422-715-9341 (el CTA principal usa el enlace corto; los botones
  por producto usan el número).
- **Confirmar el precio del Termo Skechers ($25)** — venía marcado como dudoso
  en el borrador original.
- **Confirmar la moneda** de las fichas de productos originales (el borrador
  dudaba entre $ y €; hoy todo se muestra en $).
- **Fotos reales**: la del hero ya está montada (`hero.webp`). Faltan: interior
  del showroom con espejo, y fotos de productos/categorías (hoy hay patrones
  de tela de relleno). Al llegar fotos de productos se puede restaurar el arco
  de cada card del catálogo.

## Mantenimiento

`index.html` es un bundle empaquetado (template JSON de una línea). No editar a
mano: usar el `transform.py` del historial de trabajo o pedir el cambio al
agente. `og.png`, `favicon.ico` y `apple-touch-icon.png` se generaron del logo.
