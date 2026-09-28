# Otra sorpresita

Página interactiva hecha con ASP.NET Core y archivos estáticos. Render la construye desde el `Dockerfile`.

## Subir a GitHub

Crea un repositorio y sube el contenido de esta carpeta. Incluye `Program.cs`, `Otra sorpresita.csproj`, `Dockerfile`, `.dockerignore`, `render.yaml`, `wwwroot/` y `Properties/`. No subas `bin/` ni `obj/`; son archivos generados.

## Publicar en Render

1. En Render, elige **New > Blueprint**.
2. Conecta el repositorio de GitHub.
3. Render leerá `render.yaml` y usará el `Dockerfile` para desplegar el sitio.
4. Al terminar, abre la URL que Render te proporcione.

Render asigna el puerto del servicio automáticamente. No hace falta instalar Docker en tu Mac para desplegarlo.

## Probar localmente

Abre el proyecto en VS Code y ejecuta el perfil **Otra sorpresita**. La página se abre en el navegador en `http://localhost:10000`.
