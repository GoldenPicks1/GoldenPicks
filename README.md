# GoldenPicks — guía rápida

## Qué incluye
- Diseño adaptable a celular y computadora.
- Filtros por deporte y tipo de pronóstico.
- Ejemplos claramente marcados como ficticios.
- Formulario para añadir pronósticos y estado.
- Guardado local en el navegador (localStorage).
- Sección Premium de demostración; no procesa pagos ni autentica usuarios.

## Cómo probarlo
1. Descomprime `GoldenPicks.zip`.
2. Abre `index.html` con Chrome, Safari, Firefox o Edge.
3. Filtra los picks y prueba el formulario “Publicar un pronóstico”.
4. Los cambios se guardan solo en ese navegador y dispositivo.

## Cómo publicarlo gratis con GitHub Pages
1. Crea una cuenta en GitHub.
2. Crea un repositorio público, por ejemplo `goldenpicks`.
3. Sube `index.html` (y opcionalmente este README) a la raíz del repositorio.
4. En Settings → Pages, elige publicar desde la rama `main` y la carpeta `/ (root)`.
5. Guarda y espera a que GitHub muestre la URL de tu sitio.

Alternativas sencillas: Netlify Drop o Cloudflare Pages. Comprueba sus instrucciones actuales al publicar.

## Antes de lanzar de verdad
- `localStorage` no sincroniza datos entre visitantes. Implementa una API y base de datos (por ejemplo Supabase/Firebase o backend propio).
- Protege la administración con autenticación y autorización del lado del servidor. No guardes claves secretas en el navegador.
- Para datos automáticos, elige un proveedor deportivo con licencia y API; realiza las peticiones desde un backend y guarda la hora de actualización, la fuente y el estado de cada evento.
- Para suscripciones Premium, conecta autenticación, pasarela de pago y control de acceso del lado del servidor. El botón actual solo es demostrativo.
- Añade páginas reales de privacidad, términos, contacto y política de reembolsos si corresponde. Verifica las obligaciones legales aplicables en México y los términos de los proveedores.
- No presentes picks de ejemplo como datos reales ni prometas ganancias. Registra también resultados negativos y explica que existe riesgo de pérdida.

## Estructura
- `index.html`: sitio completo (HTML, CSS y JavaScript).
- `README.md`: instrucciones de prueba y publicación.
