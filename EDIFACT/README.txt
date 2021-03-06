2.   Service code list

     Change indicators

     a plus sign (+)    for an addition
     an asterisk (*)    for an addition/subtraction/change to an entry
                        for a particular data element
     a hash sign (#)    for changes to names
     a vertical bar (|) for changes to text for descriptions,
                        notes and functions
     an X sign (X)      for marked for deletion

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0001  Syntax identifier

  Desc: Coded identification of the agency controlling the syntax, and
        of the character repertoire used in an interchange.

  Repr: a4

  Note 1: The data value consists of the letters 'UN', upper case,
          identifying the syntax controlling agency, directly followed
          by an a2 code identifying the character repertoire used.

   UNOA   UN/ECE level A
             As defined in the basic code table of ISO 646 with the
             exceptions of lower case letters, alternative graphic
             character allocations and national or
             application-oriented graphic character allocations.
   UNOB   UN/ECE level B
             As defined in the basic code table of ISO 646 with the
             exceptions of alternative graphic character allocations
             and national or application-oriented graphic character
             allocations.
   UNOC   UN/ECE level C
             As defined in ISO 8859-1 : Information processing - Part
             1: Latin alphabet No. 1.
   UNOD   UN/ECE level D
             As defined in ISO 8859-2 : Information processing - Part
             2: Latin alphabet No. 2.
   UNOE   UN/ECE level E
             As defined in ISO 8859-5 : Information processing - Part
             5: Latin/Cyrillic alphabet.
   UNOF   UN/ECE level F
             As defined in ISO 8859-7 : Information processing - Part
             7: Latin/Greek alphabet.
   UNOG   UN/ECE level G
             As defined in ISO 8859-3 : Information processing - Part
             3: Latin alphabet.
   UNOH   UN/ECE level H
             As defined in ISO 8859-4 : Information processing - Part
             4: Latin alphabet.
   UNOI   UN/ECE level I
             As defined in ISO 8859-6 : Information processing - Part
             6: Latin/Arabic alphabet.
   UNOJ   UN/ECE level J
             As defined in ISO 8859-8 : Information processing - Part
             8: Latin/Hebrew alphabet.
   UNOK   UN/ECE level K
             As defined in ISO 8859-9 : Information processing - Part
             9: Latin alphabet.
   UNOX   UN/ECE level X
             Code extension technique as defined by ISO 2022 utilising
             the escape techniques in accordance with ISO 2375.
   UNOY   UN/ECE level Y
             ISO 10646-1 octet without code extension technique.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0002  Syntax version number

  Desc: Version number of the syntax.

  Repr: an1

  Note 1: Shall be '4' to indicate this version of the syntax.

   1      Version 1
             ISO 9735:1988.
   2      Version 2
             ISO 9735:1990.
   3      Version 3
             ISO 9735 Amendment 1:1992.
   4      Version 4
             ISO 9735:1998.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

* 0007  Identification code qualifier

  Desc: Qualifier referring to the identification code.

  Repr: an..4

  Note 1: A qualifier code may refer to an organisation identification
          as in ISO 6523.

   1      DUNS (Data Universal Numbering System)
             Partner identification code assigned by Dun & Bradstreet.
   4      IATA (International Air Transport Association)
             Partner identification code assigned by the International
             Air Transport Association.
   5      INSEE (Institut National de la Statistique et des Etudes
          Economiques) - SIRET
             French national statistics institute. SIRET means Systeme
             Informatique du Repertoire des entreprises et de leurs
             ETablissements.
   8      UCC Communications ID (Uniform Code Council Communications
          Identifier)
             The Uniform Code Council Communications Identifier is a
             ten digit code used to uniquely identify physical and
             logical locations.
   9      DUNS (Data Universal Numbering System) with 4 digit suffix
             Partner identification code assigned by Dun & Bradstreet
             with the 4 digit suffix.
   12     Telephone number
             Partner identification code corresponds to the partner
             telephone number.
   14     EAN (European Article Numbering Association)
             Partner identification code assigned by the European
             Article Numbering Association.
   18     AIAG (Automotive Industry Action Group)
             Partner identification code assigned by the Automotive
             Industry Action Group.
   22     INSEE (Institut National de la Statistique et des Etudes
          Economiques) - SIREN
             French national statistics institute. SIREN means Systeme
             Informatique du Repertoire des ENtreprises (et de leurs
             etablissements).
   30     ISO 6523: Organization identification
             Partner identification code specified in ISO 6523
             (Structures for the identification of organizations).
   31     DIN (Deutsches Institut fuer Normung)
             German standardization institute.
   33     BfA (Bundesversicherungsanstalt fuer Angestellte)
             German social security association.
   34     National Statistical Agency
             Partner identification code assigned by a national
             statistical agency.
   51     GEIS (General Electric Information Services)
             Partner identification code assigned by General Electric
             Information Services.
   52     INS (IBM Network Services)
             Partner identification code assigned by IBM Network
             Services.
   53     Datenzentrale des Einzelhandels
             German data centre for retail trade.
   54     Bundesverband der Deutschen Baustoffhaendler
             German building material trade association.
   55     Bank identifier code
             Partner identification code corresponds to the partner
             bank identification code.
   57     KTNet (Korea Trade Network Services)
             Partner identification code assigned by Korea Trade
             Network Services.
   58     UPU (Universal Postal Union)
             Partner identification code assigned by the Universal
             Postal Union.
   59     ODETTE (Organization for Data Exchange through
          Tele-Transmission in Europe)
             European automotive industry project.
   61     SCAC (Standard Carrier Alpha Code)
             Directory of standard multimodal carriers and tariff
             agent codes. The SCAC lists and codes transportation
             companies.
   63     ECA (Electronic Commerce Australia)
             Australian association for electronic commerce.
   65     TELEBOX 400 (Deutsche Telekom)
             German telecommunications service.
   80     NHS (National Health Service)
             United Kingdom National Health Service.
   82     Statens Teleforvaltning
             Norwegian telecommunications regulatory authority (NTRA).
   84     Athens Chamber of Commerce
             Greek Chamber of Commerce.
   85     Swiss Chamber of Commerce
             Swiss Chamber of Commerce.
   86     US Council for International Business
             United States Council for International Business.
   87     National Federation of Chambers of Commerce and Industry
             Belgium National Federation of Chambers of Commerce and
             Industry.
   89     Association of British Chambers of Commerce
             Association of British Chambers of Commerce.
   90     SITA (Societe Internationale de Telecommunications
          Aeronautiques)
             SITA (Societe Internationale de Telecommunications
             Aeronautiques).
   91     Assigned by seller or seller's agent
             Partner identification code assigned by the seller or
             seller's agent.
   92     Assigned by buyer or buyer's agent
             Partner identification code assigned by the buyer or
             buyer's agent.
   103    TW, Trade-van
             Trade-van is an EDI VAN service center for customs,
             transport, and insurance in national and international
             trade.
   128    CH, BCNR (Swiss Clearing Bank Number)
             Code for the identification of a Swiss clearing bank as a
             sender and/or receiver of an electronic message.
   129    CH, BPI (Swiss Business Partner Identification)
             Code for the identification of a corporate or a Swiss
             non-clearing bank as a sender and/or receiver of an
             electronic message.
   144    US, DoDAAC (Department of Defense Activity Address Code)
             Code assigned to uniquely identify all military units in
             the United States Department of Defense.
   145    FR, DGCP (Direction Generale de la Comptabilite Publique)
             Code assigned by the French public accounting office.
   146    FR, DGI (Direction Generale des Impots)
             Code assigned by the French taxation authority.
   147    JP, JIPDEC/ECPC (Japan Information Processing Development
          Corporation / Electronic Commerce Promotion Center)
             Partner identification code which is registered with
             JIPDEC/ECPC.
   148    ITU (International Telecommunications Union) Data Network
          Identification Code (DNIC)
             Data network identification code assigned by the ITU.
+  Z01    Vehicle registration number
             Registration number of a vehicle assigned by a recognised
             authority.
   ZZZ    Mutually defined
             Mutually defined between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0025  Recipient reference/password qualifier

  Desc: Qualifier for the recipient's reference or password.

  Repr: an2

  Note 1: To be used as specified in the partners' interchange
          agreement.

   AA     Reference
             Recipient's reference/password is a reference.
   BB     Password
             Recipient's reference/password is a password.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0029  Processing priority code

  Desc: Code determined by the sender requesting processing priority
        for the interchange.

  Repr: a1

  Note 1: To be used as specified in the partners' interchange
          agreement.

   A      Highest priority
             Requested processing priority is the highest.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0031  Acknowledgement request

  Desc: Code requesting acknowledgement for the interchange.

  Repr: n1

  Note 1: Used if the sender requests that a message related to
          syntactical correctness be sent by the recipient in
          response.
  Note 2: For UN/EDIFACT a specific message (Syntax and service report
          - CONTRL) is defined for this purpose.

   1      Acknowledgement requested
             Acknowledgement is requested.
   2      Indication of receipt
             Confirmation of receipt only.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0035  Test indicator

  Desc: Indication that the structural level containing the test
        indicator is a test.

  Repr: n1

   1      Interchange is a test
             Indicates that the interchange is a test.
   2      Syntax only test
             Test only syntax of structure.
   3      Echo request
             To be returned without change, except for this data
             element to have the value 4.
   4      Echo response
             Returned without change except for this data element
             changing from 3 to 4.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0051  Controlling agency, coded

  Desc: Code identifying a controlling agency.

  Repr: an..3

   AA     EDICONSTRUCT
             French construction project.
   AB     DIN (Deutsches Institut fuer Normung)
             German standardization institute.
   AC     ICS (International Chamber of Shipping)
             The International Chamber of Shipping.
   AD     UPU (Union Postale Universelle)
             Universal Postal Union.
   AE     United Kingdom ANA (Article Numbering Association)
             Identifies the Article Numbering Association of the
             United Kingdom.
   AF     ANSI ASC X12 (American National Standard Institute
          Accredited Standards Committee X12)
             Identifies the United States electronic data interchange
             standards body.
   AG     US DoD (United States Department of Defense)
             The United States Department of Defense is the entity
             controlling the message specification.
   AH     US Federal Government
             The United States Federal Government is the entity
             controlling the message specification.
   AI     EDIFICAS
             European EDI association for financial, informational,
             cost, accounting, auditing and social areas.
   CC     CCC (Customs Co-operation Council)
             The Customs Co-operation Council.
   CE     CEFIC (Conseil Europeen des Federations de l'Industrie
          Chimique)
             EDI project for chemical industry.
   EC     EDICON
             UK Construction project.
   ED     EDIFICE (Electronic industries project)
             EDI Forum for companies with Interest in Computing and
             Electronics (EDI project for EDP/ADP sector).
   EE     EC + EFTA (European Communities and European Free Trade
          Association)
             The European Communities and the European Free Trade
             Association.
   EN     EAN (European Article Numbering Association)
             The European Article Numbering Association.
   ER     UIC (International Union of railways)
             European railways.
   EU     European Union
             The European Union.
   EW     UN/EDIFACT Working Group (EWG)
             United Nations working group responsible for UN/EDIFACT
             (United Nations, Electronic Data Interchange for
             Administration, Commerce and Transport).
   EX     IECC (International Express Carriers Conference)
             The International Express Carriers Conference.
   IA     IATA (International Air Transport Association)
             The International Air Transport Association.
   KE     KEC (Korea EDIFACT Committee)
             The Korea EDIFACT Committee.
   LI     LIMNET
             UK Insurance project.
   OD     ODETTE (Organization for Data Exchange through
          Tele-Transmission in Europe)
             European automotive industry project.
   RI     RINET (Reinsurance and Insurance Network)
             The Reinsurance and Insurance Network.
   RT     UN/ECE/TRADE/WP.4/GE.1/EDIFACT Rapporteurs' Teams
             United Nations Economic UN Economic Commission for Europe
             (UN/ECE), Committee on the development of trade (TRADE),
             Working Party on facilitation of international trade
             procedures (WP.4), Group of Experts on data elements and
             automatic data interchange (GE.1), EDIFACT Rapporteurs'
             Teams.
   UN     UN/CEFACT
             United Nations Centre for Trade Facilitation and
             Electronic Business (UN/CEFACT).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0052  Message version number

  Desc: Version number of a message type.

  Repr: an..3

   1      Status 1 version
             Message approved and issued as a status 1 (trial)
             message. (Valid for directories published after March
             1990 and prior to March 1993).
   2      Status 2 version
             Message approved and issued as a status 2 (formal
             recommendation) message. (Valid for directories published
             after March 1990 and prior to March 1993).
   4      Service message, version 4
             Service messages approved and issued as a part of ISO
             9735/Version 4, for use with that version of the syntax.
          Note:
             1. For earlier versions of the UN/EDIFACT CONTRL message,
             each published by the UN as a stand-alone message, the
             version number to be used is specified in the message
             documentation.
   88     1988 version
             Message approved and issued in the 1988 release of the
             UNTDID (United Nations Trade Data Interchange Directory)
             as a status 2 (formal recommendation) message.
   89     1989 version
             Message approved and issued in the 1989 release of the
             UNTDID (United Nations Trade Data Interchange Directory)
             as a status 2 (formal recommendation) message.
   90     1990 version
             Message approved and issued in the 1990 release of the
             UNTDID (United Nations Trade Data Interchange Directory)
             as a status 2 (formal recommendation) message.
   D      Draft version/UN/EDIFACT Directory
             Message approved and issued as a draft message (Valid for
             directories published after March 1993 and prior to March
             1997). Message approved as a standard message (Valid for
             directories published after March 1997).
   S      Standard version
             Message approved and issued as a standard message. (Valid
             for directories published after March 1993 and prior to
             March 1997).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

* 0054  Message release number

  Desc: Release number within the current message version number.

  Repr: an..3

   1      First release
             User message approved and issued in the first release of
             the year of the UNTDID (United Nations Trade Data
             Interchange Directory); valid for directories published
             prior to March 1990. Service message approved and issued
             as the first release of the message within a version of
             ISO 9735; valid for version 4 of IS0 9735 and later.
   2      Second release
             User message approved and issued in the second release of
             the year of the UNTDID (United Nations Trade Data
             Interchange Directory); valid for directories published
             prior to March 1990.  Service message approved and issued
             as the second release of the message within a version of
             ISO 9735; valid for version 4 of IS0 9735 and later.
   902    Trial release 1990
             Message approved and issued in the 1990 status 1 (trial)
             release of the UNTDID (United Nations Trade Data
             Interchange Directory).
   911    Trial release 1991
             Message approved and issued in the 1991 status 1 (trial)
             release of the UNTDID (United Nations Trade Data
             Interchange Directory).
   912    Standard release 1991
             Message approved and issued in the 1991 status 2
             (standard) release of the UNTDID (United Nations Trade
             Data Interchange Directory).
   921    Trial release 1992
             Message approved and issued in the 1992 status 1 (trial)
             release of the UNTDID (United Nations Trade Data
             Interchange Directory).
   932    Standard release 1993
             Message approved and issued in the 1993 status 2
             (standard) release of the UNTDID (United Nations Trade
             Data Interchange Directory).
   00A    Release 2000 - A
             Message approved and issued in the first 2000 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   00B    Release 2000 - B
             Message approved and issued in the second 2000 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   01A    Release 2001 - A
             Message approved and issued in the first 2001 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   01B    Release 2001 - B
             Message approved and issued in the second 2001 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   01C    Release 2001 - C
             Message approved and issued in the third 2001 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
+  02A    Release 2002 - A
             Message approved and issued in the first 2002 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   93A    Release 1993 - A
             Message approved and issued in the 1993 release of the
             UNTDID (United Nations Trade Data Interchange Directory).
   94A    Release 1994 - A
             Message approved and issued in the first 1994 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   94B    Release 1994 - B
             Message approved and issued in the second 1994 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   95A    Release 1995 - A
             Message approved and issued in the first 1995 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   95B    Release 1995 - B
             Message approved and issued in the second 1995 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   96A    Release 1996 - A
             Message approved and issued in the first 1996 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   96B    Release 1996 - B
             Message approved and issued in the second 1996 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   97A    Release 1997 - A
             Message approved and issued in the first 1997 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   97B    Release 1997 - B
             Message approved and issued in the second 1997 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   98A    Release 1998 - A
             Message approved and issued in the first 1998 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   98B    Release 1998 - B
             Message approved and issued in the second 1998 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   99A    Release 1999 - A
             Message approved and issued in the first 1999 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).
   99B    Release 1999 - B
             Message approved and issued in the second 1999 release of
             the UNTDID (United Nations Trade Data Interchange
             Directory).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0065  Message type

  Desc: Code identifying a type of message and assigned by its
        controlling agency.

  Repr: an..6

  Note 1: In UNSMs (United Nations Standard Messages), the
          representation is a6.

   APERAK Application error and acknowledgement message
             A code to identify the application error and
             acknowledgement message.
   AUTACK Secure authentication and acknowledgement message
             A code to identify the secure authentication and
             acknowledgement message.
   AUTHOR Authorization message
             A code to identify the authorization message.
   AVLREQ Availability request - interactive message
             A code to identify the availability request - interactive
             message.
   AVLRSP Availability response - interactive message
             A code to identify the availability response -
             interactive message.
   BALANC Balance message
             A code to identify the balance message.
   BANSTA Banking status message
             A code to identify the banking status message.
   BAPLIE Bayplan/stowage plan occupied and empty locations message
             A code to identify the bayplan/stowage plan occupied and
             empty locations message.
