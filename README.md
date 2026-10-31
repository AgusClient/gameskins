# AClient Gameskins Repository

Repositorio de almacenamiento y distribucion de gameskins para **AClient**.

## Como funciona la descarga automatica

Cuando un usuario de AClient tiene activada la opcion:
`Configuracion -> Tee -> Descargar gameskins automaticamente` (`cl_download_gameskins 1`)

Y entra a una partida con otro jugador que utiliza un gameskin registrado (por ejemplo `game_06`), el cliente consulta este repositorio directamente mediante la URL:
```text
https://raw.githubusercontent.com/AgusClient/gameskins/main/<nombre_skin>.png
```

El archivo es descargado de forma asincrona y almacenado en:
`downloaded_gameskins/<nombre_skin>.png`
quedando disponible inmediatamente en memoria para renderizar las armas y el gancho de ese jugador.

---

## Lista de Gameskins Disponibles

- `ac_asset.png`
- `ac_asseta.png`
- `agus.png`
- `game_06.png`
- `image-140.png`
- `jukki_.png`
- `soyler_game.png`

## Como agregar nuevos gameskins

Para agregar un nuevo gameskin a la coleccion comunitaria:
1. Asegurarse de que el archivo cumpla con las proporciones estandar de Teeworlds/DDNet (cuadricula y formato RGBA).
2. Colocar el archivo `.png` en la raiz de este repositorio.
3. Hacer commit y push a la rama `main`.
