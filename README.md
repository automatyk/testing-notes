# testing-notes
Notes on Testing, Unit testing, Jest, testing-library/react, etc.

## Testing Library React ##

```javascript
import { screen, render, fireEvent } from '@testing-library/react'

// shortcuts for commonly used things
const click = (testId) => fireEvent.click(screen.getByTestId(testId))
const expectComponent = (testId) => expect(screen.getByTestId(testId))

```
