# Cosmo

<img src="https://iamjason.github.io/cosmo-site/assets/icon.png" width="128" height="128" alt="Cosmo's space-tardigrade app icon">

**Reclaim the space your dev tools left behind.**

Cosmo is a free native Mac app for finding developer caches, build artifacts,
and simulator data. Review what is taking up space, understand what removal
means, and choose what to clean.

[Download the latest release](https://github.com/iamjason/cosmo-site/releases/latest)
· [Website](https://iamjason.github.io/cosmo-site/)
· [Report an issue](https://github.com/iamjason/cosmo-site/issues)

Requires **macOS 26 or later**. Download the ZIP, move **Cosmo.app** to
Applications, and open it. Releases are signed with Developer ID and notarized
by Apple.

## Find the space you can reclaim

- **156 cleanup targets across 19 categories:** Xcode, simulators, AI tools,
  local models, package managers, containers, project builds, and more.
- **Saved scan results:** reopen your last scan, see filesystem changes, and
  refresh individual targets, categories, or the whole scan.
- **Project and simulator filters:** search by project, size, activity evidence,
  and removal consequence. Protect items or whole projects and review growth.
- **Cleanup review and history:** check each removal method, follow per-item
  progress, and retry failed items.

## Review before removing

Every target has a plain-English explanation and a safety label: **Safe**,
**Quit first**, **Rebuilds**, or **Destructive**. Files move to Trash by default
and can be restored until you empty it. Permanent file deletion is opt-in.
Simulator devices and runtimes are removed permanently through Apple's
simulator tools; Cosmo identifies those items separately before confirmation.
Destructive targets are never included in safe-only cleanup.

Cosmo revalidates selected items, skips targets while their declared tools are
running, and refuses file paths outside your home directory.

## Part of the Compendium

Find Cosmo alongside Korok, Deku, and Kaepora in the
[Hyrule Compendium](https://iamjason.github.io/hyrule-compendium-site/tools/cosmo/).
The Compendium discovers this public repository through its `hyrule-tool` topic
and reads [hyrule.json](hyrule.json) for the listing, icon, and website.

This repository hosts public information, artwork, and release downloads.
Application source is maintained separately.
