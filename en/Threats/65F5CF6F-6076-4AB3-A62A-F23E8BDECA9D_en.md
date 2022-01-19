[**NAME**]
SQL Injection through SOAP Parameter Tampering

[**DESCRIPTION**]
<p>An attacker modifies the parameters of the SOAP message that is sent from the service consumer to the service provider to initiate a SQL injection attack. </p><p>On the service provider side, the SOAP message is parsed and parameters are not properly validated before being used to access a database in a way that does not use parameter binding, thus enabling the attacker to control the structure of the executed SQL query. </p><p>This pattern describes a SQL injection attack with the delivery mechanism being a SOAP message. </p><p></p><p>Reference: <a href="https://capec.mitre.org/data/definitions/110.htm">https://capec.mitre.org/data/definitions/110.htm</a>l</p>

[**LABELS**]
CAPEC-110,OWASP-A1-Injection,CAPEC-108,CAPEC-66,CAPEC-7,WASC-19,CAPEC-256,CAPEC-254,CAPEC-279,CAPEC-280,CAPEC-493,WASC-35,CAPEC

[**HIDDEN**]
false

[**RiskId**]
1

[**LIBRARY_GUID**]
EEF7DCF9-53BD-48E9-849D-21445EBAD101

[**SECURITYREQUIREMENTS_MAPPING**]
[Input Validation for database querying](SecurityRequirements/306CAB7E-68E2-45D1-BA99-61918B297A6F_en.md)
