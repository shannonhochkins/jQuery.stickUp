Stuckup
===============
This plugin makes sticky menus easy, very lightweight plugin, just does what it says, nothing else! Created by [shannon hochkins].
[shannon hochkins]: http://www.shannonhochkins.com/

Usage & Options
--------------

```javascript
$('.element').stickUp({
    topMargin: null,
    zIndex: 10,
    onStick: function(settings) {},
    unStick: function(settings) {}
});
```


Options
--------------


| Options               | Default                               | Description  |
| --------------------- |:-------------------------------------:| ------------:|
| topMargin             | null                                  | An offset param to tell the plugin where the top of the menu is. |
| zIndex                | 10                                    | The css z-index of the menu to be set when active, when inactive it will reset to it's original z-index |
| onStick               | null                                  | A callback when the menu has been activated or is sticky. |
| unStick               | null                                  | A callback when the menu has been inactivated or is not sticky. |
    


