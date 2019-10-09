# bitbucket-issue-report

## run iex
docker run -it --rm --name playground --mount type=bind,source="C:\Users\User\developer\elixir",target=/usr/src -w /usr/src elixir

## create project
docker run -it --rm --name playground --mount type=bind,source="C:\Users\User\developer\elixir",target=/usr/src -w /usr/src elixir mix new issue_report

## install dependencies
docker run -it --rm --name playground --mount type=bind,source="C:\Users\User\developer\elixir\issue_report",target=/usr/src/issue_report -w /usr/src/issue_report elixir mix deps.get

## create volume
- study issue [#173](https://github.com/vargasgabriel/study/issues/173)
