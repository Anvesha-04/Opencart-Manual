# Opencart-Manual
OpenCart-Manual

Project Overview

OpenCart-Manual is a manual software testing project focused on
validating the frontend functionality of an OpenCart e-commerce
application. The project covers requirement analysis, test scenario
identification, test case design, manual execution, defect reporting,
and requirement traceability.

The project documentation is based on the Functional Requirement
Specification (FRS), Test Plan, Test Scenarios, Test Cases, Requirement
Traceability Matrix (RTM), and Bug Report prepared for the application.

Project Name: OpenCart-Manual
Application: OpenCart
Testing Type: Manual Testing
Prepared By: Anvesha
Primary Reference: Functional Requirement Specification (FRS)

Objectives

The main objectives of this project are to:

Validate the functional requirements of the OpenCart frontend.

Verify important customer-facing e-commerce workflows.

Design and execute manual test cases against the documented
requirements.

Identify, document, and prioritize defects.

Maintain traceability between requirements, scenarios, test cases,
and defects.

Validate functional behavior across supported browsers.

Perform regression and re-testing activities for identified defects.

Provide structured QA deliverables for the testing lifecycle.

Application Overview

OpenCart is an open-source e-commerce platform for online merchants. The
application provides a storefront through which customers can browse
products, search for products, compare products, add products to a cart,
manage their account, and complete checkout.

The FRS describes the storefront architecture and customer workflows,
including:

Home page

Header and navigation

Product pages

Category product listings

Product comparison

Shopping cart

Account registration and login

Checkout

Order confirmation

Order history

Scope of Testing

In Scope

The Test Plan identifies the following major areas for testing:

Register Account

Login and Logout

Home Page

Search

Product Compare

Product Detail Page

Add to Cart

Wish List

Shopping Cart

Currency selection

Checkout

My Account

Order History

Cross-browser behavior

Functional testing

Integration testing

Performance testing

Regression testing

UAT from the tester's perspective

Fixed-defect validation

The Test Plan also identifies specific storefront behaviors such as
navigation, product display, category browsing, search, cart operations,
and checkout flows.

Out of Scope

The Test Plan lists the following as out of scope:

Database Testing

API Testing

Automation Testing

Features added later

Requirements and Information Architecture

The FRS defines the OpenCart storefront and its main customer
interaction areas.

Home Page

Testing includes navigation to the home page, featured products, partner
carousel behavior, header links, and navigation elements.

Product Page

The product page includes:

Product image and alternate views

Product details

Product code and availability

Price

Quantity selection

Add to Cart

Wish List

Product Compare

Rating and sharing

Description

Review tab

Category Product Listing

Category pages allow users to:

Browse products within categories and subcategories.

Refine searches.

Switch between list and grid views.

Sort products by name, price, rating, or model.

Change the number of displayed products.

Add products to the cart.

Add products to the wish list.

Add products to comparison.

Product Compare

The Product Compare functionality allows customers to compare product
specifications, features, and prices.

Shopping Cart

The shopping cart validates product information including:

Product image

Product name

Model

Quantity

Unit price

Total

The cart also provides options for coupons, gift vouchers, shipping and
tax estimation, continuing shopping, and checkout.

Account Management

The project covers registration, login, logout, account navigation,
password-related behavior, and account-related pages.

Checkout

The documented checkout process contains six steps:

Checkout options

Billing details

Delivery details

Delivery method

Payment method

Confirm order

The FRS also describes successful order placement and access to order
history.

Test Scenarios

The Test Scenario document contains eight primary scenarios:

Scenario ID   Scenario                                  Priority   Test Cases

TS_001        Verify Register Account functionality           P0           23
TS_002        Verify Login functionality                      P0           21
TS_003        Verify Logout functionality                     P0           11
TS_004        Verify Home Page Functionality                  P2            9
TS_005        Verify Checkout functionality                   P1           20
TS_006        Verify Search functionality                     P1           18
TS_007        Verify Add to Cart functionality                P1            9
TS_008        Verify My Account functionality                 P2            8

These scenarios are referenced by the test cases and linked back to the
FRS through the testing documentation.

Test Case Design

The test case workbook contains structured test cases with fields such
as:

Test Case ID

Test Scenario

Test Case Title

Preconditions

Test Steps

Test Data

Expected Result

Actual Result

Priority

Result

Examples of covered validations include:

Navigation between OpenCart pages.

Home page and featured product behavior.

Search with existing and non-existing product names.

Search using product description text.

Adding products to the cart from different application locations.

Checkout navigation and signed-in checkout.

My Account navigation and login behavior.

Test cases use OpenCart sample products such as Canon EOS 5D,
iMac, Mac, and Apple Cinema 30" where applicable.

Test Methodology

The Test Plan specifies an Agile approach with weekly iterations.
Testing activities follow the requirements and testing strategy
documented in the Test Plan.

Testing Levels and Types

The project includes:

Functional Testing

Integration Testing

Performance Testing

Cross-browser Testing

Security Testing for payment-related behavior

User Acceptance Testing (UAT)

Regression Testing

Progress Testing

Fixed-defect validation

Test Execution Flow

Review and understand requirements.

