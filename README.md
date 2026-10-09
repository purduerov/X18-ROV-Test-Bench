# X18 ROV Test Bench

Surface test-bench hardware for the Purdue ROV team (X18 vehicle generation):
carrier and power boards for topside validation without the vehicle in the water.

## Layout

- `MCU and Pi Board/` — MCU + Raspberry Pi carrier board
  (`mcu and pi board.kicad_sch` / `.kicad_pcb`, project-local `Libraries/`,
  `custom library.*`)
- `power/` — power distribution board (`power.kicad_sch` / `.kicad_pcb`,
  `power_symbols.*`, rail sheets such as `12-5`, `48-12`, `STM`)

## Tooling

- Designed in KiCad — open the `.kicad_pro` in each board folder.
- Fab/plot outputs (`outputs/`, `manufacturing/`, Gerbers), KiCad
  auto-backups (`*-backups/`), caches, and component source archives
  (`*.zip`) are git-ignored; regenerate them locally.