X  BAPLTE Bayplan/stowage plan total numbers message
             A code to identify the bayplan/stowage plan total numbers
             message.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
   BERMAN Berth management message
             A code to identify the berth management message.
   BMISRM Bulk marine inspection summary report message
             A code to identify the bulk marine inspection summary
             report message.
   BOPBNK Bank transactions and portfolio transactions report message
             A code to identify the bank transactions and portfolio
             transactions report message.
   BOPCUS Balance of payment customer transaction report message
             A code to identify the balance of payment customer
             transaction report message.
   BOPDIR Direct balance of payment declaration message
             A code to identify the direct balance of payment
             declaration message.
   BOPINF Balance of payment information from customer message
             A code to identify the balance of payment information
             from customer message.
   BUSCRD Business credit report message
             A code to identify the business credit report message.
   CALINF Vessel call information message
             A code to identify the vessel call information message.
   CASINT Request for legal administration action in civil proceedings
          message
             A code to identify the request for legal administration
             action in civil proceedings message.
   CASRES Legal administration response in civil proceedings message
             A code to identify the legal administration response in
             civil proceedings message.
   CHACCO Chart of accounts message
             A code to identify the chart of accounts message.
   CLASET Classification information set message
             A code to identify the classification information set
             message.
   CNTCND Contractual conditions message
             A code to identify the contractual conditions message.
   COACSU Commercial account summary message
             A code to identify the commercial account summary
             message.
   COARRI Container discharge/loading report message
             A code to identify the container discharge/loading report
             message.
   CODECO Container gate-in/gate-out report message
             A code to identify the container gate-in/gate-out report
             message.
   CODENO Permit expiration/clearance ready notice message
             A code to identify the permit expiration/clearance ready
             notice message.
   COEDOR Container stock report message
             A code to identify the container stock report message.
   COHAOR Container special handling order message
             A code to identify the container special handling order
             message.
   COLREQ Request for a documentary collection message
             A code to identify the request for a documentary
             collection message.
   COMDIS Commercial dispute message
             A code to identify the commercial dispute message.
   CONAPW Advice on pending works message
             A code to identify the advice on pending works message.
   CONDPV Direct payment valuation message
             A code to identify the direct payment valuation message.
   CONDRA Drawing administration message
             A code to identify the drawing administration message.
   CONDRO Drawing organisation message
             A code to identify the drawing organisation message.
   CONEST Establishment of contract message
             A code to identify the establishment of contract message.
   CONITT Invitation to tender message
             A code to identify the invitation to tender message.
   CONPVA Payment valuation message
             A code to identify the payment valuation message.
   CONQVA Quantity valuation message
             A code to identify the quantity valuation message.
   CONRPW Response of pending works message
             A code to identify the response of pending works message.
   CONTEN Tender message
             A code to identify the tender message.
   CONTRL Syntax and service report message
             A code to identify the syntax and service report message.
   CONWQD Work item quantity determination message
             A code to identify the work item quantity determination
             message.
   COPARN Container announcement message
             A code to identify the container announcement message.
   COPAYM Contributions for payment
             A code to identify the contributions for payment.
   COPINO Container pre-notification message
             A code to identify the container pre-notification
             message.
   COPRAR Container discharge/loading order message
             A code to identify the container discharge/loading order
             message.
   COREOR Container release order message
             A code to identify the container release order message.
   COSTCO Container stuffing/stripping confirmation message
             A code to identify the container stuffing/stripping
             confirmation message.
   COSTOR Container stuffing/stripping order message
             A code to identify the container stuffing/stripping order
             message.
   CREADV Credit advice message
             A code to identify the credit advice message.
   CREEXT Extended credit advice message
             A code to identify the extended credit advice message.
   CREMUL Multiple credit advice message
             A code to identify the multiple credit advice message.
   CUSCAR Customs cargo report message
             A code to identify the customs cargo report message.
   CUSDEC Customs declaration message
             A code to identify the customs declaration message.
   CUSEXP Customs express consignment declaration message
             A code to identify the customs express consignment
             declaration message.
   CUSPED Periodic customs declaration message
             A code to identify the periodic customs declaration
             message.
   CUSREP Customs conveyance report message
             A code to identify the customs conveyance report message.
   CUSRES Customs response message
             A code to identify the customs response message.
   DEBADV Debit advice message
             A code to identify the debit advice message.
   DEBMUL Multiple debit advice message
             A code to identify the multiple debit advice message.
   DEBREC Debts recovery message
             A code to identify the debts recovery message.
   DELFOR Delivery schedule message
             A code to identify the delivery schedule message.
   DELJIT Delivery just in time message
             A code to identify the delivery just in time message.
   DESADV Despatch advice message
             A code to identify the despatch advice message.
   DESTIM Equipment damage and repair estimate message
             A code to identify the equipment damage and repair
             estimate message.
   DGRECA Dangerous goods recapitulation message
             A code to identify the dangerous goods recapitulation
             message.
   DIRDEB Direct debit message
             A code to identify the direct debit message.
   DIRDEF Directory definition message
             A code to identify the directory definition message.
   DMRDEF Data maintenance request definition message
             A code to identify the data maintenance request
             definition message.
   DMSTAT Data maintenance status report/query message
             A code to identify the data maintenance status
             report/query message.
   DOCADV Documentary credit advice message
             A code to identify the documentary credit advice message.
   DOCAMA Advice of an amendment of a documentary credit message
             A code to identify the advice of an amendment of a
             documentary credit message.
   DOCAMI Documentary credit amendment information message
             A code to identify the documentary credit amendment
             information message.
   DOCAMR Request for an amendment of a documentary credit message
             A code to identify the request for an amendment of a
             documentary credit message.
   DOCAPP Documentary credit application message
             A code to identify the documentary credit application
             message.
   DOCARE Response to an amendment of a documentary credit message
             A code to identify the response to an amendment of a
             documentary credit message.
   DOCINF Documentary credit issuance information message
             A code to identify the documentary credit issuance
             information message.
   ENTREC Accounting entries message
             A code to identify the accounting entries message.
   FINCAN Financial cancellation message
             A code to identify the financial cancellation message.
   FINPAY Multiple interbank funds transfer message
             A code to identify the multiple interbank funds transfer
             message.
   FINSTA Financial statement of an account message
             A code to identify the financial statement of an account
             message.
   GENRAL General purpose message
             A code to identify the general purpose message.
   GESMES Generic statistical message
             A code to identify the generic statistical message.
   HANMOV Cargo/goods handling and movement message
             A code to identify the cargo/goods handling and movement
             message.
   ICASRP Insurance claim assessment and reporting message
             A code to identify the insurance claim assessment and
             reporting message.
   ICSOLI Insurance claim solicitors instruction message
             A code to identify the insurance claim solicitors
             instruction message.
   IFCSUM Forwarding and consolidation summary message
             A code to identify the forwarding and consolidation
             summary message.
   IFTCCA Forwarding and transport shipment charge calculation message
             A code to identify the forwarding and transport shipment
             charge calculation message.
   IFTDGN Dangerous goods notification message
             A code to identify the dangerous goods notification
             message.
   IFTFCC International transport freight costs and other charges
          message
             A code to identify the international transport freight
             costs and other charges message.
