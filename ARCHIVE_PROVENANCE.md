# Archive provenance

This private repository preserves a locally retained snapshot of the former
GitHub repository `alexjust-data/atas_strategy`.

- Former remote: `https://github.com/alexjust-data/atas_strategy.git`
- Retained upstream commit: `c712ffb302c70d73a5afa8d747a5b17bf53cf92c`
- Retained branch: `main`
- Original author recorded by Git: Alex Just

The retained repository is a shallow snapshot of a merge commit. Its two
parent commits are not present locally, and the former upstream is no longer
available. Consequently, the private archive starts a new pushable Git history
from the retained working tree while recording the original commit above for
provenance.

Machine-local Claude settings and a captured ATAS session-log archive were
excluded from the new archive history. Source code, documentation, test
scenarios, and non-sensitive test screenshots were retained.

No licence file or explicit licence grant was present in the retained snapshot.
Creating this private archive does not add a licence or imply redistribution
rights.

## Validation status

On 2026-08-05, a Release build of `MyAtas.Strategies.csproj` restored all five
projects but failed with `CS1705`. The retained projects target .NET 8, whereas
the locally installed ATAS assemblies reference `System.Runtime` 10. The source
targets were deliberately left unchanged so that this archive remains faithful
to the retained snapshot; migration to the current ATAS/.NET version is a
separate development task.
