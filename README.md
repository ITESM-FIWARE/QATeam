# ITESM QA Team
This document concentrates the process followed by the ITESM team to test the documentation of each FIWARE GE available in the FINEXT QA Test Plan Spreadsheet. First, the specification points considered into the documentation test are presented; secondly, the formula (specification points) followed to obtain each value of soundness and completeness labels are described. All documentation tests were performed according to the FIWARE catalog info available at official site https://catalogue-server.fiware.org/. Documentation available at other web pages or in GitHub official sites are not considered, since the documentation must be accessible from the official web site and then redirect the user to additional information resources. An example of the official documentation site that are considered for evaluation is ```https://catalogue-server.fiware.org/enablers/'GE_name'/documentation```. If you have a new version of the documentation, please search for your official URL site and update the documentation there for further evaluation.

## Review template
The evaluation considerations are described from global to specific metrics as well as the values for each one of them. 
1. **Summary**
  - GE Complete installation achieved: Yes | No
  - Complexity of the installation process: Easy | Reasonable | Difficult
  - Type of installation: From installer | From release package | From provided scripts
  - Documentation link: URL of the documentation web page
  - Software documentation version: Number of the software documentation version tested
  - Revision update: Date when the tests were performed
  - OS installation: Name and version of the OS where the GE was tested
  - Notes: Additional notes about issues and considerations

2. **General overview**

| Metric | Value |
| --- | --- |
| Versioned documentation | Yes \ No \ Partially \ NA \ Comments |					
| Documentation includes the release date | Yes \ No \ Partially \ NA \ Comments |
| Documentation is organized (has a table of contents)  | Yes \ No \ Partially \ NA \ Comments |
| The documentation establishes the versions of the software it applies to | Yes \ No \ Partially \ NA \ Comments |
| The target user of the documentation is specified | Yes \ No \ Partially \ NA \ Comments |
| If previous versions of the documentation exist, changes are highlighted or listed in a way that tells them apart | Yes \ No \ Partially \ NA \ Comments |
| Documentation use simple vocabulary familiar to the users | Yes \ No \ Partially \ NA \ Comments |
| If specific terms and/or acronyms are included, the documentation includes a glossary | Yes \ No \ Partially \ NA \ Comments |
| The documentation presents links to additional information and/or data sources when mentioned | Yes \ No \ Partially \ NA \ Comments |
| Tasks are presented in the order in which they are performed | Yes \ No \ Partially \ NA \ Comments |
| General description of the software | Yes \ No \ Partially \ NA \ Comments |
| Skills required by the installer | Yes \ No \ Partially \ NA \ Comments |
| The supported platforms list is properly described | Yes \ No \ Partially \ NA \ Comments |

3. **Installation**

| Metric | Value |
| --- | --- |					
| Installation steps are ordered | Yes \ No \ Partially \ NA \ Comments |
| Summary of the installation steps | Yes \ No \ Partially \ NA \ Comments |
| Installation steps are easy to follow | Yes \ No \ Partially \ NA \ Comments |
| Installation steps/commands are complete | Yes \ No \ Partially \ NA \ Comments |
| Tracking of installation progress | Yes \ No \ Partially \ NA \ Comments |
| Installation steps for software dependencies are provided | Yes \ No \ Partially \ NA \ Comments |
| Supported versions of software dependencies are specified | Yes \ No \ Partially \ NA \ Comments |
| The required ports are specified | Yes \ No \ Partially \ NA \ Comments |
| The installation process on different platforms is executed correctly | Yes \ No \ Partially \ NA \ Comments |
| Software prerequisites | Yes \ No \ Partially \ NA \ Comments |
| Security issues that may apply (firewall, irreversible actions, etc.) | Yes \ No \ Partially \ NA \ Comments |
| Hardware prerequisites | Yes \ No \ Partially \ NA \ Comments |
| An exception is thrown when not enough resources are found | Yes \ No \ Partially \ NA \ Comments |
| The installation resources expected to take are properly specified | Yes \ No \ Partially \ NA \ Comments |
| The installation works without administrative privileges | Yes \ No \ Partially \ NA \ Comments |
| All the installation messages are properly displayed in the UI or directed to a log file | Yes \ No \ Partially \ NA \ Comments |
| Logs location is provided | Yes \ No \ Partially \ NA \ Comments |
| The system asks for confirmation on critical operations | Yes \ No \ Partially \ NA \ Comments |
| The installation process is complemented by examples and figures | Yes \ No \ Partially \ NA \ Comments |
| If the installation process fails: | |
|     - Error feedback | Yes \ No \ Partially \ NA \ Comments |
|     - Intructions for error recovery | Yes \ No \ Partially \ NA \ Comments |
|     - The recovery process allows to complete installation | Yes \ No \ Partially \ NA \ Comments |
| Complete installation was achieved (If no): | |
|     - No: Installation is not possible at all  | Yes \ No \ Partially \ NA \ Comments |
|     - No: the procedure is too complex | Yes \ No \ Partially \ NA \ Comments |
|     - No: Takes longer than one working day | Yes \ No \ Partially \ NA \ Comments |
| Large number of installation steps | Yes \ No \ Partially \ NA \ Comments |

