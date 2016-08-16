# three-orthographic-trackball-controls
> @egraether's [THREE.OrthographicTrackballControls](https://github.com/mrdoob/three.js/blob/f11c485ad4e4826b77a7f9c32e1be4d9a1156628/examples/js/controls/OrthographicTrackballControls.js) as an npm package

## Install
`npm install --save three three-orthographic-trackball-controls`

## Usage
```javascript
const THREE = require('three') // required peer dependency
require('three-orthographic-trackball-controls')

const controls = new THREE.OrthographicTrackballControls(camera, domElement)
```

### Versioning
This package uses an unusual versioning system to better support ThreeJS's (lack of) versioning. The major version of this repo will line up with ThreeJS breaking releases (69.0.0 => r69). Often the module will continue to work (i.e. 69.0.0 should work with r70).

The minor will be reserved for any new features, and patch for bug fixes and documentation/readme updates. In some rare cases, a minor feature may introduce a breaking change; so it's generally safest to use tilde or --save-exact for this module.

If you see any version issues, open a ticket!
