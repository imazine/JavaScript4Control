# 제어의 관점에서 바라본 자바스크립트
### JavaScript for Control

* Speaker: 박일호
* aka.: iMaZiNe
* Front-end Engineer @ Company100
* Organizer @ undefine:D

- - -

## 하고싶은 이야기
현업에서의 JavaScript 이야기.

- - -

## Ability of JavaScript
### JavaScript는 과연 무엇을 할 수 있을까요?

- -

### @ BROWSER
+ DOM control
+ DOM style control
+ Browser API control
	+ canvas
	+ audio
	+ video
	+ web storage
	+ application cache
	+ xhr...

- -

### @ SERVER
+ node.js
+ vert.x
+ rhino
+ 대다수의 script language 처럼

- -

### @ API
+ Google Apps Script
+ [OS X Automation](https://developer.apple.com/library/mac/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/)
+ [Windows runtime app](http://msdn.microsoft.com/en-us/library/windows/apps/br211385.aspx)
+ etc...

- -

## Today Focus
### BROWSER !

- - -

### Frequently Usecase on BROWSER?

- -

+ DOM Control
+ DOM Style control
+ Browser API control

- -

## How we can control DOM?

- -

~~~js
// DOM Create
var DOM = document.createElement(TagName);

// DOM inject
document.body.appendChild(DOM);

// DOM style change
DOM.style.property = 'style';
~~~