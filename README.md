A small collection of utility functions.

<span id="BADGE_GENERATION_MARKER_0"></span>
[![npmV](https://img.shields.io/npm/v/suf-utils)](https://www.npmjs.com/package/suf-utils) [![install](https://badgen.net/packagephobia/install/suf-utils)](https://packagephobia.now.sh/result?p=suf-utils) [![githubLastCommit](https://img.shields.io/github/last-commit/TheRealSyler/suf-utils)](https://github.com/TheRealSyler/suf-utils)
<span id="BADGE_GENERATION_MARKER_1"></span>

<span id="DOC_GENERATION_MARKER_0"></span>

# Docs

- **[index](#index)**

  - [Position](#position)
  - [degToRad](#degtorad)
  - [clamp](#clamp)
  - [toPx](#topx)
  - [loadTexture](#loadtexture)
  - [getTextureOffset](#gettextureoffset)
  - [map](#map)
  - [distance](#distance)
  - [distanceToEllipse](#distancetoellipse)
  - [distanceSingleAxis](#distancesingleaxis)
  - [angleTo](#angleto)
  - [radToDeg](#radtodeg)
  - [interpolate](#interpolate)
  - [interpolateLinear](#interpolatelinear)
  - [interpolateCubic](#interpolatecubic)
  - [interpolateSmootherStep](#interpolatesmootherstep)
  - [floor](#floor)
  - [getIndexPos](#getindexpos)
  - [getIndex](#getindex)

### index

##### Position

```ts
interface Position {
    x: number;
    y: number;
}
```

##### degToRad

```ts
function degToRad(degrees: number): number;
```

##### clamp

```ts
function clamp(value: number, max: number, min: number): number;
```

##### toPx

```ts
function toPx(n: number): string;
```

##### loadTexture

```ts
function loadTexture(src: string): Promise<HTMLImageElement>;
```

##### getTextureOffset

```ts
function getTextureOffset(index: number, sizePerCell: number, cellsPerRow: number): number[];
```

##### map

```ts
function map(val: number, inMin: number, inMax: number, outMin: number, outMax: number): number;
```

##### distance

```ts
function distance(x1: number, y1: number, x2: number, y2: number): number;
```

##### distanceToEllipse

```ts
function distanceToEllipse(x1: number, y1: number, x2: number, y2: number, xSize: number, ySize: number): number;
```

##### distanceSingleAxis

```ts
function distanceSingleAxis(x1: number, x2: number): number;
```

##### angleTo

```ts
function angleTo(x1: number, y1: number, x2: number, y2: number): number;
```

##### radToDeg

```ts
function radToDeg(n: number): number;
```

##### interpolate

```ts
function interpolate(a0: number, a1: number, w: number): number;
```

##### interpolateLinear

```ts
function interpolateLinear(a: number, b: number, n: number): number;
```

##### interpolateCubic

```ts
function interpolateCubic(a0: number, a1: number, w: number): number;
```

##### interpolateSmootherStep

```ts
function interpolateSmootherStep(a0: number, a1: number, w: number): number;
```

##### floor

```ts
function floor(number: number): number;
```

##### getIndexPos

```ts
function getIndexPos(pos: Position, cellsPerRow: number): number;
```

##### getIndex

```ts
function getIndex(x: number, y: number, cellsPerRow: number): number;
```

_Generated with_ **[suf-cli](https://www.npmjs.com/package/suf-cli)**
<span id="DOC_GENERATION_MARKER_1"></span>

<span id="LICENSE_GENERATION_MARKER_0"></span>
Copyright (c) 2021 Leonard Grosoli Licensed under the MIT license.
<span id="LICENSE_GENERATION_MARKER_1"></span>