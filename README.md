# Tablero de MaderUP

Página estática para administrar planes, cobros y uso. Para ver o cambiar datos hay que iniciar sesión con un
email autorizado en el servidor (secret `ADMIN_EMAILS` de la función `admin`). La URL y la clave
*publishable* de `config.js` son públicas por diseño (las mismas que usa la app); la clave de servicio nunca
sale de Supabase.
