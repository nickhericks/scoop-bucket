# ScoopBucket
A bucket to install my programs using Scoop (http://scoop.sh/)

## To-do
### Still need to add json files for programs to this bucket. (See list below)

## How to use

1. If you haven't already, install [Scoop](http://scoop.sh/).
```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
set-executionpolicy -s cu unrestricted
```

2. Add this repo as a scoop bucket with the following command.
```
scoop bucket add scoop-bucket https://github.com/nickhericks/scoop-bucket
```

3. Install programs...
```
scoop install 7zip
scoop install git
scoop install concfg
concfg import solarized-dark
scoop install touch
scoop install nodejs
scoop instlal sqlite

scoop bucket add extras
scoop install sqlitebrowser
scoop install postman
scoop install filezilla
scoop install hyper

```


### Whenever you want to update any of these applications, just use the following commands:
```
scoop update
scoop update *
```