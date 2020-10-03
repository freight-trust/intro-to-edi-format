## X12 Data Type Elements

In the illustration above, DE_98 is assigned a non-built-in XSD data type of ID.
 Note that there isn't a minimum or maximum length. The enumerations themselves specify length. The following illustrates the method of defining X12 data types in XSD using a built-in XSD type.

```xml
<xs:simpleType name="AN">
<xs:annotation>
<xs:documentation>
A string data element is a sequence of any characters from the basic or extended character sets and contains at least one non-space character. The significant characters shall be left justified. Leading spaces, when they occur, are presumed to be significant characters. In the actual data stream trailing spaces should be suppressed. The representation for this data element type is AN.
</xs:documentation>
</xs:annotation>
<xs:restriction base="xs:string"/>
</xs:simpleType>
<xs:simpleType name="ID">
<xs:annotation>
<xs:documentation>
An identifier data element always contains a unique value from a single, predefined list of values. That list of values is either enumerated within the data element in X12.3 Data Element Dictionary or the source of the list of values is specified in Appendix A in the X12.3 Data Element Dictionary. Trailing spaces should be suppressed. The representation for this data element type is ID.
</xs:documentation>
</xs:annotation>
<xs:restriction base="xs:string"/>
</xs:simpleType>
```
