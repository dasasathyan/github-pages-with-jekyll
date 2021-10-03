DevOps makes the life of a developer easier in saving time by taking the code to any live environment on merge of a specific commit configured.
Once the code is merged to a configured branch the lifecycle of DevOps takes care of building the code, testing it, checking for check-style violations and any other checks needed to make the code production-ready and getting it deployed to any of the configured environments. This leverages the manual intervention of a developer in performing all the above steps. Just a merge and your code is production-ready.

Is that it? Definitely No.

More than development, almost similar or more steps are involved in initialising a project. There could be various issues in getting the dependent services installed in the local machine. Docker helps us to initialize a project with minimal steps possible. A single developer won't be working on a single project. There could be multiple developers. Docker helps us in setting up any project in any machine in minutes.

I spent days in initializing a simple Django project with MySql. Docker helped me to initialize in just a matter of minutes. Also sharing the code with my peers was even easier. The receiver machine just took the code and Dockerfile to get the project up and running.
