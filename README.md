# Polymer 1 Snippets

This extension for Visual Studio Code adds snippets for Polymer 1. The snippets are provided for HTML and Javascript as elements can be defined in a single HTML file or separate files.

The snippets are focused on conforming to [Polymer Documentation Guidelines](https://www.polymer-project.org/1.0/docs/tools/documentation), various Polymer best practices and a naming convention to help readability.

[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/WayneGoosen.polymer-1-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=WayneGoosen.polymer-1-snippets) [![Current Release](https://vsmarketplacebadge.apphb.com/version/WayneGoosen.polymer-1-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=WayneGoosen.polymer-1-snippets)

## Naming Convention

Private properties and functions should be prefixed with an underscore (_).

Any function that handles an event should be prefixed with '_handle'.

Any function assigned as a listener in the listeners object should be prefixed with '_listen'.

Any function assigned as an observer on a property or declared in the observers array should be prefixed with '_observe'.

Any compute function should be prefixed with '_compute'.

The naming convention aims to make the code base more readable and allow coders to be more aware of what their changes could affect.

## Best Practices

Boolean property snippet with value defaulted to false. If defaulted to true, you cannot set it to false from markup.

Array or Object property snippet with a function for the defaulted value. It is to ensure each element gets its own copy of the value.

## Usage

Type the prefix of the snippet (i.e. `p-basic`), press `enter` and the snippet unfolds. Tab through one or more place holders, enter a value or use the default provided.

## Features

Below describes all available snippets (p:property, f:function, d:documentation, el:element, b:behavior).

### Property Snippets

```javascript
p-basic         // Basic property with single line documentation.
p-boolean       // Boolean property, defaulted to false.
p-basic-type    // Basic property with type documentation.
p-object-array  // Object or Array property with single line documentation.
p-compute       // Property with a computed assigned.
p-observe       // Property with an observer assigned.
p-all           // Property with all available assignments.
```

### Property Documentation Snippets

```javascript
d-p-single-line     // Single line property documentation.
d-p-type            // Property documentation with annotated type.
d-p-complex-type    // Property documentation with annotated complex type.
d-p-all             // Full property documentation.
```

### Function Snippets

```javascript
f-1-param           // 1 parameter function with documentation.
f-2-param           // 2 parameter function with documentation.
f-3-param           // 3 parameter function with documentation.
f-void              // Void Function with documentation.
f-observe-property  // Function for observer of a property with documentation.
f-handle-event      // Function to handle an event with documentation.
```

### Function Documentation Snippets

```javascript
d-f-1-param         // Documentation for function with 1 parameter.
d-f-2-param         // Documentation for function with 2 parameter.
d-f-3-param         // Documentation for function with 3 parameter.
d-f-void            // Documentation for void function.
d-f-observer        // Documentation for property observer function.
d-f-handle-event    // Documentation for function that handles an event.
```

### Event Documentation Snippets

```javascript
d-event             // Documentation for an event.
d-event-complex     // Documentation for an event with an annotated complex type.
```
### Behavior Snippets

```javascript
b-basic      // Basic behavior with documentation.
b-extend     // Extend an existing behavior with documentation.
```

### Behavior Documentation Snippets

```javascript
d-b-basic      // Documentation for a behavior.
d-b-extend     // Documentation for a behavior that extends another behavior.
```

### Element Snippets

```javascript
el-basic   // Basic element with documentation.
el-all     // Element with all available assignments and documentation.
```

### Element Documentation Snippets

```javascript
d-el-basic   // Documentation for a basic element.
```

### Custom CSS Properties/Mixins Documentation Snippets

```javascript
d-custom-css   // Documentation table for any custom CSS properties and mixins.
```

## Requirements

Install Visual Studio Code 1.21.0 or higher.

## Installation

1. Install [Visual Studio Code](https://code.visualstudio.com/) 1.21.0 or higher
2. Launch Visual Studio Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension - `Polymer 1 Snippets`
6. Reload Visual Studio Code

## Change Log

All notable changes will be documented in [CHANGELOG.md](https://github.com/WayneGoosen/vscode-polymer1/blob/master/CHANGELOG.md)

## Contributing

Please fork the branch, create a new feature branch, add your changes and push. Submit a pull request :)

## License

[MIT License](https://github.com/WayneGoosen/vscode-polymer1/blob/master/LICENSE)


