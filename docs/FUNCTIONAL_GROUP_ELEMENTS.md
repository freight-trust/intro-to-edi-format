## Functional Group Elements

Forming XSD, file 2 is "included" in file 1. File 2 contains elements for the functional group. The include element in file 2 pointing to file 3:

<xs:include schemalocation="820.xsd"/>

The root node of the transaction set schema in this example is X12_007040_820 as illustrated below. The end user enters that ref attribute while assembling a transformation scenario.

```xml
<xs:element name="X12_FunctionalGroup">
<xs:annotation>
<xs:documentation>
Functional Group Envelope
</xs:documentation>
</xs:annotation>
<xs:complexType>
<xs:sequence>
<xs:element ref="GS_FunctionalGroupHeader"/>
<xs:element ref="X12_007040_820" maxOccurs="unbounded"/>
<xs:element ref="GE_FunctionalGroupTrailer"/>
</xs:sequence>
</xs:complexType>
</xs:element>
```
