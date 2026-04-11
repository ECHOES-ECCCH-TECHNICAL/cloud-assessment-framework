# Software Quality Tools

Software quality related tools.

## Summary

- **ISO/IEC 25010 software product quality model** — Defines a standardised model of software product quality characteristics and sub-characteristics, providing a common vocabulary and reference framework for specifying, evaluating and comparing software quality.
- **ISO/IEC 25023 measurement of system and software product quality** — Provides a standard catalogue of quantitative measures for assessing system and software product quality characteristics defined in ISO/IEC 25010.
- **ISO/IEC 5055 Automated Source Code Quality Measures** — Defines automated measures for assessing the structural quality of source code, focusing on maintainability, reliability, performance efficiency and security weaknesses.
- **OMG ASCQM (Automated Source Code Quality Measures) v1.1** — OMG specification for automatically measuring software structural quality through static source-code analysis. It defines a catalogue of weaknesses and detection patterns; scores per quality dimension are computed by counting and aggregating occurrences of these weaknesses by quality characteristic. The specification also defines conformance requirements to ensure that measurements are automated, objective, transparent, and repeatable.
- **Language-specific linters and formatters (e.g. ESLint, Pylint, Flake8, RuboCop, golangci-lint)** — Automatically analyse source code to enforce coding standards, detect common defects and improve consistency and basic correctness across different programming languages.
- **Radon (Python code metrics)** — Computes code complexity, maintainability and size metrics for Python codebases to support early identification of hard-to-maintain modules.
- **Visual Studio (IDE) Code Metrics (Maintainability Index and related metrics)** — Provides IDE-integrated metrics for analysing maintainability, complexity and structural properties of object-oriented code, mainly for .NET projects.
- **Chidamber Kemerer (CK) metrics suite (e.g. via CKJM or similar tools)** — Offers a widely used suite of object-oriented design metrics to assess complexity, coupling, cohesion and inheritance-related maintainability risks.
- **DORA Four Key Metrics (Four Keys)** — Defines a set of four key metrics to measure software delivery performance and operational reliability in DevOps and continuous delivery environments.
- **Defect and incident metrics from issue trackers (e.g. GitHub/GitLab Issues, Jira)** — Derives defect, incident and resolution metrics from issue and incident tracking systems to support analysis of software reliability and quality trends.
- **Test coverage tools (e.g. JaCoCo, Istanbul/nyc, pytest-cov)** — Measure the proportion of source code exercised by automated tests, providing indirect indicators of defect risk and test adequacy.
- **DORA “Documentation quality” capability** — Provides a capability-based assessment framework to evaluate the quality of internal documentation using structured, survey-based indicators.
- **Documentation quality metrics and checklists (e.g. “Evaluating Software Documentation Quality” tooling)** — Offer research-based metrics and checklists to systematically assess the completeness, structure and usability of software documentation.
- **OpenSSF Best Practices Badge** — Provides a checklist-based assessment and public badge to evaluate and communicate adherence to recognised best practices in open-source software projects.
- **FAIR for Research Software (FAIR4RS) Principles** — Defines principles and assessment criteria to improve the findability, accessibility, interoperability and reusability of research software.
- **SPDX specification** — SPDX is a standardized format for describing the components of a software system. It provides a common way for development teams to document what is included in their software, typically in the form of a Software Bill of Materials (SBOM). In addition to listing software components, SPDX can also capture information about licenses, security aspects, data, and AI related elements. The main purpose of SPDX is to improve transparency and risk assessment by making it easier to understand which third party components are used, whether known security vulnerabilities exist, which licenses apply, and what additional elements, such as data or AI models, are involved. This facilitates review by customers, auditors, and security teams, and supports compliance, security analysis, and supply chain management. Many tools support the SPDX specification: https://spdx.dev/use/spdx-tools/.

## ISO/IEC 25010 software product quality model

- **ID:** `SOFTWARE_QUALITY_TOOLS_ISO_IEC_SOFTWARE`
- **Dimensions covered:** Functional suitability, performance efficiency, compatibility, usability, reliability, security, maintainability, portability.
- **Description:** Defines a standardised model of software product quality characteristics and sub-characteristics, providing a common vocabulary and reference framework for specifying, evaluating and comparing software quality.
- **Link:** https://www.iso.org/standard/35733.html

### Additional properties

- **Adoption Likelihood:** Low.
- **Type of tool:** International standard; quality model.
- **License:** ISO standards are proprietary documents. Full access requires purchase, and the text is protected by copyright; redistribution or republication of the content is not permitted.

## ISO/IEC 25023 measurement of system and software product quality

- **ID:** `SOFTWARE_QUALITY_TOOLS_ISO_IEC_MEASUREMENT`
- **Dimensions covered:** Quantitative measures for maintainability, reliability, performance efficiency, functional suitability, usability and other ISO 25010 characteristics.
- **Description:** Provides a standard catalogue of quantitative measures for assessing system and software product quality characteristics defined in ISO/IEC 25010.
- **Link:** https://www.iso.org/standard/35747.html

