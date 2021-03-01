[![Go Report Card](https://goreportcard.com/badge/lerichardson/gocrazy)](https://goreportcard.com/report/github.com/lerichardson/gocrazy)
# gocrazy
when it's 2 am this is what your brain be like
# Installing
Two ways, one, you need go installed, one you don't
## Building it yourself
I recommend using `git` or `gh` if you have it installed, as building it requires the go.mod and go.sum files.
```
git clone https://github.com/lerichardson/gocrazy.git
```
or, for `gh`:
```
gh repo clone lerichardson/gocrazy
```
then run `go build gocrazy.go`.  
After this, if you are on windows, you can run `go install` which will also add it to your path. On linux, you will have to add it to your path yourself.
## Get the pre-built file
wget or curl:
```
wget https://github.com/lerichardson/gocrazy/releases/download/v1.0.0/gocrazy
```
curl:
```
curl -O https://github.com/lerichardson/gocrazy/releases/download/v1.0.0/gocrazy.exe
```
then add it to your PATH environment variable. You can figure that out yourself.
# Contributing
Pull Requests and Issues are welcome!
