# PublicTransportSystem

A PublicTransportSystem provides transport services to members of the public.

![PublicTransportSystem Diagram](../diagrams/PublicTransportSystem.svg)

## Formalization

| Property | Value Restriction |
|----------|-------------------|
| partwhole:hasProperPart | only ([GroupOfLines](GroupOfLines.md) or [PublicTransportLine](PublicTransportLine.md)) |
| rdfs:subClassOf | [PublicTransportElement](PublicTransportElement.md) |

## Other Annotations

- **xsd:pattern**: [PublicTransportSystemPattern](PublicTransportSystemPattern.md)

