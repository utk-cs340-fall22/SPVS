# Product Requirements Document
Name: Shivam Mistry

Product Name: Simple Port and Vulnerability Scanner (SPVS)

## Background
Professionals in Information Security sector often need to scan target or range of targets, to check for anomalies. SPVS with its CLI and web version provides a way for these professionals to scan range of targets, with little to no-setup while being fully open-source.

## Project Overview
Simple Port and Vulnerability Scanner (SPVS) is an easy-to-use network scanner. As mentioned, there will be two ways to access the SPVS tool, either on command line, or through web. The SPVS tool will be able to handle the target information either via a manual text entry, or a file. File option is usually better to scan several different targets. After scanning the targets based on user specifications, the tool will display concise and easy to interpret output. The scanner will be able to determine status of the target, open/close ports, and their known vulnerabilities.   
The main difference between the CLI and web version is that the web version is accessible anywhere to scan targets over a network, while CLI version allows to scan locally as well as over a network. CLI version is best suited for developers. The tool, however, is not intended for wide range corporate network scans.

## Features
1. **Usage.** As a new user and developer, I want to know how to use to CLI version, so that I can use the program
2. **Scan a target** As a developer, I want to scan a target on CLI, to check if the target is online.
3. **Scan a specific port.** As a developer, I want to scan a specific port on a target, to check if it is not vulnerable.
4. **Scan multiple targets with a file.** As a developer, I want to scan multiple targets using -f flag and file name, to scan range of targets.
5. **Help button.** As a non-technical person, I want to learn to use the SPVS website, to perform some task for someone else.
6. **Scan a random target.** As a website user, I want to scan random targets, to check if they exist.
7. **File Upload.** As a website user, I want to scan a file with multiple targets, to get results in a one go.
8. **Download Results.** As a website user, I want to download result, so that I can reference it later.

## Technologies to be used
**SPVS CLI TOOL:** C/C++   
**SPVS WEB FRONTEND:** Html, Css, JavaScript, Bootstrap, jQuery, React   
**SPVS WEB BACKEND:** NodeJS, ExpressJS   
