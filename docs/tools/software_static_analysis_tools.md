# Software Static Analysis Tools

Static analysis tools.

## Summary

- **Semgrep** — Multi-language static analysis tool with customizable rules.
- **Semgrep - ECHOES endpoint** — ECHOES endpoint for Semgrep tool.
- **SonarQube (Community Edition)** — Comprehensive code quality and security analysis platform. Community edition does not cover all languages/features.
- **CodeQL** — Semantic code analysis engine developed by GitHub; focuses on security vulnerabilities.
- **Lizard** — Cyclomatic Complexity Analyzer for many programming languages includingC#, C/C++, Java, JavaScript, Python and TypeScript.
- **ESLint** — Popular static analysis and linting tool for JavaScript/TypeScript.
- **PMD** — Static analyzer for Java and other languages (includes JS support).
- **cppcheck** — Static analysis tool for C and C++ detecting bugs and undefined behavior.
- **Clang-Tidy** — Part of LLVM/Clang project; performs linting and static analysis for C/C++/Objective-C.
- **Infer** — Static analysis tool from Meta for C, C++, Java, and Objective-C focused on bug detection.
- **OCLint** — Analyzes C, C++, and Objective-C code for potential issues and style violations.

## Semgrep

- **ID:** `SOFTWARE_STATIC_ANALYSIS_SEMGREP`
- **Dimensions covered:** security, quality.
- **Description:** Multi-language static analysis tool with customizable rules.
- **Link:** https://github.com/semgrep/semgrep

### Additional properties

- **Analysis type:** Static.
- **JS support:** yes.
- **C++ support:** yes.
- **python support:** yes.
- **Java support:** yes.
- **Open source:** yes.
- **License (for use in open source platforms):** LGPL-2.1.
- **GitHub integration:** Yes (via CI/GitHub Actions).

## Semgrep - ECHOES endpoint

- **ID:** `SOFTWARE_STATIC_ANALYSIS_SEMGREP_ECHOES_ENDPOINT`
- **Dimensions covered:** security, quality.
- **Description:** ECHOES endpoint for Semgrep tool.
- **Link:** https://candujar.app.n8n.cloud/form/97353602-4c6d-4e30-9503-c879acacc4d7

### Additional properties

- **Analysis type:** Static.
- **JS support:** yes.
- **C++ support:** yes.
- **python support:** yes.
- **Java support:** yes.
- **Open source:** yes.
- **License (for use in open source platforms):** LGPL-2.1.

## SonarQube (Community Edition)

- **ID:** `SOFTWARE_STATIC_ANALYSIS_SONARQUBE_COMMUNITY_EDITION`
- **Dimensions covered:** quality, security.
- **Description:** Comprehensive code quality and security analysis platform. Community edition does not cover all languages/features.
- **Link:** https://www.sonarqube.org

### Additional properties

- **Analysis type:** Static.
- **JS support:** yes.
- **C++ support:** no in Community Edition.
- **python support:** yes.
- **Java support:** yes.
- **Open source:** mixed (LGPLv3 core; bundled analyzers SSALv1).
- **License (for use in open source platforms):** LGPLv3 (server); bundled analyzers SSALv1.
- **GitHub integration:** Partial (Community: main-branch analysis only; PR decoration requires paid editions).

## CodeQL

- **ID:** `SOFTWARE_STATIC_ANALYSIS_CODEQL`
- **Dimensions covered:** security.
- **Description:** Semantic code analysis engine developed by GitHub; focuses on security vulnerabilities.
- **Link:** https://codeql.github.com

### Additional properties

- **Analysis type:** Static.
- **JS support:** yes.
- **C++ support:** yes.
- **python support:** yes.
- **Java support:** yes.
- **Open source:** Partly (queries/libraries OSS; CLI/binaries not OSS).
- **License (for use in open source platforms):** MIT (queries/libraries); CodeQL CLI under GitHub CodeQL license/terms.
- **GitHub integration:** yes.

## Lizard

