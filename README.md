# Logos Forum — module catalog

A [Logos Basecamp](https://github.com/logos-co/logos-basecamp) package
repository serving **Logos Forum**: a forum with no server, where topics and
replies travel over Logos Delivery, history is kept on the device and on Logos
Storage, and every post is signed and verified on arrival. Post as an account,
under an alias, or anonymously.

## Install in Basecamp (0.3.0)

macOS (Apple silicon) and Linux (x86_64).

1. **Settings → Package Repositories → Add a repository**, paste

   ```
   https://raw.githubusercontent.com/edenbd1/logos-forum-catalog/main/logos-repo.json
   ```

2. **Package Manager** → find **Logos Forum** → **Install**. Its dependencies,
   `delivery_module` and `storage_module`, come from the official Logos catalog
   and are installed with it.
3. Open **Logos Forum** from the sidebar.

## What is here

| File | |
|---|---|
| `logos-repo.json` | the repository descriptor Basecamp reads |
| `index.json` | packages, versions, SHA-256 and download URLs |
| releases `logos_forum-v*` | the `.lgx` packages themselves |

The format is that of the official
[`logos-modules-release`](https://github.com/logos-co/logos-modules-release).

## Licence

MIT OR Apache-2.0.
