
# CustomerLocationAttributes

Attributes for a location of type CUSTOMER.

## Properties

Name | Type
------------ | -------------
`serviceTimePerTransportStop` | number
`positionInRoute` | [PositionInRoute](PositionInRoute.md)
`routeSectionNumber` | number

## Example

```typescript
import type { CustomerLocationAttributes } from ''

// TODO: Update the object below with actual values
const example = {
  "serviceTimePerTransportStop": null,
  "positionInRoute": null,
  "routeSectionNumber": null,
} satisfies CustomerLocationAttributes

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as CustomerLocationAttributes
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


