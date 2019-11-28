# A blog app with docker
## To launch in production
```docker
$ docker-compose up
```

## To launch in development
- First
```vscode
> F5
```
- Next
```docker
$ docker-compose -f docker-compose.dev.yml up --build -d
```