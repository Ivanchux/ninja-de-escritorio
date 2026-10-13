<div align="center">

<img src="docs/banner.png" alt="Ninja de Escritorio" width="100%">

# 🗡️ Ninja de Escritorio

**Un Fruit Ninja con iconos de ordenador retro.**
Corta carpetas, disquetes y CD-ROM, esquiva virus y pantallazos azules y derrota jefes de malware. En el nuevo modo **Descenso** eliges tu camino, coleccionas mejoras y rompes el PC capa a capa hasta enfrentarte al Procesador Maestro.

[![Jugar](https://img.shields.io/badge/▶_JUGAR_AHORA-008080?style=for-the-badge)](https://ivanchux.github.io/ninja-de-escritorio/)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-e34f26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![Dependencias](https://img.shields.io/badge/dependencias-0-success?style=flat-square)
![Móvil](https://img.shields.io/badge/PC%20y%20móvil-sí-000080?style=flat-square)
![Licencia](https://img.shields.io/badge/licencia-MIT-808080?style=flat-square)

</div>

---

## 📑 Índice

[Qué es](#-qué-es) · [Capturas](#-capturas) · [En movimiento](#-en-movimiento) · [Cómo se juega](#-cómo-se-juega) · [Modo Descenso](#-modo-descenso-roguelike) · [El PC que se rompe](#-el-pc-que-se-rompe) · [Efectos y power-ups](#-efectos-y-power-ups) · [Jefes](#-jefes) · [Personalización](#-personalización-y-logros) · [Los 38 iconos](#-los-38-iconos) · [Ejecutar y publicar](#-ejecutar-y-publicar) · [Detalles técnicos](#-detalles-técnicos) · [Estructura](#-estructura-del-repositorio) · [Licencia](#-licencia)

## 🖥️ Qué es

Ninja de Escritorio es un juego de navegador en el que los objetos que vuelan son **iconos de los viejos sistemas operativos**: carpetas, papeleras, disquetes, módems, ratones de bola… y los enemigos son virus, errores y troyanos.

- Todo el arte está **dibujado a mano en píxeles** y generado por código. No hay logos reales ni imágenes externas.
- Interfaz inspirada en **Windows 95/98**: ventanas, botones biselados, barra de tareas y pantallazo azul de derrota.
- **Un solo archivo** (`index.html`), sin librerías, sin instalación y sin servidor.
- Funciona con **ratón y con pantalla táctil**.

## 📸 Capturas

<div align="center">

| Menú | Cortando iconos |
|:---:|:---:|
| <img src="docs/menu.png" width="420"> | <img src="docs/corte.png" width="420"> |

| Jefe final | Personalizar |
|:---:|:---:|
| <img src="docs/jefe.png" width="420"> | <img src="docs/shop.png" width="420"> |

<img src="docs/movil_menu.png" height="440"> &nbsp; <img src="docs/movil_juego.png" height="440">

*En el móvil se juega con el dedo y la interfaz se adapta a la pantalla.*

</div>

## 🎬 En movimiento

<div align="center">

### 📱 En el móvil

| Cortes y combos | El PC se rompe | Jefe |
|:---:|:---:|:---:|
| <img src="docs/gifs/movil-cortes.gif" width="250"> | <img src="docs/gifs/movil-capas.gif" width="250"> | <img src="docs/gifs/movil-jefe.gif" width="250"> |

### 🖥️ En el PC

**Power-ups:** Tiempo lento, Antivirus y Ctrl+Z

<img src="docs/gifs/pc-poderes.gif" width="720">

**Las capas del PC rompiéndose, de la pantalla al chip**

<img src="docs/gifs/pc-capas.gif" width="720">

**Pelea contra un jefe**

<img src="docs/gifs/pc-jefe.gif" width="720">

</div>

## 🗺️ Modo Descenso (roguelike)

Una partida es **un viaje de la pantalla al chip**. Hay 9 pisos, uno por cada capa del PC, y solo tienes una vida.

<div align="center">

| El mapa | Eliges una mejora | Jefe final |
|:---:|:---:|:---:|
| <img src="docs/mapa.png" width="300"> | <img src="docs/recompensa.png" width="300"> | <img src="docs/jefe-final.png" width="300"> |

<img src="docs/gifs/movil-descenso.gif" height="420"> &nbsp; <img src="docs/gifs/movil-jefe-final.gif" height="420">

<img src="docs/gifs/pc-descenso.gif" width="600">

</div>

### Cómo funciona

- **Mapa ramificado, como en Slay the Spire.** En cada piso eliges entre 2 o 3 nodos conectados con el anterior. Cada camino tiene un riesgo distinto.
- **Estabilidad y créditos.** La estabilidad no se rellena entre oleadas. Los créditos (que ganas jugando) sirven para comprar mejoras en el mercado.
- **Jefe a mitad (piso 5) y jefe final (piso 9).** El jefe final es el **Procesador Maestro**, con **3 fases**: más proyectiles, abanicos de virus y un colapso térmico.

| Nodo | Qué pasa |
|:-:|---|
| **O** Oleada | Alcanza los puntos que pide el piso y elige 1 de 3 mejoras. |
| **E** Élite | Oleada más difícil y más larga. Da una mejora **rara**. |
| **$** Mercado | Compra mejoras o repara con tus créditos. |
| **+** Reparación | Recupera estabilidad u optimiza (elige una mejora). |
| **?** Evento | Decisiones con riesgo: un pendrive desconocido, una ventana emergente, una copia de seguridad… |
| **J** Jefe | Pelea con un jefe y llévate un botín raro. |

### 23 mejoras

Cada mejora tiene una categoría y puedes acumular copias.

- **Espada:** Hoja larga, Corte en cruz, Onda de choque, Ráfaga, Racha larga, Reflejos.
- **Iconos:** Pepitas, Cadena explosiva, Virus mascota, Antivirus residente, Minero de bytes, Interés compuesto.
- **Supervivencia:** Disco de respaldo, Cortafuegos, Autoreparación, Sandbox, Colchón de RAM, Punto de restauración, Segundo aliento.
- **Riesgo y recompensa:** Desbordamiento, Pacto del adware, Overclock, Todo o nada.

### 6 sinergias

Si juntas dos mejoras concretas se activa un bono extra con nombre:

| Sinergia | Mejoras | Efecto |
|---|---|---|
| **Katana** | Hoja larga + Corte en cruz | El corte en cruz llega un 50% más lejos |
| **Servidor redundante** | Disco de respaldo + Cortafuegos | El cortafuegos absorbe un virus más |
| **Inmunizado** | Virus mascota + Sandbox | Cortar un virus te cura un 4% |
| **Fiebre del oro** | Pepitas + Minero de bytes | Cada dorado da 4 créditos |
| **Cadena crítica** | Onda de choque + Cadena explosiva | Las explosiones llegan un 60% más lejos |
| **Contrato de riesgo** | Pacto del adware + Overclock | Los puntos valen un 25% más |

Con los **bytes** que ganas en cada descenso compras **mejoras permanentes**: más estabilidad inicial, créditos de arranque y relanzamientos de mejoras.

## 🎮 Cómo se juega

Desliza el ratón o el dedo para **cortar los iconos** que saltan por la pantalla.

| Tipo | Qué hacer |
|---|---|
| 🟢 Iconos normales | Córtalos. Suman puntos y se encadenan en combos. |
| ⭐ Iconos dorados | Brillan en amarillo y valen +4 puntos. |
| 🔴 Virus, errores y malware | No los cortes. Brillan en rojo y te penalizan. |
| 🔵 Power-ups | Cortarlos activa un efecto especial (ver más abajo). |

### Modos

- **Descenso:** el modo roguelike. Está explicado [más abajo](#-modo-descenso-roguelike).
- **Clásico:** tienes una barra de **estabilidad**. Cada icono bueno que se cae resta un 10 %. Cortar un virus resta un 30 %. Subir de nivel recupera un 20 %. Si llega a 0 aparece el pantallazo azul.
- **Contrarreloj:** 60 segundos. Cada virus resta 3 s y Ctrl+Z suma 4 s.

Subes de nivel cada **15 puntos** y la dificultad crece con cada nivel. Cada **5 niveles** aparece un jefe.

**Teclas (PC):** `P` o `Esc` para pausar.

## 💥 El PC que se rompe

El fondo es el interior de un ordenador y **se va destruyendo según avanzas**. Cada dos niveles cambias de capa, con un temblor de pantalla y un aviso. Cada capa añade más cables sueltos, chispas y piezas que caen.

<div align="center">
<img src="docs/capas.png" width="100%">
</div>

| # | Capa | Qué verás |
|:-:|---|---|
| 1 | **Pantalla** | Grietas en el cristal |
| 2 | **Software** | Más grietas y rayas de glitch |
| 3 | **Escritorio** | Agujeros en el escritorio con datos por debajo |
| 4 | **Sistema operativo** | Ventanas rotas y barra de tareas dañada |
| 5 | **Programas** | Ventanas del sistema desmoronándose |
| 6 | **Interfaz** | La interfaz queda en alambre y cuadrícula |
| 7 | **Consola** | Código verde sobre negro con ruido |
| 8 | **Hardware** | Placa base, condensadores, tornillos, cables cortados y chispas |
| 9 | **Chip** | El procesador al descubierto, con su brillo dorado |

El movimiento del fondo es lento a propósito. Si tu sistema pide *reducir movimiento*, se ralentiza todavía más. La pantalla de derrota es plana y no se mueve.

## ✨ Efectos y power-ups

Cada corte tiene **reacción visual**:

- **Estela de corte** que cruza el icono y dos mitades que salen disparadas.
- **Partículas propias de cada icono.** Los disquetes sueltan unos y ceros, los CD cristales de colores, el papel de la carpeta se esparce y los auriculares y altavoces sueltan notas musicales.
- **Manchas de píxeles** que quedan un momento en el fondo, como el jugo en Fruit Ninja.
- **Ondas** que crecen con el combo y un destello cada 5 de racha.
- **Micro-pausa** al cortar un dorado, un power-up o un jefe.
- **Glitch de pantalla** si cortas un virus.
- Tu **estela comprada** también tiñe las partículas.

| Power-up | Icono | Efecto |
|---|:-:|---|
| **Tiempo lento** | ⏳ | La pantalla se tiñe de azul y todo va a cámara lenta 4 s, con cuenta atrás visible. |
| **Antivirus** | 🛡️ | Un rayo azul sale hacia cada virus de la pantalla y los elimina. |
| **Ctrl+Z** | ↩️ | Rebobinado amarillo. Recupera un 25 % de estabilidad o suma 4 s. |

## 👾 Jefes

Cada 5 niveles (en Clásico y Contrarreloj) aparece un jefe con **sprite propio de 48×48** que lanza iconos peligrosos. Hay que golpearlo varias veces antes de que escape. Si se va, pierdes estabilidad.

<div align="center">
<img src="docs/jefes.png" width="720">
</div>

**Rey Virus · Caballo de Troya · Ransomware · Pantallazo Gigante · Gusano Mayor · Adware Infinito**

Y en lo más profundo del PC espera el jefe final, el **Procesador Maestro** (abajo a la derecha), que solo aparece en el modo Descenso.

## 🎨 Personalización y logros

Cada partida te da **bytes** para comprar:

- **9 estelas:** Blanca, Neón, Fuego, Arcoíris, Código, Hielo, Oro, Vacío y Píxeles.
- **5 hojas de espada:** Espada de acero, Katana negra, Lápiz óptico, Destornillador y Sable láser. Cambian el cursor en PC y la hoja que ves al deslizar el dedo en el móvil.
- **11 escritorios:** Clásico (cambia de color con cada nivel), Medianoche, Atardecer, Algodón, Matriz y seis fondos propios inspirados en distintas épocas: **Pradera, Cielo de nubes, Espacio, Aurora, Sintonía retro y Burbujas**.
- **Mejoras permanentes** para el modo Descenso.

<div align="center">
<img src="docs/escritorios.png" width="720">
</div>

Hay **18 logros** (Primer corte, Racha, Cazador de oro, Cazavirus, Hasta el chip, Descenso completado…) y una tabla con tus mejores partidas de cada modo.

Además hay música chiptune generada con Web Audio (más tensa en los jefes), efectos de sonido, vibración en móvil y un menú de ajustes para desactivarlos.

> El progreso se guarda en el `localStorage` del navegador. Es independiente en cada navegador y dispositivo.

## 🗂️ Los 38 iconos

Todos son originales, inspirados en el estilo de los sistemas operativos de los 90. Están en [`assets/iconos`](assets/iconos) en PNG de 256 px y se ven también dentro del juego, en **Catálogo**.

<div align="center">
<img src="docs/hoja-de-iconos.png" width="720">
</div>

**28 buenos** (carpeta, disquete, papelera, equipo, CD-ROM, impresora, bloc de notas, paleta, internet, clip, ratón, teclado, módem, correo, lupa, joystick, RAM, procesador, disco duro, USB, webcam, altavoz, tarjeta gráfica, calculadora, candado, auriculares, SD, reloj), **7 malos** (virus, error, pantallazo, troyano, adware, gusano, ransomware) y **3 power-ups** (reloj de arena, antivirus, Ctrl+Z).

## 🚀 Ejecutar y publicar

### Jugar en local

No hace falta instalar nada. Abre `index.html` en el navegador.

```bash
git clone https://github.com/Ivanchux/ninja-de-escritorio.git
cd ninja-de-escritorio
# abre index.html, o sirve la carpeta si prefieres:
python3 -m http.server 8000   # http://localhost:8000
```

### Publicar en GitHub Pages

1. Sube el repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. En *Build and deployment* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. En un minuto estará en `https://ivanchux.github.io/ninja-de-escritorio/`.

## 🔧 Detalles técnicos

- **Canvas 2D** con bucle `requestAnimationFrame` y escalado por densidad de píxeles.
- **Pixel art procedural:** cada icono se dibuja por código en un lienzo de 32×32 (los jefes en 48×48), y los escritorios se pintan a baja resolución. Todo se escala sin suavizado.
- **Modo Descenso:** mapa generado al azar y dibujado en SVG, mejoras que modifican un objeto de modificadores del motor y sinergias que se detectan solas.
- **Entrada unificada** con *pointer events*, válida para ratón, táctil y lápiz. El corte es una intersección segmento-círculo.
- **Fondo por capas:** 9 escenas generadas por código con semilla fija, pintadas a baja resolución y escaladas sin suavizar. Es ligero en móviles.
- **Audio:** Web Audio API (osciladores), sin archivos de sonido.
- **Cursor de espada** pixel-art generado en tiempo de ejecución, solo con ratón.
- **Accesibilidad:** respeta `prefers-reduced-motion` y el modo oscuro del sistema; botones con foco visible.
- **Móvil:** `viewport-fit=cover`, márgenes de seguridad, `touch-action` controlado y partículas reducidas en pantallas pequeñas.
- **Cero dependencias**, sin peticiones de red.

## 📁 Estructura del repositorio

```text
ninja-de-escritorio/
├── index.html        # El juego completo (HTML + CSS + JS)
├── assets/iconos/    # Los 38 iconos en PNG
├── docs/             # Capturas, GIFs e imágenes de este README
├── CHANGELOG.md      # Historial de versiones
├── LICENSE           # MIT
└── README.md
```

## 🗺️ Ideas futuras

- [x] Jefe final propio para la capa del chip
- [x] Modo roguelike con mapa y mejoras
- [ ] Descenso diario con semilla fija
- [ ] Reliquias de élite y más eventos
- [ ] Ranking online
- [ ] Tutorial interactivo para móvil
- [ ] Más escritorios y estelas

## 📜 Licencia

El código y el arte están publicados bajo la licencia **[MIT](LICENSE)**. Puedes usarlos, modificarlos y compartirlos, manteniendo el aviso de copyright.

Los iconos son dibujos originales **inspirados** en el estilo de los sistemas operativos clásicos. No contienen logos, marcas ni recursos de ninguna compañía. *Windows* es una marca de Microsoft y este proyecto no está afiliado a ella.

---

<div align="center">

Hecho con 💾 por **[Ivanchux](https://github.com/Ivanchux)**

⭐ Si te ha gustado, deja una estrella al repositorio.

</div>
