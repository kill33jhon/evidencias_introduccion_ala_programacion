<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->


# Actividad:

### Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

# SOLUCION

```html

<table border="1" cellpadding="5" cellspacing="10">
  <thead>
    <tr>
      <th>codigo</th>
      <th>nombre</th>
      <th>descripcion</th>
      <th>precio</th>
      <th>stock</th>
      <th>fecha de creacion</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1223</td>
      <td>Camilo</td>
      <td>automovil</td>
      <td>30 millones</td>
      <td>3</td>
      <td>2023-09-13</td>
    <tr>
      <td>1224</td>
      <td>Maria</td>
      <td>moto</td>
      <td>8 millones</td>
      <td>2</td>
      <td>2023-09-14</td>
    </tr>
    <tr>
      <td>1225</td>
      <td>Alejandro</td>
      <td>lancha</td>
      <td>90 millones</td>
      <td>2</td>
      <td>2023-09-15</td>
    </tr>
    <tr>
      <table border="1">
        <thead>
          <tr>
            <th rowspan="2">cabezera</th>
            <th colspan="5">Columna 1</th>
          </tr>
          <tr>
            <th>Subcolumna 1</th>
            <th>Subcolumna 2</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td rowspan="2">Celda fusionada</td>
            <td>Contenido 1</td>
            <td rowspan="5">Celda fusionada</td>
          </tr>
          <tr>
            <td>Contenido 2</td>
          </tr>
          <tr>
            <td colspan="2">Totales</td>
            <td>Subtotal</td>
            <td>Impuestos</td>
          </tr>
        </tbody>
      </table>

    </tr>

    <thead>

```