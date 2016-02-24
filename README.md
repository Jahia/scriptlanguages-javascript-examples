# scriptlanguages-javascript-examples

A simple example on how to use javascript as a scripting language for Jahia views.
All standard Jahia variables are exposed as javascript variables, you can display node contents,
etc.

## Requirements
- Jahia 7.2.0.0 or more recent
- Maven 3.0+ for module compilation
- JDK 7+

## Usage

1. Compile the whole project using : mvn clean install
2. Deploy the `target/scriptlanguages-javascript-example*.jar` module
3. In Edit mode, add a Basic Content -> Javascript node rendering content node, and enter a value for the javascriptText property.
The value of this property will be displayed by the node template written in javascript.

## Example template

You will find an example template in the following directory : `src/main/resources/jnt_javascriptNode/html/javascriptNode.js`