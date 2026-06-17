# Non-Commercial Optional Backends

This project's own code is licensed under **AGPL-3.0** (see `LICENSE`) and is free
for commercial use under that license. However, some **optional** model backends it
can integrate are released by their authors under **non-commercial** licenses. If you
use this software commercially, **do not enable these backends** (or substitute a
permissively-licensed alternative):

| Optional backend | Upstream license | Commercial use |
|---|---|---|
| CodeFormer (face restoration) | S-Lab License 1.0 | ❌ non-commercial |
| MusicGen / AudioGen / MAGNeT / JASCO (AudioCraft) | CC-BY-NC 4.0 (weights) | ❌ non-commercial |
| InsightFace / inswapper (face swap) | research/non-commercial | ❌ non-commercial |
| SadTalker (talking-head) | check upstream terms | ⚠️ verify |

These models and their weights are **not bundled or auto-downloaded** by this
repository; they are fetched on demand only if you explicitly enable the
corresponding feature. Permissively-licensed defaults (e.g. MuseTalk MIT + FAN
landmarks for lip-sync) should be preferred for commercial deployments.
