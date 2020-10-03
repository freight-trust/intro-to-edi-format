## X12 Namespace

Many, but not all, of the properties specified in X12.6 map accurately to XML without change. For example, X12 data element types, such as date, do not correspond directly to the XSD date data type.

Consequently all XML simple content is declared as a string and an X12 namespace, http://schemas.x12.org/isomorph, is declared.

The elements that come from this namespace are prefixed with x12 and provide information to be used by applications within an annotation element.
 For example, the following is contained within the element for ISA09, the interchange date:

`<x12:STD_Info name="Interchange Date" Number="I08" DataType="DT" MaximumLength="6"/>`

The attributes in the example above are from the X12 EDI standard. They are useful for applications that transform EDI to XML and vice versa.
 The maximum length attribute is of particular interest because the simple type that is also within ISA09 has a larger length to accommodate the hyphens and the full four digits for the year that are in an XML date such as 2018-02-27. The entire simple type:

```xml
<xs:simpleType>
<xs:restriction base="xs:string">
<xs:minLength value="6"/>
<xs:maxLength value="10"/>
</xs:restriction>
</xs:simpleType>
```

As illustrated above, this special consideration is used for dates, but also for times for similar reasons. 
Additionally it is used for numeric and decimal types to accommodate implied decimal positions and an optional sign.
