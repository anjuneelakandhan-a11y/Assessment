# AcademyBugs.com – QA Automation & Functional Testing Capstone Project

------------

-   **Author**: Anju N
-   **Role**: QA Engineer
-   **Tools Used**: Java | Selenium WebDriver | TestNG | Maven | Page Object Model | lots of :coffee: :wink:
-   **Project Type**: Automation + Manual Functional Testing

------------

## 1. Project Overview

This capstone project focuses on testing AcademyBugs.com, a demo web application intentionally seeded with functional and UI bugs for QA practice.
The goal of the project was to:

  ⦁	Identify functional, UI, and validation defects

  ⦁	Automate core workflows using Selenium

  ⦁	Validate e-commerce features, form validations, and bug-report popups

  ⦁	Gain hands-on experience with real-world automation challenges such as dynamic waits, popups, and window handling

## 2. Objectives

  -	Build a maintainable automation framework using Java + Selenium + TestNG + Maven + POM

  -	Execute end-to-end manual test cases across all modules

  -	Perform exploratory testing to uncover hidden issues

  -	Capture real defects and document them systematically

  -	Integrate DataProviders and arrays to run multi-country billing scenarios

## 3. Scope of Testing

### :white_check_mark: In-Scope
  - Login, Registration & Forgot Password
  -	Product Search, Cart & Checkout
  -	Billing Information (Country/State dependency)
  -	Bug Popup & Bug Badge workflow
  -	Window handling (new tabs, tutorial popups)
  -	Exploratory testing across product pages

### :x: Out of Scope 
  -	API testing
  -	Backend or database verification
  -	Payment gateway processing
  -	Performance/load testing

## 4. Technology Stack

| Component | Purpose |
| -------- | ------- |
| Java | Programming language |
| Selenium WebDriver | Browser Automation |
| TestNG | Test framework + Assertions + DataProviders |
| Maven	| Build & dependency management
| Page Object Model (POM) | Framework design pattern |
| ChromeDriver/GeckoDriver/EdgeDriver | Browser execution |


## 5. Automation Framework Highlights

-	Implemented POM for reusable and maintainable locators
-	Used DataProviders to execute multi-country billing tests
-	Used Arrays to handle dynamic input & iteration
-	Implemented explicit waits for popups, slow loaders

### :star2: Automated: 

  -	Login & registration flows
  -	Bug reporting submission
  -	Quantity update in cart
  -	Multi-country dropdown validation
  -	Popup closing utility

## 6. Manual & Automation Execution Summary

| Test Type | Executed | Passed | Failed | Blocked |
| :--- | :---: | :---: | :---: | :---: |
| **Manual Functional** | 217 | 177 | 37 | 3 |
| **Automation** | 47 | 39 | 8 | 2 (App defects) |


### :anger: Blocked Scenarios 

  -	Billing Information page stuck on loader
  -	Forgot Password freezing the page
  -	Currency crash blocking validation
  -	Hot Item infinite loading
