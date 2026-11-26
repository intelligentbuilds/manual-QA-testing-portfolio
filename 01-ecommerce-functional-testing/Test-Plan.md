
# Test Plan – E-commerce Functional Testing

## 1. Document Information

| Field | Details |
|---|---|
| Project Name | E-commerce Functional Testing |
| Application | SauceDemo (Swag Labs) |
| Application URL | https://www.saucedemo.com/ |
| Prepared By | Michael Upshaw |
| Role | Manual QA Tester (Portfolio Project) |
| Version | 1.0 |
| Date | November 26, 2026 |
| Review Date | November 26, 2026 |
| Status | Final |
| Testing Type | Manual Functional Testing |


## 2. Project Overview

This project focuses on manually testing the functionality of SauceDemo, a demonstration e-commerce web application.

The purpose of this project is to evaluate application behavior, identify potential defects, validate expected functionality, and document testing results using structured software quality assurance practices.

Testing will focus on common customer workflows, including authentication, product browsing, shopping cart management, and checkout functionality.

## 3. Testing Objectives

- Verify that core application features function as expected.
- Validate positive and negative user scenarios.
- Identify and document reproducible software defects.
- Evaluate end-to-end customer purchasing workflows.
- Compare expected results against actual application behavior.
- Maintain clear and traceable testing documentation.
- Provide a final summary of application quality based on observed testing results.

  
## 4. Testing Scope

### 4.1 In Scope

The following functional areas will be evaluated during manual testing of the SauceDemo application:

| Module | Testing Coverage |
|---|---|
| Authentication | Valid login, invalid login, locked-out users, and logout |
| Product Inventory | Product listings, descriptions, images, and prices |
| Product Sorting | Sorting products by name and price |
| Product Details | Product information and navigation |
| Shopping Cart | Adding items, removing items, cart count, and cart contents |
| Checkout Information | Required fields, valid inputs, and missing information |
| Order Review | Product accuracy, subtotal, tax, and total calculations |
| Order Confirmation | Successful completion of a simulated purchase |
| Navigation | Menu functionality, buttons, links, and page transitions |
| Error Handling | Validation messages and application responses to invalid inputs |

### 4.2 Out of Scope

The following testing activities are excluded from this project:

- Automated software testing
- Performance and load testing
- Security and penetration testing
- API and backend testing
- Database validation
- Real payment processing
- Comprehensive cross-browser compatibility testing
- Mobile device compatibility testing
- Comprehensive accessibility compliance testing

### 4.3 Scope Limitations

Testing will be conducted through the application's user interface using publicly available demonstration accounts.

The project will focus on observable application behavior. Backend systems, source code, and internal databases will not be evaluated.

Expected results will be based on available application information, observable workflows, and documented testing assumptions. Any identified defects will be supported by actual test execution and reproducible evidence.

## 5. Test Environment

### 5.1 Hardware and Software Configuration

| Component | Specification |
|---|---|
| Computer | MacBook Air 13-inch (M4, 2025) |
| Processor | Apple M4 |
| Memory | 16 GB RAM |
| Operating System | macOS 26.7.3 (25G342) |
| Web Browser | Microsoft Edge |
| Browser Version | 158.0.4370.33 (Official build) (arm64) |
| Application | SauceDemo (Swag Labs) |
| Application URL | https://www.saucedemo.com/ |
| Application Environment | Public demonstration environment |
| Application Build Version | Not confirmed |
| Testing Method | Manual UI-based testing |

### 5.2 Testing Tools

| Tool | Purpose |
|---|---|
| Microsoft Edge | Manual test execution |
| GitHub | Documentation, version control, and portfolio management |
| Markdown | Test plans, defect reports, and QA summaries |
| Microsoft Excel | Test case design and execution tracking |
| macOS Screenshot Utility | Capturing visual testing evidence |

### 5.3 Test Accounts

The following demonstration accounts are planned for testing:

| Username | Intended Testing Purpose |
|---|---|
| standard_user | Baseline functional testing |
| locked_out_user | Account restriction and negative testing |
| problem_user | Investigation of potential functional issues |
| error_user | Investigation of error-related behavior |
| visual_user | Investigation of visual inconsistencies |

Public demonstration credentials provided by the application will be used.

### 5.4 Test Data

Testing will include the following data categories:

