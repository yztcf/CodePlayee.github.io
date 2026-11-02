# City surfaces and props

Every asset here and in `public/models/props/` comes from [Poly Haven](https://polyhaven.com) and is licensed [CC0](https://creativecommons.org/publicdomain/zero/1.0/). Set names describe the role in the game, so some differ from what the scan is.

| Set | Poly Haven id | URL | Res | License | Scan |
|---|---|---|---|---|---|
| `plaster_pale` | `painted_plaster_wall` | https://polyhaven.com/a/painted_plaster_wall | 1K | CC0 | |
| `plaster_damaged` | `damaged_plaster` | https://polyhaven.com/a/damaged_plaster | 1K | CC0 | |
| `stucco_grey` | `rough_plasterbrick_05` | https://polyhaven.com/a/rough_plasterbrick_05 | 1K | CC0 | Rough render |
| `limestone_block` | `large_sandstone_blocks_01` | https://polyhaven.com/a/large_sandstone_blocks_01 | 1K | CC0 | Pale sandstone ashlar |
| `brick_red` | `medieval_red_brick` | https://polyhaven.com/a/medieval_red_brick | 1K | CC0 | |
| `brick_dark` | `brick_wall_10` | https://polyhaven.com/a/brick_wall_10 | 1K | CC0 | |
| `brick_rubble_face` | `red_brick_plaster_patch_02` | https://polyhaven.com/a/red_brick_plaster_patch_02 | 1K | CC0 | Broken brick with plaster remnants |
| `slate_roof` | `grey_roof_tiles_02` | https://polyhaven.com/a/grey_roof_tiles_02 | 1K | CC0 | |
| `tile_roof` | `roof_09` | https://polyhaven.com/a/roof_09 | 1K | CC0 | |
| `setts` | `cobblestone_floor_03` | https://polyhaven.com/a/cobblestone_floor_03 | 2K | CC0 | |
| `setts_worn` | `cobblestone_floor_02` | https://polyhaven.com/a/cobblestone_floor_02 | 2K | CC0 | |
| `paving_slab` | `red_sandstone_pavement` | https://polyhaven.com/a/red_sandstone_pavement | 1K | CC0 | |
| `rubble` | `rubble` | https://polyhaven.com/a/rubble | 1K (downscaled from 2K for the texture budget) | CC0 | |
| `gravel_dusty` | `rocks_ground_09` | https://polyhaven.com/a/rocks_ground_09 | 1K | CC0 | Stony ground |
| `dirt_ash` | `burned_ground_01` | https://polyhaven.com/a/burned_ground_01 | 1K | CC0 | Contains dry grass stalks |
| `wood_charred` | `black_painted_planks` | https://polyhaven.com/a/black_painted_planks | 1K | CC0 | Black-painted boards; the catalogue has no charred wood scan |
| `wood_planks_old` | `old_planks_02` | https://polyhaven.com/a/old_planks_02 | 1K | CC0 | |
| `metal_rust` | `rusty_metal_04` | https://polyhaven.com/a/rusty_metal_04 | 1K | CC0 | |
| `plaster_interior_stained` | `concrete_wall_003` | https://polyhaven.com/a/concrete_wall_003 | 1K | CC0 | Stained pale wall |

## Props

| File | Poly Haven id | URL | License | Changes |
|---|---|---|---|---|
| `models/props/crate.glb` | `old_military_crate` | https://polyhaven.com/a/old_military_crate | CC0 | Closed variant only, meshes joined, decimated from 10,476 to 3,141 faces, maps at 768 px |
| `models/props/barrel.glb` | `barrel_03` | https://polyhaven.com/a/barrel_03 | CC0 | Blue paint regraded to field grey, maps at 768 px |

## Changes to the textures

- All maps are re-encoded JPEG. `normal` is the `nor_gl` map and `rough` the `Rough` map.
- Albedo low-frequency light falloff is flattened to reduce visible repeats: `setts`, `setts_worn`, `rubble`, `gravel_dusty`, `paving_slab`, `slate_roof`, `tile_roof`, `brick_red`, `brick_dark`, `limestone_block`, `stucco_grey`.
- Course-scale row and column brightness is also evened out: `setts`, `setts_worn`, `rubble`, `gravel_dusty`.
