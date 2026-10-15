---
"@codex-relay/mobile": patch
---

Upgrade Hot Updater to 1.0.7. Its SDK JavaScript uses artifact protocol v2 only when native code has `installArtifact`, and installs over v1 like 1.0.0 otherwise, so this OTA needs no new native code and is widened to app versions 1.6.x after its deploy, like `1.6.2-ship.2`.
