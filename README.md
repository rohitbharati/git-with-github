# Git vs Github
Git is a software and github is online service
git is free and opensource which helps in version control. Github is webapp built to run Git in the cloud Bitbucket is also runs git on cloud ;)
I mean you can see this doc on github which was pushed using git.

Terminologies in git
check version in of git-cli
```sh
% git --version
git version 2.39.5 (Apple Git-154)
```

### git config
For any tool user is important we can set the user and email
we can set user and email using
```bash
git config --global user.name="Name of user"
git config --global user.email="email.of@user.com"
```

 - Git store the configuration in git config
 -  this configuration file is saved in path `~/.gitconfig`

```sh
% git config --list
user.name=Rohit Kumar
user.email=Rohit.kumar@repo.com
```