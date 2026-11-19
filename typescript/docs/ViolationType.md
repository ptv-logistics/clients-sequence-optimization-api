
# ViolationType

Specifies the type of violation.  * `DRIVER_AVAILABILITY` - The driver availability is violated.  * `ROUTE_START_INTERVAL` - The route start interval is violated.   * `OPENING_INTERVAL` - The opening intervals of the location are violated.  * `MAXIMUM_TRAVEL_TIME_OF_DRIVER` - Indicates a violation of the maximum allowed travel time of driver as specified by the drivers\' working hours restriction.  * `MAXIMUM_DRIVING_TIME_OF_DRIVER` - Indicates a violation of the maximum allowed driving time of driver as specified by the drivers\' working hours restriction.  * `MAXIMUM_DISTANCE` - Indicates a violation of the maximum allowed driving distance as specified at the vehicle.   * `MAXIMUM_NUMBER_OF_CUSTOMER_STOPS` - Indicates a violation of the maximum allowed number of customer stops as specified at the vehicle.   * `VEHICLE_CAPACITY` - At least one of the vehicle capacities is violated.  * `STOP_POSITION` - Indicates a violation of the position of a stop.  * `ROUTE_SECTION` - Indicates a violation of the route section numbers of a customer stop.

## Properties

Name | Type
------------ | -------------

## Example

```typescript
import type { ViolationType } from ''

// TODO: Update the object below with actual values
const example = {
} satisfies ViolationType

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ViolationType
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


