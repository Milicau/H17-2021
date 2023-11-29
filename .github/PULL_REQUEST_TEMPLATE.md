## Description

_SUMMARIZE THE CHANGE HERE_

## Review

### Questions to change owner / author of PR

| Status | Review checklist item | Comment |
|:---:|---|---|
|  | No compiler warnings in touched files. |  |
|  | No doxygen warnings are introduced. |  |
|  | Software detailed design documents are created and/or updated. |  |
|  | Unit tests are created for new code and specified following the defined template. |  |
|  | Feature has been tested in simulation or on target hardware. |  |
|  | Changes are restricted to the scope of one ticket. |  |

### Questions to reviewers

Reviewer: @your_name

#### Design 

| Status Reviewer | Review checklist item | Comment |
|:---:|---|---|
|  | Is the changed design consistent in itself and with the SW architecture, e.g. usage of  interfaces? |  |
|  | Does the structure of the detailed design follow the design instruction and templates (e.g. allocation of source files to design elements)? |  |
|  | Is the traceability from the design to the corresponding source (SW Architecture, SW Requirements) documented? |  |
|  | Does the design fullfil the relevant requirements and acceptance criteria for this change? |  |

#### Code 

| Status Reviewer | Review checklist item | Comment |
|:---:|---|---|
|  | Is the implementation fully understood? |  |
|  | Are there are any obvious defects / programming errors / unintended side effects? |  |
|  | Are there improvements / refactoring needed (e.g. for efficiency, maintainability)? |  |
|  | Does the source code match the detailed design (dynamic behavior, interfaces, dependencies, structure)? |  |
|  | Is the make/build.yml guideline followed, if defined for the project? |  |
|  | Is the traceability from the implementation (source code) to the corresponding source (specification) documented? |  |

#### Unit verification 

| Status Reviewer | Review checklist item | Comment |
|:---:|---|---|
|  | Is the objective (target) of the changed/new test case(s) described? Do the test steps (with their expected results) accomplish the test objective? |  |
|  | Is the changed/updated detailed design sufficiently covered by unit test cases (behavior diagrams and descriptions, public interfaces)? |  |
|  | Is boundary value and equivalent class analysis considered? |  |


|Status|Description|
|:---:|---|
| / | Review done and all findings are fixed |
| x | Review done, findings need to be fixed |
| - | Not Applicable, see comment|

Template v1.0