X  IFTIAG Dangerous cargo list message
             A code to identify the dangerous cargo list message.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
   IFTICL Cargo insurance claims message
             A code to identify the cargo insurance claims message.
   IFTMAN Arrival notice message
             A code to identify the arrival notice message.
   IFTMBC Booking confirmation message
             A code to identify the booking confirmation message.
   IFTMBF Firm booking message
             A code to identify the firm booking message.
   IFTMBP Provisional booking message
             A code to identify the provisional booking message.
   IFTMCA Consignment advice message
             A code to identify the consignment advice message.
   IFTMCS Instruction contract status message
             A code to identify the instruction contract status
             message.
   IFTMIN Instruction message
             A code to identify the instruction message.
   IFTRIN Forwarding and transport rate information message
             A code to identify the forwarding and transport rate
             information message.
   IFTSAI Forwarding and transport schedule and availability
          information message
             A code to identify the forwarding and transport schedule
             and availability information message.
   IFTSTA International multimodal status report message
             A code to identify the international multimodal status
             report message.
   IFTSTQ International multimodal status request message
             A code to identify the international multimodal status
             request message.
   IHCEBI Interactive health insurance eligibility and benefits
          inquiry and response
             A code to identify the interactive health insurance
             eligibility and benefits inquiry and response.
   IHCLME Health care claim or encounter request and response -
          interactive message
             A code to identify the health care claim or encounter
             request and response - interactive message.
   IMPDEF EDI implementation guide definition message
             A code to identify the EDI implementation guide
             definition message.
   INFCON Infrastructure condition message
             A code to identify the infrastructure condition message.
   INFENT Enterprise accounting information message
             A code to identify the enterprise accounting information
             message.
   INSDES Instruction to despatch message
             A code to identify the instruction to despatch message.
   INSPRE Insurance premium message
             A code to identify the insurance premium message.
   INSREQ Inspection request message
             A code to identify the inspection request message.
   INSRPT Inspection report message
             A code to identify the inspection report message.
   INVOIC Invoice message
             A code to identify the invoice message.
   INVRPT Inventory report message
             A code to identify the inventory report message.
   IPPOAD Insurance policy administration message
             A code to identify the insurance policy administration
             message.
   IPPOMO Motor insurance policy message
             A code to identify the motor insurance policy message.
   ISENDS Intermediary system enablement or disablement message
             A code to identify the intermediary system enablement or
             disablement message.
   ITRRPT In transit report detail message
             A code to identify the in transit report detail message.
   JAPRES Job application result message
             A code to identify the job application result message.
   JINFDE Job information demand message
             A code to identify the job information demand message.
   JOBAPP Job application proposal message
             A code to identify the job application proposal message.
   JOBCON Job order confirmation message
             A code to identify the job order confirmation message.
   JOBMOD Job order modification message
             A code to identify the job order modification message.
   JOBOFF Job order message
             A code to identify the job order message.
   JUPREQ Justified payment request message
             A code to identify the justified payment request message.
   KEYMAN Security key and certificate management message
             A code to identify the security key and certificate
             management message.
   LEDGER Ledger message
             A code to identify the ledger message.
   LREACT Life reinsurance activity message
             A code to identify the life reinsurance activity message.
   LRECLM Life reinsurance claims message
             A code to identify the life reinsurance claims message.
   MEDPID Person identification message
             A code to identify the person identification message.
   MEDPRE Medical prescription message
             A code to identify the medical prescription message.
   MEDREQ Medical service request message
             A code to identify the medical service request message.
   MEDRPT Medical service report message
             A code to identify the medical service report message.
   MEDRUC Medical resource usage and cost message
             A code to identify the medical resource usage and cost
             message.
   MEQPOS Means of transport and equipment position message
             A code to identify the means of transport and equipment
             position message.
   MOVINS Stowage instruction message
             A code to identify the stowage instruction message.
   MSCONS Metered services consumption report message
             A code to identify the metered services consumption
             report message.
   ORDCHG Purchase order change request message
             A code to identify the purchase order change request
             message.
   ORDERS Purchase order message
             A code to identify the purchase order message.
   ORDRSP Purchase order response message
             A code to identify the purchase order response message.
   OSTENQ Order status enquiry message
             A code to identify the order status enquiry message.
   OSTRPT Order status report message
             A code to identify the order status report message.
   PARTIN Party information message
             A code to identify the party information message.
   PASREQ Travel, tourism and leisure product application status
          request - interactive message
             A code to identify the travel, tourism and leisure
             product application status request - interactive message.
   PASRSP Travel, tourism and leisure product application status
          response - interactive message
             A code to identify the travel, tourism and leisure
             product application status response - interactive
             message.
   PAXLST Passenger list message
             A code to identify the passenger list message.
   PAYDUC Payroll deductions advice message
             A code to identify the payroll deductions advice message.
   PAYEXT Extended payment order message
             A code to identify the extended payment order message.
   PAYMUL Multiple payment order message
             A code to identify the multiple payment order message.
   PAYORD Payment order message
             A code to identify the payment order message.
   PRICAT Price/sales catalogue message
             A code to identify the price/sales catalogue message.
   PRIHIS Pricing history message
             A code to identify the pricing history message.
   PROCST Project cost reporting message
             A code to identify the project cost reporting message.
   PRODAT Product data message
             A code to identify the product data message.
   PRODEX Product exchange reconciliation message
             A code to identify the product exchange reconciliation
             message.
   PROINQ Product inquiry message
             A code to identify the product inquiry message.
   PROSRV Product service message
             A code to identify the product service message.
   PROTAP Project tasks planning message
             A code to identify the project tasks planning message.
   PRPAID Insurance premium payment message
             A code to identify the insurance premium payment message.
   QALITY Quality data message
             A code to identify the quality data message.
   QUOTES Quote message
             A code to identify the quote message.
   RDRMES Raw data reporting message
             A code to identify the raw data reporting message.
   REBORD Reinsurance bordereau message
             A code to identify the reinsurance bordereau message.
   RECADV Receiving advice message
             A code to identify the receiving advice message.
   RECALC Reinsurance calculation message
             A code to identify the reinsurance calculation message.
   RECECO Credit risk cover message
             A code to identify the credit risk cover message.
   RECLAM Reinsurance claims message
             A code to identify the reinsurance claims message.
   RECORD Reinsurance core data message
             A code to identify the reinsurance core data message.
   REGENT Registration of enterprise message
             A code to identify the registration of enterprise
             message.
   RELIST Reinsured objects list message
             A code to identify the reinsured objects list message.
   REMADV Remittance advice message
             A code to identify the remittance advice message.
   REPREM Reinsurance premium message
             A code to identify the reinsurance premium message.
   REQDOC Request for document message
             A code to identify the request for document message.
   REQOTE Request for quote message
             A code to identify the request for quote message.
   RESETT Reinsurance settlement message
             A code to identify the reinsurance settlement message.
   RESMSG Reservation message
             A code to identify the reservation message.
   RESREQ Reservation request - interactive message
             A code to identify the reservation request - interactive
             message.
   RESRSP Reservation response - interactive message
             A code to identify the reservation response - interactive
             message.
   RETACC Reinsurance technical account message
             A code to identify the reinsurance technical account
             message.
   RETANN Announcement for returns message
             A code to identify the announcement for returns message.
   RETINS Instruction for returns message
             A code to identify the instruction for returns message.
   RPCALL Repair call message
             A code to identify the repair call message.
   SAFHAZ Safety and hazard data message
             A code to identify the safety and hazard data message.
   SANCRT International movement of goods governmental regulatory
          message
             A code to identify the international movement of goods
             governmental regulatory message.
   SKDREQ Schedule request - interactive message
             A code to identify the schedule request - interactive
             message.
   SKDUPD Schedule update - interactive message
             A code to identify the schedule update - interactive
             message.
   SLSFCT Sales forecast message
             A code to identify the sales forecast message.
   SLSRPT Sales data report message
             A code to identify the sales data report message.
   SOCADE Social administration message
             A code to identify the social administration message.
   SSIMOD Modification of identity details message
             A code to identify the modification of identity details
             message.
   SSRECH Worker's insurance history message
             A code to identify the worker's insurance history
             message.
   SSREGW Notification of registration of a worker message
             A code to identify the notification of registration of a
             worker message.
   STATAC Statement of account message
             A code to identify the statement of account message.
   STLRPT Settlement transaction reporting message
             A code to identify the settlement transaction reporting
             message.
   SUPCOT Superannuation contributions advice message
             A code to identify the superannuation contributions
             advice message.
   SUPMAN Superannuation maintenance message
             A code to identify the superannuation maintenance
             message.
   SUPRES Supplier response message
             A code to identify the supplier response message.
   TANSTA Tank status report message
             A code to identify the tank status report message.
   TAXCON Tax control message
             A code to identify the tax control message.
   TIQREQ Travel, tourism and leisure information inquiry request -
          interactive message
             A code to identify the travel, tourism and leisure
             information inquiry request - interactive message.
   TIQRSP Travel, tourism and leisure information inquiry response -
          interactive message
             A code to identify the travel, tourism and leisure
             information inquiry response - interactive message.
   TPFREP Terminal performance message
             A code to identify the terminal performance message.
   TSDUPD Timetable static data update - interactive message
             A code to identify the timetable static data update -
             interactive message.
   TUPREQ Travel, tourism and leisure data update request -
          interactive message
             A code to identify the travel, tourism and leisure data
             update request - interactive message.
   TUPRSP Travel, tourism and leisure data update response -
          interactive message
             A code to identify the travel, tourism and leisure data
             update response - interactive message.
   UTILMD Utilities master data message
             A code to identify the utilities master data message.
   UTILTS Utilities time series message
             A code to identify the utilities time series message.
   VATDEC Value added tax message
             A code to identify the value added tax message.
   VESDEP Vessel departure message
             A code to identify the vessel departure message.
   WASDIS Waste disposal information message
             A code to identify the waste disposal information
             message.
   WKGRDC Work grant decision message
             A code to identify the work grant decision message.
   WKGRRE Work grant request message
             A code to identify the work grant request message.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0073  First and last transfer

  Desc: Indication used for the first and last message in a sequence
        of messages related to the same topic.

  Repr: a1

   C      Creation
             First transmission of a number of transfers of the same
             message.
   F      Final
             Last transmission of a number of transfers of the same
             message.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0081  Section identification

  Desc: Identification of the separation of sections of a message.

  Repr: a1

   D      Header/detail section separation
             To qualify the segment UNS, when separating the header
             from the detail section of a message.
   S      Detail/summary section separation
             To qualify the segment UNS, when separating the detail
             from the summary section of a message.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0083  Action, coded

  Desc: A code indicating acknowledgement, or rejection (the action
        taken) of a subject interchange, or part of the subject
        interchange, or indication of interchange receipt.

  Repr: an..3

   4      This level and all lower levels rejected
             The corresponding referenced-level and all its lower
             referenced-levels are rejected. One or more errors are
             reported at this reporting-level or a lower
             reporting-level.
   7      This level acknowledged and all lower levels acknowledged if
          not explicitly rejected
             The corresponding referenced-level is acknowledged. All
             messages, packages, or groups at the lower
             referenced-levels are acknowledged except those
             explicitly reported as rejected at their reporting-level
             in this CONTRL message.
   8      Interchange received
             Indication of interchange receipt.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0085  Syntax error, coded

  Desc: A code indicating the error detected.

  Repr: an..3

   2      Syntax version or level not supported
             Notification that the syntax version and/or level is not
             supported by the recipient.
   7      Interchange recipient not actual recipient
             Notification that the Interchange recipient (S003) is
             different from the actual recipient.
   12     Invalid value
             Notification that the value of a stand-alone data
             element, composite data element or component data element
             does not conform to the relevant specifications for the
             value.
   13     Missing
             Notification that a mandatory (or otherwise required)
             service or user segment, data element, composite data
             element or component data element is missing.
   14     Value not supported in this position
             Notification that the recipient does not support use of
             the specific value of an identified stand-alone data
             element, composite data element or component data element
             in the position where it is used. The value may be valid
             according to the relevant specifications and may be
             supported if it is used in another position.
   15     Not supported in this position
             Notification that the recipient does not support use of
             the segment type, stand-alone data element type,
             composite data element type or component data element
             type in the identified position.
   16     Too many constituents
             Notification that the identified segment contained too
             many data elements or that the identified composite data
             element contained too many component data elements.
   17     No agreement
             No agreement exists that allows receipt of an
             interchange, group, message, or package with the value of
             the identified stand-alone data element, composite data
             element or component data element.
   18     Unspecified error
             Notification that an error has been identified, but the
             nature of the error is not reported.
