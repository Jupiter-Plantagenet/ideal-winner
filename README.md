# ideal-winner

Code, data and manuscript for the study, kept together in one repository.

## Layout

| Folder   | What lives here |
|----------|-----------------|
| `paper/` | The manuscript, kept in sync with [HiTeX](https://hitexapps.com). Edit it there or here; HiTeX commits and pulls through this folder only. |
| `src/`   | Analysis code. |
| `data/`  | Inputs and generated results. |

## Working with the manuscript

The `paper/` folder is connected to a HiTeX project. Compiling in HiTeX can commit
here automatically, and pushes to this repository show up in the HiTeX editor,
where they can be pulled in. Figures written by the code can be mirrored into the
paper from `src/` or `data/`.
