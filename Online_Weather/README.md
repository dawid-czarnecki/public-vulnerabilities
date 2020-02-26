# Online Weather
## Command injection in queryBCP method

|  |  |
|---|---|
| **Vulnerability** | Command injection in queryBCP method | 
| **Vendor** | IBL |
| **Product** | Online Weather - Online Weather is an application developed for the automatic publishing of meteorological information online - https://www.iblsoft.com/products/onlineweather |
| **Vulnerable version** | 4.3.5 |
| **Fixed version** | 4.3.5a |
| **CVE** | CVE-2020-9406 |
| **CVSS Score** | 10.0 Critical |
| **CVSS Vector** | CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H |

### References
* https://nvd.nist.gov/vuln/detail/CVE-2020-9406

### Description
The queryBCP method of the Online Weather Auxiliary Service is prone to a command injection vulnerability via not validated parameter passed to the eval instruction.



## Reflected XSS in redirect page

|  |  |
|---|---|
| **Vulnerability** | Reflected XSS in redirect page | 
| **Vendor** | IBL |
| **Product** | Online Weather - Online Weather is an application developed for the automatic publishing of meteorological information online - https://www.iblsoft.com/products/onlineweather |
| **Vulnerable version** | 4.3.5 |
| **Fixed version** | 4.3.5a |
| **CVE** | CVE-2020-9405 |
| **CVSS Score** | 7.1 High |
| **CVSS Vector** | CVSS:3.0/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:L |

### References
* https://nvd.nist.gov/vuln/detail/CVE-2020-9405

### Description
The Online Weather application is vulnerable to an unauthenticated reflected cross site scripting (XSS). A user input of the redirect request is directly reflected in the web page, allowing a malicious user to conduct a cross site scripting attack against users of the application.



## Information disclsure in cookie

|  |  |
|---|---|
| **Vulnerability** | Information disclosure in cookie | 
| **Vendor** | IBL |
| **Product** | Online Weather - Online Weather is an application developed for the automatic publishing of meteorological information online - https://www.iblsoft.com/products/onlineweather |
| **Vulnerable version** | 4.3.5 |
| **Fixed version** | 4.3.5a |
| **CVE** | CVE-2020-9407 |
| **CVSS Score** | 3.1 Low |
| **CVSS Vector** | CVSS:3.0/AV:N/AC:H/PR:L/UI:N/S:U/C:L/I:N/A:N |

### References
* https://nvd.nist.gov/vuln/detail/CVE-2020-9407

### Description
The **IWEBSERVICE_JSONRPC_COOKIE** contains dpotentially sensitive information encoded in base64.