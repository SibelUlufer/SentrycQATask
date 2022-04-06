"npm run cy:open" or "npx cypress open" -- to open cypress
"npm run cy:e2e" -- to run all tests headless and create mochawesome.html report as merged html file with junit and mochawesome reports
Under the mochawesome-report folder, mochawesome.html report can be found.
Under the cypress/results folder there are junit and mochawesome folder which have .xml and .json files created seperately, each file represents each spec files.


.feature files are added under the integration folder as "login" and "forgotPassword"

login.feature has 4 scenarios
../integration/login folder has .spec file as step_def file

forgotPassword.feature has 4 scenarios
../integration/forgotPassword folder has .spec file as step_def file

../support/command files has functions that can be reachable from anywhere 

For run a specific scenario, "@focus" smart tag can be used just above the scenario

.prettierrc file has format settings



#   S e n t r y Q A T a s k  
 