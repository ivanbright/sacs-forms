# SACS Forms — Form Screens

Forms module of the SACS mobile app, built with **Expo Router** and **React Native**. Home screen is a multi-section registration form (personal info, financials, security, extras) with per-field keyboard settings, inline validation, animated submit CTA, and enterprise call-to-action section.

## Stack

- **Expo SDK** — managed workflow, file-based routing via Expo Router
- **React Native** — iOS, Android & web from a single codebase
- **TypeScript** — strict types throughout
- **EAS Build** — cloud builds and OTA updates via EAS Update

## Getting started

```bash
bun install
npx expo start
```

Open on device via **Expo Go**, or spin up a dev build for full native module support:

```bash
npx expo run:android
npx expo run:ios
```

## Project structure

```
src/
  app/          # Expo Router screens & layouts
  components/   # Shared UI components
  constants/    # Theme tokens, config
  hooks/        # Custom hooks
```

## Dev commands

```bash
npx expo lint       # ESLint
npx tsc --noEmit    # Type check
npx expo-doctor     # Diagnose dependency issues
npx expo install --fix  # Fix incompatible package versions
```

## Roadmap

- [ ] Student enrollment & profiles
- [ ] Attendance tracking
- [ ] Grade & report card management
- [ ] Teacher & staff portal
- [ ] Parent communication module
- [ ] Fee management & billing
- [ ] Push notifications

## Building for production

```bash
npx eas-cli build --platform all --profile production
npx eas-cli submit
```

---

> Active development — breaking changes expected between releases.
