# Progress

Meteor component for showing an animated progress bar. [Demo](http://progress.zhenya.co).
```
meteor add zhenya:progress
```

## Usage

Use with `{{>progress progress=some_property}}`, where `some_property` is a property on the data context that returns a value between 0 and 1

## Delay

To make the progress bar react to data context changes with a delay, specify a delay property on the template call: `{{>progress progress=some_prop delay=1000}}`

## Colors, Classes

Change progress bar colors by supplying a color class string. Add your own classes here.
```
{{>progress progress=some_prop class="green"}}
```
Available colors:

- `orange`
- `darkblue`
- `blue`
- `cyan`
- `red`
- `green`
- `yellow`
- `pink`
- `magenta`
- `violet`
- `purple`
- `white`
- `light`
- `lightgray`
- `gray`
- `darkgray`
- `dark`
- `black`

