# Software Functional Tools

Functional testing or validation tools.

## Summary

- **ISO/IEC 25040 – Evaluation Process (SQuaRE)** — Defines a standard process model for planning, executing and concluding software quality evaluations, ensuring that assessments are systematic, repeatable and auditable.
- **Requirements Traceability Matrix (RTM)** — Provides a structured artefact to map functional requirements to implementation and test artefacts, supporting monitoring of functional completeness and correctness.
- **Use-case / workflow coverage checklist** — Provides a checklist-based approach to verify whether end-to-end cultural heritage workflows are fully supported by available system functions.
- **Automated functional test suites + coverage tools (e.g. JUnit/pytest/Jest with JaCoCo, coverage.py, Istanbul)** — Provides automated execution and measurement of functional tests to verify correctness of implemented behaviour and quantify test coverage of functional requirements.
- **OpenAPI-based API contract testing (e.g. Dredd, Schemathesis)** — Provides automated validation of API behaviour against formally specified OpenAPI contracts to ensure functional correctness and robustness at the interface level.
- **Property-based / fuzz testing libraries (e.g. Hypothesis; Schemathesis property-based mode)** — Provides automated generation and execution of test cases based on properties and invariants to detect functional defects under a wide range of input conditions.
- **ISO 25010-based Functional Suitability Questionnaire** — Provides a structured questionnaire to capture end-user perceptions of functional completeness, correctness and appropriateness of software services.
- **Structured interview protocol with cultural heritage professionals** — Provides a qualitative interview-based method to collect in-depth feedback from domain professionals on functional gaps, correctness issues and workflow fit.
- **Task-based user test protocol (scenario-based functional evaluation)** — Provides a scenario-based testing protocol to evaluate whether users can successfully complete representative tasks using available system functions.
- **Usage analytics dashboards for ECCCH services** — Provides analytics-based insight into real-world usage of system functions to assess functional appropriateness, detect underused features and identify functional gaps.
- **Data validation and semantic consistency test suites (e.g. SHACL, SPARQL-based checks)** — Provides automated validation of data and semantic outputs against defined constraints to ensure functional correctness and consistency at the data level.
- **Workflow-oriented functional coverage matrix for Digital Twins** — Provides a matrix-based artefact to assess whether required Digital Twin operations are supported across tools and services within defined workflows.
- **Domain expert review checklist (heritage-specific functional appropriateness)** — Provides a domain-specific expert checklist to assess whether system functions appropriately support cultural heritage research and professional practices.

## ISO/IEC 25040 – Evaluation Process (SQuaRE)

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_ISO_IEC_EVALUATION`
- **Dimensions covered:** Process for evaluating all quality characteristics, including functional suitability.
- **Description:** Defines a standard process model for planning, executing and concluding software quality evaluations, ensuring that assessments are systematic, repeatable and auditable.
- **Link:** https://www.iso.org/standard/83467.html

### Additional properties

- **Type of tool:** standard / process model.
- **Degree of automation:** manual process guidance.

## Requirements Traceability Matrix (RTM)

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_REQUIREMENTS_TRACEABILITY_MATRIX`
- **Dimensions covered:** Coverage of functional requirements; implementation and test status (completeness and correctness).
- **Description:** Provides a structured artefact to map functional requirements to implementation and test artefacts, supporting monitoring of functional completeness and correctness.
- **Link:** https://community.atlassian.com/forums/Jira-questions/How-to-generate-Requirement-Traceability-Matrix-in-JIRA/qaq-p/2683082

### Additional properties

- **Type of tool:** artefact / checklist.
- **Degree of automation:** partially automated (via ALM tools) but requiring manual maintenance.

## Use-case / workflow coverage checklist

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_USE_CASE_WORKFLOW`
- **Dimensions covered:** Support of end-to-end CH workflows; presence/absence of required functions (completeness, appropriateness).
- **Description:** Provides a checklist-based approach to verify whether end-to-end cultural heritage workflows are fully supported by available system functions.
- **Link:** (internal template; can be derived from ECCCH vertical application use cases)

### Additional properties

- **Type of tool:** checklist / matrix.
- **Degree of automation:** manual completion, can be stored in spreadsheets or issue trackers.

## Automated functional test suites + coverage tools (e.g. JUnit/pytest/Jest with JaCoCo, coverage.py, Istanbul)

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_AUTOMATED_FUNCTIONAL_TEST`
- **Dimensions covered:** Pass/fail status of functional behaviour; test coverage (correctness, partial completeness).
- **Description:** Provides automated execution and measurement of functional tests to verify correctness of implemented behaviour and quantify test coverage of functional requirements.
- **Link:** https://www.jacoco.org/jacoco/
https://coverage.readthedocs.io/
https://istanbul.js.org/

### Additional properties

- **Type of tool:** testing tools / software libraries.
- **Degree of automation:** highly automated execution within CI pipelines.

