Chosen Icon
=========

Display FontAwesome Icon with chosen.

Usage
-------

Add attribute ``` data-icon ``` to ```<option>``` items with the name of font awesome css class name.

```
    <select data-placeholder="Choose a Project..." class="icon-select">
        <option data-icon="fa-download">Project A</option>
        <option data-icon="fa-cloud">Project B</option>
        <option data-icon="fa-fighter-jet">Project C</option>
    </select>
```

Use ```chosenIcon()``` in place of ```chosen()``` passing in the same properties:

```
    $(".icon-select").chosenIcon({
        disable_search_threshold: 10
    });
```

All properties of ```chosen()``` are available through ```chosenIcon()```

Dependencies
---------

* jQuery
* Chosen

Version
-------
0.0.1
  
    
