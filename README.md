# Mission Control marketplace

A list of [Mission Control](https://github.com/LynchzDEV/mission-control) plugins.

Add it in Mission Control: sidebar, Marketplace, Add a marketplace, paste `https://github.com/LynchzDEV/mc-marketplace`.

## Listing a plugin

Add an entry to `marketplace.json`:

| Field | Meaning |
|---|---|
| `id` | The plugin's `id` from its `mc-plugin.json` |
| `repo` | Git URL of the plugin repo |
| `ref` | Tag or commit to install |
| `name`, `description` | Shown while browsing |
| `runtime` | `isolated` or `trusted`, shown while browsing |

What gets installed and what it may do always comes from the plugin's own `mc-plugin.json` at `ref`, never from this file.

Writing a plugin: start from [mc-plugin-template](https://github.com/LynchzDEV/mc-plugin-template) and read [mc-plugin-sdk](https://github.com/LynchzDEV/mc-plugin-sdk).
