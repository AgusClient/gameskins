# AClient Gameskins Repository

Repositorio de almacenamiento y distribucion de gameskins para **AClient**.

## Como funciona la descarga automatica

Cuando un usuario de AClient tiene activada la opcion:
`Configuracion -> Tee -> Descargar gameskins automaticamente` (`cl_download_gameskins 1`)

Y entra a una partida con otro jugador que utiliza un gameskin registrado, el cliente consulta este repositorio directamente mediante la URL:
```text
https://raw.githubusercontent.com/AgusClient/gameskins/main/<nombre_skin>.png
```

El archivo es descargado de forma asincrona y almacenado en:
`downloaded_gameskins/<nombre_skin>.png`
quedando disponible inmediatamente en memoria para renderizar las armas y el gancho de ese jugador.

---

## Lista de Gameskins Disponibles (106 en total)

- `1.png`
- `1kirisaki22.png`
- `2.png`
- `3.png`
- `4.png`
- `4_sin_titulo_20260210145557.png`
- `5.png`
- `6.png`
- `7.png`
- `7_Sem_Titulo_20250622181250.png`
- `8.png`
- `9.png`
- `aa.png`
- `aasdjasidjaijhdiaindwihsubaninhd.png`
- `ac_asset.png`
- `ac_asset123.png`
- `ac_asseta.png`
- `agus.png`
- `ahlgame.png`
- `ahlwhite4ShankGos.png`
- `argentinaakv1.png`
- `badoumed_FullGold.png`
- `Beautemps_Minimal2.png`
- `Beautemps_Minimal345.png`
- `black-ak.png`
- `black.png`
- `black1dot.png`
- `black_ak.png`
- `Bobo_black.png`
- `Bobo_purple.png`
- `bobo_xiaobao.png`
- `bobo_xiaobao_fulldot.png`
- `cating.png`
- `champloo.png`
- `changos_17.png`
- `colorful.png`
- `dmnred.png`
- `edited.png`
- `esportcat4cagent_3nzee1.png`
- `final.png`
- `game_06.png`
- `game_better_hammer.png`
- `guide.png`
- `hesi.png`
- `image-140.png`
- `image.png`
- `ivory.png`
- `ivoryblack.png`
- `jukki naoha.png`
- `JuKKi.png`
- `JuKKi2.png`
- `jukki_.png`
- `JuKKi_ak.png`
- `JuKKi_ak_dot.png`
- `jukki_dot.png`
- `JuKKi_Small.png`
- `jukkiwekomodifikao.png`
- `kihiyokojukki2.png`
- `kiri4naoha.png`
- `kiri_2.0.png`
- `KiriAkScythe.png`
- `kiribig2.png`
- `KiriHammer.png`
- `kirisaki.png`
- `kkuba_v2_v2.png`
- `kuro_soyler_edit.png`
- `kuro_soyler_edit_dot.png`
- `levoneon.png`
- `Makavelho.png`
- `mi_gameskin.png`
- `mice4Ziinox.png`
- `mice4Ziinoxprpl.png`
- `Mixipink.png`
- `Mixipinkv2.png`
- `my_game.png`
- `my_gamea.png`
- `my_gameadsadadsd.png`
- `naoha 2029.png`
- `Naoha black.png`
- `Naoha v2.png`
- `napolitano.png`
- `noesis_ccs_by_noesis.png`
- `NoesisMixi_refreshedwhiteblackpistol.png`
- `on_request_TopAlgerie.png`
- `plvx4jukki.png`
- `plvx4jukkiBlue.png`
- `plvx4jukkiCyan.png`
- `plvx4jukkiGreen.png`
- `plvx4jukkiLightBlue.png`
- `plvx4jukkiOrange.png`
- `plvx4jukkiPink.png`
- `plvx4jukkiPurple.png`
- `plvx4jukkiRed.png`
- `plvx4jukkirockusgreen.png`
- `plvx4jukkiYellow.png`
- `portal.png`
- `portaltonigameskin.png`
- `redshelzy.png`
- `rising.png`
- `rrs_harshe.png`
- `saez1.png`
- `soyler_game.png`
- `spareparts.png`
- `sssss.png`
- `verdinha.png`
- `zerokanired_tiphook.png`

---

## Como agregar nuevos gameskins

1. Asegurarse de que el archivo cumpla con las proporciones estandar de Teeworlds/DDNet (cuadricula y formato RGBA).
2. Colocar el archivo `.png` en la raiz de este repositorio.
3. Hacer commit y push a la rama `main`.
