A Minecraft modpack for my server.

## how to install with Prism Launcher

### 1. Make a new instance

1. Click `Add Instance` (top left).
2. Pick `Custom` on the left.
3. Give it a name.
4. In the version list, pick `1.21.1`.
5. Under `Mod loader` at the bottom, choose `NeoForge` and select version `21.1.265`.
6. Click `OK`.
7. DO NOT OPEN OR RUN IT YET

### 3. Put the updater in the instance folder

1. Download `packwiz-installer-bootstrap.jar` from here:
   <https://github.com/packwiz/packwiz-installer-bootstrap/releases/latest/download/packwiz-installer-bootstrap.jar>
2. In Prism, click your new instance once, then click `Folder` on the right. A folder opens.
3. Open the folder called `minecraft` (or `.minecraft`) inside it.
4. Move `packwiz-installer-bootstrap.jar` into that folder. The file name must stay exactly
   `packwiz-installer-bootstrap.jar`.

### 4. Prism settings

1. Click your instance, then `Edit` on the right.
2. Go to `Settings` → `Custom commands` tab.
3. Tick the `Custom Commands` box.
4. Paste this into `Pre-launch command` (all on one line):

   ```
   "$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/Sam-Sims/minecraft-pack/main/pack.toml
   ```

### 5. Give it enough memory

Still in `Settings`, open the `Java` tab, tick `Memory`, and set `Maximum memory allocation` to
at least `6144 MiB`

### 6. Press Play

1. Click `Launch`.
2. The first time, a window pops up listing `optional extras` (shaders, texture packs, minimap and so on).
   Tick what you want and click `OK` - probaly just use them all
