# EstilosAvanzados
Aplica estilos avanzados y técnicas de diseño responsivo utilizando CSS3.


## Descripcion
este dashboard administrativo presenta, el estado del inventario de una empresa. En la parte superior hay un header con buscador y acciones de usuario; a la izquierda, una sidebar con navegación.

El main muestra:
	•	Tarjetas KPI con tendencias para stock, pedidos, ventas y alertas.
	•	Un gráfico de líneas (SVG) de ventas semanales.
	•	Una tabla responsiva de movimientos recientes con badges de estado.
Todo es responsive,  el menú es colapsable en el celular.

## Tecnologías usadas
	•	HTML5 semántico: header, aside, main, section, figure, table, roles ARIA y etiquetas accesibles.
	•	CSS Grid (layout principal y rejillas de tarjetas) y Flexbox (alineación interna).
	•	Custom properties (variables CSS) para colores, radios, sombras y espacios.
	•	Temas adaptativos con prefers-color-scheme (modo claro/oscuro).
	•	Media queries para puntos de corte (1024px, 900px, 640px) 
	•	JavaScript mínimo (vanilla): sincroniza aria-expanded con el toggle del menú y permite cerrar con Escape.