- Valid usernames and passwords
- Invalid usernames and passwords
- Empty authentication fields
- Valid customer checkout information
- Missing required checkout information
- Single-product shopping carts
- Multiple-product shopping carts
- Product prices and order totals

All customer information used during testing will be fictional. No real personal, financial, or payment information will be submitted.

### 5.5 Environment Management

- Record the environment used during test execution.
- Reset application state between tests when required.
- Document browser or operating system changes.
- Maintain consistent test conditions where possible.
- Capture screenshots of observed defects and relevant test results.
- Record any environmental limitations affecting test execution.


## 6. Testing Strategy

### 6.1 Testing Approach

Testing will be performed manually using a black-box testing approach. Application functionality will be evaluated through the user interface without examining internal source code or implementation details.

Test cases will be designed to evaluate expected application behavior, identify functional inconsistencies, and validate common customer workflows.

### 6.2 Testing Techniques

| Testing Technique | Purpose |
|---|---|
| Smoke Testing | Verify that essential application features are operational before detailed testing |
| Functional Testing | Validate individual application features against expected behavior |
| Positive Testing | Verify application behavior using valid inputs |
| Negative Testing | Evaluate application responses to invalid or missing inputs |
| Equivalence Partitioning | Group similar test inputs into representative categories |
| Boundary Value Analysis | Evaluate input values at and around established limits where applicable |
| End-to-End Testing | Validate complete customer purchasing workflows |
| Exploratory Testing | Investigate application behavior beyond predefined test cases |
| Retesting | Verify previously reported defects following a confirmed correction |
| Regression Testing | Verify that existing functionality remains operational following application changes |

### 6.3 Test Execution Approach

Testing will follow a structured sequence:

1. Verify application availability and environment readiness.
2. Perform initial smoke testing.
3. Execute authentication test cases.
4. Execute product inventory and sorting test cases.
5. Execute shopping cart test cases.
6. Execute checkout and order confirmation test cases.
7. Conduct targeted exploratory testing.
8. Document actual results and observed defects.
9. Perform retesting and regression testing when applicable.
10. Prepare a final test execution summary.

### 6.4 Test Result Classification

| Status | Definition |
|---|---|
| Pass | Actual behavior matches the expected result |
| Fail | Actual behavior differs from the expected result |
| Blocked | Testing cannot proceed due to a dependency or environmental issue |
| Not Run | The test case has not been executed |
| Not Applicable | The test case does not apply to the current testing conditions |

### 6.5 Evidence and Traceability

Each test case will have a unique identifier and documented expected and actual results.

Observed defects will be linked to relevant test cases where applicable and supported by reproducible steps, screenshots, and environmental information.

Test results will reflect actual application behavior. Unexecuted tests will not be recorded as passed or failed.

Testing techniques requiring confirmed input limits or application changes will only be applied when those conditions are available.


## 7. Entry and Exit Criteria

### 7.1 Entry Criteria

The following conditions must be satisfied before formal test execution begins:

- The SauceDemo application is accessible.
- The test environment is configured and documented.
- The test plan is completed and reviewed.
- Test cases are designed and documented.
- Required demonstration accounts are available.
- Necessary test data has been prepared.
- Expected results are defined for planned test cases.
- Testing documentation and evidence collection tools are available.

### 7.2 Exit Criteria

The following conditions must be satisfied before testing is considered complete:

- All applicable planned test cases have been executed or have documented reasons for being blocked or not executed.
- Actual results and execution statuses are documented.
- Identified defects have been recorded with reproducible steps.
- Defect severity and priority have been assessed.
- Relevant screenshots and testing evidence have been collected.
- Retesting and regression testing have been performed where applicable.
- Outstanding defects, risks, and limitations are documented.
- A final QA summary and test execution report have been completed.

### 7.3 Suspension Criteria

Testing may be temporarily suspended under the following conditions:

- The application becomes unavailable.
- Network connectivity prevents test execution.
- Required demonstration accounts become inaccessible.
- A critical defect prevents further testing.
- Environmental issues make test results unreliable.

### 7.4 Resumption Criteria

Testing may resume when:

- Application accessibility has been restored.
- Environmental issues have been resolved.
- Required test accounts and data are available.
- Blocking conditions have been removed or an appropriate workaround is documented.
- The testing environment has been verified.

### 7.5 Test Completion Metrics

The following metrics will be recorded in the final test report:

