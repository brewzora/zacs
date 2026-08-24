# Contributing to ZACS

Thank you for helping develop the Zero Ambiguity Contribution Standard (ZACS).
ZACS is developed through public discussion, review, and implementation
experience. Contributions from individuals, projects, companies, researchers,
and other interested communities are welcome.

ZACS is currently a working draft. Requirements, identifiers, document
structure, and development procedures may change before ZACS 1.0.

## Ways to contribute

You can contribute by:

- reporting ambiguity, inconsistency, or unintended consequences;
- proposing normative requirements or changes;
- suggesting editorial improvements;
- sharing implementation and adoption experience;
- improving examples, adoption guidance, or accessibility;
- improving build, rendering, validation, or test tooling; or
- reviewing issues and pull requests.

Security vulnerabilities in repository tooling should not be reported in a
public issue. Use GitHub's private vulnerability-reporting feature when it is
available, or contact the project steward privately.

## Before opening a change

Search existing issues and pull requests before starting substantial work.

Open an issue before preparing a large or normative change. Early discussion
helps identify affected requirements, compatibility concerns, and alternative
approaches before significant work is invested.

Small editorial corrections, broken-link fixes, and isolated tooling fixes may
be submitted directly as pull requests.

## Types of changes

### Editorial changes

An editorial change improves clarity or presentation without changing a
requirement's meaning, scope, or conformance consequences. Examples include
spelling corrections, formatting repairs, and unambiguous wording cleanup.

If a wording change could alter how a reasonable implementer interprets a
requirement, treat it as normative rather than editorial.

### Normative changes

A normative change adds, removes, replaces, or changes a requirement,
definition, permission, prohibition, assurance profile, adoption rule, or
conformance consequence.

A normative proposal should explain:

1. the problem being addressed;
2. the proposed behavior;
3. which sections, profiles, or adopters are affected;
4. compatibility and migration consequences;
5. likely implementation or enforcement burdens;
6. alternatives considered; and
7. examples showing expected results.

Normative changes require public review and must not be merged solely as
formatting or editorial corrections.

### Tooling changes

Tooling changes affect build scripts, renderers, validators, schemas, tests, or
other software. They should include tests when practical and must not silently
change normative text.

Generated publications must not be edited directly. Change the applicable
source or generator and reproduce the generated output.

## Branch Naming

- **main** — current accepted development version.
- **proposal/[name]** — normative changes to requirements, definitions, profiles, adoption rules, or conformance.
- **editorial/[name]** — wording or formatting changes that do not alter meaning.
- **tooling/[name]** — generators, validators, schemas, build scripts, or tests.
- **docs/[name]** — non-normative guides, README changes, and website material.
- **policy/[name]** — governance, contribution, trademark, security, or community policy changes.
- **release/[version]** — temporary release-preparation work.

## Preparing a pull request

1. Fork the repository and create a focused branch.
2. Make one logically related change per pull request when practical.
3. Follow the existing source formatting and file organization.
4. Do not use tab characters in specification or documentation sources.
5. Run the available build and validation checks.
6. Update tests, examples, or documentation affected by the change.
7. Describe the change, its purpose, and any unresolved concerns.
8. Link related issues or prior discussions.

If the repository does not yet provide an automated command for a required check, state what you reviewed or tested manually.

## Pull-request description

A pull request should identify:

- whether the change is editorial, normative, tooling, or mixed;
- the problem it addresses;
- the material behavior or wording changed;
- validation performed;
- compatibility or adoption effects;
- third-party material included, if any; and
- automated generative assistance that must be disclosed under this policy.

Maintainers may ask for a proposal to be divided when independent changes would be easier to review separately.

## Automated generative assistance

ZACS is specifically concerned with accountable use of automated generative
systems. Contributions to ZACS should model that accountability even while the
standard remains a working draft.

The contributor must personally review the complete contribution, understand
it sufficiently to explain and maintain it, reasonably believe they have the
right to submit it, and accept responsibility for it regardless of the tools used.

Material use of an automated generative system must be disclosed in the pull request. The disclosure should identify:

- the system or tool used;
- the portions or kinds of material it affected;
- how it was used; and
- how the contributor reviewed and validated the resulting contribution.

Disclosure is not ordinarily required for incidental assistance that does not
supply or substantially transform retained material and does not materially
determine the contribution's design, meaning, correctness, security,
licensing, or maintainability.

When reviewers ask questions intended to assess the contributor's own
understanding, the contributor must answer from their own understanding and
without contemporaneous automated generative assistance. Ordinary
accessibility tools and non-generative reference materials remain permitted.

Disclosure does not cure an incompatible license or the unauthorized inclusion
of third-party material.

## Third-party material

Do not submit third-party code, text, artwork, data, or other material unless
you have the right to do so under the applicable repository license.

Clearly identify third-party material in the pull request and preserve all
required copyright, attribution, and license notices. Links to source material
do not replace required permission or attribution.

If provenance or licensing is uncertain, raise the concern before including
the material.

## Contribution licensing

Contributors retain copyright in their contributions. By intentionally
submitting a contribution for inclusion in this repository, you agree to the
[Contribution Licensing Terms](CONTRIBUTING-LICENSES.md).

In summary:

- specification and documentation contributions are licensed under CC BY 4.0;
- software and tooling contributions are licensed under the MIT License; and
- a file that expressly identifies another license is governed by that
  identified license.

The summary above is informational. `CONTRIBUTING-LICENSES.md` controls if the
summary conflicts with the complete contribution terms.

Do not submit a contribution if you do not have authority to grant the
applicable license. Contributors acting for an employer or another
organization are responsible for obtaining any required authorization.

## Review and acceptance

Submitting a contribution does not guarantee acceptance. Reviewers may request
changes for clarity, scope, compatibility, provenance, test coverage,
maintainability, or consistency with the goals of ZACS.

Acceptance of a contribution does not represent independent verification that
the contributor owns all submitted material or that the contribution is
lawful, original, correct, or secure.

Until a separate governance document is adopted, Brewzora Studios, as project
steward, determines whether a contribution is accepted. Material normative
decisions should be documented through public issues or pull-request review.

## Discussion and conduct

Discuss ideas and people respectfully. Critique proposals using specific
technical, legal, operational, or editorial reasoning. Harassment, threats,
discrimination, personal attacks, deliberate disruption, and disclosure of
another person's private information are not acceptable.

The project may moderate contributions or participation to protect a safe,
focused, and productive development process. A separate Code of Conduct may be
adopted as the community develops.

## Questions

For questions about contributing, open a GitHub discussion or issue in the
ZACS repository. For private copyright, licensing, provenance, trademark, or
security concerns, use the contact method published in `NOTICE.md`.