## OpenAPI-based API contract testing (e.g. Dredd, Schemathesis)

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_OPENAPI_BASED_API`
- **Dimensions covered:** Conformance of API behaviour to specified contract; robustness and correctness of API-level functions.
- **Description:** Provides automated validation of API behaviour against formally specified OpenAPI contracts to ensure functional correctness and robustness at the interface level.
- **Link:** https://dredd.org/
https://schemathesis.io/
https://schemathesis.readthedocs.io/

### Additional properties

- **Type of tool:** testing frameworks / tools.
- **Degree of automation:** fully automated once configured.

## Property-based / fuzz testing libraries (e.g. Hypothesis; Schemathesis property-based mode)

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_PROPERTY_BASED_FUZZ`
- **Dimensions covered:** Correctness and robustness of functional behaviour under varied and edge-case inputs.
- **Description:** Provides automated generation and execution of test cases based on properties and invariants to detect functional defects under a wide range of input conditions.
- **Link:** https://hypothesis.works
https://hypothesis.readthedocs.io/
https://schemathesis.io/

### Additional properties

- **Type of tool:** testing methodology and libraries.
- **Degree of automation:** largely automated test generation and execution.

## ISO 25010-based Functional Suitability Questionnaire

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_ISO_BASED_FUNCTIONAL`
- **Dimensions covered:** Perceived functional completeness, correctness, appropriateness from end-user perspective.
- **Description:** Provides a structured questionnaire to capture end-user perceptions of functional completeness, correctness and appropriateness of software services.
- **Link:** (can be implemented in tools such as LimeSurvey, or Google Forms)

### Additional properties

- **Type of tool:** questionnaire / survey instrument.
- **Degree of automation:** user-based; administration and scoring can be semi-automated via survey tools.

## Structured interview protocol with cultural heritage professionals

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_STRUCTURED_INTERVIEW_PROTOCOL`
- **Dimensions covered:** Qualitative assessment of completeness of functions, correctness issues encountered, and appropriateness to workflows.
- **Description:** Provides a qualitative interview-based method to collect in-depth feedback from domain professionals on functional gaps, correctness issues and workflow fit.
- **Link:** (internal protocol; can be documented as part of WP9 evaluation handbook)

### Additional properties

- **Type of tool:** interview protocol / qualitative method.
- **Degree of automation:** user-based, manually conducted and analysed.

## Task-based user test protocol (scenario-based functional evaluation)

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_TASK_BASED_USER`
- **Dimensions covered:** Task success, errors, efficiency, alignment of functions with real workflows (appropriateness, plus completeness/correctness checks).
- **Description:** Provides a scenario-based testing protocol to evaluate whether users can successfully complete representative tasks using available system functions.
- **Link:** (can be implemented with tools such as open-source screen recording combined with log analysis)

### Additional properties

- **Type of tool:** usability / functional testing protocol.
- **Degree of automation:** user-based observation; metrics collection can be semi-automated (screen recording, logging).

## Usage analytics dashboards for ECCCH services

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_USAGE_ANALYTICS_DASHBOARDS`
- **Dimensions covered:** Actual use of functions, feature adoption, workarounds, error frequencies (mainly appropriateness, indirectly completeness and correctness).
- **Description:** Provides analytics-based insight into real-world usage of system functions to assess functional appropriateness, detect underused features and identify functional gaps.
- **Link:** (can be implemented using tools such as Matomo, Plausible, or custom Grafana/Kibana dashboards)

### Additional properties

- **Type of tool:** analytics instrumentation and dashboards.
- **Degree of automation:** largely automated data collection and reporting once instrumentation is in place.

## Data validation and semantic consistency test suites (e.g. SHACL, SPARQL-based checks)

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_DATA_VALIDATION_AND`
- **Dimensions covered:** Correctness and consistency of data and semantic structures produced by ECCCH functions (functional correctness at data level).
- **Description:** Provides automated validation of data and semantic outputs against defined constraints to ensure functional correctness and consistency at the data level.
- **Link:** https://www.w3.org/TR/shacl/
https://www.w3.org/TR/shacl12-core/

### Additional properties

- **Type of tool:** validation rules / test suites.
- **Degree of automation:** highly automated validation once rules are defined.

## Workflow-oriented functional coverage matrix for Digital Twins

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_WORKFLOW_ORIENTED_FUNCTIONAL`
- **Dimensions covered:** Coverage of Digital Twin–related tasks and operations (completeness and appropriateness).
- **Description:** Provides a matrix-based artefact to assess whether required Digital Twin operations are supported across tools and services within defined workflows.
- **Link:** (internal ECCCH artefact; derived from Digital Twin use cases and vertical applications)

### Additional properties

- **Type of tool:** matrix / checklist.
- **Degree of automation:** manual definition and periodic review.

## Domain expert review checklist (heritage-specific functional appropriateness)

- **ID:** `SOFTWARE_FUNCTIONAL_TOOLS_DOMAIN_EXPERT_REVIEW`
- **Dimensions covered:** Appropriateness of functions to CH research and professional practice (e.g. provenance capture, collaboration, interpretive work).
- **Description:** Provides a domain-specific expert checklist to assess whether system functions appropriately support cultural heritage research and professional practices.
- **Link:** (internal checklist; can be based on CH guidelines and best practices from participating institutions)

### Additional properties

- **Type of tool:** heuristic checklist.
- **Degree of automation:** user-based, expert-driven.
