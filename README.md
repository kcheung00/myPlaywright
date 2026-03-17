## Summary of Functionality:
* The Java application (App.java) integrates with Python scripts (extractPasscode.py and extractValidationLink.py) to automate the USPS account creation process and validation.
* The Python scripts handle email parsing for passcodes/links via the Microsoft Outlook client, and the Java application automates the web interactions using Playwright.

## Prerequisites
* Desktop version 16 Microsoft Outlook with enabled COM object. (Download here)
* JDK 17
* Python 3
* Win32 COM Python library (_pip install pywin32_)
* Windows Environment ONLY
  
## Build and Execution Steps
1. Clone the project
   ```
   git clone https://github.com/kcheung00/playwright.git
   ```
2. Change Directoy
   ```
   cd playwright
   ```
3. Build
   ```
   mvn clean install
   ```
4. Execution (_Ensure desktop outlook is running._)
   ```
   java -jar target/ui-test-1.0-SNAPSHOT-jar-with-dependencies.jar
   ```
   
