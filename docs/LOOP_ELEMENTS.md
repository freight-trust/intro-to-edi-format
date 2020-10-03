Loop Elements
In the illustration above, the top level loops in the 820 use the ref attribute to an existing definition in this complex type. The following illustration is for the first of those loops named Loop_1-0700:

```xml
<xs:element name="Loop_1-0700">
<xs:annotation>
<xs:documentation>
Party Identification Loop
</xs:documentation>
</xs:annotation>
<xs:complexType>
<xs:sequence>
<xs:element ref="N1_PartyIdentification_1-0700"/>
<xs:element ref="N2_AdditionalNameInformation_1-0700"/>
<xs:element ref="N3_PartyLocation_1-0700"/>
<xs:element ref="N4_GeographicLocation_1-0700"/>
<xs:element ref="REF_ReferenceInformation_1-0700"/>
<xs:element ref="PER_AdministrativeCommunicationsContact_1-0700"/>
<xs:element ref="RDM_RemittanceDeliveryMethod_1-0700"/>
<xs:element ref="DTM_DateTimeReference_1-0700"/>
</xs:sequence>
</xs:complexType>
</xs:element>
```
