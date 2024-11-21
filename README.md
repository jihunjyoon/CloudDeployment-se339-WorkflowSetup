This is for the Workflow setup of Shopizer

Trigger:
Runs automatically whenever a Pull Request (PR) is opened or updated.

Tests Execution:
Executes the project's test suite to ensure the code changes do not break existing functionality.

Build Process:
Builds the Shopizer project to verify that the code compiles and the build process completes without errors.

Optional Deployment Step:
For future extensions, we planned to add deployment to Azure upon PR merge, conditioned on the successful execution of all tests and builds.
