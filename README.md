# SZKUNIVERSAL · Protection V3

Loader protegido para ejecutores de Roblox.

## Setup
1. Sube este proyecto a Vercel.
2. Configura `SCRIPT_SECRET` con un valor fuerte.
3. Configura `PUBLIC_WEB_URL` con la URL pública de tu despliegue.
4. Coloca tu script real en `private/script.lua`.

Loader:
```lua
loadstring(game:HttpGet("https://TU-PROYECTO.vercel.app/api/loader"))()
```

Discord: https://discord.gg/MWAeabGhpT

La interfaz usa `public/logo.png` como logo y favicon y no utiliza una imagen de fondo.