4. **Troubleshooting**

| Metric | Value |
| --- | --- |					
| Troubleshooting section is provided | Yes \ No \ Partially \ NA \ Comments |
| Common possible errors are listed with detailed instructions on how to solve them | Yes \ No \ Partially \ NA \ Comments |

5. **Functional test subprocess**

| Metric | Value |
| --- | --- |
| Instructions on how to launch or start the software are provided | Yes \ No \ Partially \ NA \ Comments |
| Instructions detail the arguments and information that can be passed to the software upon startup | Yes \ No \ Partially \ NA \ Comments |
| Sanity check procedure is clearly described | Yes \ No \ Partially \ NA \ Comments |
| The system works as expected | Yes \ No \ Partially \ NA \ Comments |

## Labels formula
In order to obtain the values for the completeness and soundness labels, the following metrics (previously described) were considered.

1. **Completeness label**
  - Metrics considered: In total, 23 metrics were considered to evaluate this label
    - Versioned documentation (From general overview)
    - Documentation includes the release date (From general overview)
    - Documentation is organized (has a table of contents) (From general overview)
    - The documentation establishes the versions of the software it applies to (From general overview)
    - If previous versions of the documentation exist, changes are highlighted or listed in a way that tells them apart (From general overview)
    - Documentation should use simple vocabulary familiar to the users (From general overview)
    - If specific terms and/or acronyms are included, the documentation includes a glossary (From general overview)
    - The documentation presents links to additional information and/or data sources when mentioned (From general overview)
    - Tasks are presented in the order in which they are performed (From general overview)
    - The supported platforms list is properly described (From general overview)
    - Summary of the installation steps (From installation)
    - Installation steps for software dependencies are provided (From installation)
    - Supported versions of software dependencies are specified (From installation)
    - Software prerequisites (From installation)
    - Security issues that may apply (firewall, irreversible actions, etc.) (From installation)
    - Hardware prerequisites (From installation)
    - The installation resources expected to take are properly specified (From installation)
    - Logs location is provided (From installation)
    - The installation process is complemented by examples and figures (From installation)
    - Troubleshooting section is provided (From Troubleshooting)
    - Common possible errors are listed with detailed instructions on how to solve them (From Troubleshooting)
    - Instructions on how to launch or start the software are provided (From Functional test subprocess)
    - Sanity check procedure is clearly described (From Functional test subprocess)

  - Formula
  
    | Number of metrics with “Yes” value |	Label value |
    | --- | --- |
    | 0 – 3 | D |
    | 4 - 7 | C |
    | 8 - 11 | B | 
    | 12 - 15 | A |
    | 16 - 19 | A+ |
    | 20 - 22 | A++ |
    | 23 | A+++ |

2. **Soundness label**
  - Metrics considered: In total, 27 metrics were considered to evaluate this label
    - Versioned documentation (From general overview)
    - Documentation includes the release date (From general overview)
    - Documentation is organized (has a table of contents) (From general overview)
    - The documentation establishes the versions of the software it applies to (From general overview)
    - The target user of the documentation is specified (From general overview)
    - If previous versions of the documentation exist, changes are highlighted or listed in a way that tells them apart (From general overview)
    - Documentation should use simple vocabulary familiar to the users (From general overview)
    - If specific terms and/or acronyms are included, the documentation includes a glossary (From general overview)
    - Tasks are presented in the order in which they are performed (From general overview)
    - General description of the software (From general overview)
    - Skill required by the installer (From general overview)
    - The supported platforms list is properly described (From general overview)
    - Summary of the installation steps (From installation)
    - Installation steps for software dependencies are provided (From installation)
    - Supported versions of software dependencies are specified (From installation)
    - The required ports are specified (From installation)
    - Software prerequisites (From installation)
    - Security issues that may apply (firewall, irreversible actions, etc.) (From installation)
    - Hardware prerequisites (From installation)
    - The installation resources expected to take are properly specified (From installation)
    - Logs location is provided (From installation)
    - The installation process is complemented by examples and figures (From installation)
    - Troubleshooting section is provided (From Troubleshooting)
    - Common possible errors are listed with detailed instructions on how to solve them (From Troubleshooting)
    - Instructions on how to launch or start the software are provided (From Functional test subprocess)
    - Instructions detail the arguments and information that can be passed to the software upon startup (From Functional test subprocess)
    - Sanity check procedure is clearly described (From Functional test subprocess)
    
  - Formula
  
    | Number of metrics with “Yes” value |	Label value |
    | --- | --- |
    | 0 – 4 | D |
    | 5 - 8 | C |
    | 9 - 13 | B | 
    | 14 - 17 | A |
    | 18 - 22 | A+ |
    | 23 - 26 | A++ |
    | 27 | A+++ |

## GE test status
The following charts denotes the status of the Completeness and Soundness Labels of the diverse FIWARE GEs tested untill a specific period. The first chart concentrates the total number of FIWARE GEs tested and the total number of FIWARE GEs that obtained each label. The second chart details the labels values obtained for each FIWARE GEs tested.
