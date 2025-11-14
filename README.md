

# Sistema Solar Procedural — Software Renderer en Rust

Simulación de un **sistema solar** generado por *shaders de color* (sin texturas ni materiales), con **Sol**, **planetas** alineados al **plano eclíptico**, **órbitas** (traslación) y **rotación** sobre su eje. Incluye **ventana interactiva**, **cámara navegable**, **estrellas de fondo** (skybox procedural), **anillos** en un gigante gaseoso y **luna** en un planeta rocoso. Basado en un *software renderer* propio (ray casting simple + shading procedural).

Link del video: https://youtu.be/qDaWGanohI8

---

## ⚡️ Ejecución rápida 
```bash
cargo run --release -- --window --width 1280 --height 800 
