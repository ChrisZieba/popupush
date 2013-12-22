popupush
========

Hits a database for a list of options and displays them in a drop down select.

Usage
-----

```html
$(document).ready(function(){
	// Target your select
	$("#your-drop-down").popupush({
		uri: '/get-results',
		ulName: 'id-of-the-results-container'
	});
});
```

Example
-------

[theSoundtrackDB](http://www.thesoundtrackdb.com) Type into the search bar at the top of the page and watch as the list repopulates. 

License
-------

MIT

Author
------

[@ChrisZieba](https://www.twitter.com/ChrisZieba)