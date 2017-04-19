[![Build Status](https://travis-ci.org/advanced-rest-client/anypoint-radio-button.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/anypoint-radio-button)  

# anypoint-radio-button

`<anypoint-radio-button>` is Anypoint styled radio button that can be either
checked or unchecked.
User can tap the radio button to check or uncheck it.

Use a `<anypoint-radio-group>` to group a set of radio buttons.  When radio buttons
are inside a radio group, exactly one radio button in the group can be checked
at any time.

### Example
```
<anypoint-radio-button></anypoint-radio-button>
<anypoint-radio-button>Label</anypoint-radio-button>
<anypoint-radio-button checked></anypoint-radio-button>
```

### Styling
`<anypoint-radio-button>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--anypoint-radio-button` | Mixin applied to the element | `{}`
`--anypoint-radio-button-size` | Size of the button (the circle) | `20px`
`--anypoint-radio-button-radio-container` |  A mixin applied to the internal radio container | `{}`
`--anypoint-radio-button-unchecked-color` | Radio button border color when the input is not checked | `--anypoint-color-aluminum5`
`--anypoint-radio-button-unchecked-background-color` | Fill color of unchecked button | `#fff`
`--anypoint-radio-button-checked-color` | Radio button border color when the input is checked | `--anypoint-color-primary`
`--anypoint-radio-button-checked-background-color` | Fill color of checked button | `#fff`
`--anypoint-radio-button-label-spacing` | MArgin between the button and label | `5px`



### Events
| Name | Description | Params |
| --- | --- | --- |
| change | Fired when the checked state changes due to user interaction. | __none__ |
| iron-change | Fired when the checked state changes. | __none__ |
