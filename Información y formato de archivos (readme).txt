

	ReadMe - BERCOS Inventario
	Por: Marcos Pinzón y Alejandro Becerra



	FORMATO DE ARCHIVOS

	Esta es la manera en la que se guardan los archivos de esta aplicación.
	Además, debajo de cada formato puede encontrarse un ejemplo.

	Tenga en cuenta que aunque es posible cambiarlos manualmente, eso no es recomendable. Si decide hacerlo, tenga en cuenta NO dejar ningun cambio de línea al final o una línea en blanco
	Además, tenga en cuenta que el separador para todos los archivos es ";".
	Por último, por favor NO cambie el orden del formato ni el nombre de los archivos, ya que esto generaría fallos en la ejecución.


	----------------------------------------------------------

	store.txt

	Nombre de la tienda; ID; Dirección; Teléfono

	TIENDA TEST; NIT 10834265-1; Cra 8 #79bis - 97, Apto 302; 324624357

	----------------------------------------------------------

	products.txt

	Categoría; ID; Precio; Stock; Cantidad de ventas; Detalles

	3; 1; 1700000.0; 60; 0; Parlante SONY 235W - Incluye cable

	----------------------------------------------------------

	clients.txt

	Nombre; Apellidos; ID; Teléfono; Dirección; Cantidad de compras; Cliente desde

	Juan; Gutierrez Tinoco; 123245678; 3001234567; Calle 17 #40-28, Apto 202; 11; 2022-01-01

	----------------------------------------------------------

	salesRecord.txt (diferentes detalles se separan con "/")

	Detalles del producto; Detalles de la tienda; Detalles del cliente; Fecha de compra; Hora de compra; Precio bruto; Impuestos

	3 / 1 / Parlante SONY 125w; TIENDA / 10834265-1 / Cra 8 #79bis-97, Apto 302 / 324624357; Carlos Duarte Díaz / 102583587 / 2542346; 2022-02-10; 21:29:41; 8500000.0; 1615000.0


