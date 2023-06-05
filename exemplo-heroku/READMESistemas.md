Apresentação Sistemas Distribuidos

- https://dashboard.heroku.com/

- https://devcenter.heroku.com/articles/heroku-cli

- npx create-react-app exemplo-heroku

- git init

- git add .

- git commit -m "Initial commit"

- heroku create exemplo-heroku

- Continuous Deployment (CD), ou Implantação Contínua

- GitHub Actions, GitLab CI/CD, Bitbucket

- git push heroku master

- $ cat .git/config

[core]
        repositoryformatversion = 0
        filemode = false
        bare = false
        logallrefupdates = true
        symlinks = false
        ignorecase = true
[remote "heroku"]
        url = https://git.heroku.com/exemplo-heroku.git
        fetch = +refs/heads/*:refs/remotes/heroku/*





- git branch
 
- git checkout -b main