- Total planned test cases
- Total executed test cases
- Passed test cases
- Failed test cases
- Blocked test cases
- Not executed test cases
- Not applicable test cases
- Test execution rate
- Test pass rate
- Total defects identified
- Defects categorized by severity and priority

Final testing conclusions will be based on documented execution results rather than assumed application quality.


#### Metric Calculation Formulas

- Total applicable test cases = Total planned test cases
  - Not applicable test cases
- Total executed test cases = Passed + Failed
- Test execution rate (%) = (Total executed test cases /
  Total applicable test cases) x 100
- Test pass rate (%) = (Passed /
  Total executed test cases) x 100

Blocked and Not Run test cases will be tracked separately.

When a calculation denominator is zero, the metric will
be reported as Not Applicable (N/A).


## 8. Defect Management

### 8.1 Defect Identification

Potential defects will be identified by comparing actual application behavior against documented expected results.

Each potential defect will be investigated to determine whether the behavior represents a software issue, expected application behavior, a test data issue, or an environmental limitation.

Defects will be reproduced where possible before being formally documented.

### 8.2 Defect Reporting

Each defect report will contain the following information:

- Unique defect identifier
- Defect title
- Date reported
- Application module
- Associated test case identifier, where applicable
- Test environment
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Defect status
- Reproducibility
- Supporting screenshots or evidence
- Additional observations

Defects will be documented in the Bug-Reports.md file.

### 8.3 Defect Severity Classification

| Severity | Description |
|---|---|
| Critical | Essential application functionality is unavailable with no reasonable workaround |
| High | Major functionality is significantly affected |
| Medium | Functionality is partially affected or a reasonable workaround exists |
| Low | Minor cosmetic, usability, or non-critical functionality issue |

### 8.4 Defect Priority Classification

| Priority | Description |
|---|---|
| P1 - Urgent | Requires immediate attention |
| P2 - High | Should be addressed as soon as reasonably possible |
| P3 - Medium | Can be scheduled for resolution |
| P4 - Low | Can be addressed when resources permit |

Severity and priority will be assessed independently based on functional impact and estimated business urgency.

### 8.5 Defect Lifecycle

A typical professional defect lifecycle includes:

1. New
2. Triaged
3. Assigned
4. In Progress
5. Resolved
6. Retesting
7. Closed or Reopened

For this independent portfolio project, defect statuses will reflect only activities that have actually occurred.

Developer assignments, corrections, and defect closures will not be fabricated.

### 8.6 Defect Verification and Evidence

Before documenting a defect, the tester will:

- Repeat the reproduction steps where possible.
- Confirm the expected behavior or document the underlying assumption.
- Verify that the correct test data and account were used.
- Investigate potential environmental or configuration issues.
- Record the frequency of occurrence.
- Capture relevant screenshots or other supporting evidence.
- Check for duplicate defect reports.

Intermittent issues will be documented with their observed frequency and reproduction conditions.

### 8.7 Defect Tracking and Traceability

Defects will use the following identification format:

- BUG-001
- BUG-002
- BUG-003

Each defect will be linked to its associated test case when applicable.

Known demonstration behaviors will be distinguished from unexpected application defects. Behaviors observed through intentionally problematic demonstration accounts will be identified accordingly.

Unresolved defects and testing limitations will be included in the final QA summary report.


## 9. Risks and Limitations

### 9.1 Risk Assessment

The following potential risks have been identified during test planning. Risk assessments are preliminary estimates and may be updated throughout test execution.

| Risk ID | Risk Description | Likelihood | Impact | Risk Level |
|---|---|---|---|---|
| RISK-001 | Application unavailability | Low | High | Medium |
| RISK-002 | Internet connectivity interruption | Medium | Medium | Medium |
| RISK-003 | Unexpected application updates | Medium | High | High |
| RISK-004 | Incorrect or incomplete test data | Medium | Medium | Medium |
| RISK-005 | Loss of testing documentation or evidence | Low | High | Medium |
| RISK-006 | Misclassification of intentional demonstration behavior as a defect | Medium | High | High |
| RISK-007 | Incomplete test coverage | Medium | High | High |
| RISK-008 | Browser or operating system configuration changes | Medium | Medium | Medium |

### 9.2 Risk Mitigation