X  19     Invalid decimal notation
             Notification that the character indicated as decimal
             notation in UNA is invalid, or the decimal notation used
             in a data element is not consistent with the one
             indicated in UNA.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
   20     Character invalid as service character
             Notification that a character advised in UNA is invalid
             as service character.
   21     Invalid character(s)
             Notification that one or more character(s) used in the
             interchange is not a valid character as defined by the
             syntax identifier indicated in UNB. The invalid character
             is part of the referenced-level, or followed immediately
             after the identified part of the interchange.
   22     Invalid service character(s)
             Notification that the service character(s) used in the
             interchange is not a valid service character as advised
             in UNA or not one of the default service characters. If
             the code is used in UCS or UCD, the invalid character
             followed immediately after the identified part of the
             interchange.
   23     Unknown Interchange sender
             Notification that the Interchange sender (S002) is
             unknown.
   24     Too old
             Notification that the received interchange or group is
             older than a limit specified in an IA or determined by
             the recipient.
   25     Test indicator not supported
             Notification that test processing can not be performed
             for the identified interchange, group, message, or
             package.
   26     Duplicate detected
             Notification that a possible duplication of a previously
             received interchange, group, message, or package has been
             detected. The earlier transmission may have been
             rejected.
X  27     Security function not supported
             Notification that a security function related to the
             referenced-level or data element is not supported.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
   28     References do not match
             Notification that the control reference in UNB, UNG, UNH,
             UNO, USH or USD does not match the one in UNZ, UNE, UNT,
             UNP, UST or USU, respectively.
   29     Control count does not match number of instances received
             Notification that the number of groups, messages, or
             segments does not match the number given in UNZ, UNE, 
             UNT or UST, or that the length of an object or of
             encrypted data is not equal to the length stated in the
             UNO, UNP, USD, or USU.
   30     Groups and messages/packages mixed
             Notification that groups have been mixed with
             messages/packages outside of groups in the interchange.
X  31     More than one message type in group
             Notification that different message types are contained
             in a functional group.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
   32     Lower level empty
             Notification that the interchange does not contain any
             messages, packages, or groups, or a group does not
             contain any messages or packages.
   33     Invalid occurrence outside message, package, or group
             Notification of an invalid segment or data element in the
             interchange, between messages or between packages or
             between groups. Rejection is reported at the level above.
X  34     Nesting indicator not allowed
             Notification that explicit nesting has been used in a
             message where it shall not be used.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
   35     Too many data element or segment repetitions
             Notification that a stand-alone data element, composite
             data element or segment is repeated too many times.
   36     Too many segment group repetitions
             Notification that a segment group is repeated too many
             times.
   37     Invalid type of character(s)
             Notification that one or more numeric characters are used
             in an alphabetic (component) data element or that one or
             more alphabetic characters are used in a numeric
             (component) data element.
X  38     Missing digit in front of decimal sign
             Notification that a decimal sign is not preceded by one
             or more digits.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
   39     Data element too long
             Notification that the length of the data element received
             exceeded the maximum length specified in the data element
             description.
   40     Data element too short
             Notification that the length of the data element received
             is shorter than the minimum length specified in the data
             element description.
X  41     Permanent communication network error
             Notification that a permanent error was reported by the
             communication network used for transfer of the
             interchange. Re-transmission of an identical interchange
             with the same parameters at network level will not
             succeed.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
X  42     Temporary communication network error
             Notification that a temporary error was reported by the
             communication network used for transfer of the
             interchange. Re-transmissions of an identical interchange
             may succeed.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
