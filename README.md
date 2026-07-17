# Midor

Second Brain desktop para macOS (Apple Silicon / MacBook Neo).

## Descargar (MacBook Neo / M1 / M2 / M3 / M4)

**→ [Descargar Midor 0.1.2 (arm64)](https://github.com/Pord2020/midor/releases/latest/download/Midor_0.1.2_arm64.dmg)**

También: [Releases](https://github.com/Pord2020/midor/releases).

### Instalación

1. Descargá el `.dmg` y abrilo
2. Doble clic en **`INSTALAR-MIDOR.command`**
3. Si macOS dice que no puede verificar:
   - **Ajustes → Privacidad y seguridad → Abrir de todos modos**
   - o en Terminal: `xattr -cr /Applications/Midor.app && open /Applications/Midor.app`

Grok ya viene configurado (sin pegar API key).

### Changelog

- **0.1.2** — Fix *Internal Server Error* (módulos nativos/aliases que Tauri eliminaba al empaquetar)
- **0.1.1** — Primer build arm64 + gift key
