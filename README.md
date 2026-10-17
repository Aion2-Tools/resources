<h1 align="center">resources</h1>

<p align="center">
  AION 2 community tools, collected in one place to learn from.
</p>

Each folder is a git submodule pointing at the original author's repository. Nothing here is
modified; the code belongs to its authors under their own licenses.

## Getting it

```sh
git clone --recurse-submodules https://github.com/Aion2-Tools/resources.git
```

Already cloned without submodules:

```sh
git submodule update --init --recursive
```

Pull the latest version of every tool:

```sh
git submodule update --remote
```

## Tools

### DPS meters

| Folder | Project | What it is | Stack |
|---|---|---|---|
| [`Aion2Flow`](https://github.com/cloris-chan/Aion2Flow) | Aion2Flow | Real-time combat analysis | C#, Avalonia |
| [`AIon2-Dps-Meter`](https://github.com/Kuroukihime/AIon2-Dps-Meter) | RATmeter | Lightweight network-based DPS meter and stat efficiency calculator (Global) | C#, WPF |
| [`AetherDPS`](https://github.com/yykk62/AetherDPS) | AetherDPS | DPS meter and companion for the EU servers (German; RATmeter fork) | C# |
| [`Aion-DPS-Meter`](https://github.com/SkeeveAN/Aion-DPS-Meter) | Aion DPS Meter | DPS meter, overlay, boss leaderboards, world boss timers, pet maps | C#, WPF |
| [`A2Tools-DPS-Meter`](https://github.com/taengu/A2Tools-DPS-Meter) | A2Tools DPS Meter | DPS meter for any region with fight analysis | Rust, Tauri |
| [`PichetMeter-Aion2-Multitool`](https://github.com/Pichetdechiasso/PichetMeter-Aion2-Multitool) | PichetMeter | Group DPS meter, armory, timers, macros and map overlay (French) | JavaScript |

### Other tools

| Folder | Project | What it is | Stack |
|---|---|---|---|
| [`aion2pettracker`](https://github.com/keytftw/aion2pettracker) | Aion 2 Pet Tracker | Pet tracking, interactive map, Spacetime Rift timers | C# |
| [`aion2-cube-radar`](https://github.com/dennisreichenberg/aion2-cube-radar) | Cube Radar | Hidden cube radar overlay (passive, Npcap) | C# |
| [`aion2_api`](https://github.com/axsddlr/aion2_api) | AION 2 API | Unofficial JSON API: notices, events, server population, characters | Python |

## Related

Built by Aion2-Tools from what was learned here:
[tenshi-core](https://github.com/Aion2-Tools/tenshi-core) (combat engine) and
[tenshi-meter](https://github.com/Aion2-Tools/tenshi-meter) (DPS overlay).
