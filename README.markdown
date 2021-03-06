# jQuery Combinations Plugin #
[http://bigab.github.com/jQuery-Combinations-Plugin](http://bigab.github.com/jQuery-Combinations-Plugin)

Version: 1.0, Last updated: 29/10/2010

jQuery Combinations Plugin is a simple utility method used to create an array of every possible combination
derived from an array of arrays.


## Documentation ##
So simple:

Pass an array of arrays to the combinations method:

	$.combinations([[1,2], ["A", "B", "C"]]);
	
...and it returns an array of the combinations between the arrays:

	returns `[[1,"A"], [2,"A"], [1,"B"], [2,"B"], [1,"C"], [2,"C"]]`


### Browsers Tested ###
Internet Explorer 8-9, Firefox 7, Chrome 15

### Unit Tests ###
[QUnit](http://bigab.github.com/jQuery-Combinations-Plugin/tests/)


## License ##
Copyright (c) 2011 "BigAB" Adam Barrett 
licensed under the MIT license.
[http://bigab.mit-license.org/](http://bigab.mit-license.org/)
