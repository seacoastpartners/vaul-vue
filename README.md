# Drawer

> Unstyled drawer component for Vue

This drawer component can be used as a Dialog replacement on tablet and mobile devices.
It uses [Reka UI's Dialog primitive](https://www.reka-ui.com/docs/components/dialog) under the hood and is a feature complete port of [Emil Kowalski's Vaul library](https://github.com/emilkowalski/vaul) (built for React).

## Installation

```bash
pnpm add @seacoastpartners/drawer
```

```bash
npm install @seacoastpartners/drawer
```

```bash
yarn add @seacoastpartners/drawer
```

## Usage

```vue
<script setup lang="ts">
import { DrawerContent, DrawerOverlay, DrawerPortal, DrawerRoot, DrawerTrigger } from '@seacoastpartners/drawer'
</script>

<template>
  <DrawerRoot>
    <DrawerTrigger> Open </DrawerTrigger>
    <DrawerPortal>
      <DrawerOverlay />
      <DrawerContent>
        <p>Content</p>
      </DrawerContent>
    </DrawerPortal>
  </DrawerRoot>
</template>
```

## Credits

All credits go to these open-source works and resources

- Major credits go to [Emil Kowalski](https://emilkowal.ski/) for the original [Vaul library](https://github.com/emilkowalski/vaul).
- [Reka UI](https://www.reka-ui.com/) for the Dialog primitive used under the hood.
- [Vaul Vue](https://vaul.unovue.com) for the original port to Vue.
