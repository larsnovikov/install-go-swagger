### Install required version of go-swagger from sources ###

1. `dir=$(mktemp -d)`
2. `git clone https://github.com/go-swagger/go-swagger "$dir"`
3. `cd $dir`
4. `git tag`
5. `git checkout <version>`
6. `go install ./cmd/swagger`
