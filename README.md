# snowpack: import not found

```
npm i https://github.com/weijarz/ts-module-demo.git
```

FILE: src/index.tsx
```
import defaultFn, { namedFn } from 'ts-module-demo'

defaultFn()
namedFn()
```

Will throw error 'Uncaught SyntaxError: import not found: namedFn' in browser console.

