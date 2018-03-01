# tic40.github.io

## site

https://tic40.github.io

## Install

Install hugo
```
$ brew install hugo
```

Refrect submodule setting after clone the repo.
```
$ git submodule init && git submodule update
```


## Add new post

```
$ hugo new posts/{year}/{title}.md
```

## Run server on local


```
$ hugo server -D
```
*-D option is: include content marked as draft

## Publish new post

Set false to the draft parameter in your post file.

```
draft: false
```

## deploy

Just run the script!
```
$ ./deploy.sh
```
