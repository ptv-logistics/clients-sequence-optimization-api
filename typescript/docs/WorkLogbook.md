
# WorkLogbook

Defines the accumulated driving and working times since the last break.  See [here](./concepts/drivers-working-hours) for more information.

## Properties

Name | Type
------------ | -------------
`lastTimeTheDriverWorked` | Date
`accumulatedDrivingTimeSinceLastBreak` | number
`accumulatedWorkingTimeSinceLastBreak` | number

## Example

```typescript
import type { WorkLogbook } from ''

// TODO: Update the object below with actual values
const example = {
  "lastTimeTheDriverWorked": null,
  "accumulatedDrivingTimeSinceLastBreak": null,
  "accumulatedWorkingTimeSinceLastBreak": null,
} satisfies WorkLogbook

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as WorkLogbook
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


