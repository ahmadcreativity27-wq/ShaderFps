# ShaderFPS

Client-side Fabric performance mod for **Minecraft 26.2**, tuned for mobile GPUs (MJ Launcher) and Iris Shaders.

- **FPS monitor + modes** - `OFF`, `BALANCED` (default, acts below 50 FPS), `AGGRESSIVE` (acts below 60 FPS). Press **K** to cycle; the mode shows in the action bar and is saved to `config/shaderfps.properties`.
- **Smart particle throttling** - randomly drops rain, smoke, fire and explosion particles (more types in `AGGRESSIVE`) while FPS is low.
- **Adaptive render distance** - shrinks entity and block-entity render range when FPS drops and restores it gradually once FPS recovers.

Requires Fabric Loader, Fabric API and Java 25.

## License

CC0-1.0
