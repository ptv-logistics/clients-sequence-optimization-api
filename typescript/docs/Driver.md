
# Driver

The driver of the specified vehicle. The driver can only operate the vehicle within the given time interval.

## Properties

Name | Type
------------ | -------------
`availability` | [TimeInterval](TimeInterval.md)
`workingHoursPreset` | [WorkingHoursPreset](WorkingHoursPreset.md)
`breakRule` | [BreakRule](BreakRule.md)
`workLogbook` | [WorkLogbook](WorkLogbook.md)
`maximumDrivingTime` | number
`maximumTravelTime` | number

## Example

```typescript
import type { Driver } from ''

// TODO: Update the object below with actual values
const example = {
  "availability": null,
  "workingHoursPreset": null,
  "breakRule": null,
  "workLogbook": null,
  "maximumDrivingTime": null,
  "maximumTravelTime": null,
} satisfies Driver

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as Driver
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


