# Jetstream Releases

This repository hosts **only** the Sparkle auto-update feed (`appcast.xml`)
and signed, notarized release archives for Jetstream — an internal Esri
marketing-email conversion tool. No application source code is published
here; it lives in a separate private repository.

Each release is signed with both:
- an Apple Developer ID certificate (notarized by Apple), and
- an EdDSA signature (verified by Sparkle before installing any update)

so this repo can safely be public without exposing anything sensitive.
