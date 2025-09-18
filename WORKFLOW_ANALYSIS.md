A. A push to main or a pull request to main
B. Code retrieval, code validation, link validation, and code uploading
C. Checkout retrieves the code from the repository so that the workflow can actually access it. This is important in order for any of the other steps to happen, as they interact with the code in some way or another.
D. Regardless of the code being run on whatever machine, environment configuration is important. It ensures that dependencies are in order, prevents weird conflicts, and otherwise ensures that a piece of code (including a workflow) has what it needs to function properly.
E. Automated deployment ensures that all of the same steps are performed each time, in the same way, and under the same scrutiny. If a step is skipped along the way, the computer knows this, did it intentionally, and will tell you.
F. Nothing would happen. For this repository, Pages is configured to work off the `main` branch, so there is no purpose in responding to changes in other branches.
