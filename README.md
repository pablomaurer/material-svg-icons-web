# material-svg-icons

Material Symbols SVGs (24px) extracted from https://github.com/google/material-design-icons.

## What you get

- 24px SVGs only
- Styles: rounded, outlined, sharp
- No fill1 icons

## Usage

### Icons

SVGs are stored under:

- `icons/rounded`
- `icons/outlined`
- `icons/sharp`

### TypeScript icon names

```ts
import type { IconName } from "material-svg-icons";
```

## Generate icons locally

You need a local clone of the upstream repo:

```bash
git clone https://github.com/google/material-design-icons.git /tmp/material-design-icons
node scripts/generate-icons.js --repo /tmp/material-design-icons
```

## License

Icons are from Google Material Design Icons (see upstream licensing). This package is Apache-2.0.
