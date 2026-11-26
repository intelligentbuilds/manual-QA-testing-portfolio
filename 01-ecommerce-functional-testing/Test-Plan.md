
# Test Plan — E-commerce Functional Testing

## 1. Document Information

| Field | Details |
|---|---|
| Project Name | E-commerce Functional Testing |
| Application | SauceDemo (Swag Labs) |
| Application URL | https://www.saucedemo.com/ |
| Prepared By | Michael Upshaw |
| Role | Manual QA Tester (Portfolio Project) |
| Document Version | 1.0 |
| Created Date | November 26, 2026 |
| Status | Draft |
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

- 
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

