# CRA Stewardship Guidelines and Templates

This repository contains guidelines and templates for open source projects for which the Rocky Enterprise Software Foundation acts as an open source software steward under the [EU Cyber Resilience Act (CRA) (Regulation 2024/2847)](https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng).

## What is the EU Cyber Resilience Act?

The EU Cyber Resilience Act establishes cybersecurity requirements for products with digital elements sold in the EU. It introduces the concept of an **Open Source Software Steward** (Article 3(14)) — an organization that provides support, oversight, or coordination for open source projects without placing those products on the market commercially.

The Rocky Enterprise Software Foundation fulfills this steward role for a number of open source projects, accepting defined obligations around vulnerability management, security disclosures, and coordination with the broader open source community.

## Repository Contents

| Path | Description |
|------|-------------|
| `Templates/Security_MD_template.md` | Template `SECURITY.md` for CRA-stewarded projects |

## Using the Templates

### `SECURITY.md`

Every CRA-stewarded project should have a `SECURITY.md` file at the root of its repository. This file tells users and researchers how to report vulnerabilities and what to expect in response.

**Steps to adopt:**

1. Copy `Templates/Security_MD_template.md` to `SECURITY.md` in your project repository.
2. Replace all `<!-- ... -->` placeholder comments with project-specific values:
   - Security contact email address
   - Response timeline
   - Link to the latest supported version
   - Link to your support matrix and vulnerability management policy
3. Remove or fill in the optional sections (GPG key, disclosure status).

The template already includes the required **EU Cyber Resilience Act — Open Source Steward Statement** identifying the Rocky Enterprise Software Foundation as the steward and referencing the CRA regulation.

## Contact

For questions about CRA stewardship obligations or this repository, contact the Rocky Enterprise Software Foundation at **cra-steward@resf.org**.

## Thanks

Thanks to Red Hat for researching EU Cyber Resilience Act compliance requirements and creating relevant helpful resources for open source organizations to use, including the repository this is templated from: https://github.com/RedHatProductSecurity/CRA
