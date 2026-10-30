# Pre-merge Legal and Licensing Review — PR #1

**Date:** 2026-10-30  
**Scope:** `LICENSE.md`, `COMMERCIAL_TERMS.md`, and README licensing representations.  
**Disposition:** **CONDITIONAL PASS / MERGE HOLD until owner confirms rights and reviews wording**.

## Source basis

- GitHub Terms of Service, §D.5, public user content license: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
- GitHub documentation, licensing a repository: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository
- Civil Code of Ukraine, IP and public licenses (including Articles 420, 424, 433, 444): https://mfa.gov.ua/npas/tsivilniy-kodeks-ukraini
- WIPO Lex, Ukraine Copyright and Related Rights Law No. 2811-IX, consolidated 2026-07-31: https://cdn.nestjs.wipolex.wji.prd.web1.wipo.int/wipolex/en/legislation/details/23798

## Findings and treatment

| Finding | Risk | Treatment |
| --- | --- | --- |
| Public GitHub users have platform viewing/forking rights regardless of custom restrictions | High if incorrectly stated | License v1.1 expressly preserves platform rights |
| Owner's authority to license and authorship chain are not independently evidenced | High | Owner confirmation required before merge; no unsupported assertion of verified title |
| Broad revocation language could overstate retroactive control | Medium | Revised to termination of new evaluation acts and no retroactive undoing of lawful acts |
| Local demo running requires incidental copies | Medium | Explicit limited internal evaluation and necessary copies |
| Individuals-only language excluded legitimate prospective corporate evaluation | Medium | Added non-production internal organizational evaluation |
| Background IP and commissioned deliverables need distinct treatment | Medium | Commercial terms define background IP, foreground deliverables and embedded components |
| Published source cannot be kept secret by calling it proprietary | Medium | Expressly no trade-secret claim for intentionally published material |
| No signed customer terms or identified governing law | Medium | Terms are non-binding; require signed agreement and jurisdiction-specific review |

## Outstanding checks before merge

- [ ] Owner verifies that **Mykola Bezruchko** is the correct legal rights holder for every included file and has authority to license them. If AI-assisted material, contributors, third-party snippets, or employment/commissioned rights are involved, document the rights chain.
- [ ] Owner confirms that the public demonstration contains no private technology, client materials, secrets, or third-party assets without permission.
- [ ] Owner approves the scope of permitted internal evaluation and GitHub forking.
- [ ] Owner reviews the README and HTML legal notices against the revised license for consistency.
- [ ] For substantial contracts, qualified counsel reviews jurisdiction, legal entity, data protection, IP schedule, acceptance and liability.

## Assessment

The proposed terms express an evaluation-only proprietary license and do not grant commercial exploitation of the demonstration or private HRONOAZA technology. They cannot prohibit GitHub platform rights, mandatory exceptions, independent implementations of unprotected ideas, or lawfully licensed third-party uses.

**This is a documented legal-risk review, not a legal opinion, judicial determination, title search, or guarantee of enforceability.** Do not merge solely on the basis of this report.
