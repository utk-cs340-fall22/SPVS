# Product Requirements Document
Product Name: Simple Port and Vulnerability Scanner (SPVS)
Name: Ankit Mistry

## Background
The today's world of everything connected to the internet, people who are in the cyber security department often need to check for vulnerabilities on a target IP address or a range of addresses. SPVS is a simplified port and vulnerability scanner which provides the functionality of scanning targets for vulnerabilites. Anyone can get started with little to no setup requried since it is completely open-source.

## Project Overview
Simple Port and Vulnerability Scanner (or SPVS) is simple tool that scans for ports on a provided IP address of a machine on the internet. It will have two forms available to use. There will be a Command-Line version and a Web version. There a couple ways to provide input. First is to manually type in the target IP address, or second is to provide a file which contains the list of IP addresses. The user can also provide a range of ports according to their requirements, but by default it scans the first 1000 common ports. After the tool is done scanning, it will display the results in a tabular form. The scan includes the following information: The status of the target, all the open ports on the target machine, the service the port serves, and their vulnerabilities.

## Features
1. **Usage.** As a new user to the tool, I would like some instructions on how to use the program.
2. **Scan a target** As a software developer, I would like to scan a target, to see if the target is online.
3. **Scan a port.** As a software developer, I want to scan a specific port on a target, to check if it is not vulnerable.
4. **Scan a certain range of ports on a target.** As a software developer, I would like to scan only certain range of ports, so that I can get just those results that I want.
5. **Supply multiple targets to scan through a file.** As a software developer, I would like to scan multiple targets using a file with a list of targets, so that I don't have to type in every single target manually.
6. **Help button.** As an average person who is not tech savvy, I want to have some instructions on how to use the SPVS web tool, so that I don't have to learn too much about programming to figure out how to use it.
7. **File Upload.** As a web tool user, I want to upload a file with multiple targets, scan them simultaneously, and get the results in one run.
8. **Download Results.** As a web tool user, I would like to save my results, so that I can take a look at it in the future if I need it.

## Technologies to be used
**SPVS Command-Line Tool:** C/C++   
**SPVS Web Tool's FrontEnd:** HTML, CSS, JavaScript, Bootstrap, React
**SPVS Web Tool's BackEnd:** NodeJS, ExpressJS