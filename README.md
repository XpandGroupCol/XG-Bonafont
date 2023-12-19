# XG-Bonafont

El código está escrito en Python, y se necesita contar con la librería pandas instalada. Está escrito en un Jupyter Notebook, por lo que se puede ejecutar en Google Colab, VSCode o en cualquier otro entorno de desarrollo de Python.

No es necesario correr todos los bloques de código, lea bien la descripción de cada bloque, y a partir de ahí, ejecute el código que necesite.

Los datos de Bonafont, vienen de la plataforma de e-commerce Magento. Los datos crudos contienen las siguientes columnas:

## Descripción de las columnas
1. **ID**: Identificador único de la orden.
2. **Purchase Point**: Punto de venta donde se realizó la compra. Tiene valores de Bonafont B2C, Bonafont y Danone.
3. **Purchase Date**: Fecha en la que se realizó la compra.
4. **Bill-to Name**: Nombre de la persona que realizó la compra.
5. **Ship-to Name**: Nombre de la persona a la que se le entregó el producto.
6. **Grand Total (Base)**: Total de la compra en pesos mexicanos.
7. **Grand Total (Purchased)**: Total de la compra en puntos.
8. **Status**: Estado de la orden.
9. **Billing Address**: Dirección de facturación.
10. **Shipping Address**: Dirección de envío.
11. **Shipping Information**: Información de envío. (Quien entrega)
12. **Customer Email**: Correo electrónico del cliente.
13. **Customer Group**: Grupo de clientes.
14. **Subtotal**: Subtotal de la compra.
15. **Shipping and Handling**: Costo de envío.
16. **Customer Name**: Nombre del cliente.
17. **Payment Method**: Método de pago.
18. **Total Refunded**: Total de reembolsos. - Normalmente vacío.
19. **Company Name**: Nombre de la compañía. - Normalmente vacío.
20. **Pickup Location Code**: Código de la ubicación de entrega. - Normalmente vacío.
21. **Allocated sources**: Fuente de la orden.
22. **Braintree Transaction Source**: Fuente de la transacción. - Normalmente vacío.
23. **Salesforce ID**: ID de Salesforce.
24. **Delivery date**: Fecha de entrega.
25. **Frog ID**: ID de la rana. - Normalmente vacío.
26. **Colonia No Normalizada**: Colonia de entrega.
27. **# Cliente en SAP**: ID del cliente en SAP. - Normalmente vacío.
28. **SKU**: SKU del producto.
29. **Product Name**: Nombre del producto.
30. **Qty**: Cantidad de productos.
31. **Origen del Cliente**: Origen del cliente.
32. **Telefono**: Teléfono del cliente.
33. **Cedi**: CEDI de entrega.
34. **Product Bundle Name**: Nombre del paquete de productos. - Normalmente vacío.
35. **Bundle Qty**: Cantidad de paquetes de productos. - Normalmente vacío.
36. **archivo**: Nombre del archivo.
