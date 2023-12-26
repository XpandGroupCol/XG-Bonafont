# Dashboard Productos 2022

![Dashboard Productos 2022](https://lookerstudio.google.com/embed/reporting/4aea8021-568a-4869-81b5-75d63f6b4005/page/p_gzsoj5zf9c)

## Descripción
El Dashboard de Productos de Bonafont 2022 contiene los datos de transacciones realizadas en el año 2022, con el objetivo de analizar el comportamiento de los productos de Bonafont en el mercado.

El tablero se divide en 3 secciones:
- **Productos y ventas:** Contiene información de los productos de Bonafont y las ventas realizadas en el año 2022. La distribución de productos por número de productos comprados, el número de productos vendidos por medio de compra, plataforma y canal.
- **Métodos de pago:** Contiene información de los métodos de pago utilizados por los clientes de Bonafont en el año 2022.
- **Clientes:** Contiene información de los clientes de Bonafont en el año 2022. Número de órdenes por clientes, ingresos por cliente, y aldunos datos sobre la órden de compra y dirección de envío.

## Fuentes de datos
El tablero de datos usa dos fuentes de datos. Los datos sin procesar 'data/2022/2022_BONAFONT_SIN-PROCESAR_v20-08.csv', unidos desde Enero hasta Diciembre, y los datos procesados 'data/2022/2022_BONAFONT_PROCESSED_v23-08.csv' que contiene los datos procesados y limpios para el análisis.

El proceso de limpieza de datos se encuentra en el archivo 'bonafont.ipynb', comienza con la eliminación de las columnas vacías, luego se eliminan las filas duplicadas.

Se calculan los campos 'same_address' y 'same_name' para identificar si la dirección de envío y el nombre del cliente son iguales a la información de facturación.

Se cambian los datos de 'Purchase Point' por Bonafont B2c, Danone o Bonafont según corresponda.

Se cambia el formato de la fecha de 'Purchase Date' a datetime. Se calcular 'Purchase Day' y 'Delivery Days'. Este últio con la diferencia entre 'Delivery date' y 'Purchase Date'.

Los datos de Bonafont se encuentran en un archivo csv. Cada fila representa una orden de compra de un cliente. Cada columna representa una característica de la orden de compra. La columna producto, tiene todos los productos de la orden de compra separados por una coma, al igual que la cantidad. Es necesario entonces, dividir cada fila de la base de datos, y crear una fila por cada producto de la orden de compra.

Es importante tener en cuenta que para suma de totales de ingresos, se debe tener en cuenta la base de datos original porque el total está por orden de compra y no por producto.

## Gráficos

Todo gráfico que muestra principalente datos de productos nace de la base de datos procesada que desglosa cada producto de la orden de compra en una fila. Los gráficos que muestran información de ingresos, órdenes y cliente, nacen de la base de datos original.





#VAYA A DESARROLLO, CLIENTES, BONAFONT, MAGENTO, PARA VER LOS ARCHIVOS QUE PESAN MAS DE 100MB

