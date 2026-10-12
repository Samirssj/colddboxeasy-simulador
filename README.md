# ColddBox: Easy Lab — Simulador educativo

Sitio estático en español basado en el PDF de resolución de ColddBox: Easy.

## Qué incluye
- Diseño responsive negro y verde terminal.
- Ruta de 6 etapas: reconocimiento, enumeración web, usuarios/credenciales, reverse shell, shell Linux y escalada de privilegios.
- Terminal ficticia con respuestas predefinidas.
- Contenido didáctico basado en el PDF y advertencias de uso responsable.

## Seguridad y alcance
La terminal solo interpreta una lista de comandos educativos en JavaScript. No ejecuta comandos del sistema, no escanea redes, no realiza fuerza bruta, no abre puertos y no se conecta a máquinas reales. Las salidas son simuladas.

## Probar localmente
1. Extrae el ZIP.
2. Abre `index.html` en un navegador moderno.
3. No se necesita Node.js, base de datos ni servidor backend.

## Publicar gratis con GitHub Pages
1. Crea un repositorio nuevo en GitHub, por ejemplo `colddboxeasy-lab`.
2. Sube `index.html` y `README.md` a la raíz del repositorio.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/(root)`, y guarda.
6. Espera a que termine el despliegue. GitHub mostrará una URL pública con formato `https://TU-USUARIO.github.io/colddboxeasy-lab/`.
7. Abre el enlace y pruébalo desde una ventana privada o desde otro dispositivo.

## Publicar con Vercel
1. Sube los archivos a un repositorio de GitHub.
2. Entra en https://vercel.com/ y crea un proyecto nuevo importando ese repositorio.
3. Para este sitio estático no hace falta comando de build ni directorio de salida especial; publica la raíz del proyecto.
4. Cuando finalice el despliegue, Vercel te dará una URL `*.vercel.app`.

## Personalizar
- Cambia los textos de las etapas en el arreglo `stages` dentro de `index.html`.
- Ajusta los colores en las variables CSS al inicio del bloque `<style>`.
- Mantén las salidas del terminal como datos ficticios. No conviertas el simulador en una herramienta que ataque sistemas de terceros.
