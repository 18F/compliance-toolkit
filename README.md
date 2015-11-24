# 18F Compliance Toolkit
Towards a more secure (and automated) future.

## Project Goals

There are several components to the initial phase of 18F's compliance toolkit:

1. Find appropriate static code analysis tools for each of 18F's main languages (Python, Ruby, JS).
    * Tool should look for insecure coding practices in the actual code written by 18F.
    * Tool (or combination of tools) should look for dependencies (python packages, ruby gems, etc.) with known vulnerabilities.
2. Find appropriate tool or combination of tools to perform application level vulnerability analysis.
3. Create an MVP of an automated workflow that takes an application through both static analysis and application level analysis and provides actionable feedback.