Prepare test scenarios and test cases.

Review test cases and test coverage.

Prepare test data.

Execute test cases manually.

Record actual results and Pass/Fail status.

Log defects for failed validations.

Re-test fixed defects.

Perform regression testing where required.

Prepare testing reports and deliverables.

Entry Criteria

Testing can begin when the documented entry conditions are satisfied,
including:

Requirements and FRS are understood.

QA resources have sufficient knowledge of the functionality.

Test Plan, Test Scenarios, and Test Cases are approved.

Required documentation and design information are available.

Unit test cases pass.

Application smoke testing is completed where applicable.

Exit Criteria

The Test Plan defines exit conditions including:

Planned test case execution is completed.

Required test coverage is achieved.

Relevant Severity 1 and Severity 2 defects are completed.

No high-priority defect remains outstanding.

UAT test evidence is collected.

Test Closure documentation is completed and signed off.

Defect Management

Defects are documented in the Bug Report with information including:

Bug ID

Description / Summary

Steps to Reproduce

Expected Result

Actual Result

Severity

Priority

Screenshot

Examples of defects recorded in the project include:

Leading and trailing spaces being accepted in registration fields.

Unexpected logout behavior when using browser navigation.

Missing warning after repeated unsuccessful login attempts.

Password visibility in page source.

Old password remaining usable after a password change.

Registration confirmation email not being received.

Weak passwords being accepted.

Search by product description not working.

The bug report contains both functional and security-related
observations, with severity and priority assigned to support defect
handling.

Requirement Traceability Matrix

The RTM maps requirements to:

Requirement → Test Scenario → Test Case → Test Result → Defect

The RTM includes requirement descriptions, scenario IDs, test case IDs,
test results, defect IDs, and defect status fields.

This provides traceability between the original FRS requirements and
their corresponding validation activities.

Test Deliverables

Before Testing

Functional Requirement Specification (FRS)

Test Plan

Test Scenarios

Test Cases

Test Design Specifications

During Testing

Test Data

Requirement Traceability Matrix (RTM)

Test Execution Results

Error / Execution Logs

After Testing

Test Results / Reports

Defect Report

Installation / Test Procedure Guidelines

Release Notes

Test Environment

The Test Plan documents the following environment information:

Operating Environment

Windows 10

4 GB RAM

3.4 GHz CPU

LAN with at least 5 Mb/s speed

Application / Server Requirements

The FRS identifies:

PHP 5.4

JavaScript

MySQL database

Apache web server

Supported Browsers

The documented browser support includes:

Microsoft Edge

Google Chrome

Mozilla Firefox

Safari

Testing Tools

Activity                   Tool

Test Case Creation         Microsoft Excel
Test Case Tracking         Microsoft Excel
Test Case Execution        Manual
Test Case Management       Microsoft Excel
Defect Management          Microsoft Excel
Test Reporting             Microsoft Excel & Jira
Configuration Management   GitHub

Test Schedule

The documented test schedule includes activities such as:

FRS

Test Planning

Review Requirements Documents

Create Test Basis

Staff and Train New Test Resources

First Deploy to QA Test Environment

Functional Testing -- Iteration 1

Iteration 2 Deploy to QA Test Environment

Functional Testing -- Iteration 2

System Testing

Regression Testing

UAT

Final Defect Resolution and Build Testing

Deployment to Staging Environment

Performance Testing

Release to Production

The schedule assigns the documented activities to Anvesha where an
owner is specified.

Project Documents

This project is supported by the following QA artifacts:

OpenCart-Manual/
│
├── FRS_1(1).pdf
├── Test_plan_1(1).pdf
├── test_scenario_1(1).xlsx
├── test_cases_all(1).xlsx
├── RTM_1(1).xlsx
├── Bug_Report_1(1).xlsx
└── README.md

QA Workflow

FRS
 │
 ▼
Requirement Analysis
 │
 ▼
Test Scenario Design
 │
 ▼
Test Case Design
 │
 ▼
Test Data Preparation
 │
 ▼
Manual Test Execution
 │
 ├── PASS ───────────────┐
 │                       │
 └── FAIL → Bug Report   │
              │          │
              ▼          │
          Bug Fix        │
              │          │
              ▼          │
           Re-testing ───┘
              │
              ▼
       Regression Testing
              │
              ▼
       Test Reporting
              │
              ▼
          Test Closure

Key QA Skills Demonstrated

This project demonstrates practical experience in:

Manual Testing

Functional Testing

Integration Testing

Regression Testing

UAT

Test Scenario Design

Test Case Design

Test Case Execution

Test Data Preparation

Requirement Analysis

Requirement Traceability

Defect Identification

Defect Reporting

Severity and Priority Classification

Re-testing

Cross-browser Testing

Test Reporting

Agile Testing

QA Documentation

Project Outcome

The OpenCart-Manual project provides a structured manual QA process from
requirement analysis through test closure. The project connects the FRS
with test scenarios, detailed test cases, execution results, defect
reports, and the RTM, providing traceability across the testing
lifecycle.

Author

Anvesha

Project: OpenCart-Manual
Role: QA / Manual Testing
Testing Approach: Manual Testing
