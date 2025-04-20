# Aetherium Widgets

Common react components for projects using Aetherium.

## Installation

```sh
# Install with npm
npm install @aetherium-nexus/widgets

# Or install with yarn
yarn add @aetherium-nexus/widgets
```

### Peer dependencies

This package requires `@aetherium-nexus/sdk`, `react`, and `react-dom`.

## Contents

### Components

- `ChainLogo`: A logo icon for a given chain ID
- `MessageTimeline`: A timeline showing stages of message delivery
- `WideChevron`: A customizable version of Aetherium's chevron logo

### Hooks

- `useMessage`: Fetch data about a message from the Aetherium Explorer
- `useMessageStage`: Fetch and compute message delivery stage and timings
- `useMessageTimeline`: Fetch message data for use with `MessageTimeline`

## Learn more

For more information, see the [Aetherium documentation](https://docs.aetherium-nexus.com/docs/intro).
