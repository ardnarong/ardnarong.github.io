<h1>Prepare Server  and Install GitLab Runner</h1>

IP : xxxxxxxxxxxxxxxxxxx

username : xxxxx

password : xxxxxxxxx


<h2>#Install Docker and Docker Compose -> Done</h2>
https://github.com/NaturalHistoryMuseum/scratchpads2/wiki/Install-Docker-and-Docker-Compose-(Centos-7) 

<h2>#Install GitLab Runner -> Done</h2>
https://docs.gitlab.com/runner/install/linux-repository.html 

<h2>#Registering Runners -> Done</h2>
https://docs.gitlab.com/runner/register/index.html


<h2>#Grant sudo permissions</h2>

You can grant sudo permissions to the gitlab-runner user as this is who is executing the build script.

$ sudo usermod -a -G sudo gitlab-runner

You now have to remove the password restriction for sudo for the gitlab-runner user.

Start the sudo editor with

$ sudo visudo
Now add the following to the bottom of the file

gitlab-runner ALL=(ALL) NOPASSWD: ALL
