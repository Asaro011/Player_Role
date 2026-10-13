# Player_Role

[English](#english) · [Español](#español)

---

## English

**PlayerRole** is a mobile-first, offline-capable character sheet for tabletop role-playing games (D&D 5e layout). It runs entirely in the browser, requires no account or server, and stores each user's data on their own device.

### Features

- **Section menu.** A hamburger menu (☰) opens each panel on its own — Profile, Combat, Attributes, Spells, Saving Throws, Skills, Backpack, Features, Personality — or an **All** view with every panel on one screen. The last view used is remembered.
- **Profile.** Character name, class and level, background, race, alignment and player name. Tap the portrait to take a photo or pick one from the gallery.
- **Combat.** Armor Class (shield), Speed (winged boot), Hit Points (one heart per point of maximum HP), initiative, proficiency bonus, attacks, hit dice and passive Perception.
- **Attributes.** Hexagon chart that redraws as scores change. Each modifier is calculated automatically and can also be overridden manually; it recalculates when its score is edited again.
- **Spells.** Spellcasting bonuses (ability, save DC, attack bonus), cantrips and levels 1–9, a slot counter per level, and add/remove for each spell.
- **Saving throws and skills.** All six saves and eighteen skills with editable values. Tap a name to mark or clear proficiency.
- **Backpack.** Illustrated backpack with an editable item list and four coin counters — copper (cp), silver (sp), gold (gp) and platinum (pp) — with **+** / **−** buttons.
- **Features and personality.** Class and racial features, languages, proficiencies, traits, ideals, bonds and flaws.
- **Themes.** The 🎨 button offers six presets and custom colors for accent, background, cards and text.

### How to use

1. Tap any value to edit it; changes are saved automatically.
2. Use the ☰ menu to move between panels or to see them all at once.
3. Use the **＋** buttons to add spells, items or features. Clear an entry's text to remove it.
4. Install it as an app: **Android (Chrome)** — menu ⋮ → *Install app* / *Add to Home screen*; **iPhone/iPad (Safari)** — Share → *Add to Home Screen*.

### Data storage and backups

Data is stored in the browser (localStorage with an IndexedDB copy, and the browser is asked to keep it persistent). It is **per device and per browser**: it is not synchronized, and clearing browser data deletes it.

To keep a copy or move a sheet to another device, use **Save copy** to get the backup text (or file) and **Load copy** to restore it. **Reset values** returns the sheet to its blank state.

### Deployment (GitHub Pages)

1. Upload the contents of this folder to the root of a repository (`index.html` must be at the root).
2. In **Settings → Pages**, choose *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. After a minute or two the site is available at `https://<user>.github.io/<repository>/`.

When publishing updates, change the cache name in `sw.js` (e.g. `playerrole-v2`) so installed copies fetch the new version.

### Project contents

| File | Purpose |
|---|---|
| `index.html` | Complete application |
| `manifest.webmanifest` | Install-as-app metadata |
| `sw.js` | Offline support and updates |
| `icons/` | App icons |
| `.nojekyll` | Disables Jekyll processing on GitHub Pages |

---

## Español

**PlayerRole** es una planilla de personaje para juegos de rol de mesa (formato de D&D 5e), pensada para el teléfono y con funcionamiento sin conexión. Se ejecuta por completo en el navegador, no requiere cuenta ni servidor, y guarda los datos de cada usuario en su propio dispositivo.

### Funcionalidades

- **Menú de secciones.** Un menú hamburguesa (☰) abre cada panel por separado — Perfil, Combate, Atributos, Conjuros, Salvaciones, Habilidades, Mochila, Rasgos, Personalidad — o una vista **Todo** con todos los paneles en una sola pantalla. Se recuerda la última vista usada.
- **Perfil.** Nombre del personaje, clase y nivel, trasfondo, raza, alineamiento y nombre del jugador. Al tocar el retrato se puede tomar una foto o elegir una de la galería.
- **Combate.** Clase de armadura (escudo), velocidad (bota alada), puntos de golpe (un corazón por cada punto de golpe máximo), iniciativa, bonificador de competencia, ataques, dados de golpe y Percepción pasiva.
- **Atributos.** Gráfico hexagonal que se redibuja al cambiar los valores. Cada modificador se calcula automáticamente y también puede escribirse a mano; se recalcula cuando se vuelve a editar su atributo.
- **Conjuros.** Datos de lanzamiento (aptitud, CD de salvación, bonificador de ataque), trucos y niveles 1 al 9, contador de espacios por nivel y alta o baja de cada conjuro.
- **Salvaciones y habilidades.** Las seis tiradas de salvación y las dieciocho habilidades con valores editables. Al tocar un nombre se marca o se quita la competencia.
- **Mochila.** Mochila ilustrada con lista de objetos editable y cuatro contadores de monedas — cobre (pc), plata (pp), oro (po) y platino (ppt) — con botones **+** / **−**.
- **Rasgos y personalidad.** Rasgos de clase y de raza, idiomas, competencias, rasgos de personalidad, ideales, vínculos y defectos.
- **Temas.** El botón 🎨 ofrece seis temas predefinidos y colores personalizados para acento, fondo, tarjetas y texto.

### Cómo usarla

1. Toca cualquier valor para editarlo; los cambios se guardan automáticamente.
2. Usa el menú ☰ para cambiar de panel o para verlos todos a la vez.
3. Usa los botones **＋** para agregar conjuros, objetos o rasgos. Para eliminar una entrada, borra su texto.
4. Instálala como app: **Android (Chrome)** — menú ⋮ → *Instalar app* / *Añadir a pantalla de inicio*; **iPhone/iPad (Safari)** — Compartir → *Añadir a pantalla de inicio*.

### Almacenamiento de datos y copias de seguridad

Los datos se guardan en el navegador (localStorage con una copia en IndexedDB, y se solicita al navegador que los conserve de forma persistente). Son **por dispositivo y por navegador**: no se sincronizan, y al borrar los datos del navegador se pierden.

Para conservar una copia o pasar una planilla a otro dispositivo, usa **Guardar copia** para obtener el texto (o archivo) de respaldo y **Cargar copia** para restaurarlo. **Restablecer valores** devuelve la planilla a su estado en blanco.

### Publicación (GitHub Pages)

1. Sube el contenido de esta carpeta a la raíz de un repositorio (`index.html` debe quedar en la raíz).
2. En **Settings → Pages**, elige *Deploy from a branch*, rama `main` y carpeta `/ (root)`.
3. En uno o dos minutos el sitio estará disponible en `https://<usuario>.github.io/<repositorio>/`.

Al publicar actualizaciones, cambia el nombre de la caché en `sw.js` (por ejemplo `playerrole-v2`) para que las copias instaladas descarguen la versión nueva.

### Contenido del proyecto

| Archivo | Función |
|---|---|
| `index.html` | Aplicación completa |
| `manifest.webmanifest` | Datos de instalación como app |
| `sw.js` | Funcionamiento sin conexión y actualizaciones |
| `icons/` | Iconos de la aplicación |
| `.nojekyll` | Desactiva el procesamiento de Jekyll en GitHub Pages |
