ecb
===

Repositorio com alguns snippets do sublime text 2 para codigo HTML e Javascript usados na ec.

sublime-snippets
POr favor ao adicionar um snippet adicione um exemplo de uso aqui. Gracias.

EXAMPLES: 

init gera:
/**
*
* init
*
*/
init: function(data) {
	this.inherited().init(); 
	this.data = data;
},

onAttach gera:
/**
*
* onAttach
*
*/
onAttach: function($1) { 
	this.inherited().onAttach();
	$2
},

tef gera:
this.elements.find('#element');

tw gera:
this.widgets['element'];

bfn gera:

/**
*
* functionName
*
*/
functionName: function() {
	// your code here dude... 
},