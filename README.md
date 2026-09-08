# Lifes Mod

Mod de Minecraft que añade un **sistema de vidas limitadas** para servidores: cada jugador dispone
de un número de vidas, morir gasta una, y quedarse sin ellas tiene consecuencias.

Forge · Minecraft 1.20.1 · Java

---

## Compatibilidad

| | |
|---|---|
| Minecraft | 1.20.1 |
| Cargador | Forge 47 o superior |
| Lado | Cliente y servidor |
| Licencia | MIT |

## Instalación

1. Instalar Forge para Minecraft 1.20.1
2. Copiar `lifesmod-1.0.0.jar` en la carpeta `mods` del perfil
3. Arrancar el juego o el servidor

En un servidor hay que ponerlo también en el cliente: el mod declara `side="BOTH"`.

## Qué contiene

```
com/white/lifesmod/
├── LifesMod              punto de entrada y registro del mod
├── LifeEventHandler      escucha las muertes y descuenta vidas
└── LifeCommandHandler    comandos para consultar y ajustar vidas
lifesmod.mixins.json      inyección sobre el comportamiento base del juego
```

El archivo `Ghost.cpmmodel` es el modelo de personaje asociado, hecho con Custom Player Models.

## Descarga

El `.jar` compilado está en este repositorio y en las
[versiones publicadas](https://github.com/Santiago-off/LifesMods-1.20.1/releases).
