# Spanish (es) translation review - flagged strings

_Covers the 2026-11 batch run (MESH-1043)._

The following strings still did not fully pass the back-translation fidelity check after a retry with alternate phrasings, and are flagged here for manual review.

## File: `cases`

### `toast.failedToLoadCase_one`

- **English original:** Failed to load case
- **Chosen Spanish translation:** No se ha podido cargar el caso en el navegador
- **Back-translation:** The case could not be loaded in the browser
- **Reason flagged:** Adds 'in the browser', which the source does not say. This is a small drift, but it is not material. It is the only alternate that keeps 'load' (cargar). The other two say 'open' (abrir), which changes the action, and 'Error al abrir' also changes the tone to a generic error.

### `toast.failedToLoadCase_other`

- **English original:** Failed to load {{count}} cases
- **Chosen Spanish translation:** No se han podido cargar {{count}} casos en el navegador
- **Back-translation:** {{count}} cases could not be loaded in the browser
- **Reason flagged:** Adds 'in the browser', which the source does not say. It is the only alternate that keeps 'load' rather than 'open', and {{count}} is preserved. It also stays consistent with the _one form.

## Resolved after retry

These were flagged on the first pass. A retry variant then fully passed. They are listed here for reference only.

| File | Key | English | Chosen Spanish | Back-translation |
|---|---|---|---|---|
| `cases` | `toast.failedToLoadCaseRanOutOfSpace_one` | Failed to load case, the browser has run out of space | No se ha podido cargar el caso en el navegador: no queda espacio de almacenamiento | The case could not be loaded in the browser: no storage space left |
| `cases` | `toast.failedToLoadCaseRanOutOfSpace_other` | Failed to load {{count}} cases, the browser has run out of space | No se han podido cargar {{count}} casos en el navegador: no queda espacio de almacenamiento | {{count}} cases could not be loaded in the browser: no storage space left |
| `template` | `label.affixText` | Affix Text | Añadir texto | Add text |
| `template` | `options.textStyle.engraved` | Engraved | Grabado | Engraved |
| `template` | `message.textStyleHelp` | Engrave will cut the text into the model.\n\nEmboss will extrude the text out of the model. | Con Grabado, el texto se talla hacia el interior del modelo.\n\nCon En relieve, el texto sobresale del modelo. | With Engraved, the text is carved into the model.\n\nWith Embossed, the text protrudes from the model. |
