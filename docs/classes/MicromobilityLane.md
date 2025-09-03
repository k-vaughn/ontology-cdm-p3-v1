# MicromobilityLane

A MicromobilityLane is a type of RoadLane that forms part of a MicromobilityPathSegment.

![MicromobilityLane Diagram](../diagrams/MicromobilityLane.svg)

## Formalization

| Property | Value Restriction |
|----------|-------------------|
| partwhole:properPartOf | min 1 [MicromobilityPathSegment](MicromobilityPathSegment.md) |
| partwhole:properPartOf | only [MicromobilityPathSegment](MicromobilityPathSegment.md) |
| rdfs:subClassOf | [RoadLane](RoadLane.md) |

## Other Annotations

- **xsd:pattern**: [MicromobilityNetworkPattern](MicromobilityNetworkPattern.md)

