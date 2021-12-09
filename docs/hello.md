---
sidebar_label: 'Api 1!'
sidebar_position: 3
---


# Servicios

Crea una nueva instancia de Pedido de paquete.

Importante: El campo CIUDAD Puedes llegar el nombre de la ciudad o el codigo DANE.


| Clave           |  Tipo  | Longitud Max. | Valor Defecto | Requerido | Descripcion |
|-----------------|:------:|--------------:|---------------|-----------|-------------|
| id              |  Int   |             3 | -             | Si        |             |
| service_id      |  Int   |            -- | -             | Si        |             |
| type_id         | Float  |            -- | -             | Si        |             |
| customer_id     |  Int   |            -- | -             | Si        |             |
| dimensions      |  ----  |            -- | -             | Si        |             |
| unit_dimensions | String |             4 | -             | Si        |             |
| weight          |  Int   |             4 | -             | Si        |             |
| unit_weight     | String |             4 | -             | Si        |             |
| properties      |  ----  |            -- | -             | Si        |             |
