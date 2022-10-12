# Code-Review-Checklist (React / Typescript)

## General

1) [ ] Do I understand what this code meant to be/ask for a demo if you need it. if not, ask for clarification<br>
2) [ ] Does the code work? <br>
3) [ ] Description / Screenshots are included. <br>
4) [ ] No Errors or warnings in the NPM log. 
5) [ ] No Issues shown in IDE.
6) [ ] Is PO happy with the outcome?

## Functional
1) [ ] Does the code serve all the functionalities requested by the feature?

## Highlevel Code Scanning
1) [ ] Code is readable and understandable.<br>
2) [ ] Code is written following the coding standards <br>
3) [ ] Code is written to match existing code patterns/technologies.<br>
4) [ ] Separation of Concerns followed.<br>
5) [ ] Are functions/classes/components dedicated to a primary purpose?<br>

## Code Style
1) [ ] DRY. (Don't Repeat Yourself) No duplication of code<br>
2) [ ] Unnecessary console.logs removed<br>
3) [ ] Naming conventions followed for variables and file names.
4) [ ] Minimum use of hardcoded values; use constants values.
5) [ ] No unnecessary comments / Add necessary comments.
6) [ ] Use Lodash Features
7) [ ] Use default values to reduce upcoming logic
8) [ ] Use destructuring assignments for arrays and objects.
9) [ ] Use Promises or Async/Await. Rejection is handled.
10) [ ] Nested logic avoided.
11)  [ ] Code should be declarative rather than imperative. Exceptions made when performance requirements make it impossible.

## React and TS
1) [ ] Do components have reasonable props
2) [ ] Are interfaces written with correct types for the props and imposes the correct compulsoriness to the props (mandatory or optional)
3) [ ] No state updates in a loop.
4) [ ] Correct use of native react hooks


## Others
1) [ ] Have meaningful commit messages
2) [ ] Check if there are mistakenly added files