### Additional properties

- **Adoption Likelihood:** Low.
- **Type of tool:** International standard; measurement catalogue.
- **License:** ISO standards are proprietary documents. Full access requires purchase, and the text is protected by copyright; redistribution or republication of the content is not permitted.

## ISO/IEC 5055 Automated Source Code Quality Measures

- **ID:** `SOFTWARE_QUALITY_TOOLS_ISO_IEC_AUTOMATED`
- **Dimensions covered:** Maintainability, reliability, performance efficiency, security (structural quality of source code).
- **Description:** Defines automated measures for assessing the structural quality of source code, focusing on maintainability, reliability, performance efficiency and security weaknesses.
- **Link:** https://www.iso.org/standard/80623.html

### Additional properties

- **Adoption Likelihood:** Low.
- **Type of tool:** International standard; automated source-code quality measurement model.
- **License:** ISO standards are proprietary documents. Full access requires purchase, and the text is protected by copyright; redistribution or republication of the content is not permitted.

## OMG ASCQM (Automated Source Code Quality Measures) v1.1

- **ID:** `SOFTWARE_QUALITY_TOOLS_OMG_ASCQM_AUTOMATED`
- **Dimensions covered:** Maintainability; Reliability; Performance Efficiency; Security.
- **Description:** OMG specification for automatically measuring software structural quality through static source-code analysis. It defines a catalogue of weaknesses and detection patterns; scores per quality dimension are computed by counting and aggregating occurrences of these weaknesses by quality characteristic. The specification also defines conformance requirements to ensure that measurements are automated, objective, transparent, and repeatable.
- **Link:** https://www.omg.org/spec/ASCQM/1.1/PDF

### Additional properties

- **Adoption Likelihood:** High.
- **Type of tool:** OMG specification; automated source-code structural quality measurement model (static-analysis-based).
- **License:** Copyrighted OMG specification; publicly downloadable, but redistribution, modification, or republication of the text is restricted by license.

## Language-specific linters and formatters (e.g. ESLint, Pylint, Flake8, RuboCop, golangci-lint)

- **ID:** `SOFTWARE_QUALITY_TOOLS_LANGUAGE_SPECIFIC_LINTERS`
- **Dimensions covered:** Code quality (style and potential defects), basic correctness, consistency, adherence to coding standards; sometimes documentation presence (docstrings).
- **Description:** Automatically analyse source code to enforce coding standards, detect common defects and improve consistency and basic correctness across different programming languages.
- **Link:** https://eslint.org, https://pylint.readthedocs.io

### Additional properties

- **Type of tool:** Static analysis tools (linters/formatters).

## Radon (Python code metrics)

- **ID:** `SOFTWARE_QUALITY_TOOLS_RADON_PYTHON_CODE`
- **Dimensions covered:** Maintainability index, cyclomatic complexity, Halstead metrics, source lines of code, comment density.
- **Description:** Computes code complexity, maintainability and size metrics for Python codebases to support early identification of hard-to-maintain modules.
- **Link:** https://radon.readthedocs.io/en/latest/intro.html, https://pypi.org/project/radon/

### Additional properties

- **Type of tool:** Static analysis and metrics tool.

## Visual Studio (IDE) Code Metrics (Maintainability Index and related metrics)

- **ID:** `SOFTWARE_QUALITY_TOOLS_VISUAL_STUDIO_IDE`
- **Dimensions covered:** Maintainability index, cyclomatic complexity, depth of inheritance, class coupling, lines of code.
- **Description:** Provides IDE-integrated metrics for analysing maintainability, complexity and structural properties of object-oriented code, mainly for .NET projects.
- **Link:** https://learn.microsoft.com/en-us/visualstudio/code-quality/code-metrics-values

### Additional properties

- **Type of tool:** IDE-integrated metrics tool.

## Chidamber Kemerer (CK) metrics suite (e.g. via CKJM or similar tools)

- **ID:** `SOFTWARE_QUALITY_TOOLS_CHIDAMBER_KEMERER_CK`
- **Dimensions covered:** Object-oriented design quality: complexity, inheritance depth, coupling, cohesion, potential fault-proneness and maintainability.
- **Description:** Offers a widely used suite of object-oriented design metrics to assess complexity, coupling, cohesion and inheritance-related maintainability risks.
- **Link:** https://www.aivosto.com/project/help/pm-oo-ck.html

### Additional properties

- **Type of tool:** Metrics suite and measurement methodology.

## DORA Four Key Metrics (Four Keys)

