# Limpito · Ventas y costos

Página web de un solo archivo (`index.html`), sin instalar nada ni depender de internet.

## Qué hace
- **Ventas:** carga diaria, con filtro por mes. Guarda el costo del producto del día de la venta, así los meses cerrados no cambian si después sube un insumo.
- **Materias primas:** insumos, botellas, tapas, stickers, etc., con precio y cantidad comprada. Calcula el costo por unidad.
- **Productos y recetas:** qué insumos lleva cada producto y cuánto. Calcula costo, ganancia y margen.
- **Resumen:** ventas, costo y ganancia mes a mes del año, con gráfico y ventas por producto.

## Usarla
Abrí `index.html` en el navegador. Los datos se guardan automáticamente **en ese navegador y en ese dispositivo**.

## Publicarla en GitHub (GitHub Pages)
1. Creá un repositorio y subí `index.html` y este `README.md`.
2. En el repo: Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)` → Save.
3. En un minuto queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Importante: dónde quedan tus datos
GitHub guarda el **código** de la página, no lo que cargás en ella. Los datos viven en el navegador. Para no perderlos:
1. Tocá **Descargar respaldo** de vez en cuando (por ejemplo, una vez por semana). Baja un archivo `limpito-datos-AAAA-MM-DD.json`.
2. Subí ese archivo al repositorio si querés tener el historial en GitHub.
3. Para pasar los datos a otro navegador o dispositivo, o recuperarlos, usá **Restaurar respaldo**.

## Público o privado
- **GitHub Pages es gratis solo con repositorios públicos.** Con un repositorio privado hace falta un plan de pago.
- Un repositorio público con solo `index.html` y este README no expone tus datos, porque la página sale vacía y lo que cargás queda en tu navegador.
- **No subas los respaldos `.json` a un repositorio público**: cualquiera vería tus precios, costos y ventas. Guardalos en un repositorio privado aparte, en tu computadora o en tu Drive.
- Si preferís repositorio privado sin pagar, no uses Pages: abrí `index.html` directo desde tu computadora o celular.
