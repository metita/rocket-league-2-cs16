<div align="center">

# Rocket League 2 for Counter-Strike 1.6 (AMXX)

**Full Rocket League game mode for CS 1.6 (AMX Mod X + Metamod-R). For sale.**

![Counter-Strike 1.6](https://img.shields.io/badge/Counter--Strike-1.6-orange?style=for-the-badge)
![AMX Mod X](https://img.shields.io/badge/AMX%20Mod%20X-1.10-blue?style=for-the-badge)
![Metamod-R](https://img.shields.io/badge/Metamod--R-compatible-green?style=for-the-badge)
![Bullet Physics](https://img.shields.io/badge/Physics-Bullet%203-red?style=for-the-badge)

![Price](https://img.shields.io/badge/PRICE-125%20USD-success?style=for-the-badge)
![Negotiable](https://img.shields.io/badge/negotiable-yes-yellow?style=for-the-badge)
![Payment](https://img.shields.io/badge/payment-crypto%20only-purple?style=for-the-badge)

### Discord: `n1colas.23`

[English](#english) | [Español](#español)

</div>

---

## English

### What is it?

A **Rocket League style game mode** that runs on a regular **Counter-Strike 1.6** server (HLDS / ReHLDS). Players drive cars with real physics, play with the ball, boost, jump, demolish each other and score goals. It has classic matches, competitive matches with ELO and ranks, and the **Heatseeker** mode.

It runs on a **native C++ module** (Metamod-R + AMXX) powered by **Bullet Physics**. Car and ball physics are real, not faked with Half-Life entities.

A good fit for CS 1.6 communities that want a mode no other server has.

### What's included

| Component | Details |
|---|---|
| **Physics module** (`.so` / `.dll`) | C++ with Bullet Physics 3: cars, ball, `.obj` arena, 44 natives and 17 forwards for plugins |
| **`pl_core`** | Full gameplay: match flow, kickoff, scoreboard, overtime, zero-second rule, car impacts, demolitions, HUD and camera |
| **`pl_inventory`** | Inventory, per-team car customization, post-match drops and admin commands |
| **`pl_quickchat`** | Rocket League style quick chat ("I got it!", "What a save!"...), customizable per player |
| **SQL** | MariaDB schema with migrations: inventory, rankings, competitive match details and integrity |
| **Resources** | Models, sounds, sprites, arena map and language files |
| **JSON configs** | Item catalog and car physics presets, editable without recompiling |
| **Build** | CMake + GitHub Actions that build the Linux `.so` (glibc compatible with real servers) |

Around **14,800 lines of Pawn**, plus the C++ module.

### Cosmetics

| Category | Amount |
|---|---|
| Car bodies | **41 models**, **438 color variants** |
| Wheels | **12 models**, **131 variants** |
| Toppers | **30 models**, **204 variants** |
| Boosts | **4 types**, **27 variants** (Ion, Rainbow, Bubbles, Digital) |
| Goal explosions | **10** (Shockwave, Solar Flare, Nuclear Attack, Singularity, Supernova, Golden Dragon, Sharky, Tornado...) |

**Some of the cars:** Octane, Dominus, Fennec, Batmobile, Breakout, Merc, Lamborghini Aventador, Audi R8, Nissan Skyline, Porsche 911, Dodge Viper, Tesla Cybertruck, Mazda RX-7, Ferrari 512 TR, Lightning McQueen, Francesco Bernoulli, Flintstones and more.

**Physics presets:** Octane, Dominus, Breakout, Hybrid, Merc and Batmobile, matching the Rocket League hitboxes.

Rarities from **Uncommon** to **Black Market**, plus Premium, Limited and Legacy items.

### Features

**Gameplay**
- Real car and ball physics (Bullet Physics)
- Boost, jump, flips, **powerslide** and **supersonic**
- **Demolitions** and car collisions
- Kickoff with the original spawn positions
- **Overtime** and the zero-second rule
- Custom goal explosions
- **Heatseeker** mode

**Competitive**
- **ELO** and every **Rocket League rank** with divisions
- **Placement matches** (10 by default)
- **Forfeit** with configurable rules
- **Rejoin** policy: players who leave and come back can keep playing without affecting their ELO
- Team **autobalance** and skill-based team randomizer
- Stats and details of every match saved to the database

**Inventory and drops**
- **Customize vehicle** menu with a separate loadout for each team
- **Drops** after every rated match (12% base chance, plus a bonus for VIP tiers)
- VIP-exclusive cosmetics (Gold, Premium, Platinum)
- Admin commands: `rl_give_item`, `rl_remove_item`, `rl_give_drop`, `rl_list_items`

**Camera**
- **Rocket League style** camera (110 FOV, 100 height, 300 distance...), fully configurable
- Orbit camera (`+rl_cam_orbit`)
- Each player can choose between the new camera and the classic one

**Quick chat**
- Quick messages bound to the radio keys
- Categories and messages customizable per player (`/qc`)

### Requirements

- Counter-Strike 1.6 **HLDS / ReHLDS** server (Linux or Windows)
- **Metamod-R** + **AMX Mod X 1.10**
- **MariaDB / MySQL**
- An account system to identify players (the mod can be adapted to yours)

### Price

**125 USD, negotiable. Crypto only.**

Add me on Discord for questions, a live demo or to buy: **`n1colas.23`**

### FAQ

**Can I see it working before buying?**
Yes. Message me on Discord and we'll set up a demo.

**Will it work on my server?**
If you run ReHLDS or HLDS with Metamod-R and AMXX 1.10, yes. Send me your setup and I'll confirm.

**Can I add my own cars or cosmetics?**
Yes. The catalog and presets are JSON files, so you can add or change items without recompiling.

**What payment methods do you accept?**
Crypto only. We agree on the coin and network over Discord.

---

## Español

### ¿Qué es?

Un **modo de juego estilo Rocket League** que corre en un servidor normal de **Counter-Strike 1.6** (HLDS / ReHLDS). Los jugadores manejan autos con física real, juegan a la pelota, usan boost, saltan, hacen demoliciones y meten goles. Tiene partidas clásicas, competitivas con ELO y rangos, y el modo **Heatseeker**.

Usa un **módulo nativo en C++** (Metamod-R + AMXX) con física de **Bullet Physics**. La física de autos y pelota es real, no una simulación con entidades de Half-Life.

Ideal para comunidades de CS 1.6 que quieren un modo que ningún otro servidor tiene.

### Qué incluye

| Componente | Detalle |
|---|---|
| **Módulo de física** (`.so` / `.dll`) | C++ con Bullet Physics 3: autos, pelota, arena `.obj`, 44 natives y 17 forwards para plugins |
| **`pl_core`** | Gameplay completo: flujo de partida, saque inicial, marcador, tiempo extra, regla del segundo cero, impactos, demoliciones, HUD y cámara |
| **`pl_inventory`** | Inventario, personalización de autos por equipo, drops por partida y comandos de administración |
| **`pl_quickchat`** | Chat rápido estilo Rocket League ("I got it!", "What a save!"...), personalizable por jugador |
| **SQL** | Esquema de MariaDB con migraciones: inventario, ranking, detalle de partidas competitivas e integridad |
| **Recursos** | Modelos, sonidos, sprites, mapa de arena y archivos de idioma |
| **Configs JSON** | Catálogo de ítems y presets de física de autos, editables sin recompilar |
| **Build** | CMake + GitHub Actions que compila el `.so` para Linux (glibc compatible con servidores reales) |

Unas **14.800 líneas de código Pawn**, más el módulo en C++.

### Cosméticos

| Categoría | Cantidad |
|---|---|
| Autos | **41 modelos**, **438 variantes** de color |
| Ruedas | **12 modelos**, **131 variantes** |
| Toppers | **30 modelos**, **204 variantes** |
| Boosts | **4 tipos**, **27 variantes** (Ion, Rainbow, Bubbles, Digital) |
| Explosiones de gol | **10** (Onda expansiva, Llamarada solar, Nuclear Attack, Singularidad, Supernova, Golden Dragon, Sharky, Tornado...) |

**Algunos autos:** Octane, Dominus, Fennec, Batmobile, Breakout, Merc, Lamborghini Aventador, Audi R8, Nissan Skyline, Porsche 911, Dodge Viper, Tesla Cybertruck, Mazda RX-7, Ferrari 512 TR, Lightning McQueen, Francesco Bernoulli, Flintstones y más.

**Presets de física:** Octane, Dominus, Breakout, Hybrid, Merc y Batmobile, igual que los hitboxes de Rocket League.

Rarezas desde **Poco común** hasta **Mercado negro**, además de ítems Premium, Limitados y Legado.

### Características

**Gameplay**
- Física real de autos y pelota (Bullet Physics)
- Boost, salto, flips, **powerslide** y **supersónico**
- **Demoliciones** y choques entre autos
- Saque inicial con las posiciones originales
- **Tiempo extra** y regla del segundo cero
- Explosiones de gol personalizadas
- Modo **Heatseeker**

**Competitivo**
- **ELO** y todos los **rangos de Rocket League** con divisiones
- **Partidas de clasificación** (10 por defecto)
- **Rendición** con reglas configurables
- Política de **reconexión**: quien abandona y vuelve puede seguir jugando sin afectar su ELO
- **Autobalance** de equipos y randomizador por habilidad
- Estadísticas y detalle de cada partida guardados en la base de datos

**Inventario y drops**
- Menú **Personalizar vehículo** con loadout separado para cada equipo
- **Drops** al terminar cada partida con rango (12 % base, más un bonus para VIP)
- Cosméticos exclusivos para VIP (Gold, Premium, Platinum)
- Comandos de admin: `rl_give_item`, `rl_remove_item`, `rl_give_drop`, `rl_list_items`

**Cámara**
- Cámara **estilo Rocket League** (FOV 110, altura 100, distancia 300...), totalmente configurable
- Cámara orbital (`+rl_cam_orbit`)
- Cada jugador elige entre la cámara nueva y la clásica

**Chat rápido**
- Mensajes rápidos con las teclas de radio
- Categorías y mensajes personalizables por jugador (`/qc`)

### Requisitos

- Servidor **HLDS / ReHLDS** de Counter-Strike 1.6 (Linux o Windows)
- **Metamod-R** + **AMX Mod X 1.10**
- **MariaDB / MySQL**
- Un sistema de cuentas para identificar a los jugadores (el mod se adapta al que uses)

### Precio

**125 USD, negociable. Solo crypto.**

Agrégame en Discord para consultas, una demostración o para comprar: **`n1colas.23`**

### Preguntas frecuentes

**¿Puedo verlo funcionando antes de comprar?**
Sí. Escríbeme por Discord y coordinamos una demostración.

**¿Es compatible con mi servidor?**
Si usas ReHLDS o HLDS con Metamod-R y AMXX 1.10, sí. Envíame tu configuración y te confirmo.

**¿Puedo agregar mis propios autos o cosméticos?**
Sí. El catálogo y los presets están en archivos JSON, así que puedes agregar o cambiar ítems sin recompilar.

**¿Qué medios de pago aceptas?**
Solo crypto. La moneda y la red las acordamos por Discord.

---

<div align="center">

<sub>rocket league 2, counter-strike 1.6, cs 1.6, rocket league, amxx, amx mod x, metamod, rehlds, hlds, goldsrc, plugin, mod, game mode, soccar, car soccer</sub>

</div>
