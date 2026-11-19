
# BreakRule

Defines when a break becomes necessary and how long it should be. See [here](./concepts/drivers-working-hours) for more information.

## Properties

Name | Type
------------ | -------------
`breakTime` | number
`maximumDrivingTimeBetweenBreaks` | number
`maximumWorkingTimeBetweenBreaks` | number
`workingTimeThreshold` | number

## Example

```typescript
import type { BreakRule } from ''

// TODO: Update the object below with actual values
const example = {
  "breakTime": null,
  "maximumDrivingTimeBetweenBreaks": null,
  "maximumWorkingTimeBetweenBreaks": null,
  "workingTimeThreshold": null,
} satisfies BreakRule

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as BreakRule
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


