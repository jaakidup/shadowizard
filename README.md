# Shadowizard

Get the perfect shadows every time for the non designer.

# Installation

`npm i shadowizard --save`

Then...

```
import { shadowizard } from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
});
```

Then...

Add the shadowizard class to the element you want a shadow add to.
```
<img src="image.jpg" class="shadowizard">
```

## Options

Shadowizard support 2 options, both of which are optional:

* *shadow_type* - _hard | soft_  (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)

