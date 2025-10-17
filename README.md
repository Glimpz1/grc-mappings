# GRC Mappings — OLIR & OSCAL (CSF pivot)

**Status:** Private working draft  
**Owner:** Aleksei Panov

This repository hosts:
- **OLIR mappings** (Supportive / Crosswalk / Set Theory) with **CSF 2.0 as focal**.
- **Public-safe OSCAL** content (CSF catalog; thin PCI catalog) — to be added.

## Current artifacts
- `olir/csf-2.0_pci-4.0.1_supportive/csf-v2_pci-dss_v4.0.1_olir-supportive.xlsx` (no PCI verbatim text)

## Template & Validator note

This OLIR is using the NIST **Focal Document Template** from  
https://csrc.nist.gov/Projects/olir/focal-document-templates#/

The validation run against  
https://csrc.nist.rip/Projects/olir/validation-tool  
did **not** pass because that tool targets a different template build and such template is not officially published on 
https://csrc.nist.rip/projects/olir/focal-document-templates

**Decision:** We will continue using the current current OLIR Focal Document Template from csrc.nist.gov because there is no better, validated alternative available at this time.

## Next steps
1. Run the NIST OLIR validator locally and fix any errors - once updated version and template is available.
2. When ready for NIST screening, make this repo **public**, create a tagged release, and use the release URL in the OLIR submission.

## Notes on rights
Third-party standards are referenced by identifier and link. **No verbatim PCI text** is redistributed here.
