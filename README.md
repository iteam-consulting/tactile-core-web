# TACTILE*web*
[![Build Status](https://travis-ci.org/iteam-consulting/tactile-core-web.svg?branch=master)](https://travis-ci.org/iteam-consulting/tactile-core-web)
[![Coverage Status](https://coveralls.io/repos/github/iteam-consulting/tactile-core-web/badge.svg?branch=master)](https://coveralls.io/github/iteam-consulting/tactile-core-web?branch=master)
## Game Engine Core
Welcome to the TACTILE*web* game engine core library!

The purpose of this codebase is to export a kernel which provides enough
surface area to run a very wide array of game genres.

## Design
Consider the following state tree:
```json
{
  "engine": {"isRunning": true},
  "updaters": {
    "physicsUpdater": {
      "internal": {},
      "components": [{
        "id": "asd34y",
        "value": {}
      }, {
        "id": "0df9eg",
        "value": { ... }
      }]
    }
  },
  "renderers": {
    "spriteRenderer": {}
  }
}
```

## Contributing
Thank you for your desire to help improve the TACTILE*web* library. To get
started, clone, then

```git submodule init```

and finally

```npm install```

Please visit our [contributing doc](https://github.com/mlynam/tactile-core-web/blob/master/CONTRIBUTING.md) for
commit guidelines.

### VS Code Users
This repository comes with a .vscode settings submodule where several extensions
are recommended to improve the community development experience. The settings
include usage of a font which renders with ligatures. If you do not install
this font, the editor will render text in the default system font.  Please
check out [our guide](https://github.com/iteam-consulting/vsc-settings-web)
for more information.

## Authors
[@mlynam](https://github.com/mlynam)
