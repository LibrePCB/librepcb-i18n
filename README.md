# LibrePCB Translation Files

This repository is included in [LibrePCB](https://github.com/LibrePCB/LibrePCB)
as a Git submodule and contains the translation files for the LibrePCB
application in various languages.

The content of this repository is automatically updated periodically with the
latest translations from [Transifex](https://www.transifex.com/librepcb/librepcb-application/).

<h3>This repository is a read-only copy of the translations stored at
Transifex! Changes made in this repository will be lost, so we have to reject
pull requests. If you want to add translations, please use Transifex.</h3>

The branches `master` and `release/*` contain the translations for the
corresponding branches of the LibrePCB source repository.

On the `master` branch of the LibrePCB source repository, the submodule points
to a commit which does not contain any translations (because they change very
often, we would have to constantly update the submodule otherwise). If you still
want to compile LibrePCB with translations, you can download the translations
with following commands in this submodule:

```bash
git checkout master
git pull origin master
```
