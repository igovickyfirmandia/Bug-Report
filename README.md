# Bug Report
A bug report is a critical part of software testing that ensures a product meets quality standards before its release. A bug report is a detailed document or record to report software application issues, defects, or problems. A bug report also helps developers understand the issue quickly, prioritize it, and address it efficiently.
## Importance of a Good Bug Report:
   * Clarity: Ensure & helps developers to understand the issue
   * Efficiency: Helps in faster identification and resolution of issues, saving time and resources
   * Documentation: Helps to track progress and ensure quality, also provides a record of issues for future reference

# 1. Tools
There are 2 types of tools: Bug Tracking Systems & Collaboration Tools
 * Bug Tracking Systems: Jira, Bugzilla, Trello, ClickUp, & Asana are commonly used to report and manage bug
 * Collaboration Tools: Bug tracking tools can be integrated with platforms like Slack and Microsoft Teams to streamline communication about bugs.

# 2. Components of Bug Report
#### BUG ID
Bug ID can be generated automatically by the tools or manually generated (e.g. BUG ID: 001)
#### Status
The current state of the bug (e.g., "Open," "In Progress," "Resolved," etc.)
#### Title
A concise description of the bug (e.g. Failed login using valid credentials)
#### Environment
Information about the environment in which the bug was found, such as the operating system, browser/device, software version, etc.
  * Operating System: Specify the OS version (e.g., Windows 11, macOS Ventura).
  * Device/Browser: Include the device model, browser, and version if applicable (e.g., iPhone 14, Chrome v110).
  * Software Version: Mention the specific version of the application where the bug was identified (e.g., v2.3.1).
#### Severity & Priority
Indicate the severity (e.g., Critical, Major, Minor) and priority (e.g., High, Medium, Low) of the bug, which helps in determining how quickly it should be addressed
#### Assignee/Assign To
The person or team responsible for fixing the bug
#### Pre-Condition
Mention any specific setup or prerequisite required to reproduce the bug
#### Step to Reproduce
Steps needed to reproduce the bug in a clear and logical sequence. Example:
    * User input valid Username
    * User input valid Password
    * User click Login button
#### Expected Result
Clearly describe the expected outcome after following the steps
#### Actual Result
What happened when the bug occurred
#### Evidence/Screenshot
Any visual evidence or logs that can help in understanding or reproducing the bug, and can attach a screenshot/video record of the bug to make it easily understand
#### Additional Information
Define any information needed like test data, logs, and notes for the dev team

# 3. Best Practices for Bug Reporting
   * No Assumptions: Use facts to report the issue. Never use assumptions to report something unclear
   * Reproduce first: Always reproduce the bug several times before reporting it to the dev team 
   * Be Specific: Provide detailed information about the bug & no unnecessary detail
   * Report Promptly: Report bugs as soon as they are identified
   * Clear Language: Write in clear & straightforward language

# 4. Follow-Up
   * Track Progress: Keep track of the reported bug's status and update the report if new information arises or if a re-test is needed after a fix is applied
   * Collaboration: Engage with the dev team, product/project managers, and other stakeholders for clarification

# 5. Common Mistakes to Avoid
   * Duplication: Always check the bug tracking system first before reporting the bug. This act is to ensure the bug hasn’t already been reported
   * Incomplete reports: Lack of key details can delay bug resolution
   * Neglecting edge cases: Identify and report edge cases that may not be part of the main flow but could still lead to issues

# 6. Sample Bug Report
Here is an example of bug report
  * Bug ID: 001
  * Status: Open/In-Progress/Resolved
  * Title: Failed login using valid credentials
  * Environment:
    * OS: Windows 11
    * Device/Browser: Chrome v125
    * App Version: v1.0.0
  * Severity: Major
  * Priority: High
  * Assign To: _Name of the developer or team assigned to fix the bug_
  * Pre-Condition:
    * User in Login Page
    * User already registered
  * Step to Reproduce:
    * User input valid username & password
    * User clicks the Login button
  * Expected Result: User logged in successfully & redirected to the Dashboard Page
  * Actual Result: An 'Invalid Username & Password' error is displayed, and user remains on the Login Page
  * Screenshot: _Screenshot/Video_
  * Additional Information:
    * Logs: {"error": "Invalid Username & Password"}
    * Test Data: User credentials
        * Username: John Doe
        * Password: password  
    * Notes: -



