First initialize your Git environment
```
git init
```

Add a remote origin
```
git remote add origin https://github.com/remote-repo-name/
```

Creates a go.mod file to track all of your project's dependencies
```
go mod init [rjhoppe/repo-name]
```

Check to make sure all imports are satisfied. Checks that all modules downloaded are needed for a go build
```
go mod tidy
```

Downloads the named package by the import path along with dependencies
```
go get [github/com/go-package-destination]
```

Run a main.go Go file
```
go run .
```
Or
```
go run main.go
```
