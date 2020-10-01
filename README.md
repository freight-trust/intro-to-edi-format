# Baseline - EDI support for mainnets/enterprises 

## true nft - audited NFT restful protocol

[https://github.com/freight-trust/truenft](https://github.com/freight-trust/truenft)

## AS2 Server

[]

## translation service 

[https://github.com/freight-trust/open-edi](https://github.com/freight-trust/open-edi)

### attestation service

[https://github.com/freight-trust/attestation-api](https://github.com/freight-trust/attestation-api)

### canadian customs 

[https://github.com/freight-trust/ace-ac](https://github.com/freight-trust/ace-ac)

### Example Integration: Amazon

[https://github.com/freight-trust/amazon-vendor](https://github.com/freight-trust/amazon-vendor)

### sample onboarding guides

[https://github.com/freight-trust/edi-onboarding/tree/master/guides](https://github.com/freight-trust/edi-onboarding/tree/master/guides)

###  Informative Reference Guide

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

#### Amazon - 810 commerical invoice

https://github.com/freight-trust/amazon-vendor/tree/master/packages/810


##### EIP's

  [eip-2718](https://eips.ethereum.org/EIPS/eip-2718)
  Simple Summary
Defines a new transaction type that is an envelope for future transaction types.

Abstract
TransactionType || TransactionPayload is a valid transaction and TransactionType || ReceiptPayload 

is a valid transaction receipt where TransactionType identifies the format of the transaction and *Payload is the 
transaction/receipt contents, which are defined in future EIPs.
  [eip-2733](https://eips.ethereum.org/EIPS/eip-2733)
  
  
## Tooling & Development 
### Visutal studio code
### VIM 
### GNU EMACS
What does x12-mode do

Either view is easier to navigate - visually, emotionally,or by keystrokes. To summarize, the mode will provide the following functionality for you:

Colorize segment names and delimiters.
Define navigation by fields (called "data elements" in X12 argot).
Define navigation by segments.
Split an X12 message to be presented as one segment per line (or "break" it) - it is easier to read this way.
Combine segments together into one big string (or, "glue" it) - it is usually the way the messages are transmitted.
Visualize blank space in the message. It's particurlaly useful for the fixed length fields and for spotting un-printable characters that got into the message accidentally.


### additional documentation