| Risk ID | Mitigation Strategy |
|---|---|
| RISK-001 | Verify application availability before testing and resume when service is restored |
| RISK-002 | Verify network connectivity and document interrupted test executions |
| RISK-003 | Record testing dates and available application version information |
| RISK-004 | Prepare and validate test data before execution |
| RISK-005 | Maintain documentation in GitHub and retain local backups of testing evidence |
| RISK-006 | Compare account behavior against available documentation and baseline functionality |
| RISK-007 | Map test cases to defined functional areas and review coverage before test closure |
| RISK-008 | Record environment changes and repeat affected test cases when necessary |

### 9.3 Testing Limitations

The following limitations apply to this project:

- Testing is limited to a publicly available demonstration application.
- Testing is performed by a single independent QA tester.
- Access to application source code, backend systems, and databases is unavailable.
- Formal business requirements and acceptance criteria may be limited or unavailable.
- Testing is primarily conducted using Microsoft Edge on macOS.
- Comprehensive browser and device compatibility testing is excluded.
- Real financial transactions and payment processing are not evaluated.
- Application updates and defect corrections are outside the tester's control.
- Testing cannot guarantee that every possible defect has been identified.

### 9.4 Assumptions and Dependencies

This project depends on the following conditions:

- The SauceDemo application remains publicly accessible.
- Demonstration accounts remain available for testing.
- The documented testing environment remains operational.
- Testing and documentation tools remain accessible.
- Expected behavior can be established through available documentation, baseline functionality, or clearly documented assumptions.

### 9.5 Risk and Limitation Reporting

Any risks or limitations that affect test execution, coverage, reproducibility, or result accuracy will be documented in the test execution report and final QA summary.

Final conclusions will be limited to the functionality, test data, environment, and scenarios actually evaluated.


## 10. Test Deliverables

### 10.1 Planned Deliverables

The following deliverables will be produced throughout the E-commerce Functional Testing project:

| Deliverable ID | Deliverable | File Name | Purpose |
|---|---|---|---|
| DEL-001 | Test Plan | Test-Plan.md | Define testing objectives, scope, strategy, environment, and procedures |
| DEL-002 | Test Cases | Test-Cases.xlsx | Document test scenarios, preconditions, test steps, and expected results |
| DEL-003 | Test Execution Results | Test-Cases.xlsx | Record actual results, execution statuses, and associated defect identifiers |
| DEL-004 | Test Execution Report | Test-Execution-Report.md | Summarize test execution activities, coverage, and results |
| DEL-005 | Bug Reports | Bug-Reports.md | Document observed defects, reproduction steps, severity, priority, and evidence |
| DEL-006 | Testing Evidence | Screenshots/ | Maintain visual evidence supporting test results and defect reports |
| DEL-007 | QA Summary Report | QA-Summary-Report.md | Present overall findings, unresolved issues, limitations, and recommendations |

### 10.2 Deliverable Schedule

| Testing Phase | Expected Deliverables |
|---|---|
| Test Planning | Test Plan |
| Test Design | Test Cases and Test Data |
| Test Execution | Execution Results and Testing Evidence |
| Defect Reporting | Bug Reports and Supporting Evidence |
| Test Closure | Test Execution Report and QA Summary Report |

### 10.3 Documentation Standards

All testing deliverables will follow consistent documentation standards:

- Clear and professional formatting
- Unique test case and defect identifiers
- Accurate and reproducible test steps
- Clearly defined expected and actual results
- Consistent terminology and status classifications
- Traceability between test cases, defects, and evidence
- Accurate testing dates and environment information
- Version-controlled documentation

### 10.4 Deliverable Storage and Version Control

All project deliverables will be maintained within the manual-QA-testing-portfolio GitHub repository.

Project-specific documentation will be stored within the 01-ecommerce-functional-testing directory.

GitHub commit history will be used to track documentation changes throughout the testing lifecycle.

Screenshots and supporting evidence will use descriptive filenames and reference associated test case or defect identifiers where applicable.

### 10.5 Deliverable Completion Criteria

A deliverable will be considered complete when:

- All required information has been documented.
- Content has been reviewed for accuracy and completeness.
- Formatting and readability have been verified.
- Relevant test cases, defects, and evidence are traceable.
- The deliverable accurately reflects actual testing activities.
- The final version has been committed to GitHub.

No test results, defects, evidence, or execution activities will be fabricated.

### 10.6 Project Completion Statement

The completed project will demonstrate practical manual software testing skills, including test planning, test case design, functional testing, defect identification, defect reporting, evidence collection, and QA reporting.

All conclusions will be supported by documented observations and actual test execution results.
