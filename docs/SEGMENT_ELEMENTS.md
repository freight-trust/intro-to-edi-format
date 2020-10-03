## Segment Elements

In the illustration above, the N1 segment is the first segment in Loop_1-0700.
 The following illustration is for that segment. Not the entire segment is illustrated, just enough to point out how a code list for the first data element is specified.

```xml
<xs:element name="N1_PartyIdentification_1-0700">
<xs:annotation>
<xs:documentation>
Party Identification
</xs:documentation>
</xs:annotation>
<xs:complexType>
<xs:sequence>
<xs:element name="N101__EntityIdentifierCode" type="DE_98"/>
<xs:annotation>
<xs:documentation>
Code identifying an organizational entity, a physical location, property or an individual
</xs:documentation>
```
