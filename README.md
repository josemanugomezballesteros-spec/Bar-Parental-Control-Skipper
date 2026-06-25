# Bar-Parental-Control-Skipper For Mac OS


BarTube es un cliente web para macOS pensado para vivir solo en la barra superior. No tiene ventana principal: al tocar el icono aparece un panel compacto donde pegas una URL y la página se carga dentro del propio desplegable.

## Qué hace

- Vive en la barra de menú y no aparece como app clásica en el Dock.
- Carga cualquier URL dentro del panel.
- Ajusta automáticamente muchas webs para que encajen mejor en la mini pantalla.
- Permite excluir dominios concretos de ese reescalado.
- Incluye YouTube en la lista de exclusión por defecto para evitar problemas con su interfaz.

## Cómo se usa

1. Pulsa el icono de BarTube en la barra superior.
2. Pega una URL en el campo de entrada.
3. Pulsa `Cargar aquí` o Enter.
4. La página aparece en el display 16:9 del panel.

También puedes usar `Pegar` para traer directamente la URL del portapapeles.

## Reescalado y excepciones

BarTube intenta encajar muchas webs dentro del display para que no se desborden horizontalmente.

Abajo del panel hay una sección llamada `Sin reescalado`:

- Muestra los dominios que se cargan sin tocar su tamaño.
- YouTube ya viene incluido.
- Puedes añadir un dominio escribiéndolo en el campo y pulsando `Añadir`.
- Puedes añadir el dominio de la página actual con `Añadir actual`.
- Cada dominio puede quitarse con la `x`.

Si una web se ve rara con el encaje automático, añádela a esa lista y se mostrará tal cual.

For running the app just drop the .app that is in the .dmg in your applications folder and run tis command in your terminal: 
xattr -d com.apple.quarantine /Applications/BarPCskiper.app 
