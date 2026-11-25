# XML Sitemap Validator

[![XML Sitemap Validator](https://img.shields.io/badge/TAVARDT-Sitemap%20XML-5b3cf5.svg)](https://tools.tavardt.com/ca/xml-sitemap-validator/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Technical sitemap validation utility for Canadian digital channels, verifying URL structure, encoding, and search engine compatibility.

Developed and maintained by the digital systems and crawl engineering unit at **TAVARDT**.

***

## XML Sitemap Validation Capabilities

* **Schema Conformance Testing**: Structural validation of `<urlset>` containers and linked `<sitemapindex>` directories.
* **Attribute Syntax Precision**: Probing for proper date formatting in `<lastmod>` and valid change frequencies.
* **URL Canonicalization Checks**: Pinpoints non-canonical URLs, broken relative routes, and mixed protocol entries.
* **Volume Compliance Verification**: Enforcing the 50,000 URL threshold per individual XML document.
* **Sitemap Cleanliness Metric**: Standardized 0 to 100 evaluation with actionable XML repair steps.

***

## Installation and Execution

Requires Python 3.8 or higher using standard library modules.

```bash
git clone https://github.com/TAVARDT-Canada/xml-sitemap-validator-ca.git
cd xml-sitemap-validator-ca
python sitemap_validator.py https://example.ca/sitemap.xml
```

To output structured JSON:

```bash
python sitemap_validator.py https://example.ca/sitemap.xml -json
```

***

## Online Diagnostic Platform

For ad-hoc sitemap inspections and continuous index verification:

* **Official XML Sitemap Validator**
* **TAVARDT Portal**

***

## Canadian Web Crawl and Indexing Advisory

For enterprise URL architecture and technical alignment with Sitemaps.org Specifications and Web Guidelines, contact the specialists at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/ca/
* **Diagnostic Suite:** https://tools.tavardt.com/ca/
* **Technical Contact:** https://ag.tavardt.com/ca/contact/

***

### License
Released under the MIT License. See [LICENSE](LICENSE) for full details.

***

© 2026 TAVARDT. All rights reserved.
