# adapt-iframe

An adapt component that loads content into an iframe

## Usage

See settings

## Settings overview

For example JSON format, see the example.json file


#### _component

This value must be: `iframe`

#### _classes

You can use this setting to add custom classes to your template and LESS file.

#### _layout

This defines the position of the component in the block. Values can be `full`, `left` or `right`.

#### displayTitle and body

The `displayTitle` and `body` settings can be left blank.

#### _src
The url of the iframe contents

#### _dimensionDelegateSelector

If the dimensions of the iframe should be delegated to a child element of the iframe use this attribute to select which child element this is.

#### _initialWidth

Specify the native width of the iframe - this is used (along with height) to make the iframe responsive

#### _initialHeight

Specify the native height of the iframe - this is used (along with width) to make the iframe responsive

#### _scripts

Contains attributes for loading external _scripts

#### _isEnabled

Turns external scripts off. Acceptable values are true and false

#### _externalScripts

Add any external scripts here. Will be embedded in a script tab within the template below the iframe.  

## Limitations

To be completed.

## Browser spec

This component has been tested to the standard Adapt browser specification.

=======
