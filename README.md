# FoldSpace updates

Signed Android APKs for FoldSpace. Application source is maintained privately.

[Download the latest signed APK](https://github.com/Schildhorn12/Foldspace-Updates/releases/latest/download/FoldSpace-release.apk).

In FoldSpace, open the menu and tap **Update**, then **Open download**. Open the downloaded APK and approve Android's installation prompt. Allow installation from your browser if Android requests it.

The first move from an older debug build to a release build may require uninstalling the old FoldSpace app once. Switch to One UI Home and record your layout first: uninstalling removes FoldSpace settings. Subsequent releases use the same signing certificate and increasing Android version codes to allow updates in place.

Signing certificate SHA-256: `69DA84826F2785C766783BF58AD1C9761D98264CB6E8970FED8324CA99840DD1`.

The private build pipeline verifies the APK signature before publishing files under `latest/`. This repository verifies their checksum and publishes a versioned GitHub release. No signing keys or passwords belong in this repository.
