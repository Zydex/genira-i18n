# Spanish (es) translation review - flagged strings

_Covers the 2026-11 batch run (MESH-1043)._

All strings passed the back-translation fidelity check, either on the first pass or after a retry with alternate phrasings. **No strings remain flagged for manual review.**

## Resolved in manual review

| File | Key | English | Chosen Spanish |
|---|---|---|---|
| `cases` | `toast.failedToLoadCase_one` | Failed to load case | No se ha podido cargar el caso |
| `cases` | `toast.failedToLoadCase_other` | Failed to load {{count}} cases | No se han podido cargar {{count}} casos |

The pipeline's choice added "en el navegador" ("in the browser"), which isn't in the source. A reviewer removed it.

## Resolved after retry

These were flagged on the first pass. A retry variant then fully passed. They are listed here for reference only.

| File | Key | English | Chosen Spanish | Back-translation |
|---|---|---|---|---|
| `cases` | `toast.failedToLoadCaseRanOutOfSpace_one` | Failed to load case, the browser has run out of space | No se ha podido cargar el caso en el navegador: no queda espacio de almacenamiento | The case could not be loaded in the browser: no storage space left |
| `cases` | `toast.failedToLoadCaseRanOutOfSpace_other` | Failed to load {{count}} cases, the browser has run out of space | No se han podido cargar {{count}} casos en el navegador: no queda espacio de almacenamiento | {{count}} cases could not be loaded in the browser: no storage space left |
| `template` | `label.affixText` | Affix Text | Añadir texto | Add text |
| `template` | `options.textStyle.engraved` | Engraved | Grabado | Engraved |
| `template` | `message.textStyleHelp` | Engrave will cut the text into the model.\n\nEmboss will extrude the text out of the model. | Con Grabado, el texto se talla hacia el interior del modelo.\n\nCon En relieve, el texto sobresale del modelo. | With Engraved, the text is carved into the model.\n\nWith Embossed, the text protrudes from the model. |
