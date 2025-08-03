# js9727690-create.github.io

Este proyecto redirige automáticamente a un álbum de Spotify.  
Puedes abrirlo desde aquí:  
[🔗 Abrir Página](https://js9727690-create.github.io)

---

## Código de la página

```html
<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title>Redireccionando a Spotify...</title>
    <script>
        // Redirección inmediata al URI de Spotify
        window.location.href = "spotify://track/0dI23ZVQTJq9wlx8Wm3nre";

        // Intento cerrar la pestaña después de 1 segundo
        setTimeout(() => {
          window.close();
        }, 10000);
    </script>
</head>
<body>
    <p>Abriendo Spotify...</p>
</body>
</html>