X  43     Unknown interchange recipient
             Notification that the interchange recipient is not known
             by a network provider.
          Note:
             1. This code value will be removed effective with the
             first release of the service code list in 2003.
   45     Trailing separator
             Notification of one of the following:
             - the last character before the segment terminator is a
             data element separator or a component data element
             separator or a repeating data element separator, or
             - the last character before a data element separator is a
             component data element separator or a repeating data
             element separator.
   46     Character set not supported
             Notification that one or more characters used are not in
             the character set defined by the syntax identifier, or
             the character set identified by the escape sequence for
             the code extension technique is not supported by the
             recipient.
   47     Envelope functionality not supported
             Notification that the envelope structure encountered is
             not supported by the recipient.
   48     Dependency condition violated
             Notification that an error condition has occurred as the
             result of a dependency condition violation.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0113  Message type sub-function identification

  Desc: Code identifying a sub-function of a message type.

  Repr: an..6

  Note 1: The code qualifies the message type data element (0065) to
          allow the recipient to identify a specific sub-function of a
          message.

   AA     Interactive, perform sell
             This sub-function is to notify the receiver that the
             purpose of the message is an instruction to perform a
             sell.
   AB     Interactive, modify current dialogue data
             This sub-function is to notify the receiver that the
             message data is a modification to data previously sent in
             the current interactive dialogue.
   AC     Interactive, modify previous dialogue data
             This sub-function is to notify the receiver that the
             message data is a modification to data sent in a previous
             interactive dialogue.
   AD     Interactive, cancel reserved product
             This sub-function is to notify the receiver that the
             purpose of the message is to cancel a product previously
             reserved in an interactive dialogue.
   AE     Interactive, ignore reserved product
             This sub-function is to notify the receiver that the
             purpose of the message is to ignore a product previously
             reserved in an interactive dialogue.
   AF     Interactive, conclude current reservation
             This sub-function is to notify the receiver that the
             purpose of the message is to conclude the current
             reservation transaction.
   AG     Interactive, display reserved product
             This sub-function is to notify the receiver that the
             purpose of the message is to display a product previously
             reserved in an interactive dialogue.
   AH     Interactive, perform reference sell
             This sub-function is to notify the receiver that the
             purpose of the message is an instruction to perform a
             sell, based on data returned in a previous interactive
             response.
   AI     Interactive, modify previous dialogue reservation
             This sub-function is to notify the receiver that the
             purpose of the message is to modify a reservation, made
             during a previous interactive dialogue.
   AJ     Interactive, display voucher template
             This sub-function is to notify the receiver that the
             purpose of the message is to display the template for a
             voucher.
   AK     Interactive, print voucher
             This sub-function is to notify the receiver that the
             purpose of the message is to print a voucher.
   AL     Interactive, cancel current dialogue reservation
             This sub-function is to notify the receiver that the
             purpose of the message is to cancel a reservation made
             during the current interactive dialogue.
   AM     Interactive, cancel previous dialogue reservation
             This sub-function is to notify the receiver that the
             purpose of the message is to cancel a reservation made
             during a previous interactive dialogue.
   AN     Interactive, duplicate sell message
             This sub-function is to notify the receiver that the
             message is a duplicate of a previously sent interactive
             sell message.
   AO     Interactive, duplicate modify current dialogue data
             This sub-function is to notify the receiver that the
             message is a duplicate of a previously sent message to
             modify data in the current interactive dialogue.
   AP     Interactive, duplicate modify previous dialogue reservation
             This sub-function is to notify the receiver that the
             message is a duplicate of a previously sent message to
             modify a reservation made during a previous interactive
             dialogue.
   AQ     Interactive, availability request, multiple suppliers
             This sub-function is to notify the receiver that the
             message is an interactive request for availability which
             is simultaneously being sent to multiple suppliers.
   AR     Interactive, availability request, one specific supplier
             This sub-function is to notify the receiver that the
             message is an interactive request for availability from
             only one specific supplier.
   AS     Interactive, product rules request
             This sub-function is to notify the receiver that the
             message is an interactive request for product rules.
   SECACK Security acknowledgment
             This sub-function of the AUTACK message is for the secure
             acknowledgement of receipt, including the reporting of
             any associated security violation(s).
   SECAUT Security authentication and/or non-repudiation of origin
             This sub-function of the AUTACK message is for secure
             integrity, authentication and/or non-repudiation of
             origin.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0133  Character encoding, coded

  Desc: Coded identification of the character encoding used in the
        interchange.

  Repr: an..3

  Note 1: To be used as specified in the partners' interchange
          agreement, for the purpose of identifying the character
          repertoire encoding technique used in the interchange (when
          the default encoding defined by the character repertoire's
          associated character set specification is not used).

   1      ASCII 7 bit
             ASCII 7 bit code.
   2      ASCII 8 bit
             ASCII 8 bit code.
   3      Code page 500 (EBCDIC Multinational No. 5)
             Encoding schema for the repertoire as defined by the code
             page.
   4      Code page 850 (IBM PC Multinational)
             Encoding schema for the repertoire as defined by the code
             page.
   5      UCS-2
             Universal Multiple-Octet Coded Character Set (UCS)
             two-octet per character encoding schema as defined in
             ISO/IEC 10646-1.
   6      UCS-4
             Universal Multiple-Octet Coded Character Set (UCS)
             four-octet per character encoding schema as defined in
             ISO/IEC 10646-1.
   7      UTF-8
             UCS Transformation Format 8 (UTF-8) multi-octet (of
             length one to six octets) per character encoding schema
             as defined in ISO/IEC 10646-1, Annex R.
   8      UTF-16
             UCS Transformation Format 16 (UTF-16) two-octet per
             character encoding schema as defined in ISO/IEC 10646-1,
             Annex Q.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0135  Service segment tag, coded

  Desc: Code identifying a service segment.

  Repr: an..3

   UCD    Data element error indication
             To identify an erroneous stand-alone, composite or
             component data element, and to identify the nature of the
             error.
   UCF    Group response
             To identify a group in the subject interchange and to
             indicate acknowledgement or rejection (action taken) of
             the UNG and UNE segments, and to identify any error
             related to these segments. It can also identify errors
             related to the USA, USC, USD, USH, USR, UST, or USU
             security segments when they appear at the group level.
             Depending on the action code, it may also indicate the
             action taken on the messages and packages within that
             group.
   UCI    Interchange response
             To identify the subject interchange, to indicate
             interchange receipt, to indicate acknowledgement or
             rejection (action taken) of the UNA, UNB and UNZ
             segments, and to identify any error related to these
             segments. It can also identify errors related to the USA,
             USC, USD, USH, USR, UST, or USU security segments when
             they appear at the interchange level. Depending on the
             action code, it may also indicate the action taken on the
             groups, messages, and packages within that interchange.
   UCM    Message/package response
             To identify a message or package in the subject
             interchange, and to indicate that message's or package's
             acknowledgement or rejection (action taken), and to
             identify any error related to the UNH, UNT, UNO, and UNP
             segments. It can also identify errors related to the USA,
             USC, USD, USH, USR, UST, or USU security segments when
             they appear at the message or package level.
   UCS    Segment error indication
             To identify either a segment containing an error or a
             missing segment, and to identify any error related to the
             complete segment.
   UGH    Anti-collision segment group header
             To head, identify and specify an anti-collision segment
             group.
   UGT    Anti-collision segment group trailer
             To end and check the completeness of an anti-collision
             segment group.
   UIB    Interactive interchange header
             To head and identify an interchange.
   UIH    Interactive message header
             To head, identify and specify a message.
   UIR    Interactive status
             To report the status of the dialogue.
   UIT    Interactive message trailer
             To end and check the completeness of a message.
   UIZ    Interactive interchange trailer
             To end and check the completeness of an interchange.
   UNB    Interchange header
             To identify an interchange.
   UNE    Group trailer
             To end and check the completeness of a group.
   UNG    Group header
             To head, identify and specify a group of messages and/or
             packages, which may be used for internal routing and
             which may contain one or more message types and/or
             packages.
   UNH    Message header
             To head, identify and specify a message.
   UNO    Object header
             To head, identify and specify an object.
   UNP    Object trailer
             To end and check the completeness of an object.
   UNS    Section control
             To separate header, detail and summary sections of a
             message.
   UNT    Message trailer
             To end and check the completeness of a message.
   UNZ    Interchange trailer
             To end and check the completeness of an interchange.
   USA    Security algorithm
             To identify a security algorithm, the technical usage
             made of it, and to contain the technical parameters
             required.
   USB    Secured data identification
             To contain details related to the AUTACK.
   USC    Certificate
             To convey the public key and the credentials of its
             owner.
   USD    Data encryption header
             To specify size (i.e. length of data in octets of bits)
             of encrypted data following the segment terminator of
             this segment.
   USE    Security message relation
             To specify the relation to earlier security messages,
             such as response to a particular request, or request for
             a particular answer.
   USF    Key management function
             To specify the type of key management function and the
             status of a corresponding key or certificate.
   USH    Security header
             To specify a security mechanism applied to a EDIFACT
             structure (i.e.: either message/package, group or
             interchange).
   USL    Security list status
             To specify the status of security objects, such as keys
             or certificates to be delivered in a list, and the
             corresponding list parameters.
   USR    Security result
             To contain the result of the security mechanisms.
   UST    Security trailer
             To establish a link between security header and security
             trailer segment groups.
   USU    Data encryption trailer
             To provide a trailer for the encrypted data.
   USX    Security references
             To refer to the secured EDIFACT structure and its
             associated date and time.
   USY    Security on references
             To identify the applicable header, and to contain the
             security result and/or to indicate the possible cause of
             security rejection for the referred value.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0323  Transfer position, coded

  Desc: Indication of the position of a transfer.

  Repr: a1

   F      First message
             First message in sequence. Can only appear once at the
             start of the sequence.
   I      Intermediate message
             Intermediate message in sequence. May appear zero or more
             times within the sequence.
   L      Last message
             Last message in sequence. Can appear only once at the end
             of the sequence.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0325  Duplicate Indicator

  Desc: Indication that the structure is a duplicate of a previously
        sent structure.

  Repr: a1

   D      Duplicate
             A duplicate transfer.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0331  Report function, coded

  Desc: Coded value identifying type of status or error report.

  Repr: an..3

   1      Information
             Non Error information, e.g. acknowledgement that party is
             still operational.
   2      Warning
             Warning, e.g. resources getting low.
   3      Non-fatal error
             Non-fatal error detected by party sending the UIR.
             Dialogue integrity may be compromised.
   4      Abort dialogue
             Established dialogue cannot continue.
   5      Query status
             Request for a status report from other party. Should be
             answered with a 'Status report' (see code value '6'
             below).
   6      Status report
             Reporting status of dialogue as perceived by sending
             party.
   7      Pause dialogue
             Advise other party to stop transferring data within this
             dialogue until a 'Continue dialogue' is received.
   8      Continue dialogue
             Advise that data flow may continue after being 'Paused'
             (see code value '7' above).
   9      Start dialogue reject
             Dialogue cannot be initiated.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0333  Report reason, coded

  Desc: Code identifying the reason for the status or error report.

  Repr: an..3

   1      OK response
             No further information.
   2      Syntax error
             Error detected in syntax.
   3      Invalid header
             Invalid header segment received.
   4      Invalid trailer segment
             Invalid trailer segment received.
   5      Unsupported syntax
             Syntax version/release not supported.
   6      Unsupported scenario type
             Scenario type not supported.
   7      Unsupported scenario version
             Scenario version/release not supported.
   8      Unsupported dialogue type
             Dialogue type not supported for this scenario.
   9      Unsupported dialogue version
             Dialogue type version/release not supported.
   10     Unauthorised sender
             Sender not authorised.
   11     Sender rejected
             Sender rejected for administrative reasons.
   12     Multiple transactions unsupported
             Multiple parallel transactions not supported.
   13     Multiple dialogues unsupported
             Multiple parallel dialogues not supported.
   14     Resources unavailable
             Resources unavailable for requested function.
   15     Unknown transaction
             Referenced transaction does not exist.
   16     Unknown dialogue
             Referenced dialogue does not exist.
   17     Invalid function
             Function invalid for current dialogue state.
   18     Service unavailable
             Requested service is unavailable.
   19     Application unavailable
             Requested application not available.
   20     Time-out
             Response not received within expected time.
   21     Unable to process interactively
             To notify the initiator that a specific request cannot be
             processed interactively.
   22     Correctable application error
             To notify the initiator that an application error, that
             is correctable by the initiator, was made in the request
             message.
   23     Nothing to return
             To notify the initiator that there is no information to
             return in response to an inquiry.
   24     Data not accessible
             To notify the initiator that the requested information
             cannot be returned.
   25     Non-correctable application error
             To notify the initiator that some type of system or
             processing error was encountered, not related to the data
             received.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0501  Security service, coded

  Desc: Specification of the security service applied.

  Repr: an..3

   1      Non-repudiation of origin
             The message includes a digital signature protecting the
             receiver of the message from the sender's denial of
             having sent the message.
   2      Message origin authentication
             The actual sender of the message cannot claim to be some
             other (authorised) entity.
   3      Integrity
             The message content is protected against the modification
             of data.
   4      Confidentiality
             The message content is protected against the unauthorised
             reading, copying or disclosure of its content.
   5      Non-repudiation of receipt
             Non-repudiation of receipt protects the sender of an
             object message from the receiver's denial of having
             received the message.
   6      Receipt authentication
             Receipt authentication assures the sender that the
             message has been received by the authenticated recipient.
   7      Referenced EDIFACT structure non-repudiation of origin
             The referenced EDIFACT structure is secured by a digital
             signature protecting the receiver of the message from the
             sender's denial of  having sent the message.
   8      Referenced EDIFACT structure origin authentication
             The actual sender of the referenced EDIFACT structure
             cannot claim to be some other (authorised) party.
   9      Referenced EDIFACT structure integrity
             The referenced EDIFACT structure content is protected
             against the modification of data.
   10     Time stamping request
             Ask for the EDIFACT structure to be time stamped.
   11     Entity authentication
             The initiator and/or responder cannot claim to be another
             party.
   12     Entity authentication with key establishment
             The initiator and/or responder cannot claim to be another
             party, and security keys are established.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0503  Response type, coded

  Desc: Specification of the type of response expected from the
        recipient.

  Repr: an..3

   1      No acknowledgement required
             No AUTACK acknowledgement message expected.
   2      Acknowledgement required
             AUTACK acknowledgement message expected.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0505  Filter function, coded

  Desc: Identification of the filtering function used to reversibly
        map any bit pattern on to a restricted character set.

  Repr: an..3

   1      No filter
             No filter function is used.
   2      Hexadecimal filter
             Hexadecimal filter.
   3      ISO 646 filter
             ASCII filter as described in DIS 10126-1.
   4      ISO 646 Baudot filter
             Baudot filter as described in DIS 10126-1.
   5      UN/EDIFACT EDA filter
             Filter function for UN/EDIFACT character set repertoire A
             as described in Part 5 of ISO 9735.
   6      UN/EDIFACT EDC filter
             Filter function for UN/EDIFACT character set repertoire A
             as described in Part 5 of ISO 9735.
   7      Base 64 filter
             Base 64 filter function as described in RFC 1521.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0507  Original character set encoding, coded

  Desc: Identification of the character set in which the secured
        EDIFACT structure was encoded when security mechanisms were
        applied.

  Repr: an..3

   1      ASCII 7 bit
             ASCII 7 bit code.
   2      ASCII 8 bit
             ASCII 8 bit code.
   3      Code page 850 (IBM PC Multinational)
             Encoding schema for the repertoire as defined by the code
             page.
   4      Code page 500 (EBCDIC Multinational No. 5)
             Encoding schema for the repertoire as defined by the code
             page.
   5      UCS-2
             Universal Multiple-Octet Coded Character Set (UCS)
             two-octet per character encoding schema as defined in
             ISO/IEC 10646-1.
   6      UCS-4
             Universal Multiple-Octet Coded Character Set (UCS)
             four-octet per character encoding schema as defined in
             ISO/IEC 10646-1.
   7      UTF-8
             UCS Transformation Format 8 (UTF-8) multi-octet (of
             length one to six octets) per character encoding schema
             as defined in ISO/IEC 10646-1, Annex R.
   8      UTF-16
             UCS Transformation Format 16 (UTF-16) two-octet per
             character encoding schema as defined in ISO/IEC 10646-1,
             Annex Q.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0509  Role of security provider, coded

  Desc: Identification of the role of the security provider in
        relation to the secured item.

  Repr: an..3

   1      Issuer
             The security provider is the rightful issuer of the
             signed document.
   2      Notary
             The security provider acts as a notary in relation to the
             signed document.
   3      Contracting party
             The security provider endorses the content of the signed
             document.
   4      Witness
             The security provider is a witness, but is not
             responsible for  the content of the signed document.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0513  Security party code list qualifier

  Desc: Identification of the type of identification used to register
        the security parties.

  Repr: an..3

   1      ACH
             Automated clearing house identification.
   2      EAN
             European Association for Numbering.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0515  Security party code list responsible agency, coded

  Desc: Identification of the agency in charge of registration of the
        security parties.

  Repr: an..3

   1      UN/CEFACT
             United Nations Centre for Trade Facilitation and
             Electronic Business (UN/CEFACT).
   2      ISO
             International Organization for Standardization.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0517  Date and time qualifier

  Desc: Specification of the type of date and time.

  Repr: an..3

   1      Security Timestamp
             Security timestamp of the secured message.
   2      Certificate generation date and time
             Identifies the date and time of generation of the
             certificate by the Certification Authority.
   3      Certificate start of validity period
             Identifies the date and time from which the certificate
             must be considered valid.
   4      Certificate end of validity period
             Identifies the date and time until which the certificate
             must be considered valid.
   5      EDIFACT structure generation date and time
             Date and time of generation of the secured EDIFACT
             structure.
   6      Certificate revocation date and time
             Identifies the date and time of revocation of the
             certificate by the Certification Authority.
   7      Key generation date and time
             Identifies the date and time of generation of the key(s).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0523  Use of algorithm, coded

  Desc: Specification of the usage made of the algorithm.

  Repr: an..3

   1      Owner hashing
             Specifies that the algorithm is used by the message
             sender to compute the hash function on the message (as in
             the case of Integrity or Non-repudiation of Origin
             identified in the security function qualifier of USH).
   2      Owner symmetric
             Specifies that the algorithm is used by the message
             sender either for integrity, confidentiality, or message
             origin authentication (specified by security service,
             coded in USH).
   3      Issuer signing
             Specifies that the algorithm is used by the Certificate
             Issuer (CA) to sign the hash result computed on the
             certificate.
   4      Issuer hashing
             Specifies that the algorithm is used by the Certificate
             Issuer (CA) to compute the hash result on the
             certificate.
   5      Owner enciphering
             Specifies that the algorithm is used by the message
             sender to encrypt a symmetric key.
   6      Owner signing
             Specifies that the algorithm is used by the message
             sender to sign either the hash result computed on the
             message or the symmetric keys.
   7      Owner enciphering or signing
             Specifies that the algorithm may be used by the message
             sender either to encrypt a symmetric key or sign the hash
             result computed on the  message. This value may only be
             used in a USA segment within a USC segment group. When
             encrypting a symmetric key a receiver certificate shall
             be used. When signing a hash result a sender certificate
             shall be used.
   8      Owner compressing
             Specifies that the algorithm is used by the message
             sender to compress the data before (encryption and)
             submission.
   9      Owner compression integrity
             Specifies that the algorithm is used by the message
             sender on the compressed data before (encryption and)
             submission. The integrity value is used to verify the
             contents of the compressed text before expansion.
   10     Key agreement
             Specifies that the algorithm is used by the initiator and
             responder to agree a secret key.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0525  Cryptographic mode of operation, coded

  Desc: Specification of the mode of operation used for the algorithm.

  Repr: an..3

   1      ECB
             DES modes of operation, Electronic Code Book; FIPS Pub 81
             (1981); ANSI X3.106; IS 8372 (64 bits); ISO 10116
             (n-bits).
   2      CBC
             DES modes of operation, Cipher Block Chaining; FIPS Pub
             81 (1981); ANSI X3.106; IS 8372 (64 bits); ISO 10116
             (n-bits).
   3      CFB1
             DES modes of operation, Cipher feedback; FIPS Pub 81
             (1981); ANSI X3.106; IS 8372 (64 bits); ISO 10116 (n-
             bits).
   4      CFB8
             DES modes of operation, Cipher feedback; FIPS Pub 81
             (1981); ANSI X3.106; IS 8372 (64 bits); ISO 10116 (n-
             bits).
   5      OFB
             DES modes of operation; FIPS Pub 81 (1981); IS 8372 (64
             bits); ISO 10116 (n-bits).
