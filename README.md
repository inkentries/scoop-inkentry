# scoop-inkentry

The [Scoop](https://scoop.sh) bucket for [inkentry](https://github.com/inkentries/inkentry) — code intelligence for AI agents: persistent memory, code graph, search.

## Install

```powershell
scoop bucket add inkentry https://github.com/inkentries/scoop-inkentry
scoop install inkentry
```

That installs `inkentry.exe` and `inkentry-server.exe`. Keep them current with:

```powershell
scoop update inkentry
```

## About this repository

`bucket/inkentry.json` is generated, not hand-edited. The release workflow in
[inkentries/inkentry](https://github.com/inkentries/inkentry) regenerates it on
every stable tag and pushes the result here, the same way the Homebrew tap at
[inkentries/homebrew-inkentry](https://github.com/inkentries/homebrew-inkentry)
is maintained.

Manifest changes should therefore be made to the generator upstream
(`.github/scripts/update-scoop-manifest.js`), not to this repository — an edit
made here is overwritten by the next release.
