# web

use file protocol to emulate the package installed from npm registry

I'm an innocent user

```json
{
  "name": "web",
  "version": "1.0.0",
  "description": "",
  "main": "dist/index.js",
  "types": "dist/index.d.ts",
  "scripts": {
    "build": "tsc"
  },
  "dependencies": {
    "react": "18.2.0",
    "component": "file:../../packages/component"
  },
  "devDependencies": {
    "@types/react": "18.2.38"
  },
  "keywords": [],
  "author": "",
  "license": "MIT"
}
```
