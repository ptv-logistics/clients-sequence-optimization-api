
# WayReport

A way report contains a summary of the values of the events on the way from the previous stop to the current stop, including the driving time. The very first stop of a route has a way report with empty values.

## Properties

Name | Type
------------ | -------------
`distance` | number
`drivingTime` | number
`breakTime` | number

## Example

```typescript
import type { WayReport } from ''

// TODO: Update the object below with actual values
const example = {
  "distance": null,
  "drivingTime": null,
  "breakTime": null,
} satisfies WayReport

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as WayReport
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


