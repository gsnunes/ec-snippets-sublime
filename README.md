#JS Sublime Snippets

> Custom JS Sublime snippets.


Click on snippet to see your usage:

* [setTimeout](#settimeout)
* [init](#init)
* [onAttach](#onattach)
* [tef](#tef)
* [tw](#tw)
* [bfn](#bfn)


### setTimeout
```javascript
setTimeout(function () {
	//your code here
}, 1000);
```

### init
```javascript
/**
*
* init
*
*/
init: function(data) {
	this.inherited().init(); 
	this.data = data;
},
```

### onAttach
```javascript
/**
*
* onAttach
*
*/
onAttach: function($1) { 
	this.inherited().onAttach();
},
```

### tef
```javascript
this.elements.find('#element');
```

### tw
```javascript
this.widgets['element'];
```

### bfn
```javascript
/**
*
* functionName
*
*/
functionName: function() {
	// your code here dude... 
},
```