# EU Test Certificate Schema

## Metadata
* Certificate name: Ditital Test Certificate
* Certificate Issuer: E.g. "Ministry of Health" (**Note**: that this is coming from the scanned data)
* Country: <EU member state>

## Data card region
All EU Countries

## Fields

|   | Attribute name                         | Description                                                      |
|---|----------------------------------------|------------------------------------------------------------------|
| 1 | EU Certificate Issuer        | Full name of the individual                                      
| 2 | EU Beneficiary Name         | Full name of the individual                                      |
| 3 | EU Date Of Birth            | Date of birth of the individual                                  |
| 4 | EU Member State             | Memberstate in EU where the individual has taken the tests |
| 5 | EU Unique Certificate Identifier | Unique identifier, if any, of the issued certificate             |
| 6 | EU Disease                  | Disease or agent targeted |
| 7 | EU Type of Tests            | The type of the test used, based on the material targeted by the test. Example: "tt": "LP6464-4" (Nucleic acid amplification with probe detection), "tt": "LP217198-3" (Rapid immunoassay)  |
| 8 | EU Test Name           | The name of the nucleic acid amplification test (NAAT) used. The name includes the name of the test manufacturer and the commercial name of the test, separated by a comma. |
| 9 | EU Test Device Identifier          | Rapid antigen test (RAT) device identifier from the JRC database |
| 10 | EU Sample Collection Date | The date and time when the test sample was collected. |
| 11 | EU Test Result | The result of the test. |
| 12 | EU Test Center| Name of the actor that conducted the test. |


## Source

* https://ec.europa.eu/health/sites/default/files/ehealth/docs/covid-certificate_json_specification_en.pdf
* https://ec.europa.eu/health/sites/default/files/ehealth/docs/digital-green-value-sets_en.pdf

