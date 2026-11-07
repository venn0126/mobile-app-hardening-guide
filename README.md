# Mobile App Hardening Guide (Android & iOS)

Defensive hardening practices and checklists for protecting Android and iOS applications against reverse engineering, tampering, and common mobile threats.

This repository documents practical defensive techniques I use when hardening applications that I own or am authorized to secure.

## Overview

Focus areas:
- Android application hardening
- iOS application hardening
- Anti-tampering & integrity protection
- Anti-debugging and runtime protection (defensive)
- Secure communication and storage

All content is strictly for **defensive security purposes**.

## Android Hardening Checklist

- [ ] Code obfuscation (R8 / ProGuard / commercial tools)
- [ ] Root & emulator detection
- [ ] Basic anti-debugging and anti-instrumentation checks
- [ ] Certificate pinning
- [ ] APK signature & integrity verification
- [ ] EncryptedSharedPreferences / secure storage
- [ ] Native library protection (if used)
- [ ] Remove debug logs and disable debugging flags in release builds
- [ ] Network Security Config hardening

## iOS Hardening Checklist

- [ ] Symbol stripping and basic obfuscation
- [ ] Jailbreak detection
- [ ] Anti-debugging checks (ptrace, sysctl, etc.)
- [ ] Certificate pinning
- [ ] Keychain + Data Protection classes
- [ ] Runtime integrity verification
- [ ] Strict App Transport Security (ATS)
- [ ] Remove debugging entitlements in release builds

## Defensive Practices

I regularly perform defensive security reviews on mobile applications under my control, including:

- Static analysis for insecure configurations
- Validation of hardening effectiveness
- Review of common reverse-engineering entry points
- Hardening recommendations for personal and self-managed projects

## Disclaimer

This repository is intended **only for defensive security purposes** — protecting applications you own or are explicitly authorized to secure.  
Do not use any content for unauthorized testing or offensive activities.

## Author

Independent security researcher focused on mobile application hardening and defensive security testing.
