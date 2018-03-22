# Polymer 1 Snippets

This extension for Visual Studio Code adds snippets for Polymer 1. The snippets are provided for HTML and Javascript as elements can be defined in a single HTML file or separate files.

The snippets are focused on conforming to [Polymer Documentation Guidelines](https://www.polymer-project.org/1.0/docs/tools/documentation), various Polymer best practices and a naming convention to help readability.

## Naming Convention

Private properties and methods should be prefixed with an underscore (_);

Any method that handles an event should be prefixed with '_handle'.

Any method assigned as a listener in the listeners object should be prefixed with '_listen'.

Any method assigned as an observer on a property or declared in the observers array should be prefixed with '_observe'.

Any compute method should be prefixed with '_compute'.

The naming convention aims to make the code base more readable and allow coders to be more aware of what their changes could affect.

## Best Practices

Boolean property snippet with value defaulted to false. If defaulted to true, you cannot set it to false from markup.

Array or Object property snippet with a function for the defaulted value. It is to ensure each element gets its own copy of the value.

## Features

Below describes all available snippets.

Prefixes


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

### Method Snippets

```javascript
m-1-param           // Method with 1 paramter with documentation.
m-2-param           // Method with 2 paramter with documentation.
m-3-param           // Method with 2 paramter with documentation.
m-void              // Void method with documentation.
m-observe-property  // Method for observer of a property with documentation.
m-handle-event      // Method to handle an event with documentation.
```

### Method Documentation Snippets

```javascript
d-m-1-param         // Documentation for method with 1 parameter.
d-m-2-param         // Documentation for method with 2 parameter.
d-m-3-param         // Documentation for method with 3 parameter.
d-m-void            // Documentation for void method.
d-m-observer        // Documentation for property observer method.
d-m-handle-event    // Documentation for method that handles an event.
```

### Event Documentation Snippets

```javascript
d-event             // Documentation for an event.
d-event-complex     // Documentation for an event with an annotated complex type.
```

## Requirements

Install Visual Studio Code 1.21.0 or higher.

## Release Notes

### 1.0.0

Initial release of Polymer 1 Snippets.

## Contributing

Please fork the branch, create a new feature branch, add your changes and push. Submit a pull request :)

## License

[MIT License](https://github.com/WayneGoosen/vscode-polymer1/blob/master/LICENSE)


