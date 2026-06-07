# Study - Reloj Flip 24h

Proyecto estático (HTML + CSS) que muestra un reloj tipo "flip" en formato 24 horas. Es una implementación ligera y accesible pensada para ejecutarse directamente en el navegador sin dependencias externas.

## Sobre el nombre
El nombre "Study" refleja el propósito del proyecto: está pensado para sesiones largas de estudio y para favorecer la concentración. Su diseño busca mitigar que la pantalla se apague y reducir las distracciones, además de mostrar la hora de forma precisa para facilitar el control temporal de bloques de trabajo y descansos.

Cuando se utiliza un fondo negro junto con la opción de ocultar la barra divisoria central, la interfaz está planteada para minimizar el riesgo de quemado en pantallas OLED evitando mantener los mismos píxeles encendidos con la misma imagen durante períodos prolongados.

## Características principales
- Visualización tipo "flip" para horas, minutos y opcionalmente segundos.
- Panel de control integrado: cambiar colores, fuente de dígitos, alternar segundos, pantalla completa y opciones de estilo.
- Soporte para mantener la pantalla activa (Wake Lock) cuando el navegador lo permite.
- Opciones de personalización guardadas en `localStorage`.

## Uso
1. Abrir el archivo `index.html` o visitar (av4sin.github.io/study)[https://av4sin.github.io/study] en cualquier navegador.
2. Mostrar/ocultar el panel de opciones moviendo el cursor o tocando la pantalla.
3. Desde el panel se pueden cambiar colores y tipo de fuente; las preferencias se almacenan automáticamente.

## Estructura de archivos
- `index.html`: interfaz y lógica JavaScript integrada.
- `reloj.css`: estilos y variables CSS (colores, fuentes, tamaños, animaciones).
- `LICENSE`: licencia del proyecto.
- `README.md`: este documento.

## Personalización rápida
- Variables CSS útiles (en `reloj.css`): `--bg-color`, `--card-color`, `--top-shade`, `--bottom-shade`, `--digit-font`, `--digit-scale`.
- También se pueden ajustar las opciones desde el panel UI: color de fondo, color de tarjeta, colores de los dígitos y fuente.

## Desarrollo y despliegue
- No requiere build: es un sitio estático. Para desarrollo basta con abrir `index.html` localmente.
- Para publicar en GitHub Pages, subir el contenido al repositorio y activar Pages desde la rama correspondiente.

## Accesibilidad y controles
- Etiquetas ARIA en elementos clave y botones.
- Atajos y controles por teclado/tacto están habilitados (por ejemplo, mostrar controles y combinaciones especiales para desbloquear la manecilla analógica de segundos).

## Licencia
- Revisa el archivo `LICENSE` para los detalles de licencia.