X  6      MAC
             Message Authentication Code ISO 8731-1, using DES CBC
             mode.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  7      DIM1
             Data integrity mechanism using a cryptographic check
             function; ISO DIS 9797, first method.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  8      DIM2
             Data integrity mechanism using a cryptographic check
             function; ISO DIS 9797, second method.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  9      MDC2
             Modification Detection Code - IBM System Journal, vol 30,
             no 2, 1991.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  10     HDS1
             Hash functions - Part 1 : Hash functions using a n-bit
             block cipher algorithm providing a single length hash
             code. ISO CD 10118-1.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  11     HDS2
             Hash functions - Part 2 : Hash functions using a n-bit
             block cipher algorithm providing a double length hash
             code. ISO CD 10118-2.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  12     SQM
             Square-mod-n hash function for RSA. Annex D, ITU X 509,
             ISO 9594-8.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  13     NVB7.1
             Dutch Standard hash function for banking.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  14     NVBAK
             Dutch Banking Standard, NVB Authenticity Mark, published
             by the NVB, May 1992.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
X  15     MCCP
             Banking key management by means of asymmetric algorithms,
             algorithms using the RSA cryptosystem. Signature
             construction by means of a separate signature. ISO
             11166-2.
          Note:
             1. This code value will be removed effective with the
             second release of the service code list in 2002.
   16     DSMR
             Digital Signature scheme giving Message Recovery. ISO
             9796.
   17     CFB64
             DES mode of operation, cipher feedback; ISO 10116
             (n-bits).
   23     TCBC
             TDEA mode of operation, Cipher Block Chaining, ANSI
             X9.52.
   24     TCBC-I
             TDEA mode of operation, Cipher Block Chaining -
             Interleaved, ANSI X9.52.
   25     TCFB1
             TDEA mode of operation, Cipher Feedback - 1 bit feedback,
             ANSI X9.52.
   26     TCFB8
             TDEA mode of operation, Cipher Feedback - 8 bit feedback,
             ANSI X9.52.
   27     TCFB64
             TDEA mode of operation, Cipher Feedback - 64 bit
             feedback, ANSI X9.52.
   28     TCFB1-P
             TDEA mode of operation, Cipher Feedback Pipelined - 1 bit
             feedback, ANSI X9.52.
   29     TCFB8-P
             TDEA mode of operation, Cipher Feedback Pipelined - 8 bit
             feedback, ANSI X9.52.
   30     TCFB64-P
             TDEA mode of operation, Cipher Feedback Pipelined - 64
             bit feedback, ANSI X9.52.
   31     TOFB
             TDEA mode of operation, Output Feedback Mode, ANSI X9.52.
   32     TOFB-P
             TDEA mode of operation, Output Feedback Mode Pipelined,
             ANSI X9.52.
   33     TCBCM
             TDEA mode of operation, Cipher Block Chaining with output
             feedback Masking, ANSI X9.52.
   34     TCBCM-I
             TDEA mode of operation, Cipher Block Chaining with output
             feedback Masking Interleaved, ANSI X9.52.
   35     TECB
             TDEA mode of operation, Electronic Cookbook Mode, ANSI
             X9.52.
   36     CTS
             RC5 mode of operation, Cipher Text Stealing, Published in
             RCF 2040.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0527  Algorithm, coded

  Desc: Identification of the algorithm.

  Repr: an..3

   1      DES
             Data Encryption Standard. FIPS Pub 46 (January 1977).
   2      MAA
             Message Authentication Algorithm. Banking-Approved
             Algorithms for message Authentication. ISO 8731-2.
   3      FEAL
             FEAL Fast Data Encipherment Algorithm.
   4      IDEA
             International Data Encryption Algorithm: Lai X., Massey
             J. ""A Proposal for a New Block Encryption Standard"",
             Proceedings of Eurocrypt'90, LNCS vol 473,
             Springer-Verlag, Berlin 1991, and Lai X., Massey J.
             ""Markov Ciphers and Differential Cryptanalysis"",
             Proceedings of Eurocrypt'91, LNCS vol 547,
             Springer-Verlag, Berlin 1991.
   5      MD4
             The MD4 Message digest algorithm. Rivest R. RSA Data
             Security Inc. (1990).
   6      MD5
             The MD5 Message digest algorithm. Rivest R. Dusse S. RSA
             Data Security Inc. (1991).
   7      RIPEMD
             Extension of the MD4 - Ripe Report CS - R9324, April 93.
   8      SHA
             Secure Hashing Algorithm.
   9      AR/DFP
             Hash function of the German banking industry, submitted
             to ISO/IEC JTC 1/SC 27/WG 2, Doc N179.
   10     RSA
             Rivest, Shamir, Adleman: A Method for obtaining Digital
             Signatures and Public Key Cryptosystems.  Communications
             of the ACM, Vol.21(2), pp 120-126 (1978).
   11     DSA
             Digital Signature Algorithm/Digital Signature Standard
             NIST Pub 1993 Draft.
   12     RAB
             Rabin, "Digitalized signatures and public-key functions
             as intractable as factorization", MIT Laboratory for
             Computer Science Technical Report LCS/TR-212, Cambridge,
             Mass, 1979.
   13     TDEA
             Triple Data Encryption Algorithm; ANSI X9.52.
   14     RIPEMD-160
             Dedicated Hash-Function #1; ISO 10118-3.
   15     RIPEMD-128
             Dedicated Hash-Function #2; ISO 10118-3.
   16     SHA1
             Secure Hash Algorithm, dedicated Hash-Function #3; ISO
             10118-3.
   17     ECC
             Elliptic Curve Algorithm, Draft IEEE P1363 standard.
   18     ZLIB
             Data compression algorithm; Deflate/inflate algorithm
             published in RFC1950, RFC1951 and RFC1952.
   20     INFOZIP
             Data compression algorithm.
   21     OLZW
             Data compression algorithm; Optimized LZW; Published in
             'Dr. Dobb's Journal' (Jun 1990).
   22     ARITCODE
             Data compression algorithm; Arithmetic coding; Published
             in 'Comm. Of the ACM' (Jun 1987).
   23     SHUFF
             Data compression algorithm; Static Huffman; Published in
             'Proceedings of the I.R.E.' (Sep. 1952).
   24     DHUFF
             Data compression algorithm; Dynamic Huffman; Published in
             'ACM Transaction on Mathematical Software' (Jun 1989).
   25     CRC-32
             Cyclic Redundancy Check - 32-bit; Ethernet CRC.
   26     CRC-CCITT
             Cyclic Redundancy Check - 16-bit.
   27     ISO12042
             Data compression for information exchange - Binary
             arithmetic coding algorithm; ISO-12042.
   28     RC4
             Variable-Key Size Symmetric Stream Cipher, specified by
             RSA Security Inc.
   29     RC5
             Variable-Key Size Symmetric Block Cipher, published in
             RFC 2040.
   30     HMAC-SHA1
             Message Authentication using keyed SHA-1 (published in
             RFC 2104).
   31     HMAC-MD5
             Message Authentication using keyed MD5 (published in RFC
             2104).
   32     HMAC-RIPEMD-160
             Messahe Authentication using keyed RIPEMD-160 (published
             in RFC 2104).
   33     HMAC-RIPEMD-128
             Message Authentication using keyed RIPEMD-128 (published
             in RFC 2104).
   34     DB-MACv3
             MAC calculation (variant 3), using RIPEMD-160 and triple
             DES (published by Deutsche Bundesbank 1998).
   35     LZ77
             Lempel Ziv, 1977 data compression algorithm.
   36     LZW
             Lempel Ziv Welch data compression algorithm.
   37     MAC-ISO 8731-1
             Message authentication code defined in ISO 8731, Part 1.
   38     DIM1
             Data integrity mechanism using a cryptographic check
             function; ISO DIS 9797, first method.
   39     DIM2
             Data integrity mechanism using a cryptographic check
             function; ISO DIS 9797, second method.
   40     MDC2
             Modification detection code, IBM System Journal, vol 13,
             #2, 1991.
   41     HDS1
             ISO CD 10118-1, hash functions -part 1; hash functions
             using an n-bit block cipher algorithm providing a single
             length hash code.
   42     HDS2
             ISO CD 10118-1, hash functions -part 1; hash functions
             using an n-bit block cipher algorithm providing a double
             length hash code.
   43     SQM
             ISO 9594-8. Square-Mod-N hash function for RSA.
   44     NVB 7.1
             Dutch banking standard for hashing and signing using RSA.
   45     PKCS#1-v2_MGF1
             Mask Generation Function defined in PKCS#1, Version 2.
   46     NVBAK
             Dutch banking standard, NVB Authenticity Mark,  published
             by the NVB, May 1992.
   47     MCCP
             Banking key management by means of asymmetric algorithms,
             algorithms using the RSA cryptosystem. Signature
             construction by means of a separate signature. ISO
             11166-2.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0529  Algorithm code list identifier

  Desc: Specification of the code list used to identify the algorithm.

  Repr: an..3

   1      UN/CEFACT
             United Nations Centre for Trade Facilitation and
             Electronic Business (UN/CEFACT).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0531  Algorithm parameter qualifier

  Desc: Specification of the type of parameter value.

  Repr: an..3

   1      Initialisation value, clear text
             Identifies the algorithm parameter value as an
             unencrypted initialisation value.
   2      Initialisation value, encrypted under a symmetric key
             Identifies the algorithm parameter value as an
             initialisation value which is encrypted under the
             symmetric data key.
   3      Initialisation value, encrypted under a public key
             Identifies the algorithm parameter value as an
             initialisation value encrypted under the public key of
             the  receiving party.
   4      Initialisation value, format mutually agreed
             Identifies the algorithm parameter value as an
             initialisation value in a format agreed between the two
             parties.
   5      Symmetric key, encrypted under a symmetric key
             Identifies the algorithm parameter value as a symmetric
             key which is encrypted with a previously agreed algorithm
             under a previously exchanged symmetric key.
   6      Symmetric key, encrypted under a public key
             Identifies the algorithm parameter value as a symmetric
             key encrypted under the public key of the  receiving
             party.
   7      Symmetric key, signed and encrypted
             Identifies the algorithm parameter value as a symmetric
             key signed under the sender's secret key, then encrypted
             under the receiver's public key.
   8      Symmetric key encrypted under an asymmetric key common to
          the sender and the receiver
             Identifies the algorithm parameter value as a symmetric
             key encrypted under an asymmetric key common to the
             sender and the receiver (use of Diffie and Hellman
             scheme, for instance).
   9      Symmetric key name
             Identifies the algorithm parameter value as the name of a
             symmetric key. This may be used in the case where a key
             relationship has already been established between the
             sender and receiver.
   10     Key encrypting key name
             Identifies the parameter value as the name of a key
             encrypting key.
   11     Symmetric key, format mutually agreed
             Identifies the algorithm parameter value as a symmetric
             key in a format agreed between the two parties.
   12     Modulus
             Identifies the algorithm parameter value as the modulus
             of a public key which is to be used according to the
             function defined by the use of algorithm.
   13     Exponent
             Identifies the algorithm parameter value as the exponent
             of a public key which is to be used according to the
             function defined by the use of algorithm.
   14     Modulus length
             Identifies the algorithm parameter value as the length of
             the modulus (in bits) of the public key used in the
             algorithm. The length is independent of whatever
             filtering function may be in use.
   15     Generic parameter 1
             Identifies the algorithm parameter value as the first
             generic parameter.
   16     Generic parameter 2
             Identifies the algorithm parameter value as the second
             generic parameter.
   17     Generic parameter 3
             Identifies the algorithm parameter value as the third
             generic parameter.
   18     Generic parameter 4
             Identifies the algorithm parameter value as the fourth
             generic parameter.
   19     Generic parameter 5
             Identifies the algorithm parameter value as the fifth
             generic parameter.
   20     Generic parameter 6
             Identifies the algorithm parameter value as the sixth
             generic parameter.
   21     Generic parameter 7
             Identifies the algorithm parameter value as the seventh
             generic parameter.
   22     Generic parameter 8
             Identifies the algorithm parameter value as the eighth
             generic parameter.
   23     Generic parameter 9
             Identifies the algorithm parameter value as the ninth
             generic parameter.
   24     Generic parameter 10
             Identifies the algorithm parameter value as the tenth
             generic parameter.
   25     DSA parameter P
             Identifies the algorithm parameter value as the parameter
             P of DSA algorithm.
   26     DSA parameter Q
             Identifies the algorithm parameter value as the parameter
             Q of DSA algorithm.
   27     DSA parameter G
             Identifies the algorithm parameter value as the parameter
             G of DSA algorithm.
   28     DSA parameter Y
             Identifies the algorithm parameter value as the parameter
             Y of DSA algorithm.
   29     Initial value for CRC calculation
             Identifies the algorithm parameter value as the initial
             value for the CRC calculation.
   30     Initial directory tree
             Identifies the algorithm parameter value as the initial
             directory tree for the data compression algorithm
             specified.
   31     Integrity value offset
             Identifies the algorithm parameter value as the offset
             within the compressed text where the integrity value is
             located.
   33     Generator
             Identifies the algorithm parameter value as the generator
             for a secret key agreement mechanism.
   34     Symmetric key activation date/time
             Identifies the activation date/time of a symmetric key.
             The date/time format shall be CCYYMMDDHHMMSS.
   35     PKCS#1-EME-OAEP HF
             Identifies the algorithm parameter value as the code of
             the hash function used by EME-OAEP padding mechanism as
             defined in PKCS#1, Version 2.
   36     PKCS#1-EME-OAEP MGF
             Identifies the algorithm parameter value as the code of
             the mask generation function used by EME-OAEP padding
             mechanism as defined in PKCS#1, Version 2.
   37     PKCS#1-EME-OAEP P Init
             Identifies the algorithm parameter value as the initial
             octets of the encoding parameter octet string (P) used by
             EME-OAEP padding mechanism as defined in PKCS#1, Version
             2.
   38     PKCS#1-EME-OAEP P Cont
             Identifies the algorithm parameter value as the
             additional octets of the encoding parameter octet string
             (P) following the initial octets, used by EME-OAEP
             padding mechanism as defined in PKCS#1, Version 2.
   39     PKCS#1-EME-OAEP P Final
             Identifies the algorithm parameter value as the final
             octets of the encoding parameter octet string (P)
             following the initial or additional octets, used by
             EME-OAEP padding mechanism as defined in PKCS#1, Version
             2.
   40     PKCS#1-EME-OAEP HF/MGF
             Identifies the algorithm parameter value as the code of
             the hash function used by the mask generation function
             used by EME-OAEP padding mechanism as defined in PKCS#1,
             Version 2.
   41     PKCS#1-EME-OAEP LENGTH
             Identifies the algorithm parameter value as the intended
             length of the result produced by EME-OAEP padding
             mechanism as defined in PKCS#1, Version 2.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0533  Mode of operation code list identifier

  Desc: Specification of the code list used to identify the
        cryptographic mode of operation.

  Repr: an..3

   1      UN/CEFACT
             United Nations Centre for Trade Facilitation and
             Electronic Business (UN/CEFACT).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

