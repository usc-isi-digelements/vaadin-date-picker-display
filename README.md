# vaadin-date-picker-display
A Polymer Element that displays a date picker used for filtering (uses vaadin-date-picker).


### Example
```js
var facets = {
  dates: {
    dateStart: {},
    dateEnd: {}
  }
};
```

```html
<vaadin-date-picker-display
  facet-key="dates"
  facets="{{facets}}"
  key="dateStart"
  title="Date From"
  prefix-label="From"
  date-identifier="start">
</vaadin-date-picker-display>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct
