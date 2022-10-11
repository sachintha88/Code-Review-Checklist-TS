# Code-Review-Checklist (Typescript)

## General

1) Do I understand what this code meant to be / ask for demo if you need? if not ask for clarification<br>
2) Does the code work? <br>
3) Description / Screenshots are included. <br>
4) No Errors or warnings in NPM log. 
5) No Issues shown in IDE.

## Functional
Does written code serve all the functionalities requested by the feature?

## Highlevel Code Scanning
1) Code is readable and understandable.<br>
2) Code is written following the coding standarts<br>
3) Code is written to match existing code patterns/technologies.<br>
4) Separation of Concerns followed.<br>
5) Are functions/classes/components reasonably small?<br>

## Code Style
1) DRY.(Don't Repeat Yourself) No duplication of code<br>
2) unnessary console.logs removed<br>
3) Naming conventions followed for variables, file names.<br>
4) Minimum use of hardcoded values, use constants values.
5) No unnecessary comments / Add necessary comment.
6) Use Lodash Features
7) Use default values to reduce upcomming logic
8) Use destructuring assignment for arrays and objects.
9) Use Promises or Asyns/Await. Rejection is handled.

## React and TS
1) Do components have reasonable props
2) Are interfaces written with correct types for the props and correct necessity of the prop (mandatory or optional)
3) No state updates in loop.
4) Correct use of native react hooks


## Others
1) Have meaningful commit messages
2) Check if there are mistakenly added files
