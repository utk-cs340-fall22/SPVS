# Product Requirements

## Background

Many tools for information security are expensive, complex, and not very user friendly. This is the motivation for the creation of Simple Port and Vulnerability Scanner (SPVS). The goal is to create a light-weight Unix tool that can be used by beginners or people who are look for a quick experience. The addition of a hosted site allows for people to demo the tool and provides exteneded usage to people looking to use the tool quickly.

## Product Overview

Simple Port and Vulnerability Scanner (SPVS) is an easy-to-use network scanner that can be used on a command line or in a browser. The tool can take input directly or as a file. By default it scans the first 1000 common ports, but can be specified by the user otherwise. Scans will return concise easy to interpret results including the status of the target, open/close ports, and their known vulnerabilities. As previously mentioned, the tool will feature a downloadable command line version for more advanced users and a web version. The web version will provide new users with a easy to use intuitive experience as well as a helpful introductory guide. 

## Features
1. Usage. As a new user, I would like some instructions on how to use to CLI version of the program.
2. Scan a target. As a developer, I want to scan a target to see if it is online.
3. Scan a specific port. As a developer, I want to scan a specific port on a target to check it's vulnerability.
4. Scan multiple targets with a file. As a developer, I want to scan multiple targets using -f flag and file name, to scan range of targets.
5. Help button. As a non-technical person, I want to learn the basics of port scanning and vulnerability.
6. Scan a random target. As a website user, I want to scan random targets, to validate machines.
7. File Upload. As a website user, I want to scan a file with multiple targets, to run large scans.
8. Download Results. As a website user, I want to download result, so that they can be processed.

## Technologies

### Tool
* C, C++
### Web
* Server: NodeJS, ExpressJS
* Frontend: HTML, CSS, JavaScript
