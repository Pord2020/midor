# Midor

Second Brain desktop para macOS (Apple Silicon / MacBook Neo).

## Descargar

**→ [Midor 0.1.3 arm64 (DMG)](https://github.com/Pord2020/midor/releases/latest/download/Midor_0.1.3_arm64.dmg)**

[Todos los releases](https://github.com/Pord2020/midor/releases) · [latest.json (auto-update)](https://github.com/Pord2020/midor/releases/latest/download/latest.json)

### Instalación (primera vez)

1. Descargá el DMG y abrilo  
2. **INSTALAR-MIDOR.command**  
3. Si macOS bloquea: **Ajustes → Privacidad y seguridad → Abrir de todos modos**  
   o: `xattr -cr /Applications/Midor.app && open /Applications/Midor.app`

Grok ya viene configurado.

### Actualizaciones automáticas

A partir de **0.1.3**, la app consulta:

`https://github.com/Pord2020/midor/releases/latest/download/latest.json`

Cuando hay una versión nueva: banner **Midor vX disponible** → **Actualizar** (o Configuración → Actualizaciones).

Para publicar un update (desarrollador):

```bash
cd studio
export TAURI_SIGNING_PRIVATE_KEY="$(cat ~/.tauri/midor.key)"
MIDOR_SKIP_DESKTOP_BUILD=1 npm run desktop:release -- 0.1.4
```

### Sync Obsidian

Capturar → **Sincronizar vault** (ruta en Configuración si no es `~/Documents/Midor/Second Brain`).
