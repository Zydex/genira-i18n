# Hungarian (hu) translation review - flagged strings

_Covers the 2026-11 batch run (MESH-1043)._

All strings passed the back-translation fidelity check, either on the first pass or after a retry with alternate phrasings. **No strings remain flagged for manual review.**

## Resolved after retry

These were flagged on the first pass. A retry variant then fully passed. They are listed here for reference only.

| File | Key | English | Chosen Hungarian | Back-translation |
|---|---|---|---|---|
| `cases` | `issues.modelBasing.pillarGenerationError.message` | Failed to generate attachments.\n<a>Learn More</a> about this error. | Nem sikerült létrehozni a rögzítőelemeket.\n<a>További információ</a> erről a hibáról. | Could not create the fixing elements.\n<a>Learn more</a> about this error. |
| `cases` | `issues.modelBasing.pillarGenerationError.status` | Failed to generate attachments | Nem sikerült létrehozni a rögzítőelemeket | Could not create the fixing elements |
| `cases` | `issues.modelBasing.retry.withoutAttachments` | Retry design without attachments? <a>Retry</a> | Újrapróbálja a tervezést rögzítőelemek nélkül? <a>Újrapróbálás</a> | Retry the design without fixing elements? <a>Retry</a> |
| `common` | `alt.logo` | Genira Model Basing | Genira Model Basing | Genira Model Basing |
| `common` | `message.noConnection` | Unable to connect, retrying in {{time}} | Nem sikerült csatlakozni, újrapróbálkozás {{time}} múlva | Unable to connect, retrying in {{time}} |
