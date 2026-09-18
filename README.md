# Lossless Audit Releases

Lossless Audit is a read-only macOS application for auditing locally stored audio libraries for suspicious lossless provenance and indicators of lower-quality or transcoded source history.

Findings are indicators for review, not proof of source history or audible quality.

Current beta requirements: macOS 14 or newer, Apple silicon or Intel Mac.

Normal application use performs no telemetry, uploads, or network communication. Audio files are opened read-only.

Releases are currently distributed outside the Mac App Store using ad-hoc code signing rather than Apple Developer ID signing or notarization. macOS will therefore require the documented **Open Anyway** approval on first launch.

Download binaries only from this repository's Releases page and compare the published SHA-256 checksum if you want to verify file integrity.

Please report beta problems through this repository's Issues section.
