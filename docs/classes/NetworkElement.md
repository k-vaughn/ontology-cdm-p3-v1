# NetworkElement

![NetworkElement Diagram](../diagrams/NetworkElement.svg)

## Restrictions

| Property | Restriction Type |
|----------|------------------|
| genProp:hasIdentifier | All values from xsd:string |
| partwhole:hasProperPart | All values from NetworkElement |
| partwhole:properPartOf | All values from NetworkElement |
| status | All values from ScheduledCode |

## Other Annotations

- **protege:abstract**: true
- **terms:description**: A NetworkElement represents any element of a transport network. It can be a part of another NetworkElement and can be decomposed into smaller NetworkElements.
- **xsd:pattern**: TransportNetworkPattern

