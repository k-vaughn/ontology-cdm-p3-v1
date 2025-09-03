# RoutePoint

A RoutePoint represents a point of interest along a PublicTransportRoute.

![RoutePoint Diagram](../diagrams/RoutePoint.svg)

## Formalization

| Property | Value Restriction |
|----------|-------------------|
| isBorderCrossing | exactly 1 xsd:boolean |
| isBorderCrossing | only xsd:boolean |
| isViaPoint | max 1 xsd:boolean |
| isViaPoint | only xsd:boolean |
| rdfs:subClassOf | [PublicTransportElement](PublicTransportElement.md) |
| rdfs:subClassOf | [TransportNode](TransportNode.md) |

## Other Annotations

- **xsd:pattern**: [PublicTransportSystemPattern](PublicTransportSystemPattern.md)

