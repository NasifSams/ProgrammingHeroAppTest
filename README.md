Prerequisites:
Java (JDK 8 or higher)
Maven
Appium Server (running at http://127.0.0.1:4723/wd/hub)
Android Device
Dependencies
Appium Java Client
Selenium Java
TestNG
ExtentReports etc.
Test Cases:
Navigation to Views - Verifies "Views" section opens.
Expandable Lists Selection - Verifies scroll and selection of "Expandable Lists".
Custom Adapter - Long press on "People Names" and validate popup.
Drag and Drop - Perform drag-and-drop from "circle1" to "circle2" and check "Dropped" indicator.
Common Issues
Appium Server Not Running: Ensure appium is running.
Device Not Found: Run adb devices to confirm connection.
Element Not Found: Verify locators; add waits if needed.
ExtentReports Not Generating: Check output path in configuration.
