## alternative-true

## When false isn't true enough.

Welcome to coding in Trump's America.
Here is an example use case:

```js
import { alternativeTrue } from 'alternative-true';

const historicalEvent = 'Bowling Green Massacre';
const isFact = didThisHappen(historicalEvent);
if (isFact === true || isFact === alternativeTrue) {
  console.log('This DEFINITELY happened!);
}
```
