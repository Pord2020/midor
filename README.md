# Midor

Second Brain desktop para macOS (Apple Silicon / MacBook Neo).

## Descargar (MacBook Neo / M1 / M2 / M3 / M4)

**→ [Descargar Midor 0.1.1 (arm64)](https://github.com/Pord2020/midor/releases/latest/download/Midor_0.1.1_arm64.dmg)**

También en la página de [Releases](https://github.com/Pord2020/midor/releases).

### Instalación (si macOS dice “no se puede abrir”)

1. Abrí el `.dmg`
2. Doble clic en **`INSTALAR-MIDOR.command`** (recomendado)  
   **o** arrastrá Midor a Aplicaciones → clic **derecho** → **Abrir**
3. Si sigue bloqueado, en Terminal:
   ```bash
   xattr -cr /Applications/Midor.app && open /Applications/Midor.app
   ```

Grok ya viene configurado: no hay que pegar ninguna API key.

### Notas

- Build **arm64** (Apple Silicon). No sirve en Mac Intel.
- Primera vez macOS puede avisar porque la app aún no está notarizada por Apple.
- Actualizaciones futuras: [Releases](https://github.com/Pord2020/midor/releases).
