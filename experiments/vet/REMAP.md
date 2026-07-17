# Remap Manifest — mycelium-proj → proj

_DN-109 §5.2 provenance ledger. Guarantee: **Declared** — this records proposed/performed structural and idiom choices; it does not certify them (no guarantee-tag upgrade from the manifest's existence alone, VR-5). Rendered from `remap` in `summary.json` — this file is a pure projection, never a second source of truth._

## Nodules (5)

| Target nodule | Operation | Safety | API surface changed | Identity neutral | Sources | Rationale |
|---|---|---|---|---|---|---|
| `proj.cert_scope` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-proj/src/cert_scope.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `proj.header` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-proj/src/header.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `proj` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-proj/src/lib.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `proj.manifest` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-proj/src/manifest.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `proj.resolve` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-proj/src/resolve.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |

## Idiom choices (0)

_(none in this run — v0 Mechanical-only auto-fire with no located idiom-choice instrumentation yet; see DN-109 §7-e and this module's doc comment)_
