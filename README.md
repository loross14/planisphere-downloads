# Planisphere downloads

Installers for Planisphere apps, published as GitHub releases. The Windows app lives here today.

- **Planisphere for Windows** (`windows-v*` releases): early test builds for Windows 10 (1809) or later, x64. They
  are not code-signed yet, so Windows SmartScreen may warn the first time: choose More info, then Run anyway. Each
  release lists the SHA-256 of its installer.
- Get it from [www.planisphere.ooo/windows](https://www.planisphere.ooo/windows). Installed copies update themselves.

Every published release is installed on a clean Windows runner and checked by
[the Windows self-test](.github/workflows/windows-self-test.yml) (`Planisphere.exe --self-test`); the results are on
the release's workflow run.

This repository holds release files only. The source is private.
