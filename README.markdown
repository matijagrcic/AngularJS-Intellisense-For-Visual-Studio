# AngularJS Intellisense for Visual Studio 2010 and 2012

## Why should you care?
Get intellisense support for [AngularJS](https://github.com/angular/angular.js) in Visual Studio
![Intellisense](https://raw.github.com/matijagrcic/AngularJS-Intellisense-For-Visual-Studio/blob/master/Content/vs-intellisense.png)

## Quick start
# Visual Studio 2012
* Copy "html_5_angularjs.xsd" from VS 2012 directory
* Go to C:\Program Files (x86)\Microsoft Visual Studio 11.0\Common7\Packages\schemas\html 
* Paste "html_5_angularjs.xsd" 
* Double click on "Schema AngularJS.reg" in VS 2012 directory
* Open Visual Studio
* Go to Tools > Options > Text Editor > HTML > Validation
* From the Target dropdown choose AngularJS
* Click OK

# Visual Studio 2010
* Copy "html_5_angularjs.xsd from" VS 2010 directory
* Go to C:\Program Files (x86)\Microsoft Visual Studio 10.0\Common7\Packages\schemas\html 
* Paste "html_5_angularjs.xsd" 
* Double click on "Schema AngularJS.reg" in VS 2010 directory
* Open Visual Studio
* Go to Tools > Options > Text Editor > HTML > Validation
![Tools options](https://raw.github.com/matijagrcic/AngularJS-Intellisense-For-Visual-Studio/blob/master/Content/vs-tools-options.png)
* From the Target dropdown choose AngularJS 
![HTML validation](https://raw.github.com/matijagrcic/AngularJS-Intellisense-For-Visual-Studio/blob/master/Content/vs-html-validation.png)
* Click OK

## What does *.reg do?
It adds a new Key in the Schema
![Registry editor](https://raw.github.com/matijagrcic/AngularJS-Intellisense-For-Visual-Studio/blob/master/Content/registry-editor.png)

## Contributing
Feel free to send a pull request so that the schema is up to date

## Credits
* Thanks to [@mkristensen](http://twitter.com/mkristensen) for his AngularJS Intellisense in Visual Studio 2012 post.
* Thanks to [@markrendle](http://twitter.com/markrendle) for adding missing tags for form parts (e.g. ng-pattern) and updating to AngularJS 1.1.4. 

## Coordinators
* Matija Grcic ([@matijagrcic](https://twitter.com/matijagrcic))

## Community

## License 
