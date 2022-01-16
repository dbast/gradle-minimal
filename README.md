# gradle-minimal

Minimal example to reproduce the handling of verification metadata by the renovate bot:
* Minimal `renovate.json` created via renovate activation PR.
* Inital skeleton created by `gradle init`
* Verification metadata added by `./gradlew --write-verification-metadata sha256,sha1`
* Minimal Github CI action added to run `./gradlew build` on pushes.
