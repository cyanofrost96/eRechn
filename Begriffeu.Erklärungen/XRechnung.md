ist eine Art von [[CIUS]] (Core Invoice User Specification)
## Definition(en)
XRechnung ist ein Standard auf XML-Basis, in welchem definiert ist, wie eine elektronische Rechnung an öffentliche Auftraggeber in Deutschland aufgebaut sein muss. Vereinfacht: welche Angaben enthalten sein und wie diese strukturiert sein müssen. [afi-solutions](https://www.afi-solutions.com/fileadmin/Blog/2020/Whitepaper-Wissen-Kompakt-E-Rechnungen.pdf)

Aus Copilot:
**XRechnung**:
- **Purpose**: XRechnung is designed for invoicing in the context of **government agencies and administrative bodies**.
- **Standardization**: It adheres strictly to the **European Norm EN 16931-1**.
- **Format**: XRechnung uses a **pure XML format**.
- **Legal Compliance**: Like ZUGFeRD, XRechnung complies with the same legal requirements as paper-based invoices.
- **Benefits of Digital Invoicing**:
	- Both formats offer significant advantages, including cost savings, time efficiency, and faster payment processing.
	- Regardless of the format, digital invoicing is gaining prominence and will likely continue to establish itself as the preferred method.

In Bezug auf das zu verwendende Rechnungsdatenmodell gilt § 4 E-RechV, wonach eine elektronische Rechnung dem Standard XRechnung in der jeweils aktuellsten Version bzw. der europäischen Norm EN 16931-1-2017 entsprechen muss.

Der Standard XRechnung wurde von der Koordinierungsstelle für IT-Standards im Auftrag des IT-Planungsrates erarbeitet.  
Die jeweils aktuelle Version des Standards XRechnung finden Sie [hier](https://www.xoev.de/xrechnung-16828).  
Die europäische Norm für die elektronische Rechnungsstellung EN 16931-1-2017 wurde vom Europäischen Komitee für Normung (CEN) am 28. Juni 2017 veröffentlicht.

Die Prüfung zu übermittelnder elektronischer Rechnungen auf Übereinstimmung mit den Vorgaben des Standards XRechnung bzw. der europäischen Norm EN16931-1-2017 erfolgt mittels einer Schema- sowie einer Schematronprüfung, die den jeweiligen Vorgaben entspricht.
[xrechnung-bund](https://xrechnung.bund.de/prod/er_files/nutzungsbedingungen_de.jsp)
### Inhalte
- Leitweg-ID: ist die eindeutige elektronische Adresse eines Rechnungsempfängers.
	- Die Leitweg-ID besteht aus einer Grobadressierung, einer Feinadressierung und einer Prüfziffer. Grobadressierung und Prüfziffer sind Pflichtbestandteile, die Feinadressierung optional. Eine Leitweg-ID kann minimal 5 Stellen sowie maximal 46 Stellen lang sein ![[pic.LeitwegID.png]]
	- 