- **ID:** `SOFTWARE_QUALITY_TOOLS_DORA_FOUR_KEY`
- **Dimensions covered:** Change failure rate, mean time to recovery (MTTR), deployment frequency, lead time for changes.
- **Description:** Defines a set of four key metrics to measure software delivery performance and operational reliability in DevOps and continuous delivery environments.
- **Link:** https://dora.dev/guides/dora-metrics-four-keys/

### Additional properties

- **Type of tool:** Process/performance metric model and associated data collection tooling.

## Defect and incident metrics from issue trackers (e.g. GitHub/GitLab Issues, Jira)

- **ID:** `SOFTWARE_QUALITY_TOOLS_DEFECT_AND_INCIDENT`
- **Dimensions covered:** Defect rates, incident frequency, resolution performance, stability of releases.
- **Description:** Derives defect, incident and resolution metrics from issue and incident tracking systems to support analysis of software reliability and quality trends.
- **Link:** https://docs.gitlab.com/user/analytics/dora_metrics/

### Additional properties

- **Type of tool:** Derived indicator set from issue/incident management tools.

## Test coverage tools (e.g. JaCoCo, Istanbul/nyc, pytest-cov)

- **ID:** `SOFTWARE_QUALITY_TOOLS_TEST_COVERAGE_TOOLS`
- **Dimensions covered:** Extent of code exercised by automated tests, indirectly linked to defect risk and maintainability.
- **Description:** Measure the proportion of source code exercised by automated tests, providing indirect indicators of defect risk and test adequacy.
- **Link:** https://www.jacoco.org/jacoco/, https://istanbul.js.org/, https://pytest-cov.readthedocs.io/

### Additional properties

- **Type of tool:** Coverage measurement tools.

## DORA “Documentation quality” capability

- **ID:** `SOFTWARE_QUALITY_TOOLS_DORA_DOCUMENTATION_QUALITY`
- **Dimensions covered:** Quality of internal documentation: clarity, completeness, findability, accuracy, up-to-dateness.
- **Description:** Provides a capability-based assessment framework to evaluate the quality of internal documentation using structured, survey-based indicators.
- **Link:** https://dora.dev/capabilities/documentation-quality/

### Additional properties

- **Type of tool:** Capability model and questionnaire-style assessment.

## Documentation quality metrics and checklists (e.g. “Evaluating Software Documentation Quality” tooling)

- **ID:** `SOFTWARE_QUALITY_TOOLS_DOCUMENTATION_QUALITY_METRICS`
- **Dimensions covered:** Documentation completeness, consistency, structure, example coverage, navigability.
- **Description:** Offer research-based metrics and checklists to systematically assess the completeness, structure and usability of software documentation.
- **Link:** https://github.com/ualberta-smr/DocumentationQuality, https://www.computer.org/csdl/proceedings-article/msr/2023/118400a067/1OIKZbvehXi

### Additional properties

- **Type of tool:** Research-based metrics, checklist and web-tool for documentation assessment.

## OpenSSF Best Practices Badge

- **ID:** `SOFTWARE_QUALITY_TOOLS_OPENSSF_BEST_PRACTICES`
- **Dimensions covered:** Project-level practices covering documentation, testing, code review, security, CI, issue management and release process.
- **Description:** Provides a checklist-based assessment and public badge to evaluate and communicate adherence to recognised best practices in open-source software projects.
- **Link:** https://www.bestpractices.dev/en, https://openssf.org/projects/best-practices-badge/

### Additional properties

- **Type of tool:** Checklist and badging system for FLOSS project practices.

## FAIR for Research Software (FAIR4RS) Principles

- **ID:** `SOFTWARE_QUALITY_TOOLS_FAIR_FOR_RESEARCH`
- **Dimensions covered:** Findability, accessibility, interoperability, reusability of research software and associated documentation and metadata.
- **Description:** Defines principles and assessment criteria to improve the findability, accessibility, interoperability and reusability of research software.
- **Link:** https://doi.org/10.1038/s41597-022-01710-x, https://zenodo.org/records/6623556

### Additional properties

- **Type of tool:** Principle set and assessment checklist.

## SPDX specification

- **ID:** `SOFTWARE_QUALITY_TOOLS_SPDX_SPECIFICATION`
- **Dimensions covered:** Security, Maintainability, Compatibility, Reliability.
- **Description:** SPDX is a standardized format for describing the components of a software system. It provides a common way for development teams to document what is included in their software, typically in the form of a Software Bill of Materials (SBOM). In addition to listing software components, SPDX can also capture information about licenses, security aspects, data, and AI related elements. The main purpose of SPDX is to improve transparency and risk assessment by making it easier to understand which third party components are used, whether known security vulnerabilities exist, which licenses apply, and what additional elements, such as data or AI models, are involved. This facilitates review by customers, auditors, and security teams, and supports compliance, security analysis, and supply chain management. Many tools support the SPDX specification: https://spdx.dev/use/spdx-tools/.
- **Link:** https://spdx.dev/

### Additional properties

- **Type of tool:** Specification.
