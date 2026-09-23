# Rust en el ESP32

Aprendiendo Rust embebido (`no_std`, `esp-hal`) sobre un ESP32 clásico, camino de construir robots.

- Lecciones: abre `lecciones/index.html` en el navegador.
- Cada lección es un proyecto cargo en `lecciones/NN-nombre/`. Para compilar y flashear: `cd lecciones/01-blink && cargo run --release`.
- Toolchain: `espup install --targets esp32` y cargar `~/export-esp.sh` (en fish vale `source`).
- Editor: `.helix/languages.toml` lanza rust-analyzer con la toolchain `stable`, porque `esp` no lo trae, y compila para `xtensa-esp32-none-elf`. Abre `hx` desde cualquier carpeta del repo.
