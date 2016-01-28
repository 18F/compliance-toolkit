# 18F Compliance Toolkit

_Towards a more secure (and automated) future._

The long-term goal of this project is to end up with an automated "compliance and risk-assessment" pipeline that does all the grunt work between Compliance Masonry and an Authorizing Official (AO), making the AO's "risk acceptance" sign-off for ATOs a very simple affair. In the meantime, we are working to make the steps to getting an ATO more clear, and enabling any number of people to handle the manual grunt work by following directions.

## Project Goals

* Inform project teams of the necessary steps to acquire an ATO
* Get ATOs completed in fewer hours
* Reduce the burden on the Information Security team leading up to new projects launching
* Assure greater security over 18F's projects in the long term
* Establish best practices for the security and compliance of our projects

## Roadmap

There are several components to the initial phase of 18F's compliance toolkit:

### Compliance Concierge Service

We’d like to offer ourselves up to support your ATO efforts. If you have a question about or need help with vulnerability scanning, static code analysis, or the ATO process in general, please reach out to us. Feel free to message us in #compliance-toolkit or tag us in an issue on Github with @18F/ato.

### Short Term

1. Document the ATO process with exactly:
    * What the project teams need to know
    * What steps they need to complete
    * When they need to complete them
1. Find appropriate static code analysis tools for each of 18F's main languages (Python, Ruby, JS).
    * Tool should look for insecure coding practices in the actual code written by 18F.
    * Tool (or combination of tools) should look for dependencies (python packages, ruby gems, etc.) with known vulnerabilities.
1. Find appropriate tool or combination of tools to perform application-level vulnerability analysis.

TL;DR - the project team should have everything they need to successfully tee up an ATO.

### Long Term
Once the project teams have everything needed to manually run through the process, we will begin automating it.

We aim to:
 * Automate the scans
 * Automate related processes
 * Build out an effective Continuous Monitoring platform 

## Things we maintain

* [The team Trello board](https://trello.com/b/QYPc32q1/compliance-toolkit)
* Compliance information in the [Before You Ship](https://pages.18f.gov/before-you-ship/) site (around ATOs, etc.)
* [Compliance pipelines for Concourse](https://github.com/18F/concourse-compliance-testing)
* [The Google Docs folder](https://drive.google.com/a/gsa.gov/folderview?id=0B5fn0WMJaYDnTVctaUgzZm94bnc&usp=sharing) (private)


