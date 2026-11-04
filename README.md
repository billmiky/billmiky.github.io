# billmiky.github.io

Root GitHub Pages site for `billmiky.github.io`. It exists to serve
`/.well-known/assetlinks.json`, which lets Android apps that wrap sites on this
domain open full-screen (Trusted Web Activities).

- `io.github.billmiky.mise`: the Mise app (`billmiky/mise`, `android/`).

To add another app, append an entry with its package name and the SHA-256
fingerprint of its signing key. `.nojekyll` makes Pages publish the dot-folder.

Project sites (`/mise/`, `/blue-flames/`, …) are served from their own repos and
are not affected by this one. Don't add folders here that share a name with a
project repo.
