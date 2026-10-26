# Ora Updates

Public macOS Apple Silicon downloads and signed updates for Ora.

[Download the latest release](https://github.com/aurelienfvre/ora-updates/releases/latest)

The development repository remains private. Every binary release includes its matching Ora source snapshot and the engine source companion under the applicable licenses. See the release notes and `docs/ora-source-distribution.md` inside the source snapshot for build instructions and exact Chromium dependencies. Git history and private signing keys are not included.

Ora with its engine is distributed under GPLv3. Ardia’s own source retains Apache-2.0, and dependencies retain their respective licenses and notices. Ora is based on Ardia by Mantra Patel and Chromium/Helium; these attributions are retained in the source and packages.

## Updates

Install Ora 0.2.15 manually once. Later releases can be downloaded and installed through Ora’s Sparkle updater. The appcast and archives use Ora’s Ed25519 signing key. The public repository does not contain that private key.

These builds are signed ad hoc, not Apple-notarized. First launch can require the macOS Privacy & Security “Open Anyway” action. Never disable Gatekeeper globally.

## Source availability

Each release links both `Ora-VERSION-source.tar.gz` and its matching `ArdiaCore-TREE-source.tar.xz` alongside the DMG/ZIP. The source documentation identifies exact Chromium source and dependency versions. Please report a missing source asset through this repository’s Issues.
