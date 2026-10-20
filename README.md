# Voxira – Releases

Fertige Installationsdateien von Voxira: Windows-Client, Android-App und Server-Pakete für Debian/Ubuntu (amd64,
arm64), jeweils mit Signaturdatei (`.vxsig`) und `SHA256SUMS.txt`. Der Quellcode liegt hier nicht.

Voxira fragt diese Seite selbst nach Updates. Jede Datei wird vor der Installation mit dem Voxira-Release-Schlüssel
geprüft, eine veränderte Datei lehnt die App ab.

**Installieren:** im neuesten Release unter „Assets“ die Datei für dein Gerät laden
(`Voxira-Setup-<Version>.exe` für Windows, `Voxira-<Version>.apk` für Android). Server:
`sudo apt install ./voxira-server_<Version>_amd64.deb` (die eigene `server.toml` bleibt erhalten).

---

Ready-made Voxira installers (Windows client, Android app, server packages for Debian/Ubuntu) with signature files. The apps check this page for updates
and verify every file with the Voxira release key before installing.
