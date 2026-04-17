# Welcome to the IRI Digital First for Annuity Standards!

This repository supports the Insured Retirement Institute (IRI) Digital First for Annuity Standards initiative. The goal is to develop open, industry-aligned API standards for the annuity ecosystem. Annuity industry participants collaborate here to define, review, and improve standards that support more consistent and efficient data exchange.

IRI welcomes and appreciates your contributions to our Digital-First for Annuity Standards initiative, open to industry participants for API standardization across the annuity insurance industry. To help us respect the intellectual property rights of others, please adhere to the following guidelines:
1.	Original Work: Ensure that all code, documentation, and other materials you submit are your original work. Do not include or use any content that is owned by others without proper authorization.
2.	No Unauthorized Use of Intellectual Property: Do not submit any material that infringes on the intellectual property rights of others, including but not limited to copyrights, trademarks, patents, or trade secrets.
3.	Proper Attribution: If your submission includes third-party content that is permissible to use under an open-source license, provide proper attribution and comply with the terms of the license.
4.	Compliance with Licenses: Ensure that your contributions comply with the licensing terms of any third-party software or libraries you use.
5.	Clear Documentation: Provide clear and thorough documentation for your submissions, including any necessary disclaimers or notices regarding third-party content.

By submitting your contributions, you agree to these guidelines and warrant that your submission does not violate any intellectual property rights.

## Specifications

The OpenAPI specifications can be found at [specs.dfa.irionline.org](https://specs.dfa.irionline.org/), which is the published GitHub Page of the [Digital-First-Specifications](https://github.com/Insured-Retirement-Institute/Digital-First-Specifications) repository.

All standards have a corresponding repository where work **in progress** documentation lives as the standards are being developed.

### Active Specifications
- [Application Status](https://specs.dfa.irionline.org/api-viewer.html?api=appstatus.yaml&version=v2) This open standard is an alternative to the legacy ActivityStatusAPI specs owned and managed by ACORD. Please contact ACORD for implementation details regarding the legacy ActivityStatusAPI specs.
- [Producer Training](https://specs.dfa.irionline.org/api-viewer.html?api=producertraining.yaml&version=v1)
- [Activated Annuity Income](https://specs.dfa.irionline.org/api-viewer.html?api=activatedannuityincome.yaml&version=v1)
- [One Time Withdrawals](https://specs.dfa.irionline.org/api-viewer.html?api=onetimewithdrawal1.yaml&version=v1)
- [Systematic Program Setup](https://specs.dfa.irionline.org/api-viewer.html?api=systematicwithdrawalprogramsetup.yaml&version=v1)
- [Systematic Program Update](https://specs.dfa.irionline.org/api-viewer.html?api=systematicwithdrawalprogramupdate.yaml&version=v1)
- [One Time Withdrawal Quote](https://specs.dfa.irionline.org/api-viewer.html?api=onetimewithdrawalquote1.yaml&version=v1)

### Specifications under development
- [Ceding Carrier Data](https://github.com/Insured-Retirement-Institute/Ceding-Carrier-Data)
- [Policy Inquiry](https://github.com/Insured-Retirement-Institute/Policy-Inquiry)
- [One Time Fund Transfer](https://github.com/Insured-Retirement-Institute/One-Time-Fund-Transfer)
- [Systematic Program Inquiry](https://github.com/Insured-Retirement-Institute/Systematic-Program-Inquiry)
- [Rates](https://github.com/Insured-Retirement-Institute/Rates)


## Standards governance 

Please review the [Digital First for Annuities Standards Playbook](https://www.irionline.org/operations-and-technology/article/digital-first-for-annuities-standards-playbook/) for a structured framework for creation, governance, and implementation of industry-wide standards and best practices. 

A request for a new standard or an update to the standard that will result in a minor or major revision must be submitted via the [DFA Business Case](https://forms.office.com/r/cJhKbAUZUF).

The Business Case must include: 
- Experience Outcomes
- Measures of Success
- Use Cases
- Points of Integration
- Firms needed to be able to send and receive the data (Distributor, Carrier, Solution Provider...)

Contact hpikus@irionline.org if you want to submit a standard for consideration or join any open discussion.

## How to engage, contribute, and give feedback

Patches, and Minor and Major edits will be handled with versioning.  Minor and Major edits and will go through the Strategy Implementation Committee for awareness, consideration, and if the business case is approved the working group will manage the request and it will follow the existing governance process. Patches will be evaluated within thge Governance Subcommittee and brought to the Strategy Implementation Committee if broader discussion is needed.

Anyone can submit an edit following the below process.
1. Fork this repo
2. Navigate to the appropriate adopters.yml file
3. Add your info (see format below)
4. Submit a pull request

## Reporting security issues and bugs, and code of conduct

Issues and bugs can be reported directly within the issues tab of each repository. See [Digital-First-Specifications](https://github.com/Insured-Retirement-Institute/Digital-First-Specifications) for technical governance of standards, data dictionary, and the [code of conduct](https://github.com/Insured-Retirement-Institute/Digital-First-Specifications/blob/main/CODE_OF_CONDUCT.md). Change requests, both minor and major revisions should follow the standards governance workflow outlined on the [main page](https://github.com/Insured-Retirement-Institute).

## Versioning

Versioning will follow the format major.minor.patch. 
Each version will follow the naming convention Major.Minor.Patch
- Major: Add incompatible API changes
- Minor: Add functionality in a backward compatible manner
- Patch: Backward compatible bug fixes
