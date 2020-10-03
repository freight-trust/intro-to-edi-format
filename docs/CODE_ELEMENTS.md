## Code Elements

In the illustration above, N101 is assigned a non-built-in XSD data type consisting of the literal "DE_" and the data element number. 
The resulting DE_98 is used to define the available internal code values and their descriptions. The following illustration is for the code lists.

```xml
<xs:simpleType name="DE_98">
<xs:annotation>
<xs:documentation>
```

Code identifying an organizational entity, a physical location, property or an individual

```xml
</xs:documentation>
</xs:annotation>
<xs:restriction base="ID">
<xs:enumeration value="01">
<xs:annotation>
<xs:documentation>
Loan Applicant
</xs:documentation>
</xs:annotation>
</xs:enumeration>
```