* 0541  Scope of security application, coded

  Desc: Specification of the scope of application of the security
        service defined in the security header.

  Repr: an..3

  Note 1: It defines the data that have to be taken into account by
          the related cryptographic process.

   1      Security header and message body
             The current security header segment group and the object
             body itself, only. In this case no other security header
             or security trailer segment group shall be encompassed
             within this scope.
   2      From security header to security trailer
             From the current security header segment group, to the
             associated security trailer segment group. In this case
             the current security header segment group, the object
             body and all the other embedded security header and
             trailer segment groups shall be encompassed within this
             scope.
   3      Whole related message, package, group or interchange
             From the first character of the message, group, or
             interchange to the last character of the message, group
             or interchange.
   4      Interactive security information, security header and
          message body
             Related security information, related interactive
             security header and interactive message body.
   5      Interactive security information plus security header to
          security trailer
             Related security information, security header, all other
             embedded interactive security headers, interactive
             message body and all other embedded interactive security
             trailers.
+  6      Entire batch message
             From and including, the first character ("U") of the
             message header segment (UNH) through to and including,
             the last character (segment  terminator) of the
             corresponding message trailer segment (UNT).
   ZZZ    Mutually agreed
             The scope of security application is defined in an
             agreement between sender and receiver.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0543  Certificate original character set repertoire, coded

  Desc: Identification of the character set repertoire used to create
        the certificate it was signed.

  Repr: an..3

   1      UN/ECE level A
             As defined in the basic code table of ISO 646 with the
             exceptions of lower case letters, alternative graphic
             character allocations and national or
             application-oriented graphic character allocations.
   2      UN/ECE level B
             As defined in the basic code table of ISO 646 with the
             exceptions of alternative graphic character allocations
             and national or application-oriented graphic character
             allocations.
   3      UN/ECE level C
             As defined in ISO 8859-1 : Information processing - Part
             1: Latin alphabet No. 1.
   4      UN/ECE level D
             As defined in ISO 8859-2 : Information processing - Part
             2: Latin alphabet No. 2.
   5      UN/ECE level E
             As defined in ISO 8859-5 : Information processing - Part
             5: Latin/Cyrillic alphabet.
   6      UN/ECE level F
             As defined in ISO 8859-7 : Information processing - Part
             7: Latin/Greek alphabet.
   7      UN/ECE level G
             As defined in ISO 8859-3 : Information processing - Part
             3: Latin alphabet.
   8      UN/ECE level H
             As defined in ISO 8859-4 : Information processing - Part
             4: Latin alphabet.
   9      UN/ECE level I
             As defined in ISO 8859-6 : Information processing - Part
             6: Latin/Arabic alphabet.
   10     UN/ECE level J
             As defined in ISO 8859-8 : Information processing - Part
             8: Latin/Hebrew alphabet.
   11     UN/ECE level K
             As defined in ISO 8859-9 : Information processing - Part
             9: Latin alphabet.
   12     UN/ECE level X
             Code extension technique as defined by ISO 2022 utilising
             the escape techniques in accordance with ISO 2375.
   13     UN/ECE level Y
             ISO 10646-1 octet without code extension technique.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0545  Certificate syntax and version, coded

  Desc: Coded identification of the syntax and version used to create
        the certificate.

  Repr: an..3

   1      EDIFACT version 4
             ISO 9735 version 4.
   2      EDIFACT version 3
             ISO 9735 version 3.
   3      X.509
             ISO/IEC 9594-8, ITU X.509 key/certificate reference.
   4      PGP
             PGP (Pretty Good Privacy) based format key/certificate
             reference.
   5      EDI 5 v1.4
             Version 1.4 of the EDI 5 certificate (French national
             standard).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0551  Service character for signature qualifier

  Desc: Identification of the type of service character used when the
        signature was computed.

  Repr: an..3

   1      Segment terminator
             Specifies that this is the separator at the end of
             segments.
   2      Component data element separator
             Specifies that this is the separator between component
             data elements.
   3      Data element separator
             Specifies that this is the separator between data
             elements.
   4      Release character
             Specifies that this is the release character.
   5      Repetition separator
             Specifies that this is the separator between repeating
             data elements.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0563  Validation value, qualifier

  Desc: Identification of the type of validation value.

  Repr: an..3

   1      Unique validation value
             Specifies that this is the unique validation value. This
             code shall be used when the algorithm involved produces a
             single parameter result (one MAC with DES algorithm, or
             one digital signature with RSA algorithm, for instance).
   2      DSA algorithm r parameter
             Specifies that this is the r parameter, resulting of the
             use of DSA algorithm.
   3      DSA algorithm s parameter
             Specifies that this is the s parameter, resulting of the
             use of DSA algorithm.
   4      Random number for party A
             A random number generated by party A in a key agreement
             or entity authentication protocol.
   5      Random number for party B
             A random number generated by party B in a key agreement
             or entity authentication protocol.
   6      Enciphered block under a symmetric algorithm
             The result of the encipherment of data under a symmetric
             algorithm in an entity authentication protocol.
   7      Enciphered block under an asymmetric algorithm
             The result of the encipherment of data under an
             asymmetric algorithm in an entity authentication
             protocol.
   8      Key agreement value
             The value calculated in a key agreement protocol.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0565  Message relation, coded

  Desc: Relationship with another message, past or future.

  Repr: an..3

   1      No relation
             The message is initial.
   2      Response
             The message is a response message.
   3      Response requested
             The message requests an answer.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0567  Security status, coded

  Desc: Identification of the security element (key or certificate,
        for instance) status.

  Repr: an..3

   1      Valid
             The security element is valid.
   2      Revoked
             The security element has been revoked.
   3      Unknown
             The status of the security element is unknown.
   4      Discontinued
             The security element should not be used for ?????
   5      Alert
             The security element has been put on alert, but is not
             revoked yet.
   6      Expired
             The validity period of the security element is expired.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0569  Revocation reason, coded

  Desc: Identification of the reason why the certificate has been
        revoked.

  Repr: an..3

   1      Owner key compromised
             The owner key linked to this certificate has been
             compromised.
   2      Issuer key compromised
             The issuer key used to generate this certificate has been
             compromised.
   3      Owner changed affiliation
             The identification details of the certificate are no
             longer valid.
   4      Certificate superseded
             This certificate has been renewed and is superseded by
             another certificate.
   5      Certificate terminated
             This certificate has reached the end of its validity
             period and has not been renewed.
   6      No information available
             This certificate is revoked but the reason is not
             explicit stated.
   ZZZ    Mutually agreed
             Mutually agreed between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0571  Security error, coded

  Desc: Identifies the security error causing the rejection of the
        EDIFACT structure.

  Repr: an..3

  Note 1: This element shall specify the security error encountered.
          These may be the reason for non-acknowledgement by a request
          for secure acknowledgement, or may be sent on the initiative
          of the receiver of an AUTACK or secured EDIFACT structure
          which contains error.

   1      Wrong authenticator
             The validation is wrong.
   2      Wrong certificate
             The certificate is wrong.
   3      Certification path
             The certification path is incomplete. Cannot verify.
   4      Algorithm not supported
             The algorithm is not supported.
   5      Hashing method not supported
             The hashing method is not supported.
   6      Protocol error
             The stated protocol has not been followed.
   7      Security expected but not present
             It was expected the user message would be secured (eg
             using integrated message security or the AUTACK message
             in authentication mode), but this was not present or
             received in the expected time period.
   8      Security parameters do not match those expected
             The parameters specifying the applied security do not
             match those expected (eg from an interchange agreement).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0575  List parameter qualifier

  Desc: Specification of the type of list parameter.

  Repr: an..3

   ZZZ    Mutually defined
             Mutually defined between trading partners.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0577  Security party qualifier

  Desc: Identification of the role of the security party.

  Repr: an..3

   1      Message sender
             Identifies the party which generates the security
             parameters of the message (i.e. security originator).
   2      Message receiver
             Identifies the party which verifies the security
             parameters of the message (i.e. security recipient).
   3      Certificate owner
             Identifies the party which owns the certificate.
   4      Authenticating party
             Party which certifies that the document (i.e. the
             certificate) is authentic.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0579  Key management function qualifier

  Desc: Specification of the type of key management function.

  Repr: an..3

   101    Registration submission
             Submission of information for registration.
   102    Asymmetric key pair request
             Request a trusted party to generate an asymmetric key
             pair.
   110    Certification request
             Request certification of credentials and public key.
   111    Certificate renewal request
             Request to extend the validity period of the current
             valid key, whose certificate is about to expire.
   112    Certificate replacement request
             Request to replace the current certificate by a new one
             with a different public key (and possibly other
             information).
   121    Certificate (path) retrieval request
             Request the delivery of an existing (valid or revoked)
             certificate, with path details where appropriate.
   123    Certificate list retrieval request
             Request full or partial list of certificate.
   124    Certificate status request
             Request current status of a given certificate.
   125    Certificate validation request
             Request the CA to validate an existing certificate.
   126    Certificate delivery request
             Request the CA to deliver a (valid or revoked)
             certificate to a list of recipients known to the CA or
             specified elsewhere.
   130    Revocation request
             Request revocation of a party's certificate.
   131    Alert request
             Request to put a party's certificate on alert.
   140    Revocation list request
             Request full or partial list of revoked certificates.
   150    Symmetric key request
             Request the delivery of symmetric keys.
   151    Symmetric key discontinuation request
             Request discontinuation of symmetric key.
   152    Asymmetric key discontinuation request
             Request discontinuation of asymmetric key.
   221    Certificate delivery
             Delivery of an existing (valid or revoked) certificate.
   222    Certificate path delivery
             Delivery of a path.
   224    Certificate status notice
             Notice of current status of a given certificate.
   225    Certificate validation notice
             Notice of validation of an existing certificate.
   231    Revocation confirmation
             Confirmation of revocation of a party's certificate.
   251    Symmetric key delivery
             Delivery of symmetric keys.
   252    Discontinuation acknowledgement
             Acknowledgement of the requested discontinuation.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0591  Padding mechanism, coded

  Desc: Padding mechanism or padding scheme applied.

  Repr: an..3

   1      Zero padding
             Message padding used for block cipher algorithms. Binary
             zeros are appended to the end of the message in order to
             make the message length an exact integer multiple of the
             block length. The block length is implicitly specified
             through the algorithm and mode of operation.
   2      PKCS #1 padding
             Message padding used for block cipher algorithms
             according to PKCS #1 (published by RSA Inc., 1993).
   3      ISO 10126 padding
             Message padding used for block cipher algorithms
             according to ISO-10126 specification.
   4      TBSS padding
             Message padding used for block cipher algorithms
             according to TBSS (Swiss standard, published by Telekurs
             AG, 1996).
   5      FF padding
             Message padding used for block cipher algorithms. Binary
             255 are padded to fill a message up to a block length.
             The block length is implicit specified through the
             algorithm and mode of operation.
   6      ISO 9796 #1 padding
             Message padding for digital signature schemes according
             to ISO 9796 part 1.
   7      ISO 9796 #2 padding
             Message padding for digital signature schemes according
             to ISO 9796 part 2.
   8      ISO 9796 #3 padding
             Message padding for digital signature schemes according
             to ISO 9796 part 3.
   9      TBSS envelope padding
             Message padding for digital envelopes according to TBSS
             (Swiss standard, published by Telekurs AG, 1996)
   10     PKCS #1 envelope padding
             Message padding for digital envelopes according to PKCS
             #1 (published by RSA Inc, 1993).
   11     PKCS #1 signature padding
             Message padding for digital signature schemes according
             to PKCS #1 (published by RSA Inc, 1993).
   12     BCS signature padding
             Message padding for digital signature schemes according
             to ZKA (German standard published by ZKA 1995).
   13     OAEP
             Optimal Asymmetric Encryption Padding (published in IEEE
             P1363).
   14     RSAES-OAEP
             Padding mechanism specified in PKCS#1, version2, for
             encryption with a RSA public key.
   15     RSAES-PKCS#1-v1_5
             Padding mechanism specified in PKCS#1, version2, for
             encryption with a RSA public key.
   16     RSASA-PKCS-v1_5
             Padding mechanism specified in PKCS#1, version2, for
             digital signatures.
   17     Encryption Block Formatting
             Padding mechanism specified in PKCS#1, version 1.5.
   18     PKCS#5
             Padding mechanism specified in PKCS#5 for symmetric
             encryption.
   19     ANSI X9.23
             Padding mechanism specified in ANSI X9.23 for symmetric
             encryption.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0601  Padding mechanism code list identifier

  Desc: Specification of the code list used to identify the padding
        mechanism or padding scheme.

  Repr: an..3

   1      UN/CEFACT
             United Nations Centre for Trade Facilitation and
             Electronic Business (UN/CEFACT).

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0805  Object type qualifier

  Desc: Qualifier referring to the type of object.

  Repr: an..3

   1      Computer environment type
             Specification of the type of computer environment for
             which the object is intended.
   2      Computer environment version
             Specification of the version of the computer environment
             for which the object is intended.
   3      Computer environment release
             Specification of the release of the computer environment
             for which the object is intended.
   5      Computer environment name
             Specification of the name of the computer environment for
             which the object is intended.
   6      Non-EDIFACT security level code
             Specification of the level such as interchange, group or
             message at which non-EDIFACT security is applied to the
             data constituting the object.
   7      Non-EDIFACT security version
             Specification of the version of the non-EDIFACT security
             technique applied to the data constituting the object.
   8      Non-EDIFACT security release
             Specification of the release of the non-EDIFACT security
             technique applied to the data constituting the object.
   9      Non-EDIFACT security technique
             Specification of the non-EDIFACT security technique
             applied to the data constituting the object.
   10     Non-EDIFACT security free text information
             Free form description of the non-EDIFACT security
             technique applied to the data constituting the object.
   11     File identification by number
             Identification number assigned to the file constituting
             the object.
   12     File identification by name
             Name assigned to the file constituting the object.
   13     File format
             Specification of the format of the file constituting the
             object.
   14     File version
             Specification of the version of the file constituting the
             object.
   15     File release
             Specification of the release of the file constituting the
             object.
   16     File status
             Specification of the status of the file constituting the
             object.
   17     File size
             Specification of the size of the file constituting the
             object in bytes.
   18     File description
             Free form description of the file constituting the
             object.
   19     File block type
             Specification of the type of blocking used to partition
             the file constituting the object.
   20     File block length
             Specification of the length of the blocks used to
             partition the file constituting the object.
   21     File record length
             Specification of the length of the records contained in
             the file constituting the object expressed as the number
             of character positions.
   22     Program identification by number
             Identification number assigned to the program
             constituting the object.
   23     Program identification by name
             Name assigned to the program constituting the object.
   24     Program type
             Specification of the type of program constituting the
             object.
   25     Program version
             Specification of the version of the program constituting
             the object.
   26     Program release
             Specification of the release of the program constituting
             the object.
   27     Program status
             Specification of the status of the program constituting
             the object.
   28     Program description
             Free form description of the program constituting the
             object.
   29     Program size
             Specification of the size of the program constituting the
             object in bytes.
   30     Interchange format
             Specification of the format of the interchange
             constituting the object.
   31     Interchange version
             Specification of the version of the interchange
             constituting the object.
   32     Interchange release
             Specification of the release of the interchange
             constituting the object.
   33     Interchange status
             Specification of the status of the interchange
             constituting the object.
   34     Interchange identification
             Identification number assigned to the interchange
             constituting the object.
   35     Compression technique identification
             An identification assigned to the compression technique
             applied to the object.
   36     Compression technique version
             Specification of the version of the compression technique
             applied to the object.
   37     Compression technique release
             Specification of the release of the compression technique
             applied to the object.
   38     Drawing identification by name
             Name assigned to the drawing constituting the object.
   39     Drawing identification by number
             Identification number assigned to the drawing
             constituting the object.
   40     Drawing type
             Specification of the type of drawing constituting the
             object.
   41     Drawing format
             Specification of the format of the drawing constituting
             the object.
   42     Drawing version
             Specification of the version of the drawing constituting
             the object.
   43     Drawing release
             Specification of the release of the drawing constituting
             the object.
   44     Drawing status
             Specification of the status of the drawing constituting
             the object.
   45     Drawing size
             Specification of the size of the drawing constituting the
             object in bytes.
   46     Drawing description
             Free form description of the drawing constituting the
             object.
   48     Filter type
             Specification of the type of filtering technique applied
             to the object.
   49     Filter version
             Specification of the version of the filtering technique
             applied to the object.
   50     Filter code page
             Specification of the code page used for the filtering
             technique applied to the object.
   51     Filter technique
             Specification of the filtering technique applied to the
             object.
   52     Character set repertoire identification
             Identification of the character set repertoire used for
             the object.
   53     Character set encoding technique
             Specification of the character set encoding technique
             used for the object.
   54     Character set encoding technique code page
             Specification of the code page used for the character set
             encoding technique used for the object.
   55     Certificate type
             Specification of the type of certificate constituting the
             object.
   56     Certificate version
             Specification of the version of the certificate
             constituting the object.
   57     Certificate release
             Specification of the release of the certificate
             constituting the object.
   58     Certificate status
             Specification of the status of the certificate
             constituting the object.
   60     Certificate identification by name
             Name assigned to the certificate constituting the object.
   61     Certificate identification by number
             Identification number assigned to the certificate
             constituting the object.
   62     Certificate format
             Specification of the format of the certificate
             constituting the object.
   63     Certificate code page
             Specification of the code page used when generating the
             certificate constituting the object.

ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

  0813  Reference qualifier

  Desc: Code giving specific meaning to a reference identification
        number.

  Repr: an..3

   1      Object identification number
             Identification number assigned to an object.
   2      Application message reference number
             Reference number assigned to a message by a computer
             application.
