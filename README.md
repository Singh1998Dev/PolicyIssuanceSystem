Policy Issuance Automation Framework
About This Project

This project is a Selenium automation suite built to test the end‑to‑end Policy Issuance journey on the Policy Search portal.

The idea behind building this was simple - instead of manually testing the same login, OTP, quote and policy flows again and again, we automate the entire journey and validate the important checkpoints along the way.

It covers both negative and positive scenarios, including real error validations that occur during quote generation.

What This Framework Covers
Login & OTP

Invalid mobile number validation

OTP generation failure handling

Wrong OTP verification

Successful login flow
Quote Journey

Automates the complete vehicle selection and quote process:
Select Manufacturer → TATA
Select Model → HARRIER EV
Select Variant → ADVENTURE
Select Registration Date
Select RTO → KA28
Choose → No Previous Policy
Select Cover → Comprehensive
Skip customer details
Error Validation
Validates the quote engine error:

Invalid Make Code or Model Code, Error During Quote ENQ
Logout
Waits for logout button
Performs logout
Confirms user is back on login screen

Tech Stack Used

Java - Core programming language
Selenium WebDriver - UI automation
TestNG - Test execution & assertions
Extent Reports - HTML reporting
WebDriverManager - Driver handling
Gradle - Build & dependency management
Reporting

Execution report is generated here:
test-output/ExtentReport.html

The report includes:
Test status (Pass/Fail)
Execution timestamps
Step logs
Screenshots attached to tests

Screenshots are automatically captured during validations.

Author

Devraj Singh
Automation Test Engineer
devrajsinghh455@gmail.com
