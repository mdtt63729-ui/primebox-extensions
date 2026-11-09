# PrimeBox Extensions

CloudStream `.cs3` extension binaries, collected from four upstream repositories and
re-published here folder by folder. Every file is an unmodified build; nothing was
renamed, rebuilt or edited.

**Total extensions: 93**

## Repository manifest

Add this repository in a CloudStream-compatible app (Settings → Extensions → Add repository):

```
https://raw.githubusercontent.com/mdtt63729-ui/primebox-extensions/main/repo.json
```

`repo.json` points to `plugins.json`, which lists every extension below with its
version, language, file size and SHA-256 hash, with each `url` rewritten to this
repository.

## Folders

| Folder | Source repository | Extensions |
| --- | --- | --- |
| [`Phisher/`](Phisher) | https://github.com/phisher98/cloudstream-extensions-phisher | 28 |
| [`CNCVerse/`](CNCVerse) | https://github.com/NivinCNC/CNCVerse-Cloud-Stream-Extension | 42 |
| [`CSX/`](CSX) | https://github.com/SaurabhKaperwan/CSX | 5 |
| [`Redowan/`](Redowan) | https://github.com/redowan99/Redowan-CloudStream | 18 |

## Notes

- The original upstream `plugins.json` of each source repository is available from the links above; this repo republishes the compiled binaries only.
- Compatibility across CloudStream forks is not tested. These are builds for CloudStream API version 1.
- Licensing and attribution terms are those of each upstream repository. Some providers target sites that host unlicensed copies of films and shows; check the upstream licence and how you redistribute before sharing.
