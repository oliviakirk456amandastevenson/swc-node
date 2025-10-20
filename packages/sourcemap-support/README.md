# `@swc-node/sourcemap-support`

```ts
import { SourcemapMap, installSourceMapSupport } from '@swc-node/sourcemap-support'

installSourceMapSupport()

function transform(sourcecode, filename, options) {
  const { code, map } = transformSync(sourcecode, filename, options)
  SourcemapMap.set(filename, map)
  return code
}
```

<!-- Auto-update: 2025-10-20T13:14:36.196754 -->
