# Modern Slavery UK Cities and Towns

Exports a list of UK Cities and Towns to be used in the modern slavery app.

Can be used with the [Typeahead Aria](https://github.com/UKHomeOffice/typeahed-aria), which is exported with [HOF Frontend Assets](https://github.com/UKHomeOfficeForms/hof-frontend-assets).

## Example Usage

The following is an example of Modern Slavery UK Cities and Towns in a HOF `field` with Typeahead Aria:
```
'country-select'-step: {
  mixin: 'select',
  className: ['typeahead', 'js-hidden'],
  options: [''].concat(require('ms-uk-cities-and-towns')),
  legend: {
    className: 'visuallyhidden'
  },
  validate: ['required']
},
```