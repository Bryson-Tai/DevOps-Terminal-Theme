# Release Notes

## v2.0.0 — 2026-07-25

### Added
- New theme `themes/autumn-ember.yaml`.
- New theme `themes/forest-tide.yaml`.
- New Oh My Posh segments in `pink-duck.yaml`: Azure cloud info, Kubernetes
  context & namespace, Docker context, and AI-Token usage (integrated with
  [AI-Engineering-Fluency](https://github.com/rajbos/ai-engineering-fluency)).
- Preview images for the new themes (`autumn-ember.png`, `forest-tide.png`)
  and an updated `pink-duck.png`.
- `README.md`: new Features bullets for Cloud Provider Info (Azure),
  Kubernetes Context & Namespace, Docker Context, and AI-Token Usage.
- `README.md`: Themes section entries for Autumn Ember and Forest Tide.

### Changed
- `themes/pink-duck.yaml` reworked:
  - Palette restructured — `first-left-prompt`/`second-left-prompt` renamed
    to `first-row-icon`/`wording`; refreshed color values throughout.
  - `kubernetes-text` set to a unique blue (`#0abdc6`), distinct from
    `wording` and `cloud-text-azure`.
  - Tooltip block trimmed down to Helm only (AWS/GCP/kubectl CLI tooltips
    removed from the active config, kept commented for reference).
- `README.md`: corrected the `.zshrc` `--config` path snippet; simplified
  DevOps Workspace Tooltips section to Helm Version only.

### Removed
- Theme `themes/yellow-calm-blue.yaml` and its README entry/preview image.
- Standalone preview images no longer referenced: `aws.png`, `azure.png`,
  `git.png`, `kubernetes.png`.

---

## v1.0.0 — 2026-07-25

### Added
- Initial stable release of the DevOps Terminal Theme project.
- `themes/` folder introduced, consolidating theme configs:
  - `themes/pink-duck.yaml`
  - `themes/yellow-calm-blue.yaml`
- `README.md` with installation instructions (Oh My Posh + Nerd Font setup)
  and initial feature list (SSH session, Git & remote info, execution time,
  date & time, directory path, Python env, DevOps workspace tooltips for
  AWS/Azure/GCP CLI and Kubernetes via kubectl/kubectx/helm).

### Changed
- Migrated and consolidated early prototype configs
  (`1_shell.omp.yaml`, `cloud-context.omp.yaml`, `custom-made.omp.yaml`)
  into the structured `themes/` folder.

### Removed
- Legacy top-level prototype files: `1_shell.omp.yaml`,
  `cloud-context.omp.yaml`, `custom-made.omp.yaml`.
