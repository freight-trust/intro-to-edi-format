# Baseline - EDI Transaction Onboarding

## Overview

This is to get you familiar with just the format and syntax for EDI data, we will not be generating any EDI data in this *lesson*.

- editor-plugins
	* this contains syntax highlighting for popular editors

- examples:
 * this contains some reference files for transaction sets and XSD schemas to validate against

- edi-diff-compare:
	* this is an example of comparing (i.e. diffing) between a `valid` and `invalid` transaction.
	> *NOTE* for proper diffing you need to set your `.gitattributes` 

- schemas:
	* this is for reference for X12 4010 in `.json` format

More examples can be posted, simply open an issue if you like to request something specific

#### Why?

The *WHY* is important: EDI data can be *big*, especially when going into a format like `JSON`. The purpose of this
repository is so that you can eventually be able to answer this question:

#### `What Data Elements do I need for my use case?`

Specific Data elements are described in the `version` and `transaction set` for example: 

`810 4010 X12`

This mean:
`810` = The Transaction Set
`4010` = The Version
`X12` = The Standards Agency / Issuing Body

## Reference Guide

[Google Sheets Webpage for an Example 846 transaction with Amazon, broken down into separate sheets](https://docs.google.com/spreadsheets/d/e/2PACX-1vQuu9LCzRpVJ0uaSWRhXcQapI-WJEW1CUa6fwz4xJFWzcgfNLeYQJGfJm77bPBfhwyZlnBjNLenBjFe/pubhtml)

> Quick Glossary of Terms


### Abbreviations

ANSI: American National Standards Institute <br>
AU: Access unit <br>
DIT: Directory information tree <br>
DL: Distribution list <br>
DUA: Directory user agent <br> 
EDI: Electronic data interchange <br>
EDIME: EDI messaging environment <br>
EDIFACT Electronic data interchange for Administration, commerce and transport <br>
EDIM: EDI message <br>

## Terms  ANSI X12
 Application reference <br>
 Date and Time ofTransmission <br> 
 GS <br>
 Interchange header <br>
 Functional group header <br>
 Transaction set header <br>
 ISA <br>
 IEA <br>
 Recipient;s transmission reference/password <br>
 ST <br>
 Transmission sender <br>
 Transmission recipient <br>
 Transmission priority code <br> 


## ISO 9735

 Acknowledgment request <br>
 Application reference <br>
 Communication agreement ID <br>
 Date/time of preparation <br> 
 Functional group header <br>
 Interchage control reference <br>
 Interchange header <br>
 Interchange recipient <br>
 Interchange sender <br>
 Message header <br>
 Processing priority code <br> 
 Recipients reference, password <br>
 Service string advice <br>
 Syntax identifier <br>
 Test indicator <br>
 UNA <br>
 UNB <br>
 UNG <br>
 UNH <br>
 UNT <br>
 UNZ <br>

## Visual Studio Code

> Marketplace Extensions

## VSCode Plugin for EDIFACT

[https://marketplace.visualstudio.com/items?itemName=DAXaholic.vscode-edifact](https://marketplace.visualstudio.com/items?itemName=DAXaholic.vscode-edifact)

### VSCode Plugin for ASC X12

A Visual Studio Code extension aimed at providing basic support for the EDI X12 format

[https://marketplace.visualstudio.com/items?itemName=Silvenga.edi-x12-support](https://marketplace.visualstudio.com/items?itemName=Silvenga.edi-x12-support)

### Informative Reference Guide

  [https://github.com/freight-trust/informative-baseline](https://github.com/freight-trust/informative-baseline)

### X12/EDIFACT Background

In 1978, The American National Standards Institute (ANSI) chartered a Accredited Standard Committee (ASC) X12. This committee's objective was "...to develop uniform standards for inter-industry electronic interchange of business
transactions". The result was an example of the "design by committee" - a set of EDI (electronic data interchange) standards
now known as X12 - more than 300 specifications published so far. The next most exciting bureaucratic organization in the 
world, naturally, could not stay away for long and in 1986, the United Nations Economic Commission for Europe (UN/ECE) adopted 
UN/EDIFACT (United Nations Electronic Data Interchange for Administration, Commerce and Transport), which is roughly the same 
thing as ANSI's X12.

Both standards should be long dead by now, but X12 has made its way into government regulations and, therefore, is mandated for use in government-regulated industries. The United State's health care is one of these. The http://www.x12.org contains a broader and prouder overview of the whole thing.


The raw X12 message looks like this:
```
ISA*03*ABRA      *01*PASSWORD  *ZZ*ABRACADABRA    *ZZ*SECRET         *040115
*1144*U*00401*000003421*0*T*:~GS*HB*RGP4530*FJRIDNKLEKSJDFL*20040115*114427*
473829384*004010X059~ST*278*1000~BHT*0083*49*WYCKJHSLXBWF*20030529*1653*18~H
L*1**20*1~NM1*X3*2*TEST*****PI*PYRCD**~HL*2*1*21*1~NM1*1P*1*Provider*Request
ing*B***46*taxID2**~REF*ZH*P2**~PRV*PC*ZZ*SPECIALITY1**SC1*~HL*3*2*22*1~HI*B
F:9993*BF:9998*BF:0132*********~NM1*IL*1*LastName*FirstName*M*Mr.*II*MI*MEM 
ID-01**~REF*EJ*PAT ACCT NUM~DMG*D8*19650113*M******~HL*4*3*PA*1~NM1*DN*1*Pro
vider*Referring*T*Dr.**46*REF TAX ID**~REF*ZH*163459281**~N3*Referring Provi
der Address*Suite 100~N4*Chicago*IL*60606***~PRV*AT*ZZ*REFERRING SPECIALTY**
SC2*~HL*5*4*19*1~NM1*SJ*1*Provider*Service*T*Dr.**46*SERV TAX ID*~REF*ZH*163
459281**~N3*Service Provider Address*Suite 200~N4*Chicago*IL*60606***~PRV*PE
*ZZ*SERVICE SPECIALTY**SC3*~HL*6*5*SS*0~TRN*2*TRACE NUM*ORIG CMPNY*~UM*SC*I*
1*11:B*****r*~HCR*A1*REFERRAL NUMBER**~REF*BB*PREV CERT NUM**~DTP*472*RD8*20
030101-20030630~DTP*102*D8*20030101~DTP*036*D8*20030630~DTP*007*D8*20030101~
DTP*881*D8*20030202~HSD*VS*3******~SE*37*1000~GE*1*001127092~IEA*1*001123616
```


### Picture of the Schema for one transaction set

[https://raw.githubusercontent.com/freight-trust/protocol/a6320bd452b0e65f86f6352f44a7f5769f1f5859/ROOT/32768.svg](https://raw.githubusercontent.com/freight-trust/protocol/a6320bd452b0e65f86f6352f44a7f5769f1f5859/ROOT/32768.svg)

> hint, zoom out, like 25%

![](https://cdn.mathpix.com/snip/images/W6niCDX2Y6DU_gxNrCU7km-uPOTDgNJbYGSmy2AsTy0.original.fullsize.png)

### EDI Support for Microsoft VSl Studio Code

https://raw.githubusercontent.com/freight-trust/linguist-edi/master/edi.tmLanguage.json

### Interchange Library

[https://github.com/freight-trust/libinterchange/](https://github.com/freight-trust/libinterchange/)

### Example Integrations

#### Amazon - 810 commercial invoice

https://github.com/freight-trust/amazon-vendor/tree/master/packages/810

## Ethereum EIP's

> These may prove to further extend functionality down the road, they are put here for informative purposes.

  [eip-2718](https://eips.ethereum.org/EIPS/eip-2718)
  Simple Summary
Defines a new transaction type that is an envelope for future transaction types.

Abstract
TransactionType || TransactionPayload is a valid transaction and TransactionType || ReceiptPayload 

is a valid transaction receipt where TransactionType identifies the format of the transaction and *Payload is the 
transaction/receipt contents, which are defined in future EIPs.
  [eip-2733](https://eips.ethereum.org/EIPS/eip-2733)
  

## Tooling & Development

### GNU EMACS

What does x12-mode do

Either view is easier to navigate - visually, emotionally,or by keystrokes. To summarize, the mode will provide the following functionality for you:

Colorize segment names and delimiters.
Define navigation by fields (called "data elements" in X12 argot).
Define navigation by segments.
Split an X12 message to be presented as one segment per line (or "break" it) - it is easier to read this way.
Combine segments together into one big string (or, "glue" it) - it is usually the way the messages are transmitted.
Visualize blank space in the message. It's particularly useful for the fixed length fields and for spotting un-printable characters that got into the message accidentally.

### additional documentation


- translation service 

[https://github.com/freight-trust/open-edi](https://github.com/freight-trust/open-edi)

- attestation service

[https://github.com/freight-trust/attestation-api](https://github.com/freight-trust/attestation-api)

- canadian customs

[https://github.com/freight-trust/ace-ac](https://github.com/freight-trust/ace-ac)

- Example Integration: Amazon

[https://github.com/freight-trust/amazon-vendor](https://github.com/freight-trust/amazon-vendor)

- sample onboarding guides 

> These are refereed to as `ESC` guides

[https://github.com/freight-trust/edi-onboarding/tree/master/guides](https://github.com/freight-trust/edi-onboarding/tree/master/guides)


## License

All Licenses are owned by their respective Authors. We make no claim on license nor copyright. 

Accredited Standards Committee X12, X12N. [www.x12.org](https://www.x12.org)
004010 X12 Incorporated

```
U.S. Copyright laws and X12 Intellectual Property (IP) policies apply to the use and distribution of any X12 
product, including published and draft works. X12's copyrighted products, include but are not limited to, 
standards, technical reports, guidelines, workbooks, segment directories, element directories, data element 
dictionaries, table data, schema, and mapping instructions.
```
