
# Learning Go

## Installation

Install Go:

```sh
brew install go
```

Add to ~/.bash_profile:

```sh
export PATH=$(go env GOPATH)/bin:$PATH
export GOPATH=$(go env GOPATH)
```

## First App

Following the [tutorial](https://golang.org/doc/code.html#Command).

```sh
mkdir -p $GOPATH/src/github.com/s2t2/hello
cd $GOPATH/src/github.com/s2t2/hello
touch hello.go # then paste in the code
```

Install packages:

```sh
go install # or from anywhere with: go install github.com/user/hello
```

Run the app:

```sh
$GOPATH/bin/hello # or just... hello
```
