# sj26's Homebrew Forks

The `gist` and `hub` formulae have moved unchanged to
[sj26/tap](https://github.com/sj26/homebrew-tap).
This repository remains available with Homebrew migration metadata.

For existing installations, tap the destination before updating:

```sh
brew tap sj26/tap
brew update
```

Homebrew updates receipts for installations from `sj26/forks` without
rebuilding the kegs. Homebrew/core installations are not moved. If you
already updated before tapping the destination and migration was skipped,
explicitly reinstall the affected fork with `brew reinstall --HEAD
sj26/tap/gist` or `brew reinstall --HEAD sj26/tap/hub`.

For new installations:

```sh
brew install --HEAD sj26/tap/gist
brew install --HEAD sj26/tap/hub
```

Once your installations have migrated, remove this empty tap with
`brew untap sj26/forks`. See the
[new tap's migration notes](https://github.com/sj26/homebrew-tap#moving-from-the-old-taps).
