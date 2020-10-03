### Interchange Elements
Many of the descriptions below pertain to all of the files and all of the sections of those files. 
Those descriptions are not repeated with each sub section below.

As described in 4.2, Forming XSD, file 1 contains elements for the interchange and includes file 2.
 The include element in file 1 pointing to file 2:

`<xs:include schemalocation="FunctionalGroup.xsd"/>`

By way of an example, the following represents the initial element that ultimately includes all of the other elements that comprise an EDI standard schema:

```xml
<xs:element name="X12_Interchange">
<xs:annotation>
<xs:documentation>
Interchange Envelope
</xs:documentation>
</xs:annotation>
<xs:complexType>
<xs:sequence>
<xs:element ref="ISA_InterchangeControlHeader"/>
<xs:element ref="ISX_InterchangeSyntaxExtension"/>
<xs:element ref="X12_FunctionalGroup" maxOccurs="99999"/>
<xs:element ref="IEA_InterchangeControlTrailer"/>
</xs:sequence>
</xs:complexType>
</xs:element>
```

When a minimum occurrence or a maximum occurrence equals 1, the XSD default, that is not included in the schemas. 
The ref attribute to an existing definition is used within a complex type. This allows the schemas to declare, for example, the REF segment once, but to be used many times in a given transaction set.
