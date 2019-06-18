# iwesep2019.github.io

[![Build Status](https://travis-ci.org/iwesep2019/iwesep2019.github.io.svg?branch=develop)](https://travis-ci.org/iwesep2019/iwesep2019.github.io)


Here is a project for the web site of [IWESEP 2019](https://iwesep2019.github.io/).


## How to Contribute

### Branch policy

If you make some changes, you should create Pull Request.
In your PR, you select `develop` branch as target branch.
Please DO NOT select `master` as target.
`master` branch manages web pages deployed via Travis CI.

The overview of branch policy is below.

```
feature/xx 
--(Pull request)-> develop 
--(Deploy via Travis CI)-> master
```

## How to Build and Review Pages

1. [Install HUGO CLI tool](https://gohugo.io/getting-started/installing/)
1. Clone this project
1. `git checkout develop`
1. `hugo server -D`
1. you can access local web server (e.g. http://localhost:1313/)
