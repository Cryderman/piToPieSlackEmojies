# There is no reason to ever use this.
### I just wanted to learn to publish to npm
#### see code below on how to use it

```javascript
let { getNDigitsOfPiAsPie } = require('pi-to-pie-slack-emoji')

let one = getNDigitsOfPiAsPie(1)

console.log(one) // ( :pie: :pie: :pie: )

let two = getNDigitsOfPiAsPie(2)

console.log(two) // ( :pie: :pie: :pie: ).( :pie: )

let four = getNDigitsOfPiAsPie(4)

console.log(two) // ( :pie: :pie: :pie: ).( :pie: )( :pie:  :pie:  :pie:  :pie: )( :pie: )


```
