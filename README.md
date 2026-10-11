# Sindri

A native macOS app for Apple platform developers. It reads what is already on your Mac (keychain certificates,
provisioning profiles, Xcode installations) and what App Store Connect reports about your team's apps, and tells you
what is wrong and what to do about it.

This repository only hosts the signed and notarized builds.

## Download

**[Download the latest version](https://github.com/sassiwalid/sindri-releases/releases/latest)**: open the DMG and
drag Sindri to Applications.

Requires macOS 15 or later.

## Free and Pro

**Free:** Signing (diagnose a project's signing) and Certificates (every signing certificate with its expiry, renewal
in one click).

**Sindri Pro**, a one-time purchase, unlocks:
- **Xcodes**: install, switch and uninstall Xcode versions, simulator runtimes and disk usage.
- **Swift Preview**: a SwiftUI view rendered next to its code, or a Swift program next to its output.
- **SwiftUI Analyzer**: the view hierarchy as a graph, a performance score and the issues with their fix as a diff.
  The analysis runs on your Mac; a deeper one by an AI agent is optional, with your own API key.
- **Releases**: where each build stands, from processing to the App Store.
- **Reminders**: notifications before certificates and profiles expire.

**[Buy Sindri Pro](https://walidsassi.lemonsqueezy.com/checkout/buy/1f725d03-3779-46a1-88d8-c0c7f8c62b81)**, then open
Sindri › Activate and paste the license key from your receipt email.

Every Pro tool can be tried free for 14 days from the app, with no account or card.

## Privacy

There is no Sindri account and no backend. Secrets (App Store Connect key, license key, AI provider keys) stay in your Keychain.
Requests go to Apple, and license checks to Lemon Squeezy. SwiftUI Analyzer's deep analysis, only when you ask for it,
sends the files you chose to the AI provider you picked.
