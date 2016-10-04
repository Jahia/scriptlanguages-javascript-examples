# scriptlanguages-javascript-examples

A Jahia Digital Experience Manager (DX) module that provides a simple example on using javascript a a scripting 
language for Jahia DX views. All standard Jahia variables are exposed as javascript variables, you can display node 
contents, etc. 

This module should mostly be considered as a proof-of-concept. It is not recommended to use this code in a production
 environment. For more information about Jahia DX, please go to: https://www.jahia.com/platform/digital-experience-manager

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