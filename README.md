# Initial Setup

```bash

# Install dependencies
pnpm i
```

```bash
# Run on dev
pnpm dev
```
# How to test on Physical Device?

## Android Device Setup
- Make sure Settings > Developer options on your phone is activated.
- From Settings > Developer options. Enable USB Debugging
- Connect your device to your computer via USB cable

```bash
npx cap add android
```

```bash
pnpm build-sync-run-android
```


