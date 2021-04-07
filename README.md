<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i>test</i>
    <br>
    <br>
    <img src="https://github.com/garronej/cautious_winner/workflows/ci/badge.svg?branch=main">
    <img src="https://img.shields.io/bundlephobia/minzip/cautious_winner">
    <img src="https://img.shields.io/npm/dw/cautious_winner">
    <img src="https://img.shields.io/npm/l/cautious_winner">
</p>

-   [Home](https://github.com/garronej/cautious_winner)
-   [Documentation](https://github.com/garronej/cautious_winner)

# Install / Import

`cautious_winner` is both a [Deno](https://deno.land/x/cautious_winner) and an [NPM](https://www.npmjs.com/cautious_winner) module.

## Node:

```bash
$ npm install --save cautious_winner
```

```typescript
import { myFunction, myObject } from "cautious_winner";
```

Specific import

```typescript
import { myFunction } from "cautious_winner/myFunction";
import { myObject } from "cautious_winner/myObject";
```

## Deno:

For the latest version:

```typescript
import { myFunction, myObject } from "https://deno.land/x/cautious_winner/mod.ts";
```

To import a specific [release](https://github.com/garronej/cautious_winner/releases):

```typescript
import { myFunction, myObject } from "https://deno.land/x/cautious_winner@0.1.0/mod.ts";
```

Specific imports:

```typescript
import { myFunction } from "https://deno.land/x/cautious_winner/myFunction.ts";
import { myObject } from "https://deno.land/x/cautious_winner/myObject.ts";
```

## Import from HTML, with CDN

Import it via a bundle that creates a global ( wider browser support ):

```html
<script src="//unpkg.com/cautious_winner/bundle.min.js"></script>
<script>
    const { myFunction, myObject } = cautious_winner;
</script>
```

Or import it as an ES module:

```html
<script type="module">
    import { myFunction, myObject } from "//unpkg.com/cautious_winner/zz_esm/index.js";
</script>
```

_You can specify the version you wish to import, see [unpkg.com](https://unpkg.com)_

## Contribute

```bash
npm install
npm run build
npm test
```
