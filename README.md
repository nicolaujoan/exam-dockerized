# exam-dockerized
Dockerized Daw Dual Exam, designed by our teacher <a href="https://github.com/dfleta">dfleta</a> and explained in his <a href="https://github.com/dfleta/examen-galley-grub">repo</a> with all the requirements, UML diagram ...

We take advantage of the creation and usage of our Azure VM created to dockerize an app. So, we will dockerize our exam and run its container in our Debian VM.

<hr>

First, clone the repo of my solution:

![sol](./imgs/1-clone_solution.png)

this Dockerfile will be used

![dfile](./imgs/2-dockerfile_used.png)

we have git installed in our Debian VM, so we clone the solution

![clonevm](./imgs/3-git_clone.png)

now execute the build command

![build](./imgs/4-build.png)

and run a container to see the output of the app

![cli1](./imgs/5-cli1.png)

![cli1](./imgs/6-cli2.png)

