# Cogizmo
Base convenience SuperClass for vanilla WebComponents.

## Usage

1. Make a Custom Element class that extends Component

**Cogizmo.js**
```
class MyComponent extends Cogizmo {
    // Component implementation details
}
```

**template.html**
```
<template>
    <!-- Template details -->
</template>
```

2. Start the resource linking and component registration
```
MyComponent.manage();
```

### Installation
Installation is very simple. Just place the required files in a web accessible directory.

1. Place Cogizmo.js in a web accessible directory.
2. Add `<script src="path/to/Cogizmo.js"></script>` to document `<head>`
    a. If using webcomponents polyfill, Cogizmo.js must come after the polyfill.

### For Compatibility
Some browsers do not have the complete WebComponents spec implemented. As a result, some browsers may require the webcomponents polyfills. Webcomponents polyfill is a smart polyfill that only includes features that are not yet implemented.

1. Add `<script src="path/to/webcomponents.js"></script>` to document `<head>`

## Features