- **ID:** `SOFTWARE_STATIC_ANALYSIS_LIZARD`
- **Dimensions covered:** complexity.
- **Description:** Cyclomatic Complexity Analyzer for many programming languages includingC#, C/C++, Java, JavaScript, Python and TypeScript.
- **Link:** https://github.com/terryyin/lizard

### Additional properties

- **Analysis type:** Static.
- **JS support:** yes.
- **C++ support:** yes.
- **python support:** yes.
- **Java support:** yes.
- **Open source:** yes.
- **License (for use in open source platforms):** MIT.
- **GitHub integration:** Yes (via CI/GitHub Actions), not native.

## ESLint

- **ID:** `SOFTWARE_STATIC_ANALYSIS_ESLINT`
- **Dimensions covered:** style, quality.
- **Description:** Popular static analysis and linting tool for JavaScript/TypeScript.
- **Link:** https://eslint.org

### Additional properties

- **Analysis type:** Static.
- **JS support:** yes.
- **C++ support:** no.
- **python support:** no.
- **Java support:** no.
- **Open source:** yes.
- **License (for use in open source platforms):** MIT.
- **GitHub integration:** Yes (via CI/GitHub Actions), not native.

## PMD

- **ID:** `SOFTWARE_STATIC_ANALYSIS_PMD`
- **Dimensions covered:** quality, style.
- **Description:** Static analyzer for Java and other languages (includes JS support).
- **Link:** https://pmd.github.io

### Additional properties

- **Analysis type:** Static.
- **JS support:** yes.
- **C++ support:** no.
- **python support:** no.
- **Java support:** yes.
- **Open source:** yes.
- **License (for use in open source platforms):** BSD-style (mostly); some components Apache-2.0.
- **GitHub integration:** Yes (via CI/GitHub Actions), not native.

## cppcheck

- **ID:** `SOFTWARE_STATIC_ANALYSIS_CPPCHECK`
- **Dimensions covered:** quality.
- **Description:** Static analysis tool for C and C++ detecting bugs and undefined behavior.
- **Link:** https://cppcheck.sourceforge.io/

### Additional properties

- **Analysis type:** Static.
- **JS support:** no.
- **C++ support:** yes.
- **python support:** no.
- **Java support:** no.
- **Open source:** yes.
- **License (for use in open source platforms):** GPL-3.0.
- **GitHub integration:** Yes (via CI/GitHub Actions), not native.

## Clang-Tidy

- **ID:** `SOFTWARE_STATIC_ANALYSIS_CLANG_TIDY`
- **Dimensions covered:** quality, style.
- **Description:** Part of LLVM/Clang project; performs linting and static analysis for C/C++/Objective-C.
- **Link:** https://clang.llvm.org/extra/clang-tidy

### Additional properties

- **Analysis type:** Static.
- **JS support:** no.
- **C++ support:** yes.
- **python support:** no.
- **Java support:** no.
- **Open source:** yes.
- **License (for use in open source platforms):** Apache-2.0 with LLVM-exception.
- **GitHub integration:** yes.

## Infer

- **ID:** `SOFTWARE_STATIC_ANALYSIS_INFER`
- **Dimensions covered:** security, quality.
- **Description:** Static analysis tool from Meta for C, C++, Java, and Objective-C focused on bug detection.
- **Link:** https://fbinfer.com

### Additional properties

- **Analysis type:** Static.
- **JS support:** no.
- **C++ support:** yes.
- **python support:** no.
- **Java support:** yes.
- **Open source:** yes.
- **License (for use in open source platforms):** MIT.
- **GitHub integration:** yes.

## OCLint

- **ID:** `SOFTWARE_STATIC_ANALYSIS_OCLINT`
- **Dimensions covered:** style, quality.
- **Description:** Analyzes C, C++, and Objective-C code for potential issues and style violations.
- **Link:** http://oclint.org

### Additional properties

- **Analysis type:** Static.
- **JS support:** no.
- **C++ support:** yes.
- **python support:** no.
- **Java support:** no.
- **Open source:** yes.
- **License (for use in open source platforms):** BSD-3-Clause.
- **GitHub integration:** Yes (via CI/GitHub Actions), not native.
