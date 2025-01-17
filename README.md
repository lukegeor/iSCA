# iSCA
SCA scan service, including an embedded scanner, and a web site that shows results, and allows for triaging and analysis of results

## Background
I can't freaking find an SCA tool that does what I want. So I'm writing one myself.

## Features
* Scans .Net projects and Node.js projects
* Supports direct and transitive dependencies
* Uploads results to a cloud service
* Displays vulnerabilities grouped by vulnerable package
* Displays all projects the vulnerable package affects
* Displays dependency path for each vulnerable package
* Allows comments and dispositioning for each discovered vulnerability
* Allows review of dispositions
* Role-based access to disposition and review
* Output SBOM
* Supports branch / pull request scans diffing with default branch
* Suports writing PR comments and pass-fail PR checks
