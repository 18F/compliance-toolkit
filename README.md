# 18F Compliance Toolkit

_Towards a more secure (and automated) future._

## Project Goals

* Inform project teams of the necessary steps to acquire an ATO
* Get ATOs completed in fewer hours
* Reduce the burden on the Information Security team leading up to new projects launching
* Assure greater security over 18F's projects in the long term
* Establish best practices for the security and compliance of our projects

## Roadmap

There are several components to the initial phase of 18F's compliance toolkit:

1. Document the ATO process with exactly:
    * What the project teams need to know
    * What steps they need to complete
    * When they need to complete them
1. Find appropriate static code analysis tools for each of 18F's main languages (Python, Ruby, JS).
    * Tool should look for insecure coding practices in the actual code written by 18F.
    * Tool (or combination of tools) should look for dependencies (python packages, ruby gems, etc.) with known vulnerabilities.
1. Find appropriate tool or combination of tools to perform application-level vulnerability analysis.
1. Create an MVP of an automated workflow that takes an application through both static analysis and application level analysis and provides actionable feedback.

## Things we maintain

* [The team Trello board](https://trello.com/b/QYPc32q1/compliance-toolkit)
* Compliance information in the [Before You Ship](https://pages.18f.gov/before-you-ship/) site (around ATOs, etc.)
* [The Google Docs folder](https://drive.google.com/a/gsa.gov/folderview?id=0B5fn0WMJaYDnTVctaUgzZm94bnc&usp=sharing) (private)
