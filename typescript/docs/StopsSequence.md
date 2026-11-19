
# StopsSequence

Indicates if and how the sequence of stops that is already part of the input route, should be retained. Will be ignored, if there are no stops in input route.  * `ANY` - Sequence of stops already in input route can be modified arbitrarily in order to obtain an optimal route.  * `RELATIVE` - Relative sequence of stops as given in input route should be retained.

## Properties

Name | Type
------------ | -------------

## Example

```typescript
import type { StopsSequence } from ''

// TODO: Update the object below with actual values
const example = {
} satisfies StopsSequence

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as StopsSequence
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


